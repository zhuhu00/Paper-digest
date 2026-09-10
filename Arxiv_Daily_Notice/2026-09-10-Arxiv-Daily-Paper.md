# Showing new listings for Thursday, 10 September 2026
## Keyword: SLAM
### Title:
          Valerant: An Automatic Navigable Game Map Generator via Action-Conditioned World Model Exploration
 - **Authors:** Yiran Qiao, Feng Wang, Jing Ma
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) couple predictive world modeling with action generation, allowing anticipated future states to guide agent behavior. Although WAMs are rapidly advancing embodied AI, general-purpose counterparts remain largely unexplored in games. Existing game-oriented approaches often combine action-conditioned world models with external policies and reward functions to realize WAM-like decision-making, yet they operate mainly in 2D visual observation space and do not instantiate persistent 3D geometry. Extending this paradigm to 3D games introduces a distinct challenge. In autonomous driving and robotics, the physical environment exists independently of the model, providing a persistent 3D world in which selected actions can be executed. Games have no such external substrate; the virtual world itself must be instantiated. Most playable games require a persistent and navigable space, while 3D games additionally require explicit geometry that supports movement and interaction. Action-conditioned video rollouts provide visual observations but not this spatial representation. We present \textsc{Valerant}, a training-free framework that transforms a pretrained action-conditioned world model into a WAM for exploring and constructing 3D game maps. By coupling predictive visual rollouts with SLAM-based spatial reconstruction and exploration-driven action selection, \textsc{Valerant} progressively transforms a single image into a persistent 3D game map. This framework extends WAM-based interaction beyond 2D visual simulation and offers a new approach to reducing manual effort in 3D game-map creation.
## Keyword: odometry
### Title:
          IMU-Centric Moving Horizon Estimation for Lateral Dynamics Estimation Across Vehicles and Grip Conditions
 - **Authors:** Seuffo Akouan ha Ngoune, Alessandro Toschi, Paolo Burgio, Marko Bertogna
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate estimation of lateral vehicle dynamics near the adhesion limit is important for stability control and high-performance driving, but lateral velocity is rarely measured directly because sensors such as optical sensors are costly. This paper presents an inertial measurement unit (IMU)-centric Moving Horizon Estimation framework that reconstructs lateral velocity using standard onboard signals, without relying on exteroceptive odometry or detailed tire-parameter tuning. Experimental validation on human-driven sports cars and an autonomous open-wheel race car across tracks, maneuvers, and conditions demonstrates accurate and robust lateral velocity and lateral acceleration estimates. The proposed framework is available at this https URL
### Title:
          Odometer-Agnostic Drift Correction Using OpenStreetMap Lane Geometry
 - **Authors:** Joaquin Caballero, Emilio Garcia-Fidalgo, Alberto Ortiz, Jarno Ralli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite significant progress in odometry estimation, long-term drift remains a fundamental limitation of incremental pose integration, especially in large-scale or loop-free environments. Existing map-assisted methods can reduce drift, but often depend on dense maps, sensor-specific processing, or complex matching pipelines. We propose a lightweight open-source, odometry-agnostic correction method that aligns short trajectory segments to OpenStreetMap (OSM) lane centerlines. By formulating drift correction as a direct alignment between recent odometry and sparse lane geometry, the method enables efficient online operation without dense priors or expensive preprocessing. Experiments with LiDAR and visual odometry backends demonstrate consistent improvements, with particularly strong gains under severe drift.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          CLFTv2: Efficient Camera-LiDAR Fusion for Semantic Segmentation via Hierarchical Feature Pyramids
 - **Authors:** Toomas Tahves, Mauro Bellone, Raivo Sell
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation for autonomous driving requires reliable detection of vulnerable road users (VRUs) despite heavy class imbalance. We introduce CLFTv2, a hierarchical camera-LiDAR fusion framework replacing global ViT attention with a Swin-based multi-scale encoder and a lightweight FPN-style residual decoder. Operating in the 2D perspective domain, CLFTv2 integrates multi-scale geometric cues through shifted-window attention and per-scale residual fusion, avoiding the computational overhead of query-matching decoders. Across three driving datasets, CLFTv2 consistently improves VRU recall. On ZOD, CLFTv2-Large achieves 53.5\% mIoU, improving pedestrian IoU from 35.5\% to 44.9\% over the prior CLFT model. On Waymo, CLFTv2 reaches 61.7\% mIoU. Additionally, a modality-isolation study suggests ViT's global receptive field yields stronger fusion gains only under dense LiDAR returns. Compared to a Swin-based Mask2Former adaptation, CLFTv2 requires 1.4$\times$ fewer GFLOPs and delivers 2.2$\times$ higher throughput, while achieving comparable overall accuracy. These results demonstrate that hierarchical local-attention fusion offers an efficient, scalable alternative to global-attention and query-based decoders for real-time on-vehicle perception in intelligent transportation systems. Source code is publicly available.
### Title:
          Robust Beam Prediction for V2X Networks with Multi-Modal Sensing
 - **Authors:** Chen Shang, Dinh Thai Hoang, Diep N. Nguyen, Jiadong Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrated sensing and communication (ISAC) provides a promising foundation for beam prediction in future vehicle-to-everything (V2X) networks. However, existing sensing-assisted beamforming methods still rely heavily on radio-frequency sensing, which may become unreliable in complex vehicular environments. Meanwhile, the growing availability of heterogeneous sensors, such as cameras and LiDAR, offers new opportunities to improve beam prediction through richer environmental perception. Motivated by this, this paper proposes a multi-modal beam prediction framework for V2X networks. Specifically, we develop BeamTransFuser, a hierarchical Transformer-based architecture that progressively fuses camera, LiDAR, radar, and GPS observations for robust beam prediction. In addition, to handle possible missing modalities in practical deployment, we introduce a generative module that reconstructs missing modality features from the available observations. Experimental results on a real-world multi-modal V2X dataset show that the proposed framework consistently outperforms representative baselines, while the generative module further improves robustness under incomplete sensing conditions.
### Title:
          Geometry Without Coordinates: LiDAR Diffusion as a 3D Feature Bridge
 - **Authors:** Samed Doğan, Nico Leuze, Alfred Schöttl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transferring the rich priors of large 2D foundation models to sparse 3D LiDAR remains challenging, as training native 3D foundation models at comparable scale is limited by data and annotation scarcity. We introduce a LiDAR-conditioned diffusion model trained on pseudo-labels from off-the-shelf 2D foundation models. The model supports multiple output modalities, including depth, semantic segmentation and instance prediction, selectable via a textual task prompt. Because the model is conditioned on LiDAR, both its outputs and its intermediate UNet features can be projected back onto the input point cloud, enabling analysis of a 3D representation learned entirely under 2D supervision. We study this representation directly in point-cloud space, explicitly excluding raw spatial coordinates to isolate feature content from projection geometry. Linear probes recover up to ~23% Mean Intersection over Union (MIoU) on 3D semantic classes, compared to ~3.5% for a matched Gaussian-noise control, indicating substantial non-trivial structure. Pairwise cosine similarity across modality-specific feature streams reveals a layered organization. Early encoder layers remain weakly aligned across modalities while individually decodable, intermediate layers converge toward a shared representation, and decoder layers re-specialize toward task-specific outputs. These findings indicate that LiDAR-conditioned diffusion models can induce structured 3D representations from 2D supervision alone, with a modality-dependent manifold that locally unifies near a shared bottleneck. This positions diffusion as a viable mechanism for transferring large-scale 2D priors into sparse 3D domains.
### Title:
          Odometer-Agnostic Drift Correction Using OpenStreetMap Lane Geometry
 - **Authors:** Joaquin Caballero, Emilio Garcia-Fidalgo, Alberto Ortiz, Jarno Ralli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite significant progress in odometry estimation, long-term drift remains a fundamental limitation of incremental pose integration, especially in large-scale or loop-free environments. Existing map-assisted methods can reduce drift, but often depend on dense maps, sensor-specific processing, or complex matching pipelines. We propose a lightweight open-source, odometry-agnostic correction method that aligns short trajectory segments to OpenStreetMap (OSM) lane centerlines. By formulating drift correction as a direct alignment between recent odometry and sparse lane geometry, the method enables efficient online operation without dense priors or expensive preprocessing. Experiments with LiDAR and visual odometry backends demonstrate consistent improvements, with particularly strong gains under severe drift.
### Title:
          Retrofitting Code Using LLMs to Support Exceptional Behavior
 - **Authors:** Linghan Zhong, Jiyang Zhang, Jayanth Srinivasa, Junyi Jessy Li, Milos Gligoric
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Exception Related Code (ERC), which includes throw statements, conditions (if statements) that guard those throw statements, and try/catch blocks, is an essential component of software systems, allowing developers to detect and handle exceptional states that deviate from the expected program behavior. However, manually writing ERC across large codebases is tedious. We propose a novel task: retrofitting existing code with ERC. Namely, given code (without ERC) and Exceptional Behavior Tests (EBTs) (e.g., check if method throws InvalidArgumentException if null is given as the value to the argument) we aim to automatically generate missing ERC, such that the given tests pass. We design and implement Exception Coder (EXCODER) that performs context engineering to help Large Language Models (LLMs) tackle this task. EXCODER integrates static and dynamic program analysis with LLMs by providing the extracted contextual information to the LLMs. To evaluate EXCODER, we build a benchmark constructed from GitHub Java repositories, where we systematically remove ERC in 304 methods from 75 projects. Our results demonstrate that EXCODER provides an effective, though imperfect, solution to this problem in automated code generation, offering developers the first way to implement ERC following test-driven development. When combined with Qwen 2.5 Coder 32b, EXCODER achieves pass@1, 5, and 10 rates of 85.92% (12.56 percentage points over baseline), 86.18% (12.82 p.p. over baseline), and 86.51% (13.15 p.p. over baseline), respectively, on developer-written test suites. Our manual inspection of the generated code further reveals limitations of EXCODER, pointing to directions for future work.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          RouteBridge: Reliability-Routed Bidirectional Distillation Between Neural Radiance Fields and 3D Gaussian Splatting
 - **Authors:** YuanHang Wang, Xin Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural radiance fields (NeRFs) and 3D Gaussian Splatting (3DGS) encode a scene with complementary inductive biases, but existing cross-representation distillation typically fixes one representation as teacher for the entire scene. A globally fixed teacher can propagate local reconstruction errors. We present RouteBridge, a bidirectional framework that selects the teaching direction for each ray. Its reliability estimator combines photometric residuals with representation-specific geometric evidence and routes supervision from NeRF to 3DGS, from 3DGS to NeRF, or abstains. A renderer-independent interface transfers color, opacity, and normalized depth without shared features or point correspondence. On mip-NeRF 360, the NeRF and 3DGS exports reach 28.56 and 28.77 dB, respectively. The 3DGS export improves over 3DGS by 1.56 dB and over NeRF-GS by 0.45 dB while reducing LPIPS to 0.207. On static three-view DTU, RouteBridge obtains 21.12 dB. Ablations show that both adaptive routing and geometric ray targets contribute to the improvement.
### Title:
          LinearMask-GS: Stable-Mask Importance Pruning for Compact 3D Gaussian Splatting
 - **Authors:** Donghun Ryu, Minhyeok Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) enables real-time novel view synthesis but produces millions of primitives through adaptive densification, leading to significant storage overhead. Learned-mask pruning methods such as LP-3DGS address this by assigning each Gaussian a learnable mask to identify and prune redundant primitives. However, we identify a limitation of this paradigm: the steep slope of the Gumbel-Sigmoid activation drives mask values to the extremes within the short mask-training window, before the importance ranking has stabilized, producing a sharply bimodal distribution from which that ranking can no longer be reliably recovered. We propose LinearMask-GS, which replaces Gumbel-Sigmoid with a linear increment activation that keeps mask values in a mid-confidence regime throughout mask training, producing a stable, unimodal mask distribution whose ranking tracks importance. On Mip-NeRF 360, our method achieves 3.6x and 1.6x Gaussian reductions over 3DGS and LP-3DGS, respectively, while maintaining or improving rendering quality. For outdoor scenes, it yields a 1.6x reduction (from 2.18M to 1.36M) with notable gains in PSNR (+0.38 dB), SSIM (+0.025), and LPIPS (-0.029).
### Title:
          View-Structured Conformal Prediction for 3D Gaussian Splatting
 - **Authors:** Junzheng Chu, Bin Pan, Zhenwei Shi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) renders novel views in real time, but an uncertainty heatmap does not certify that a rendered view meets a certain prediction coverage. We treat novel-view synthesis as structured regression and ask that, with probability at least $1-\alpha$, RGB prediction boxes cover at least a $1-\beta$ fraction of pixels in a new view. We propose View-Structured Conformal Prediction (VSCP). It splits the pre-calibration scale into a spatial shape from the renderer and a transferable view-difficulty factor, which predicts the smallest view-wise multiplier that shape needs. A held-out quantile over views (View-CP) then gives finite-sample validity even when transferring to new scenes. The same factorization makes the analysis exact: a conformity score is the ratio of oracle to predicted view difficulty, and excess width separates into a test-side and a calibration-side term. Across 13 real scenes, pixel-pooled calibration reaches 89.9\% marginal pixel coverage but only 61.4\% view-event coverage at a 90\% target, while View-CP reaches 91.7--92.0\%. At matched coverage VSCP cuts width by 22.1\% against a constant scale, and matches a ten-model ensemble's 21.0\% reduction using only one model per scene and four rather than ten rasterization passes per query. VSCP also improves on the closest single-model baseline, the 3DGS-U field, by 4.7 points ($p=0.0225$). The view predictor transfers from bounded source families to all nine unbounded Mip-NeRF~360 scenes. There the full scale beats the constant scale with 20.7\% width saving on all nine scenes. It also keeps an 18.3\% saving under a different densification backbone and runs at 216--280 FPS on an RTX~4090.
## Keyword: mapping
### Title:
          AccelMPC: High-Rate, Low-Power FPGA-Accelerated Model Predictive Control for Tiny Drones
 - **Authors:** Andrea Grillo, Brian Plancher
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unlocking the potential of tiny aerial robots requires order of magnitude improvements in the performance of embedded edge control. In particular, although recent cached model predictive control (MPC) solvers can handle the fast system dynamics and complex constraints required for agile drone flight, their computational demands remain prohibitive for resource-constrained robots, forcing prior implementations to operate at reduced control rates. AccelMPC overcomes this challenge through an end-to-end co-design approach that jointly optimizes the solver algorithm, numerical representation, hardware mapping, and physical integration. AccelMPC pairs a co-designed FPGA-accelerated alternating direction method of multipliers (ADMM)-based MPC solver with a custom 6g PCB, providing high-bandwidth communication for deployment on a 35g Crazyflie. Hardware experiments demonstrate 1 kHz onboard constrained MPC with dynamic obstacles, up to 15.6x faster solve times and 195.4x improvement in energy-delay product over state-of-the-art embedded microcontroller-based solvers, all while scaling to optimization problems with over 20,000 optimization variables and a comparable number of constraints. We release our PCB design files, firmware, and FPGA solver code open source.
### Title:
          Uncertainty-Aware Sea-Ice Type Mapping with Multiple Ice Charts
 - **Authors:** Samira Alkaee Taleghan, Younghyun Koo, Andrew P. Barrett, Farnoush Banaei-Kashani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sea-ice stage of development (SoD) describes the age and associated thickness of sea ice and provides important information for navigation, and operational ice monitoring. SoD labels are obtained from operational ice charts, where trained analysts interpret satellite observations and assign standardized stage codes to regions with similar ice conditions. These codes often represent ranges of compatible ice thicknesses rather than exact physical values. Deep-learning methods can automate SoD mapping and commonly adopt operational ice charts as reference labels for training. These annotations are not exact, however; this is because chart interpretation relies on analyst judgement and on the observations available at the time, so different ice services may assign different SoD labels to the same conditions. We term this variation across independently produced expert annotations multi-annotator label uncertainty; collapsing the annotations into a single deterministic target discards this variation. A second source of uncertainty originates in the learned model itself. In this paper, we quantify both sources: annotation uncertainty from disagreement among independent ice-service charts and model uncertainty from the learned predictive models. We then evaluate their relationship by testing whether model uncertainty is higher where ice services disagree. We observe that supervision incorporating information from multiple annotators can improve this correspondence, with soft supervision achieving the highest overall correlation of 0.256. The relationship becomes substantially stronger near the ice edge, where model predictive uncertainty closely tracks multi-annotator disagreement, reaching a correlation of 0.704 within 0--10 km. Among the uncertainty-estimation approaches, Monte Carlo dropout provides the best-calibrated confidence estimates, with an expected calibration error of 0.050.
### Title:
          Exploring 3D Glyph Physicalizations for Public Engagement through River Health
 - **Authors:** Maria Teresa Ortoleva, Min Chen, Rita Borgo, Alfie Abdul-Rahman
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Introduction: In this paper, we present the preliminary design of a toolkit for making glyph-based physicalizations for public engagement. We use London river health data as a case study: a data set of significance to urban issues related to climate change and of interest to draw public attention, as part of the Greater London Authority's strategies. Design: We present the components of a 3D glyph-making toolkit, its encodings, and a step-by-step process for crafting a physicalization of a river's water quality using recycled materials. We reason about how users can use the template to learn about a data set while reflecting on the data's significance to their personal experience and self-mapping onto the physicalization. Reflection: We reflect on the opportunities that extending the design space of glyphs to 3D physicalization offers for supporting public engagement with complex, multi-dimensional data sets, scaffolding cognitive processes, and self-reflection, thereby bringing crucial environmental data to life. Conclusion: Future implementation of the 3D glyph template will enable the public of all abilities to explore river health data, physicalize complexity, and realize its relevance. We hope that its use in public engagement workshops will help raise awareness, invite care, and foster a sense of belonging.
### Title:
          Prototyping QoE-Aware Rate Adaptation in Cellular Networks with Commercial Applications
 - **Authors:** Szilveszter Nádas, Lars Ernström, Dan Druta, Igor Pruzhansky, David Lindero, Jonathan Lynam, Eric Petajan
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Multimedia (cs.MM); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prior work has shown that QoE-aware resource sharing for real-time interactive video can support up to three times more simultaneous sessions at acceptable quality compared to rate-fair allocation. However, the required capabilities (QoE-targeted encoding, runtime spatial complexity estimation, and rich application-network APIs) are not yet available in commercial deployments. In this paper, we take an evolutionary approach: we design a system that delivers QoE-aware resource allocation using only capabilities that can be assembled in a lab today. We extend the utility-based allocation framework to the radio resource domain by introducing composite spatial complexity, which combines a session's video spatial complexity with its time-variant spectral efficiency into a single resource demand function. To operate with commercial real-time video streaming applications that use rate-based congestion control and lack capability to measure QoE, we use external tooling for QoE measurements. We develop an incremental reallocation algorithm with per-interval limits that encode both the congestion control algorithm's speed constraint and that spatial complexity estimates are reliable only near the current rate. The resulting prototype combines external QoE measurements with congestion-signal-based rate steering and does not require modification to commercial applications. We chart an evolution path from this prototype toward full QoE-aware resource sharing, mapping emerging standards (IETF SCONE, CAMARA, Media over QUIC) to the progressive capabilities they enable.
### Title:
          Geometric organization of olfactory descriptor data in the Poincaré disk
 - **Authors:** Aniss Aiman Medbouhi, Farzaneh Taleb, Giovanni Luca Marchetti, Danica Kragic
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Machine Learning (cs.LG); Applications (stat.AP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Odor quality is commonly represented using high dimensional descriptor profiles, yet their low dimensional organization remains unclear. We investigated whether a two-dimensional hyperbolic embedding can provide an interpretable representation of this structure. We applied hyperbolic metric multidimensional scaling to two complementary datasets: 480 Sagar rating profiles from three participants rating 160 odorants on 15 continuous descriptors, and 4983 GoodScents--Leffingwell molecules annotated with 138 binary descriptors. The embeddings substantially preserved pairwise descriptor distances, supporting subsequent analyses of radial and angular organization. In Sagar, rating profile entropy was strongly and negatively associated with hyperbolic radius, with diffuse profiles closer to the center and concentrated profiles closer to the boundary. This radial organization emerged primarily at the level of the full descriptor profile, rather than any individual descriptor, and remained robust across alternative descriptor representations, participant specific analyses, and averaged ratings. Sweet, musky, fruity, pleasantness showed the strongest directional trends. In GoodScents--Leffingwell, active label entropy, reflecting descriptor multiplicity, increased with radius, whereas orthogonalized descriptor entropy, reflecting spread across orthogonal modes, decreased with radius. Related binary descriptors occupied coherent localized high-density regions. These findings reveal complementary radial and angular organization in the hyperbolic representation of olfactory descriptor data. They support hyperbolic mapping as an interpretable descriptive framework in which radius summarizes global profile properties, while the angular component captures continuous descriptor gradients and categorical organization.
### Title:
          Marker-free eye-gaze estimation using a single image and depth from defocus
 - **Authors:** David Hurtubise-Martin, Feriel Fass, Djemel Ziou, Marie-Flavie Auclair-Fortier
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a marker-free eye-gaze estimation approach using a single 2D camera, such as an integrated laptop webcam. The gaze-related features are estimated from iris localization and head pose estimated by using depth from defocus. A variational Bayesian multinomial logistic regression framework is used as mapping from the estimated features to the position of regard, based on an 8-dimensional feature vector of head-pose and iris-displacement parameters. No external marker is needed. Experiments were conducted by estimating the gaze of people watching a computer screen at different distances and compared against five existing methods. The obtained scores demonstrate the effectiveness of the proposed approach.
### Title:
          Black-Box Red Teaming of Agentic AI: A Taxonomy-Driven Framework for Automated Risk Discovery
 - **Authors:** Divyanshu Kumar, Nitin Aravind Birur, Tanay Baswa, Sahil Agarwal, Prashanth Harshangi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic systems are rapidly moving to production, where they read untrusted inputs, call tools with real permissions, and act autonomously, expanding the security surface beyond chat-only models. Yet standard evaluations remain single-turn and fail to capture multi-step agent vulnerabilities. We present a systematic black-box framework for risk-aware agent evaluation requiring only basic system descriptions. Our approach introduces: (1) a seven-domain taxonomy mapping observable behaviors to risk categories, (2) fully automated SAGE-RT red teaming producing 120 adversarial scenarios per domain, and (3) human-validated evaluation using LLM judges. Empirical validation across two agent architectures (CrewAI and AutoGen) with four base models reveals alarming patterns: 56.25\% average governance risk, 65\% privacy risk in multi-agent configurations, and agent behavior vulnerabilities reaching 85\%. Our black-box approach effectively identifies critical architectural vulnerabilities without privileged access, providing a scalable path toward safer agent deployments.
### Title:
          With a Thermomix You Lose the Ability to Cook: A Kitchen Machine Analogy for Applications of Generative AI in Education
 - **Authors:** Nikol Rummel, Valentina Nachtigall, Ernesto Panadero
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid adoption of generative AI tools such as ChatGPT has sparked intense debate about their risks and opportunities for education, as well as the ways researchers should investigate them. In this paper, we approach these discussions through an analogy with the Thermomix, a smart kitchen appliance that has similarly provoked both enthusiasm and critique. By mapping Thermomix use cases onto examples of learning with generative AI, and situating them within the ICAP and SAMR frameworks, we show how different modes of tool use can either support or undermine meaningful engagement and learning. The Thermomix metaphor underscores that the central question is not whether learners employ AI, but how such use shapes their learning processes. In doing so, we provide a conceptual lens for researchers and practitioners to critically examine - and more effectively guide - the integration of generative AI into educational practice.
### Title:
          Contrastive Projection: Reading Transformer Internals by Differencing Logit Lenses
 - **Authors:** Olli Tuomi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reading a transformer's internal states in token space is easy to do and hard to trust: a logit lens on a single hidden state is dominated, at intermediate layers, by the generic tokens the model would predict for almost any input. We read the difference instead. Subtracting two closely matched prompts' hidden states and projecting through the unembedding cancels the shared component and surfaces what separates them, an operation equivalent to reading a RepE/ActAdd steering vector through a logit lens. Built into a training-free tracer that reads at every position, sub-layer, and head and averages over designed baselines, it traces a compound- noun MLP->attention chain in Phi-2, confirmed there by activation patching, with the same distinction recovered across three architectures by readout and probe rather than by patching; it reads what retrieval surfaces for real versus fictional entities, and reads metaphor as a set of domain-to-domain mappings rather than a single figurativity feature. A cross-seed control marks the boundary: across five networks differing only in initialization, the same distinction surfaces as almost entirely different tokens (top-10 overlap 0.08). What a computation looks like in token space is network-specific; the distinction it draws is not
### Title:
          OntologyAligner: Ontology-Aligned Retrieval and Hierarchy-Guided Large Language Model Reranking for Biomedical Ontology Normalization
 - **Authors:** Jie Song, Zhichuan Xu, Ziyu Lu, Meng Xiao, Cheng Bi, Yuxin Zhang, Xin Zheng, Xiaoran Li, Qiongfang Cao, Hao Yang, Bairong Shen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Biomedical ontology normalization maps free-text expressions to standardized concepts, enabling consistent integration and analysis of biomedical data. This task remains challenging because lexical variation and subtle distinctions among hierarchically related concepts can obscure concept boundaries. We present OntologyAligner, a three-stage framework that combines ontology-aligned retrieval, large language model candidate reranking, and selective hierarchy-guided refinement. We also construct PhenoNormBench, a unified benchmark comprising 13,390 samples from seven Human Phenotype Ontology datasets. OntologyAligner achieved state-of-the-art performance on HPO normalization, with 88.78% Macro Top-1 Accuracy and 86.75% Micro Top-1 Accuracy, exceeding the strongest baseline by 4.85 and 5.07 percentage points, respectively. Ablation analyses showed complementary contributions from all three stages, and sensitivity analyses demonstrated stability across candidate-set sizes and model backbones. Applications to MONDO, MEDIC, and NCBITaxon further established portability to other ontologies. OntologyAligner offers a generalizable framework for accurate mapping of biomedical text to structured ontology concepts. PhenoNormBench and the code are publicly available at this https URL.
### Title:
          CoGe-GCD: Reframing Generalized Category Discovery with Compositional Generalization
 - **Authors:** Luyao Tang, Jiewei Zheng, Kunze Huang, Chaoqi Chen, Yue Huang, Cheng Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalized Category Discovery (GCD) assigns unlabeled instances, mixed with labeled data, to known or novel categories, requiring human-like compositional reasoning: reusing primitives learned from known classes and deciding when new combinations imply new categories. Existing GCD methods operate on unstructured token features and struggle to extrapolate to novel compositions. We propose CoGe-GCD, which rethinks GCD through compositional generalization with two coupled stages. (i) Compositional Perception structures patch tokens by mapping them to a small vocabulary of primitives and refining token embeddings via competitive token-primitive assignment and information passing, yielding coherent groups for discovery. (ii) Generalizing Induction exploits the induced geometric structure and applies a structure-preserving calibration over spatial relations, maintaining probabilistic semantics while improving extrapolation to unseen primitive combinations. CoGe-GCD is implemented as an inductive-bias module between backbone and projection head, without modifying heads or losses, and can be plugged into diverse GCD frameworks. On standard benchmarks, it consistently improves all-class accuracy, unknown-class number estimation, and geometric quality, with marginal computational overhead. Code is available at this https URL.
### Title:
          Senseful Consense: Towards Simplified Cookie Banners using Plain Language
 - **Authors:** Minela Bećirović, Ha Dao, Mannat Kaur, Martin Johns, Alexandra Dirksen
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While the GDPR and ePrivacy Directive mandate that consent information must be clear and accessible, most modern cookie banners remain obscured by technical jargon, vague phrasing, and frequent content overload or underload. This feasibility study investigates the impact of applying plain language (Einfache Sprache) to cookie banners within the IAB Transparency & Consent Framework (TCF). In our study, we analysed cookie banner texts from 200 websites, using AI-based mapping to categorise extracted content into standardised processing purposes. By substituting complex legal terms with simplified descriptions, we successfully demonstrated that the comprehension barrier can be lowered from a college-graduate level to a 7th-grade level. However, the effectiveness of plain language is inherently constrained by the informativeness of the original content; it cannot compensate for banners that omit legally required details. We conclude that while plain language is a vital tool for digital accessibility, it must be paired with standardised implementation guidelines to ensure that cookie banners are both readable and informative.
### Title:
          The Semantic Bottleneck: Leveraging Semantic Representations for Non-Invasive Speech Decoding
 - **Authors:** Gilad D. Landau, Dulhan Jayalath, Oiwi Parker Jones
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Non-invasive speech decoding remains constrained by the low signal-to-noise ratio of neural recordings, which makes fine-grained reconstruction of phonemes or individual words difficult. Motivated by neuroscientific evidence that high-level semantic representations are distributed across cortical regions and evolve over slower temporal scales, we hypothesize that semantic content may provide a more suitable target for non-invasive decoding than low-level acoustic or lexical features. We introduce Brain2Semantics2Text, a method that reconstructs text through an intermediate semantic embedding space. Our model maps sentence-level MEG responses into a semantic manifold and then inverts the predicted embeddings into natural language. This semantic bottleneck enables recovery of high-level meaning without word-level alignment. We describe the core principles of the approach, its implementation, and the strategies used to mitigate the challenges of learning a reliable neural-to-semantic mapping. Finally, we compare against prior non-invasive Brain2Text methods and show improved sentence-level results.
### Title:
          CertiFlash: A Formal Verification Framework for Flash Translation Layers in Computational Solid State Drives
 - **Authors:** Harshita Gupta, Mayank Kabra, Rakesh Nadig, Nika Mansouri Ghiasi, Sahand Divsalar, F. Nisa Bostanci, Ataberk Olgun, Konstantinos Kanellopoulos, Jisung Park, Haiyu Mao, Abdullah Giray Yaglikci, Mohammad Sadrosadati, Onur Mutlu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Cryptography and Security (cs.CR); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-intensive applications move large amounts of data from storage to the compute unit, incurring significant data movement overhead. Storage-centric computing reduces this overhead by moving computation near or inside solid-state drives (SSDs). Enabling it requires modifying SSD policies, e.g., address translation and garbage collection, which are part of the Flash Translation Layer (FTL), the SSD's firmware. Modifying the FTL is error-prone. Because FTL logic has direct access to security-critical device components, even a functionally correct FTL can leak data between tenants, drop integrity tags, or assign a flash block to the wrong tenant. We show that a faulty FTL can corrupt the device state at five surfaces inside the SSD, and demonstrate them on a DaisyPlus OpenSSD. Prior work verifies individual FTL designs, but has two limitations. (1) It establishes only functional correctness, so a modified FTL can violate isolation, integrity, and ownership and still pass verification. (2) It is tied to a single FTL design, so every modification requires redoing every proof. We propose CertiFlash, a formal verification framework for FTLs, mechanized in the Rocq proof assistant, that gives designers a machine-checked proof of security and correctness. CertiFlash models an FTL as a deterministic state machine with a single global invariant over mapping, isolation, integrity, ownership, and allocation. We prove once, over a general FTL model, that (i) every FTL operation preserves the invariant and (ii) the model refines an idealized block device. For a new design, a designer discharges five hypotheses about its own operations instead of redoing either proof. Across four case studies, a designer adds 27 to 3,231 lines against a 16,489-line framework, significantly reducing the verification effort. CertiFlash is open source.
### Title:
          SceneHI: High-Resolution 3D-Consistent Scene Texturing with Controllable Illumination
 - **Authors:** Athanasios Tragakis, Marco Aversa, Daniela Ivanova, Chaitanya Kaul, Roderick Murray-Smith, Daniele Faccio, Paul Henderson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 SceneHI is a framework that lifts high-resolution, illumination-aware priors from 2D diffusion models to perform 3D texture synthesis. It is the first to demonstrate that high-resolution textures, previously limited to 2D synthesis, can be generated directly on 3D objects without model fine-tuning or optimization. Designed for complex, multi-object environments, SceneHI uniquely combines 3D-consistency, high-resolution fidelity, and physically plausible baked shadows within a single generative pipeline. To enforce strict geometric coherence, we introduce an exact analytical pixel-to-texel mapping that aligns diffusion trajectories across multiple viewpoints. We utilize High-Resolution Latent Textures (HRLTs) as a persistent canvas for gradually denoised textures, while camera views perform the denoising steps in latent pixel space. This ensures a shared base texture that can be subsequently refined to high resolution without compromising multi-view consistency. Finally, a light-aware generative pass embeds realistic geometry-consistent shadows directly into the atlases, bridging the gap to production workflows. SceneHI achieves high visual fidelity while reducing generation time by 80% compared to existing scene-level methods.
### Title:
          Beyond Weak Labels: Prompt-Guided Local Refinement for Weakly Supervised Water Segmentation in High-Resolution Multispectral Imagery
 - **Authors:** Muhammad Farhan Humayun, Mohammad Imangholiloo, Afifah Shah, Tomi Westerlund, Jukka Heikkonen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution water mapping supports environmental monitoring and related applications, but accurate pixel-level labels are difficult and costly to produce. Official hydrographic vectors provide scalable weak supervision, but they contain artifacts like boundary noise, temporal mismatch, and omissions of small water structures. We propose a two-stage framework for weakly supervised water segmentation in high resolution multispectral imagery. Stage 1 learns initial masks from rasterized vector pseudo-labels, and Stage 2 converts these masks into structured component-wise prompts for localized refinement. On a manually corrected validation set, refinement improves SegFormer-B0 from 0.9509 to 0.9535 IoU and U-Net from 0.9408 to 0.9486 IoU, with corresponding F1 gains from 0.9749 to 0.9762 and 0.9695 to 0.9736. It leads to sharper shorelines, reduced boundary spillover, and better thin-structure delineation. The results indicate that prompt-guided refinement can improve pseudo-label-based water segmentation by targeting local errors that are poorly captured by global training supervision.
## Keyword: localization
### Title:
          VANTAGE-Bench: Evaluating the Infrastructure AI Gap in Vision-Language Models
 - **Authors:** Zaid Pervaiz Bhat, Nimra Nayyar, Arihant Jain, Lap Fung Chan, John Suchanek, Yu Wang, Varun Praveen, Tomasz Kornuta, Vidya Nariyambut Murali
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As Vision-Language Models (VLMs) advance toward physical deployment, the focus has remained on action-oriented Embodied AI evaluated on subject-centric consumer video. This overlooks a pervasive class of Physical AI: Infrastructure AI, which relies on fixed cameras for open-loop insights like safety monitoring and operational logging. We introduce VANTAGE-Bench, a benchmark measuring this "Infrastructure AI Gap." It spans three operational domains (Logistics, Transportation, and Smart Spaces), unifies image and video evaluation across semantic, spatial, temporal, and spatio-temporal capabilities, and moves beyond multiple-choice to eight task formulations including dense captioning and spatio-temporal grounding. It adds a single-pass trajectory protocol for Single Object Tracking and, to our knowledge, the first such evaluation on fixed-camera infrastructure video, scored against specialist trackers. Annotation spans three regimes over 3,346 media assets: 3,342 video-task annotations, 4,281 image-grounding annotations, and 27,404 detection boxes. Evaluating 17 models zero-shot, we find the shortfall relative to consumer-centric benchmarks is concentrated, not general. Event verification, referring expressions, and temporal localization fall roughly 9 to 24 points at every model scale, while video question answering stays within 5.3 points of VideoMME and 2D spatial pointing shows no shortfall against BLINK. The temporal pillar is weakest in absolute terms: no system exceeds 55.7 mIoU on temporal localization or 37.3 SODA_c on dense video captioning. On tracking, frontier models come within roughly 5 points of specialist trackers over short horizons but separate as the horizon extends. Open-weight models lead 2D object localization outright, so neither scale nor proprietary access explains the pattern. Data, evaluation harness, and leaderboard: this https URL
### Title:
          Marker-free eye-gaze estimation using a single image and depth from defocus
 - **Authors:** David Hurtubise-Martin, Feriel Fass, Djemel Ziou, Marie-Flavie Auclair-Fortier
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a marker-free eye-gaze estimation approach using a single 2D camera, such as an integrated laptop webcam. The gaze-related features are estimated from iris localization and head pose estimated by using depth from defocus. A variational Bayesian multinomial logistic regression framework is used as mapping from the estimated features to the position of regard, based on an 8-dimensional feature vector of head-pose and iris-displacement parameters. No external marker is needed. Experiments were conducted by estimating the gaze of people watching a computer screen at different distances and compared against five existing methods. The obtained scores demonstrate the effectiveness of the proposed approach.
### Title:
          SEA-SpeechBench: A Large-Scale Multitask Benchmark for Speech Understanding Across Southeast Asia
 - **Authors:** Jingyi Liao, Wenyu Zhang, Zhuohan Liu, Yingxu He, Geyu Lin, Xunlong Zou, Shuo Sun, Syed Ali Redha Alsagoff, Ai Ti Aw
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of audio and multimodal large language models has unlocked transformative speech understanding capabilities, yet evaluation frameworks remain predominantly English-centric, leaving Southeast Asian (SEA) languages critically underrepresented. We introduce SEA-SpeechBench, to the best of our knowledge, the first large-scale multitask benchmark that evaluates speech understanding in 11 SEA languages through 97,194 samples across 99 evaluation sets and 597 hours of curated audio data. Our benchmark comprises 9 diverse tasks across 3 categories: speech processing (automatic speech recognition, speech translation, spoken question answering), paralinguistic analysis (emotion, gender, age, speaker recognition), and temporal understanding, a novel dimension featuring timestamped content queries and temporal localization within extended audio sequences up to 3 minutes. We implement multilingual prompting in both native SEA languages and English to reflect user interactions with audio-language models. Evaluation of leading open-source and proprietary systems reveals marked performance gaps. Across all models, performance remains underwhelming on temporal understanding, emotion recognition, and speech translation. Prompting in low-resource languages such as Burmese and Tamil lags behind English by up to 41 percentage points. Our findings expose critical model limitations and underscore the need for inclusive model development. The SEA-SpeechBench benchmark is available at this https URL.
### Title:
          XAgent: eXecution-guided Agentic AI for Effective Localization and Resolution of GitHub Issues
 - **Authors:** Hieu Huynh, Patanamon Thongtanunam, Michael Fu, Bach Le, Kla Tantithamthavorn
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic AI has enabled capabilities in leveraging Large Language Models (LLMs) to autonomously resolve repository-level GitHub issues. However, due to the reliance on limited static description of issues, existing agentic approaches suffer from incorrect localization and incomplete validation. Solely relying on this information can bias LLM reasoning toward the narrow scope of the issue description, leading to incomplete patches that fail to address the underlying issue. In this paper, we present XAgent, an execution-guided agentic framework that analyzes dynamic behavior and additional program context to localize and validate issues. The experimental results on the SWE-bench-lite dataset demonstrate that XAgent outperforms other existing approaches, achieving a resolve rate of 62.0% and a function localization accuracy of 72.8%, while maintaining cost efficiency. Our analysis further shows that XAgent successfully resolves 7 additional issues that the top existing baselines fail to address. This work highlights a shift from static, description-oriented patch generation toward dynamic execution-guided issue resolution, opening new opportunities for LLM-based coding agents to achieve more robust and generalizable software maintenance.
### Title:
          CrossLink: Breaking Location Privacy by Linking Device Identifiers Across Protocols
 - **Authors:** Aneet Kumar Dutta, Mihirraj Dixit, Kevin Gni, Wouter Lueks, Mridula Singh
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Smartphones simultaneously transmit temporary identifiers over LTE, WiFi, and BLE. Existing privacy defenses analyze identifier randomization per protocol, implicitly assuming that these protections compose across protocols. We show that they do not: Even when each protocol leaks only temporary identifiers and the adversary is fully passive, unsynchronized identifier rotations allow cross-protocol stitching of device traces. We present CrossLink, an uncertainty-aware tracing algorithm that links identifiers across time, space, and protocols under noisy localization and mobility. We evaluate CrossLink using controlled lab experiments with commodity devices and large-scale mobility simulation. Under large-scale mobility simulation, CrossLink reconstructs full traces for 83% of users, versus 22% for the best single-protocol baseline, showing that location privacy must be analyzed jointly across protocols. We further show that CrossLink remains effective under partial coverage: strategically placed sniffers near LTE handover regions, mobile sniffers, and limited high-coverage subregions retain sufficient cross-protocol evidence to bridge observation gaps, achieving substantially higher linkability than random deployments.
### Title:
          TrajMark: Ownership Attribution and Segment-Level Tamper Localization for Coding-Agent Trajectories
 - **Authors:** Bokang Zeng, Zheng Gao, Xiaoyu Li, Xiaoyan Feng, Jiaojiao Jiang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Watermarking the final patch produced by a coding agent provides provenance evidence for the submitted artifact, but does not authenticate the visible process that produced it. Behavioral watermarking methods primarily provide a global detection or identifier-recovery signal, so a locally edited trajectory may retain sufficient ownership evidence without revealing which protected region has become inconsistent. To address this limitation, we propose TrajMark, a training-free, symmetric-key, visible-only trajectory watermarking framework that separates robust ownership attribution from fragile local integrity verification. Our framework consists of two complementary layers: a sparse owner layer that encodes a six-bit deployment identifier by rewriting a keyed subset of naturally occurring READ actions into masked linear equations, and a localization layer that inserts linked Q12 ordinary, group, and terminal seals to commit to protected critical-action segments. This separation allows ownership evidence to accumulate robustly across trajectories, while local modifications perturb nearby keyed commitments and expose the affected protocol region. We further provide a design-level analysis of owner recoverability, integrity collision probability, structural overhead, and localization behavior. Across three coding-agent frameworks and three LLMs, TrajMark recovers the exact owner in all evaluated clean full-watermark batches. Under exhaustive eligible single-site attacks it detects 95.5%-100% of edits, and under random single-action corruption it localizes 95.8% of modified sites to an accepted protocol region rather than to the individual action. Owner marking adds no trajectory actions; the integrity layer adds explicit read-only seals, and matched Pass@1 is 26.9% versus 26.3% for unwatermarked runs.
### Title:
          IdeaAMBIG: Benchmarking Implementation-Critical Gaps in Research-Idea Specifications
 - **Authors:** Yiling Ma, Yilun Zhao, Sihong Wu, Manasi Patwardhan, Arman Cohan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A research idea may be novel, coherent, and scientifically plausible, yet its proposed method may remain insufficiently specified for faithful implementation. We study the codification readiness of implementation-facing research-method specifications, defined by whether they provide sufficient methodological information for a competent implementer or coding agent to construct the intended method without unsupported assumptions. We construct evidence-grounded specifications and their supported resolutions from papers, codebases, issue threads, and reproduction artifacts. We introduce IdeaAMBIG, a benchmark of 660 evidence-grounded instances: 163 real-world gaps from reproducibility reports and GitHub issues, and 497 controlled synthetic gaps injected into codification-ready references. IdeaAMBIG evaluates three capabilities: codification-readiness assessment, defect localization, and clarification action generation. Defect localization receives only the specification, whereas clarification additionally receives the annotated defect. Across 13 LLMs, the best model achieves 9.6% Macro Defect Recovery Rate on real-world instances but 80.6% Macro Clarification Action Success Rate when given the defect. In an oracle study, supplying the gold resolution raises the downstream codification-ready rate from 14% to 98%. Across all evaluated models, defect localization is the main bottleneck, with stronger clarification given the defect.
## Keyword: transformer
### Title:
          OpenDiscoveryTrace: Process Traces for Evaluating AI Scientist Workflows
 - **Authors:** Aayam Bansal, Keertan Balaji
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing benchmarks for autonomous AI scientists evaluate only final outputs---generated code, hypotheses, or papers---yet discard the reasoning process by which those outputs were obtained. This makes it impossible to audit scientific methodology, diagnose failure modes, or distinguish systematic reasoning from fortunate guessing. We present \textbf{OpenDiscoveryTrace}, a public dataset of 558 complete AI scientific agent trajectories that captures how models reason, not just what they produce. Each trajectory records a structured 9-field-per-step trace---including thoughts, tool calls, observations, errors, revision triggers, and self-reported confidence---as models execute 124 scientific tasks spanning drug discovery, materials science, genomics, and scientific literature analysis. The dataset covers seven models: three frontier models (GPT-5.4, Claude Opus 4.6, and Gemini 3.1 Pro; 124 trajectories each, fully balanced across domains and difficulty levels) and four open-weight models (Qwen2.5-7B, Mistral-7B-v0.3, Phi-3.5-mini, and Qwen2.5-1.5B; 30 each), plus 60 live-retrieval variant trajectories. Pilot analysis on 363 LLM-judged trajectories reveals that process traces expose behavioral differences invisible to output-only evaluation: all three frontier models achieve comparable success rates (84--89%), yet Claude Opus 4.6 produces 30$\times$ more errors than GPT-5.4 (2.5 vs. 0.08 per trajectory, $p < 0.0001$, Cliff's $\delta = 0.613$), with qualitatively different error profiles---66.7% tool misuse for Claude versus 83.6% reasoning errors for GPT-5.4. We define five benchmark tasks with baselines from logistic regression, random forests, LSTMs, and Transformer models. The dataset, trace schema, agent harness, and benchmark definitions are publicly available under CC BY 4.0 to support research on process-level evaluation, scientific agent auditing, and AI governance.
### Title:
          Efficient Fairness Auditing Across Guidance Scales in Text-to-Image Diffusion Models via Causal Abstraction
 - **Authors:** Nabila Tasfiha Rahman, Rajatsubhra Chakraborty, Depeng Xu, Lu Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fairness auditing of text-to-image diffusion models often requires generating large numbers of images across sampling configurations, making comprehensive evaluation computationally expensive. We propose a causal-abstraction-based audit instrument for efficiently evaluating fairness under interventions on the classifier-free guidance scale. Given a fixed prompt and a target feature function, we represent the diffusion process as a low-level structural causal model and construct a corresponding high-level model over abstract denoising states. We characterize the projected causal structure, establish identifiability of the fairness-relevant interventional query, and provide sufficient conditions under which the high-level model preserves this query. A probabilistic transformer implements the high-level model as an amortized predictor of target-feature distributions across guidance scales. Experiments evaluate distributional fidelity, fairness-query accuracy, and computational efficiency. We present two auditing demonstrations: one using standard Stable Diffusion 1.5 and another using StayFair, a fairness-enhanced Stable Diffusion model, to examine their behavior across guidance scales.
### Title:
          BuzzASR: A Swarm of 100+ Monolingual Speech Recognition Models
 - **Authors:** Shivam Singh, Aditya Yadavalli, Catherine Arnett, Alex Warstadt
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce BuzzASR, a collection of language-specialized fine-tuned Whisper models adapted for automatic speech recognition (ASR) in 102 languages. Large end-to-end Transformer-based ASR models such as Whisper have revolutionized ASR, but most prominent models are highly multilingual. As a result, these models often perform poorly on languages less well-represented in their training set. While it has long been known that effective language adaptation can be achieved through simple fine-tuning on monolingual data, this strategy has only been applied to a small number of languages. We massively scale up this simple approach to 102 languages covered in the FLEURS dataset, while also implementing a more complex language adaptation strategy that integrates monolingual tokenizer replacement and data augmentation using text-only fine-tuning. BuzzASR models outperform Whisper-large-v3 on 77 out of 102 languages, reducing character error rates (CER) by a factor of over 2.8 on average. Our models achieve state-of-the-art CER among open-source systems on 27 of 102 languages on the combined FLEURS and Common Voice test set. Our tokenizer replacement strategy yields an average 3.3x improvement in compression rate (characters per token) over Whisper's multilingual BPE, with gains of up to 21.7x. We release all models, code, and detailed results: this https URL
### Title:
          JEPA Policy: Diffusion-Free Imitation Learning via Paired Action and Future Representation Prediction
 - **Authors:** Jie Xu, Kangjin Yu, Ziyi Jin, Junjie Gao, Liqing Chen, Yixian Li, Shuai Tian, Zhongpu Xia
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard behavior cloning supervises actions without explicitly constraining the future representation paired with each demonstrated action chunk. We introduce JEPA Policy, a diffusion-free framework that uses the action chunk and its observed future representation as paired training targets. Action and future-representation tokens interact in a shared Transformer and are refined through two forward passes. Future prediction can therefore shape the representation used to generate actions. Dual-branch and gradient-routing controls attribute the gain to this shared topology rather than to an auxiliary prediction head alone. Across nine simulated tasks, JEPA Policy improves mean success over the action-only MIP baseline and outperforms Diffusion Policy under the evaluated configurations, while adding 0.29 ms to MIP's model latency. A five-task, 630-episode physical-robot study produces the same pooled ranking. Further audits find no complete representation collapse under action supervision and identify a task-conditioned failure-ranking signal in future-prediction error. These results support paired future-representation supervision as a practical approach to low-latency visuomotor imitation without iterative generative sampling.
### Title:
          EFQ-Softmax: Exp-Free Quantization for Softmax
 - **Authors:** Haohui Han (1), Yuming Wan (2), Hongni Wang (3), Pengcheng Xie (2), Xiaodong Yan (1), Runqi You (1), Wencong Zhang (1) ((1) Xi'an Jiaotong University, (2) Huawei Technologies Co., Ltd, (3) Shandong University of Finance and Economics)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-bit attention accelerates Transformer inference by moving the $QK^\top$ and $PV$ matrix multiplications to FP8 or FP4 matrix engines. However, the softmax path often evaluates shifted-score exponentials in higher precision, forms a temporary probability block, and quantizes it before low-bit $PV$ multiplication. This exp-then-quantize path creates a mismatch between a high-precision probability producer and a low-bit matrix consumer. We propose EFQ-Softmax (Exp-Free Quantization for Softmax), a low-bit probability-generation method that directly maps shifted attention scores to block-scaled E2M1 operands. For each microscaling block, EFQ-Softmax selects an exponent-only scale from the local maximum, maps the shifted scores to a normalized residual domain, and generates nonnegative E2M1 probability codes using a single affine rule. The resulting operand is used consistently in both the $\widetilde{P}V$ numerator update and the $\widetilde{P}\mathbf{1}$ denominator update. The FlashAttention-style row-maximum update, historical rescaling, high-precision accumulation, and final normalization remain unchanged. We evaluate end-to-end quality on Qwen3-8B, Qwen3-VL-8B-Instruct, and WAN2.2-TI2V-5B, and separately measure kernel-level performance on the A5 vector unit. EFQ-Softmax improves the Qwen3-8B seven-task mean from 0.6749 with MXFP4 to 0.6773 and the Qwen3-VL nine-task mean from 0.7826 to 0.8000. On WAN2.2, it maintains temporal consistency and visual quality comparable to the FP16 and MXFP4 baselines under VBench. On the A5 vector unit, EFQ-Softmax reduces the vector-stage latency of the fused probability-generation kernel by 40.33% on average across sequence lengths from 16K to 128K. These results show that direct low-bit probability generation can replace the conventional exp-then-quantize path while preserving end-to-end model quality.
### Title:
          Can Artificial Intelligence Support Healthcare and Mental Health Through Early Cyberbullying Detection ? The Impact of Emotion-Aware AI on Proactive Online Safety
 - **Authors:** Hamed Jelodar, Amir Firouzi, Yen-Wu Lo, Maryam Tanha, Sajjad Dadkhah
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Healthcare systems, mental health, and public well-being are increasingly affected by cyberbullying and harmful online interactions. This paper presents CareGuard, an early-warning framework designed to support healthcare-driven mental health protection and proactive online safety through the detection of cyberbullying-related content using advanced natural language processing techniques. CareGuard integrates zero-shot semantic labeling with fine-tuned transformer-based models, including BERT, DistilBERT, and RoBERTa, to enable robust and context-aware classification across sensitive cyberbullying categories. To improve efficiency and reduce unnecessary computation in healthcare-oriented monitoring settings, the framework incorporates an emotion-aware filtering mechanism alongside cosine similarity-based semantic screening, allowing the system to focus on semantically relevant and emotionally salient content. Experimental results on benchmark datasets demonstrate that CareGuard effectively balances detection accuracy and computational efficiency, highlighting its potential for scalable deployment in healthcare systems, mental health monitoring, and online safety applications.
### Title:
          Learning-Aided Short Code Design for ISAC based on MIMO-OFDM
 - **Authors:** Mingcheng Nie, Shuangyang Li, Geng Wang, Peng Cheng, Shenghong Li, Chang Liu, Giuseppe Caire, Yonghui Li
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a deep learning (DL)-based coded waveform design for integrated sensing and communications (ISAC), enabling flexible trade-offs between communication reliability and ranging accuracy in short-block transmissions. The proposed scheme is built upon a practical multiple-input multiple-output orthogonal frequency-division multiplexing (MIMO-OFDM) architecture, where the communication channel state information and the angles of the static targets are assumed available at the transmitter. A transformer-based transmitter encodes input information bits directly into ISAC transmit waveforms to jointly optimize the bit error rate (BER) performance and the delay modified Cramer-Rao bound (MCRB). A corresponding transformer-based receiver is adopted at the communication side to recover the transmitted information bits. We further examine the learned codewords for communication-oriented and sensing-oriented designs, revealing that a balanced ISAC waveform naturally exhibits an intermediate structure between these two extremes. Numerical results illustrate these codeword structures and demonstrate that the proposed design provides substantial trade-off gains over conventional schemes based on standard channel coding and modulation.
### Title:
          TempTPI: Informer-Based trajectory prediction for maritime vessels
 - **Authors:** Kevin Ferneding, Veronika Lietavcova, Aleksandra M. Blachowiak, Peder Heiselberg
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate long-term trajectory prediction for maritime vessels is essential for safety and logistical efficiency. While deep learning models, particularly Transformers, have shown promise in processing Automatic Identification System (AIS) data, they often struggle with the quadratic computational complexity of self-attention and the loss of accuracy over extended forecasting horizons. This study proposes TempTPI, a novel prediction framework that integrates an Informer-based encoder with a multi-channel temporal encoding mechanism. The Informer architecture leverages a ProbSparse self-attention mechanism to reduce computational overhead and focus on the most significant dependencies, while the temporal encoder utilizes Fourier-like frequency expansions to capture cyclic patterns (hourly, daily, and seasonal) in vessel behavior. We evaluate our model against the state-of-the-art TPTrans architecture using AIS data from Danish waters. Experimental results demonstrate that TempTPI consistently outperforms existing methods across prediction windows of 1 to 5 hours. Notably, at a 5-hour horizon, the proposed model achieves a 55% improvement in Mean Squared Error (MSE), offering a robust solution for long-range maritime situational awareness.
### Title:
          Pretraining and Distillation Matter More Than Architecture Family for Label-Free Single-Cell Classification
 - **Authors:** Philip Graemer, Giuseppe Di Caprio
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Choosing a deep learning architecture for label-free single-cell classification remains an open question, with microscopy benchmarks reporting conflicting conclusions about CNNs versus transformers. We present a controlled benchmark on LIVECell phase-contrast microscopy data using source-image-disjoint train/validation/test splits to prevent parent-image leakage and matched optimisation, augmentation, and evaluation protocols across EfficientNet, Vision Transformer (ViT), and EVA-02 models. This allows the effects of architecture, pretraining, fine-tuning, tokenisation, and distillation to be disentangled. We find that the previously reported CNN advantage is largely explained by pretraining rather than architecture: the smallest pretrained model outperforms the strongest model trained from scratch despite far fewer parameters. Pretraining improves macro-F1 by 3-4 points, while the gap between the best pretrained CNN and transformer is below 0.5 points. Architectural choices nevertheless matter: ViT-S/8 outperforms ViT-S/16 and matches the four-times-larger ViT-B/16 at a quarter of the parameters, showing that finer tokenisation benefits small cell crops. Conversely, layer-wise learning-rate decay, central to the EVA-02 fine-tuning recipe, degrades performance, highlighting that transfer heuristics from natural-image recognition may not generalise to microscopy. Finally, knowledge distillation substantially improves the deployment frontier: compact EfficientNet-B0 students distilled from teacher councils outperform every individually trained backbone, including the EfficientNet-B5 and EVA-02 teachers. Overall, our results show that rigorous control of pretraining and evaluation is essential for interpreting biomedical architecture benchmarks, while distillation may be a more effective route to practical single-cell classification than architecture choice alone.
### Title:
          Forward-Free LLM Depth Pruning via Weight Redundancy
 - **Authors:** Vincent-Daniel Yun, Woosang Lim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Depth pruning reduces large language model (LLM) inference cost by removing complete Transformer blocks. Activation-based methods collect hidden states through forward passes on calibration data, while existing forward-free methods score each Transformer block separately without measuring similarity between blocks. We propose Weight-Redundancy Pruning (WRP), a forward-free depth-pruning method that estimates inter-layer redundancy from checkpoint weights to select blocks without calibration data or model forward passes. WRP compares attention output and MLP down-projection weights across layers and combines their pairwise similarities with relative projection-scale information. The resulting all-pairs similarity matrix guides layer grouping and block selection. Across multiple pruning settings, model families, and downstream tasks, WRP consistently outperforms existing forward-free magnitude pruning and approaches the performance of activation-based methods.
### Title:
          Decision Transformer for UAV-Mounted RIS-Assisted Dynamic D2D Communications
 - **Authors:** Yaxuan Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies unmanned aerial vehicle (UAV)-mouted reconfigurable intelligent surface (RIS)-assisted device-to-device (D2D) communication with stochastic link activation. It models UAV motion and attitude, time-varying Rician angles, and angle-dependent RIS reflection. A joint optimization of UAV trajectory, attitude, and RIS phases is formulated to maximize average sum rate under mobility, energy, and hardware constraints. The problem is addressed using deep reinforcement learning and a Decision Transformer trained on expert trajectories from multiple scenarios. Results demonstrate effective cross-scenario generalization, with zero-shot transfer outperforming direct DRL transfer and online fine-tuning achieving competitive performance with fewer interactions.
### Title:
          Contrastive Projection: Reading Transformer Internals by Differencing Logit Lenses
 - **Authors:** Olli Tuomi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reading a transformer's internal states in token space is easy to do and hard to trust: a logit lens on a single hidden state is dominated, at intermediate layers, by the generic tokens the model would predict for almost any input. We read the difference instead. Subtracting two closely matched prompts' hidden states and projecting through the unembedding cancels the shared component and surfaces what separates them, an operation equivalent to reading a RepE/ActAdd steering vector through a logit lens. Built into a training-free tracer that reads at every position, sub-layer, and head and averages over designed baselines, it traces a compound- noun MLP->attention chain in Phi-2, confirmed there by activation patching, with the same distinction recovered across three architectures by readout and probe rather than by patching; it reads what retrieval surfaces for real versus fictional entities, and reads metaphor as a set of domain-to-domain mappings rather than a single figurativity feature. A cross-seed control marks the boundary: across five networks differing only in initialization, the same distinction surfaces as almost entirely different tokens (top-10 overlap 0.08). What a computation looks like in token space is network-specific; the distinction it draws is not
### Title:
          Multimodal Emotion Recognition in Conversations via Class-Wise Adaptive Modality Fusion and Affective Geometry
 - **Authors:** Oriol Marín, Roger Marí, Gloria Haro, Rafael Redondo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emotion Recognition in Conversations (ERC) requires integrating heterogeneous textual, audio, and visual cues while accounting for conversational context and emotional dynamics. We extend the Self-Distillation Transformer architecture for ERC with appearance+geometry visual representations, class-wise adaptive modality fusion, and a valence-arousal prior for affective transitions. On the MELD and IEMOCAP datasets, geometry-enhanced visual representations improve weighted F1 by 0.27 and 4.36 points over appearance-only features, respectively, while class-wise adaptive fusion provides further gains of 0.17 and 0.25 points over the original softmax gate. The valence-arousal prior yields targeted improvements of 0.30 and 0.74 accuracy points on emotionally shifted utterances while preserving performance on stable turns. These results indicate that structured facial cues, emotion-dependent modality weighting, and affective geometry provide complementary benefits for multimodal ERC.
### Title:
          Adversarial Training for Tabular Credit Scoring: A Multi-Attack Robustness Evaluation in P2P Lending
 - **Authors:** Gijs A. F. Niewzwaag, Marijn G. S. Veth, Manuele Massei, Marcos R. Machado
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Risk Management (q-fin.RM); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning-based credit scoring is increasingly central to Peer-to-Peer (P2P) lending, yet its resilience to adversarial manipulation, where applicants strategically alter self-reported inputs to secure favourable decisions, remains poorly understood. Most adversarial-robustness evidence comes from image and text domains and evaluates a single attack against a matching defence, offering little guidance on how defences generalise across attack types in tabular credit data. We address this with a systematic train-test robustness benchmark on a large Lending Club subset, spanning three model families (logistic regression, a feed-forward neural network, and a transformer for tabular data) and four attacks confined to applicant-mutable features: Fast Gradient Sign Method (FGSM), Projected Gradient Descent (PGD), Salt-and-Pepper (S&P) noise, and DeepFool, plus a mixed-attack regime. Across a full grid evaluated with stratified cross-validation, adversarial training sharply improves robustness against the attack it is trained on and transfers well within the gradient-based family, but transfers weakly to non-gradient corruption, so single-attack defences overstate real-world resilience. Mixed training delivers the most balanced robustness across heterogeneous attacks while preserving clean-test performance, supporting multi-attack stress testing in credit-model governance.
### Title:
          Multi-Functional Embedding Models for Funder Name Disambiguation in Scientific Publication Records
 - **Authors:** Kanyao Han, Zhiwen You, Jinseok Kim, Jana Diesner
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the historical allocation and distribution of research funding advances our knowledge of how scientific research is supported across fields, institutions, and regions. However, large-scale analyses are hindered by the lack of comprehensive funder name disambiguation solutions, as funder names often exhibit spelling variations, translations, abbreviations, and inconsistent levels of granularity. In this paper, we present a framework for developing multilingual, multi-functional funder name disambiguation models and demonstrate its application to research publications in biodiversity conservation. To construct a training dataset, we integrated the Research Organization Registry (ROR), which provides unique identifiers for research organizations, with two publication datasets: the Web of Science (WoS) and the Crossref Open Funder Registry (OFR). We used multi-task learning with Contrastive Loss and Multiple Negatives Ranking Loss to fine-tune three open-weight embedding models from the Sentence Transformer, Gemma, and Qwen3 families. The best-performing models achieved accuracy above 0.90 when matching WoS funder names to ROR identifiers, outperforming general-purpose LLMs, including GPT-5.2, Claude-Sonnet-4.6, and Gemini-2.5-Flash, by more than 0.1. For funder names not indexed in ROR, we constructed a similarity network among funder names and identified clusters within it. Finally, we analyzed the disambiguation results and highlighted challenges arising from limited knowledge of smaller funders and funders from non-English-speaking countries. This work provides a reusable framework for funder name disambiguation with potential applicability across different model architectures and datasets, featuring cost-effective training data creation and multi-task learning and disambiguation.
### Title:
          Elastoformer: Enabling Dynamic Adaptivity via Elastic Model Transformation
 - **Authors:** Sudaksh Kalra, Dolly Sapra
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Performance (cs.PF); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 EdgeAI systems are increasingly employing computer vision applications to enable intelligent, on-device decision-making in real-time. However, these deployments face highly dynamic operational conditions, with fluctuating constraints on latency, power availability, and memory resources. Deep Neural Networks (DNN), which follow fixed computational execution flows, lack the flexibility to adapt to such variability, resulting in inefficient and suboptimal performance in edge scenarios. This underscores the need for architectures that are not only efficient but also dynamically scalable at runtime. In this paper, we propose Elastoformer: A framework that transforms conventional neural networks (NN) into Elastic NN capable of real-time elastic inference. Unlike the conventional bag-of-models approach, which requires maintaining multiple independent models for different operating conditions, Elastoformer offers a single, modular solution that dynamically switches between multiple modes of operation at runtime, adapting efficiently to the changing computational budgets of edge devices without the overhead of managing separate models. Experiments reveal that our framework achieves up to 85% reduction in computation FLOPs, 50% reduction in latency and 76% reduction in memory overhead, while showcasing the architecture agnostic nature of the framework across both Vision Transformers and CNNs. Our code is available at this https URL.
### Title:
          MedDeID enables locally governed clinical-text de-identification from real or synthetic training data
 - **Authors:** Stig Hellemans, Tom Stroobants, Elyne Scheurwegs, Pieter Meysman, Philippe G. Jorens, Kris Laukens
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Clinical notes contain personally identifiable information (PII), restricting reuse for research and medical AI, especially when data cannot leave an institution. We developed MedDeID, an on-premises framework combining in-house annotation and synthetic-note generation with model training, inference, pseudonymisation and evaluation. On an independently annotated, adjudicated 300-note Dutch hospital benchmark, a hospital-trained compact transformer detected 98.9% of identifying text while redacting 0.24% of text outside annotated identifiers; a synthetic-only counterpart detected 96.1%. On 100 primary-care notes, the synthetic-trained model achieved higher recall than the hospital-trained model (90.3% versus 87.0%) and greater robustness to identifier-format perturbations. An English instantiation trained without real text detected 99.7% and 98.9% of annotated identifier characters on two external synthetic benchmarks. These results demonstrate transfer of the workflow to another language, but not clinical English performance. MedDeID provides a route to locally governed de-identification using real or synthetic training data.
### Title:
          A Systematic Evaluation of Molecule Generation Models for De Novo Drug Design: From Benchmarks to Practical Insights
 - **Authors:** Xinrui Xu, Xueer Wang, Dan Luo, Sisi Yuan, Xuan Lin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Molecule generation has emerged as a powerful computational tool for de novo drug design, enabling the exploration of chemical space beyond the limits of conventional virtual screening. The field has progressed rapidly, driven by advances in molecular representations, generative architectures, and target-aware modeling strategies. However, existing reviews typically address specific model families or application scenarios in isolation, rather than offering an integrated perspective on how these components collectively form a coherent generation workflow. In this review, we present a comprehensive evaluation of molecule generation models for de novo drug design, covering 82 methods across five deep generative frameworks, including recurrent neural network (RNN)- and Transformer-based models, variational autoencoders (VAEs), generative adversarial networks (GANs), flow-based models, and diffusion models. We first summarize widely used benchmarks and molecular representations, and then examine the methodological principles underlying both general and pocket-conditioned generation. A central contribution of this work is a systematic synthesis and comparative analysis of reported performance across commonly used benchmarks and evaluation metrics. We also summarize representative experimentally validated case studies. Looking ahead, we discuss future directions in standardized 3D data, interaction-aware generation, receptor flexibility, and multi-objective molecular design, with the aim of improving the reliability and experimental relevance of molecule generation. All collected benchmark resources, evaluation metrics, and model references are provided in a publicly accessible repository at this https URL.
### Title:
          TransGaze-Object: Transformer Based Driver Gaze Object Prediction Framework in Real Driving
 - **Authors:** Pavan Kumar Sharma, Ayush Pande, Pranamesh Chakraborty
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Driver gaze provides information regarding driver visual attention and situational awareness to the surrounding traffic. Existing driver gaze estimation studies represent gaze in terms of gaze zone or gaze vector/point-of-gaze (PoG). However, object-level gaze information provides a more semantically meaningful representation of visual attention by identifying attended objects, such as vehicles, pedestrians, or traffic signals. In this study, we propose an end-to-end driver gaze object prediction framework, TransGaze-Object, Transformer-based Gaze Object prediction model. The proposed framework first extracts facial features, including face and iris-weighted eye features, along with trafficobject spatial features. A transformer based cross-attention mechanism is then used to compute similarity scores and attention weights for predicting the drivers gaze object. To train this model, we propose a benchmark driver gaze dataset, Urban Driving-Face Scene Gaze (UD-FSG), comprising synchronized driver-face and traffic-scene images, scene objects bounding boxes, and gaze labels in terms of 2D gaze coordinate and gaze object. The TransGaze-Object model achieves an overall accuracy of 60% for gaze-object prediction, compared to 51% accuracy obtained from associating the estimated Point-of-Gaze to traffic objects. The error analysis reveals that TransGaze-Object reduces confusion between traffic objects (predicted) and the background (ground-truth), achieving an error rate of 11.68%, a 49.7% relative reduction compared with 23.21% error obtained from PoG-based gaze-object association. Overall, the results demonstrate the effectiveness of directly predicting gaze objects from driver-face and traffic-scene information, rather than estimating an intermediate Point-of-Gaze and subsequently associating it with traffic objects.
### Title:
          Sound Debloating of Redundant Checks in Zero-Knowledge Machine-Learning Circuits
 - **Authors:** Zhantong Xue, Pingchuan Ma, Zhaoyu Wang, Yuguang Zhou, Huaijin Wang, Shuai Wang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-knowledge (ZK) proof systems for neural-network inference compile the model into a system of arithmetic constraints. Many of these constraints are redundant checks: range proofs, sign lookups, and bit decompositions who are globally entailed by the rest of the circuit through chains of reasoning that span distant gadgets. Removing them shrinks the circuit and accelerates proving, but the removal must be carefully justified: an unsoundly debloated circuit becomes forgeable, accepting witnesses the original would have rejected and so allowing a prover to claim, for example, that a neural network produced an output it never actually computed. Such soundness vulnerabilities are not hypothetical: under-constrained circuits in deployed ZK systems have enabled attackers to forge transactions and bypass verification entirely. We present an automated framework that removes redundant checks while provably preserving soundness. For each candidate removal, our tool first checks whether the rest of the circuit, on its own, can still rule out every value the removed check was excluding. Using whole-circuit abstract interpretation, the analysis searches for such alternative justifications and records them in a provenance graph; a check is then removed only when an alternative path through the graph still derives the facts that it is checking. This ensures that the debloated circuit opens no new forging strategy to an adversary. We evaluate circuits spanning MLP, CNN, RNN, and transformer architectures generated by two production frameworks (ezkl and zkml), with up to 25.3 million constraints. Our tool removes up to 48.7\% of constraints and reduces prover time by up to 72.8\%, without weakening security.
### Title:
          Politics of Feelings: Emotional Expression and Legislative Effectiveness in the U.S. Congress
 - **Authors:** Segun Aroyehun
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emotions are a pervasive feature of political communication, yet existing research has focused primarily on describing patterns of emotional expression rather than examining whether they are associated with consequential legislative outcomes. We address this gap by investigating the expression and correlates of discrete emotions in more than 1.7 million speeches delivered in the U.S. Congress between 1973 and 2024. Using a transformer-based emotion classifier, we measure eight discrete emotions: anger, fear, disgust, sadness, joy, enthusiasm, pride, and hope. We examine how these emotions vary over time, across policy topics, legislator characteristics, and their relationship with legislative effectiveness. We find that congressional speeches are becoming emotionally expressive over time. Emotional expression also varies systematically across policy domains and ideological positioning of legislators. Notably, the relationship between emotional expression and legislative effectiveness depends on the specific emotions expressed: enthusiasm and pride are positively associated with effectiveness, whereas anger exhibits a negative association. Emotional valence and emotional diversity are positively associated with legislative effectiveness, while emotional intensity is negatively associated with legislative effectiveness. These findings demonstrate that computationally derived measures of discrete emotions can provide insight into affective dimensions of legislative speeches and facilitate our understanding of how legislators communicate, interact, and perform within democratic institutions.
### Title:
          Robust Beam Prediction for V2X Networks with Multi-Modal Sensing
 - **Authors:** Chen Shang, Dinh Thai Hoang, Diep N. Nguyen, Jiadong Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrated sensing and communication (ISAC) provides a promising foundation for beam prediction in future vehicle-to-everything (V2X) networks. However, existing sensing-assisted beamforming methods still rely heavily on radio-frequency sensing, which may become unreliable in complex vehicular environments. Meanwhile, the growing availability of heterogeneous sensors, such as cameras and LiDAR, offers new opportunities to improve beam prediction through richer environmental perception. Motivated by this, this paper proposes a multi-modal beam prediction framework for V2X networks. Specifically, we develop BeamTransFuser, a hierarchical Transformer-based architecture that progressively fuses camera, LiDAR, radar, and GPS observations for robust beam prediction. In addition, to handle possible missing modalities in practical deployment, we introduce a generative module that reconstructs missing modality features from the available observations. Experimental results on a real-world multi-modal V2X dataset show that the proposed framework consistently outperforms representative baselines, while the generative module further improves robustness under incomplete sensing conditions.
### Title:
          Through the Looking Glass: Directly Reading and Writing Transformers
 - **Authors:** Mark Oskin
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How many of a transformer's components decide a token? Counted by the absolute value of each unit's and channel's contribution to the logit, one prediction rests on thousands to hundreds of thousands of them. But contributions are signed, and across eighteen models the mass pushing away from the predicted token is a median of seven times the mass carrying it. Divide by the net and the count is dozens: on the baseline, 53 components carry ninety percent of a prediction, 13 it cannot survive losing, and 8 suffice to produce it alone. Across twelve models trained elsewhere, 124M to 7B parameters, the sufficient set runs from two components to sixteen, and what a prediction draws on, followed all the way back, is one to three percent of the model, a share that does not grow with size. Three quarters of a layer's update is a fixed linear map of the state it received. Everything is read from the model's own parameters and activations, with nothing trained or fitted, and it names a component on both sides: what it writes, from the predictions it drives, reaching close to half of every model; what it reads, from its weights in the frame of its own layer, at 58.9 percent above chance over its eight strongest inputs. Sorting the remainder by upstream source yields grammatical categories the embedding cannot see. A name can be acted on. An association the model does not hold installs into one spare unit, key and value read from the weights, for a quarter of a percent of held-out loss, a fortieth of what a rank-one update costs. An installed attention head and a unit two layers above it make an edit fire only where a token occurred earlier in the context, and a unit the model trained for itself is driven from two layers upstream, 86 percent of the effect passing through it. An order-preserving activation puts a unit's inputs at the instrument's ceiling, at the price of a two-part install.
### Title:
          Training Trajectories Determine Circuit Removability in Annealable Soft-Prior Transformers
 - **Authors:** Zonglin Yang, Ziming Zhao, Wei Tang, Xunyu Jiang, Yihong Liu, Tailin Chen, Zifu Yu, Jiayu Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Soft positional priors can help small Transformers learn retrieval circuits, but it is unclear whether the resulting circuits remain functional once the prior is removed. We test this with an annealable soft-prior Transformer whose attention biases can be learned, faded, or zeroed during training and evaluation. On associative recall, unforced models perform well with the prior active ($0.772 \pm 0.020$) but collapse at zero gate ($0.095 \pm 0.009$). Smooth fade-to-zero training preserves high zero-gate accuracy ($0.734 \pm 0.028$), whereas forced-zero training, hard switching, and post hoc continuation fail to recover the same effect. The pattern also appears on Markov induction. Linear regression ICL provides a boundary case because zero-gate training can learn that task directly. Mechanistic traces show that circuit consolidation occurs after the gate reaches zero, even though the responsible heads vary across seeds. These results suggest that circuit removability in small discrete retrieval tasks depends on the training trajectory, not just the final architecture.
### Title:
          RiLM: Parameter-Efficient Language Modeling via Geodesic Decoding
 - **Authors:** Fang Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models under one million parameters matter for edge deployment, domain adaptation, and reproducible research, yet a two-layer LSTM or Transformer at embedding width d = 128 still spends roughly one third of its capacity on the output matrix W_out in R^(d x |V|). We propose Riemannian Language Models (RiLM), which remove that layer entirely: context unfolds as a trajectory on a Riemannian manifold, and next-token probabilities arise from squared geodesic distance between the current state and vocabulary embeddings. The same embedding map serves input and output -- decoding is geometry. We instantiate the framework on flat R^d (Flat RiLM) and the Poincare ball H^d (HypRiLM) with a shared MLP composition map phi (~290k parameters, d = 128, |V| = 2000). Across five seeds on WikiText-2, HypRiLM reaches 54.2 +/- 0.2 validation perplexity versus 87.6 +/- 0.6 for Flat RiLM; tied and matched LSTM, Transformer, and SSM controls remain at 113-147 PPL on WT-2 -- HypRiLM leads by roughly 2x over the strongest tied recurrent baseline (SSM, 113.0 +/- 3.8). Penn Treebank and a 10k-vocabulary stress test confirm that geodesic decoding transfers across corpora and larger |V|, while hyperbolic curvature helps selectively. We also characterize boundary collapse in naive hyperbolic recurrence and show how Mobius stabilization restores trainability. Claims are scoped to controlled small-model comparisons, not full-vocabulary state of the art.
### Title:
          Decoupled Self-Forcing Distillation for Streaming Talking Head Generation
 - **Authors:** Yanru An, Ruiyan Wang, Wenwu Wei, Rui Bu, Qi Wang, Hongwei Hu, Zhengxue Cheng, Rong Xie, Li Song, Wenjun Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming talking-head generation produces each frame as its driving audio arrives, yet fidelity and efficiency have so far pulled in opposite directions: end-to-end methods condition a video diffusion model on audio directly and achieve high quality but only at large scale, while cheaper two-stage methods generate an intermediate motion representation and trail in fidelity. We argue the cost of the former lies in the target of fusion: the video latent is dominated by identity, appearance and background, none of which audio bears on, so coupling audio to every pixel blurs detail and wastes capacity. We instead fuse conditions in a low-dimensional identity-disentangled motion space, routing audio and motion captions by their temporal granularity, and generate motion latents with a small causal autoregressive transformer that a pretrained diffusion renderer turns into video. Conditions thus control video transitively, and high fidelity no longer requires a large backbone. Streaming this decomposition needs both models to be causal, and the exposure-bias problem could be solved by self-forcing given a bidirectional teacher. But there is no such teacher in motion space. Our decoupled self-forcing distillation resolves both models under one frozen teacher: conditioned on motion, it distills the renderer into a block-causal student; unconditionally, it scores rendered rollouts against real videos, supervising motion by the video it produces. This lifts the fidelity ceiling from the motion generator onto the stronger renderer. The two models run as parallel causal streams, reaching 15.4 FPS at 1.3 s latency with no quality degradation.
### Title:
          Forgetting Only What Matters: Layer-Selective Unlearning toward Robust LLMs
 - **Authors:** Ravi Ranjan, Olivera Kotevska, Agoritsa Polyzou
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) can memorize and reproduce sensitive, copyrighted, or otherwise undesirable training content, creating privacy, safety, and regulatory concerns. Machine unlearning offers a practical alternative to full retraining, but many existing methods apply broad or fixed parameter updates that can degrade utility and remain brittle under deployment changes such as post-training quantization, where forgotten knowledge may partially re-emerge. We propose Forgetting Only What Matters via Unlearning Layers (FOM-UL), a layer-level unlearning framework that selects transformer layers using a forget-to-retain significance score. This score identifies layers with high influence on the forget set and low sensitivity to the retain set, allowing FOM-UL to concentrate updates where they are most effective while leaving most of the model unchanged. This targeted update strategy improves the forgetting-utility trade-off and provides an empirical path toward quantization-resilient unlearning by reducing the chance that small, diffuse updates are erased by low-bit rounding. Across TOFU, KnowUnDo, and MUSE-style evaluations, FOM-UL reduces residual memorization compared with strong GA, NPO, KLD, SURE, ReLearn, and LUNAR-based baselines while preserving retain-set utility close to the vanilla model. Under 8-bit and 4-bit post-training quantization, FOM-UL maintains stronger memorization suppression and utility preservation than competing methods, and adversarial prompt evaluations show lower recovery of forgotten content. Overall, FOM-UL provides an efficient unlearning strategy that improves targeted forgetting, utility preservation, and deployment robustness without claiming formal guarantees of erasure.
### Title:
          Field Converter: Geometry-Initialized Temporal Residual Refinement for World-Grounded Player Pose Estimation from Soccer Broadcasts
 - **Authors:** Simon Khan, Laurent Gajny, Jennyfer Lecompte, Sébastien Laporte
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recovering 3D human pose from monocular sports broadcasts remains challenging when players must be localized in a shared metric world coordinate system rather than only reconstructed relative to their own body. We introduce Field Converter, a geometry-initialized temporal residual framework for world-grounded 3D player pose estimation from calibrated soccer broadcasts. Our method first uses camera and pitch geometry to initialize the player root through ray-ground intersection, then predicts a temporal residual correction from pose, image, camera, and geometric cues. On match-disjoint evaluation sequences, residual refinement reduces root error from 49cm with geometry alone to 14cm with a frame-wise MLP and 10cm with a TCN, while a Transformer achieves a comparable 11cm. The resulting world-space MPJPE reaches 13.2cm, and ablations show that residual prediction clearly outperforms direct global-root regression while temporal context matters more than the specific temporal backbone. Failure analysis further identifies airborne motion as the main limitation of the ground-based geometric initialization.
## Keyword: autonomous driving
### Title:
          Valerant: An Automatic Navigable Game Map Generator via Action-Conditioned World Model Exploration
 - **Authors:** Yiran Qiao, Feng Wang, Jing Ma
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) couple predictive world modeling with action generation, allowing anticipated future states to guide agent behavior. Although WAMs are rapidly advancing embodied AI, general-purpose counterparts remain largely unexplored in games. Existing game-oriented approaches often combine action-conditioned world models with external policies and reward functions to realize WAM-like decision-making, yet they operate mainly in 2D visual observation space and do not instantiate persistent 3D geometry. Extending this paradigm to 3D games introduces a distinct challenge. In autonomous driving and robotics, the physical environment exists independently of the model, providing a persistent 3D world in which selected actions can be executed. Games have no such external substrate; the virtual world itself must be instantiated. Most playable games require a persistent and navigable space, while 3D games additionally require explicit geometry that supports movement and interaction. Action-conditioned video rollouts provide visual observations but not this spatial representation. We present \textsc{Valerant}, a training-free framework that transforms a pretrained action-conditioned world model into a WAM for exploring and constructing 3D game maps. By coupling predictive visual rollouts with SLAM-based spatial reconstruction and exploration-driven action selection, \textsc{Valerant} progressively transforms a single image into a persistent 3D game map. This framework extends WAM-based interaction beyond 2D visual simulation and offers a new approach to reducing manual effort in 3D game-map creation.
### Title:
          A Risk-Sensitive and Uncertainty-Aware Decision-Making and Control Framework for Safe and Robust Autonomous Driving
 - **Authors:** Zhuoren Li, Ran Yu, Weiqi Zhang, Ming Liu, Lu Xiong, Chen Sun, Bo Leng
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning (RL) has demonstrated considerable potential for autonomous driving decision-making. However, its deployment in urban autonomous driving, particularly at highly interactive unsignalized intersections, remains challenging, as learned policies may struggle to maintain both safety and robust decision-making in complex traffic situations. Conventional safety-filtering approaches typically employ fixed conservative constraints, which may improve safety at the cost of excessive intervention and degraded traffic efficiency. To address these limitations, we propose a Risk-sensitive and Uncertainty-aware Decision-making and Control (RUDC) framework for safe and robust autonomous driving. RUDC couples risk-sensitive distributional RL with ensemble-based policy uncertainty quantification, jointly accounting for tail risks in return distributions and uncertainty in learned policies. An uncertainty-aware high-order control barrier function (HOCBF)-based safety correction mechanism adaptively adjusts constraint strictness according to policy uncertainty, while a learnable residual predictor compensates for CBF model mismatches and discretization errors. Extensive simulations at unsignalized intersections demonstrate that RUDC achieves a favorable balance among safety, efficiency, and robustness, outperforming representative safe RL baselines under both nominal and challenging OOD and long-tail scenarios while satisfying real-time requirements.
### Title:
          CLFTv2: Efficient Camera-LiDAR Fusion for Semantic Segmentation via Hierarchical Feature Pyramids
 - **Authors:** Toomas Tahves, Mauro Bellone, Raivo Sell
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation for autonomous driving requires reliable detection of vulnerable road users (VRUs) despite heavy class imbalance. We introduce CLFTv2, a hierarchical camera-LiDAR fusion framework replacing global ViT attention with a Swin-based multi-scale encoder and a lightweight FPN-style residual decoder. Operating in the 2D perspective domain, CLFTv2 integrates multi-scale geometric cues through shifted-window attention and per-scale residual fusion, avoiding the computational overhead of query-matching decoders. Across three driving datasets, CLFTv2 consistently improves VRU recall. On ZOD, CLFTv2-Large achieves 53.5\% mIoU, improving pedestrian IoU from 35.5\% to 44.9\% over the prior CLFT model. On Waymo, CLFTv2 reaches 61.7\% mIoU. Additionally, a modality-isolation study suggests ViT's global receptive field yields stronger fusion gains only under dense LiDAR returns. Compared to a Swin-based Mask2Former adaptation, CLFTv2 requires 1.4$\times$ fewer GFLOPs and delivers 2.2$\times$ higher throughput, while achieving comparable overall accuracy. These results demonstrate that hierarchical local-attention fusion offers an efficient, scalable alternative to global-attention and query-based decoders for real-time on-vehicle perception in intelligent transportation systems. Source code is publicly available.
### Title:
          Mitigating Degradation Attacks in Cooperative Autonomous Driving via Intention Sharing: A Vehicle-in-the-Loop Study
 - **Authors:** Prakhar Gupta, Tyler Ard, Rongyao Wang, Jagruti Sahoo, Judith Mwakalonge, Ardalan Vahidi, Yunyi Jia
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Communication delays induced by cyber attacks present a critical challenge to the safe operation of connected autonomous driving. This study investigates the use of intention sharing communication strategy to enhance the resilience of model predictive controllers under Denial-of-Service attacks. We employ a vehicle-in-the-loop testbed integrating a real drive-by-wire vehicle with a microscopic traffic simulator and vehicle-to-X communication infrastructure. We emulate Denial-of-service attacks that induce communication delays of up to two seconds. We evaluate three controller variants: baseline status-sharing, intention-sharing, and delay-aware intention-sharing control. Experimental results reveal that while baseline control suffers significant performance degradation and frequent collisions under adversarial delay, intention sharing eliminates collisions and maintains behavior near nominal levels for the tested scenarios. These findings demonstrate the practical potential of intention-sharing architectures for safeguarding connected vehicles against network-layer degradation.
### Title:
          Data-Driven Risk Fields for Safer End-to-End Autonomous Driving
 - **Authors:** Yuanxin Tian, Zhiyuan Liu, Jinhao Li, Zhenhua Xu, Wenhao Yu, Jianqiang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety is a fundamental requirement for autonomous driving, yet existing end-to-end driving models still lack explicit risk-aware learning capacities. Existing rule-based risk models provide interpretable safety priors, yet their absolute risk scores depend on handcrafted functions, coefficients, and thresholds. Learning-based risk representations reduce part of this manual design, but their supervision often relies on occupancy-derived labels or heuristic cost values, which may not capture ego-conditioned planning risk. In this paper, we propose DRiF, a data-driven risk-field framework for safer end-to-end autonomous driving. DRiF learns a shared BEV feature with static map segmentation, dynamic risk prediction, and vehicle planning. For dynamic risk learning, DRiF converts rule-based safety priors into pairwise risk labels, and trains the risk field to preserve relative risk ordering instead of regressing handcrafted absolute scores. Experiments on Bench2Drive show that DRiF achieves competitive overall performance, with consistent improvements in driving score, success rate, and collision-related metrics. These results establish relative risk supervision as an effective way to connect explicit safety structure with end-to-end planning. The data and code will be publicly available.
