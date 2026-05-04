# Showing new listings for Monday, 4 May 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Paired-CSLiDAR: Height-Stratified Registration for Cross-Source Aerial-Ground LiDAR Pose Refinement
 - **Authors:** Montana Hoover, Jing Liang, Tianrui Guan, Dinesh Manocha
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Paired-CSLiDAR (CSLiDAR), a cross-source aerial-ground LiDAR benchmark for single-scan pose refinement: refining a ground-scan pose within a 50 m-radius aerial crop. The benchmark contains 12,683 ground-aerial pairs across 6 evaluation sites and per-scan reference 6-DoF alignments for sub-meter root-mean-square error (RMSE) evaluation. Because aerial scans capture rooftops and canopy while ground scans capture facades and under-canopy, the two modalities share only a fraction of their geometry, primarily the terrain surface, causing standard registration methods and learned correspondence models to converge to metrically incorrect local minima. We propose Residual-Guided Stratified Registration (RGSR), a training-free, geometry-only refinement pipeline that exploits the shared ground plane through height-stratified ICP, reversed registration directions, and confidence-gated accept-if-better selection. RGSR achieves 86.0% S@0.75 m and 99.8% S@1.0 m on the primary benchmark of 9,012 scans, outperforming both the confidence-gated cascade at 83.7% and GeoTransformer at 76.3%. We validate RMSE-based pose selection with independent survey control and trajectory consistency, and show that added Fourier-Mellin BEV proposals can reduce RMSE while increasing actual pose error under extreme partial overlap. The dataset and code are being prepared for public release.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Beyond Heuristics: Learnable Density Control for 3D Gaussian Splatting
 - **Authors:** Zhenhua Ning, Xin Li, Jun Yu, Guangming Lu, Yaowei Wang, Wenjie Pei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While 3D Gaussian Splatting (3DGS) has demonstrated impressive real-time rendering performance, its efficacy remains constrained by a reliance on heuristic density control. Despite numerous refinements to these handcrafted rules, such methods inherently lack the flexibility to adapt to diverse scenes with complex geometries. In this paper, we propose a paradigm shift for density control from rigid heuristics to fully learnable policies. Specifically, we introduce \textbf{LeGS}, a framework that reformulates density control as a parameterized policy network optimized via Reinforcement Learning (RL). Central to our approach is the tailored effective reward function grounded in sensitivity analysis, which precisely quantifies the marginal contribution of individual Gaussians to reconstruction quality. To maintain computational tractability, we derive a closed-form solution that reduces the complexity of reward calculation from $O(N^2)$ to $O(N)$. Extensive experiments on the Mip-NeRF 360, Tanks \& Temples, and Deep Blending datasets demonstrate that \textbf{LeGS} significantly outperforms state-of-the-art methods, striking a superior balance between reconstruction quality and efficiency. The code will be released at this https URL
### Title:
          GOR-IS: 3D Gaussian Object Removal in the Intrinsic Space
 - **Authors:** Yonghao Zhao, Yupeng Gao, Jian Yang, Jin Xie, Beibei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Neural Radiance Fields (NeRF) and 3D Gaussian Splatting (3DGS) have made it standard practice to reconstruct 3D scenes from multi-view images. Removing objects from such 3D representations is a fundamental editing task that requires complete and seamless inpainting of occluded regions, ensuring consistency in geometry and appearance. Although existing methods have made notable progress in improving inpainting consistency, they often neglect global lighting effects, leading to physically implausible results. Moreover, these methods struggle with view-dependent non-Lambertian surfaces, where appearance varies across viewpoints, leading to unreliable inpainting. In this paper, we present 3D Gaussian Object Removal in the Intrinsic Space (GOR-IS), a novel framework for physically consistent and visually coherent 3D object removal. Our approach decomposes the scene into intrinsic components and explicitly models light transport to maintain global lighting effects consistency. Furthermore, we introduce an intrinsic-space inpainting module that operates directly in the material and lighting domains, effectively addressing the challenges posed by non-Lambertian surfaces. Extensive experiments on both synthetic and real-world datasets demonstrate that our framework substantially improves the physical consistency and visual coherence of object removal, outperforming existing methods by 13% in perceptual similarity (LPIPS) and 2dB in peak signal-to-noise ratio (PSNR). Code is publicly available at this https URL
## Keyword: mapping
### Title:
          ROSA: Robust and Energy-Efficient Microring-Based Optical Neural Networks via Optical Shift-and-Add and Layer-Wise Hybrid Mapping
 - **Authors:** Huifan Zhang, Yun Hu, Caizhi Sheng, Yurui Qu, Pingqiang Zhou
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents ROSA, a microring-based optical neural network architecture that improves robustness and energy efficiency using an optical shift-and-add (OSA) module and a layer-wise hybrid mapping strategy. It introduces a noise-aware voltage-to-weight model considering DAC and thermal variations, and a workload-aware framework to co-optimize MRR array size and layer-wise dataflow. Optimized arrays reduce the aggregated relative energy-delay product (EDP) by 64% and 26% compared with DEAP-CNNs and a general compact array, respectively. OSA further contributes 29% EDP reduction. The proposed hybrid mapping strategy improves CIFAR-10 accuracy by 8.3% over weight-stationary mapping while achieving an average 54.7% lower EDP than DEAP-CNNs.
### Title:
          Being-H0.7: A Latent World-Action Model from Egocentric Videos
 - **Authors:** Hao Luo, Wanpeng Zhang, Yicheng Feng, Sipeng Zheng, Haiweng Xu, Chaoyi Xu, Ziheng Xi, Yuhui Fu, Zongqing Lu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-Language-Action models (VLAs) have advanced generalist robot control by mapping multimodal observations and language instructions directly to actions, but sparse action supervision often encourages shortcut mappings rather than representations of dynamics, contact, and task progress. Recent world-action models introduce future prediction through video rollouts, yet pixel-space prediction is a costly and indirect substrate for control, as it may model visual details irrelevant to action generation and introduces substantial training or inference overhead. We present Being-H0.7, a latent world-action model that brings future-aware reasoning into VLA-style policies without generating future frames. Being-H0.7 inserts learnable latent queries between perception and action as a compact reasoning interface, and trains them with a future-informed dual-branch design: a deployable prior branch infers latent states from the current context, while a training-only posterior branch replaces the queries with embeddings from future observations. Jointly aligning the two branches at the latent reasoning space leads the prior branch to reason future-aware, action-useful structure from current observations alone. At inference, Being-H0.7 discards the posterior branch and performs no visual rollout. Experiments across six simulation benchmarks and diverse real-world tasks show that Being-H0.7 achieves state-of-the-art or comparable performance, combining the predictive benefits of world models with the efficiency and deployability of direct VLA policies.
### Title:
          Network Digital Untwinning: Towards Backward Optimization of Digital Twins
 - **Authors:** Zifan Zhang, Dianwei Chen, Anjun Gao, Manhua Wang, Mingzhe Chen, Minghong Fang, Xianfeng Yang, Yuchen Liu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Network digital twins (NDTs) are transforming network management by offering precise virtual replicas of physical network systems. However, their reliance on diverse and sensitive data introduces significant challenges related to data management, regulatory compliance, and user privacy. In scenarios where selective data removal is necessary, such as device deactivation, network reconfiguration, or regulatory compliance, traditional approaches often fall short of preserving the integrity of the twin model. To address this gap, we introduce a network digital untwinning framework that enables the targeted removal of deprecated NDT contributions while maintaining model integrity. Our approach comprises two complementary components: Single Request Untwinning (\algO) and Parallel Request Untwinning (\algM) mechanisms. \algO leverages connectivity metrics based on geographical proximity, data distribution, and network-level attributes to identify and remove the target NDT along with its propagating influence. This is achieved through an optimally selected rollback checkpoint augmented with injected Gaussian noise, followed by a precise remapping phase. \algM extends this mechanism to efficiently handle multiple removal requests by clustering NDTs with similar attributes and performing a coordinated rollback and untwinning schedule. We provide theoretical guarantees on model indistinguishability from scratch-built twins, and validate the framework through extensive experiments on real-world traffic data, demonstrating its effectiveness and operational efficiency.
### Title:
          CompleteRXN: Toward Completing Open Chemical Reaction Databases
 - **Authors:** Gabriel Vogel, Minouk Noordsij, Evgeny Pidko, Jana M. Weber
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chemical reaction datasets such as USPTO suffer from substantial incompleteness, frequently missing byproducts, co-reactants, and stoichiometric coefficients. This limits their applicability and reliability in downstream applications. Here, we introduce CompleteRXN, a large-scale supervised benchmark for reaction completion under realistic missing-data conditions. We construct a dataset of aligned incomplete and atom-balanced reactions by mapping USPTO records to curated mechanistic reactions. We evaluate representative baselines, including a novel encoder-decoder reaction completion model with constrained decoding, the Constrained Reaction Balancer (CRB), and a recent algorithmic method, SynRBL. On our CompleteRXN benchmark, the CRB achieves high performance across splits of increasing difficulty, reaching 99.20% equivalence accuracy on the random split and 91.12% on the extreme out-of-distribution split. SynRBL produces many balanced and chemically plausible completions, but with lower accuracy on the benchmark test splits. Across all methods, performance degrades with increasing incompleteness. We observe a substantial drop when evaluating on reactions outside the benchmark (full uncurated USPTO), highlighting the gap between benchmark performance and practical robustness and motivating future work.
### Title:
          Beyond Visual Fidelity: Benchmarking Super-Resolution Models for Large-Scale Remote Sensing Imagery via Downstream Task Integration
 - **Authors:** Zhili Li, Kangyang Chai, Zhihao Wang, Xiaowei Jia, Yanhua Li, Gengchen Mai, Sergii Skakun, Dinesh Manocha, Yiqun Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Super-resolution (SR) techniques have made major advances in reconstructing high-resolution images from low-resolution inputs. The increased resolution provides visual enhancement and utility for monitoring tasks. In particular, SR has been increasingly developed for satellite-based Earth observation, with applications in urban planning, agriculture, ecology, and disaster response. However, existing SR studies and benchmarks typically use fidelity metrics such as PSNR or SSIM, whereas the true utility of super-resolved images lies in supporting downstream tasks such as land cover classification, biomass estimation, and change detection. To bridge this gap, we introduce GeoSR-Bench, a downstream task-integrated SR benchmark dataset to evaluate SR models beyond fidelity metrics. GeoSR-Bench comprises spatially co-located, temporally aligned, and quality-controlled image pairs from about 36,000 locations across diverse land covers, spanning resolutions from 500m to 0.6m. To the best of our knowledge, GeoSR-Bench is the first SR benchmark that directly connects improved image resolution from SR models with downstream Earth monitoring tasks, including land cover segmentation, infrastructure mapping, and biophysical variable estimation. Using GeoSR-Bench, we benchmark GAN, transformer, neural operator, and diffusion-based SR models on perceptual quality and downstream task performance. We conduct experiments with 270 settings, covering 2 cross-platform SR tasks, 9 SR models, 3 downstream task models, and 5 downstream tasks for each SR task. The results show that improvements in traditional SR metrics often do not correlate with gains in task performance, and the correlations can be negative, indicating that these metrics provide limited guidance for selecting superior models for downstream tasks. This reveals the need to integrate downstream tasks into SR model development and evaluation.
### Title:
          Unbox Responsible GeoAI: Navigating Climate Extreme and Disaster Mapping
 - **Authors:** Hao Li, Steffen Knoblauch
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As climate extreme and disaster events become more frequent and intense, Geospatial Artificial Intelligence (GeoAI) has emerged as a transformative approach for large-scale disaster mapping and risk reduction. However, the purely mechanical, performance-driven deployment of GeoAI models can result in amplifying inherent spatial inequalities, preventing effective emergency decision-making, and producing severe environmental carbon footprint. To unbox the concept of responsible GeoAI, this position paper examines its emerging role, e.g., in climate extreme and disaster mapping, from a critical GIS perspective. We address the nexus of responsible GeoAI into four interrelated theoretical dimensions, specifically Representativeness, Explainability, Sustainability, and Ethics, with examples from climate extreme and disaster mapping. Moreover, targeting at the operational practice, we then propose a conceptual governance Model of responsible GeoAI that categorizes its governance practices into Data, Application, and Society scopes. Last, this position paper aims to raise the attention in the broader GIS community that the future of climate resilience relies not just on building better algorithms, but on fostering a governance ecosystem where GeoAI is deployed responsibly, ethically, and sustainably.
### Title:
          Real-Time Neural Distributed Energy Resources Dispatch with Feasibility Guarantees
 - **Authors:** Jie Zhu, Yinliang Xu, Hongbin Sun
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing penetration of renewable energy necessitates high-frequency real-time scheduling. While neural network-based surrogates enable computationally efficient scheduling, strictly enforcing nonconvex power flow constraints without external solvers remains a fundamental challenge. To bridge this gap, this letter proposes a solver-free neural dispatch framework with rigorous feasibility guarantees. A convex inner approximation of the DistFlow model is first derived via the convex envelope theorem. Building upon this approximation, a robust optimization-based affine policy is formulated to yield a theoretically certified interior-point mapping rule, which is then embedded within a bisection-based projection scheme to efficiently recover feasibility for infeasible NN outputs without any external solver. Experimental results demonstrate that the proposed method restores feasibility on the order of $10^{-3}$ s while maintaining near-optimal performance.
### Title:
          BWLA: Breaking the Barrier of W1AX Post-Training Quantization for LLMs
 - **Authors:** Zhixiong Zhao, Zukang Xu, Dawei Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have driven major progress in NLP, yet their substantial memory and compute demands still hinder practical deployment. Binarization can compress weights to 1 bit, fundamentally lowering compute and bandwidth cost. However, existing methods cannot address activation heavy tails and thus must keep activations in high precision, preventing true end-to-end acceleration. To overcome this limitation, we propose BWLA (Binarized Weights and Low-bit Activations), the first post-training quantization framework that preserves high accuracy while achieving 1-bit weight quantization together with low-bit activations (e.g., 6 bits). The Orthogonal-Kronecker Transformation (OKT) learns an orthogonal mapping via EM minimization, converting unimodal weights into symmetric bimodal forms while suppressing activation tails and incoherence. The Proximal SVD Projection (PSP) then performs lightweight low-rank refinement through proximal SVD projection, further enhancing quantizability with minimal overhead. On Qwen3-32B, BWLA reaches a Wikitext2 perplexity of 11.92 under 6-bit activations (vs. 38 from SOTA), improves five zero-shot tasks by more than 70%, and delivers 3.26 times inference speedup, demonstrating strong potential for real-world LLM compression and acceleration.
### Title:
          MSACT: Multistage Spatial Alignment for Stable Low-Latency Fine Manipulation
 - **Authors:** Xianbo Cai, Hideyuki Ichiwara, Masaki Yoshikawa, Tetsuya Ogata
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world fine manipulation, particularly in bimanual manipulation, typically requires low-latency control and stable visual localization, while collecting large-scale data is costly and limited demonstrations may lead to localization drift. Existing approaches make different trade-offs: action-chunking policies such as ACT enable low-latency execution and data efficiency but rely on dense visual features without explicit spatial consistency, generative methods such as Diffusion Policy improve expressiveness but can incur iterative sampling latency, vision-language-action and voxel-based methods enhance generalization and geometric grounding but require higher computational cost and system complexity. We introduce a multistage spatial attention module that extracts stable 2D attention points and jointly predicts future attention sequences with a temporal alignment loss. Built upon ACT with a pretrained ResNet visual prior, a multistage attention module extracts task-relevant 2D attention points as a local spatial modality for action prediction. To maintain consistent object tracking, we introduce a self-supervised objective that aligns predicted attention sequences with visual features from future frames, suppressing drift without keypoint annotations and improving stability of the vision-to-action mapping under limited data. Experiments on simulated and real-world fine manipulation tasks, conducted on the ALOHA bimanual platform, evaluate task success, attention drift, inference latency, and robustness to visual disturbances. Results indicate improvements in localization stability and task performance while maintaining low-latency inference under the tested conditions.
### Title:
          Scale-Aware Adversarial Analysis: A Diagnostic for Generative AI in Multiscale Complex Systems
 - **Authors:** Mengke Zhao, Guang-Xing Li, Duo Xu, Keping Qiu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Complex physical systems, from supersonic turbulence to the macroscopic structure of the universe, are governed by continuous multiscale dynamics. While modern machine learning architectures excel at mapping the high-dimensional observables of these systems, it remains unclear whether they internalize the governing physical laws or merely interpolate discrete statistical correlations. Standard Explainable AI (XAI) architectures, particularly perturbation-based and gradient-saliency methods, rely on pixel-wise perturbations, which generate unphysical artifacts and push inputs off the valid empirical distribution. To resolve this, we introduce a diagnostic framework driven by Constrained Diffusion Decomposition (CDD), a diffusion-based multiscale data decomposition algorithm that enables physically constrained data generation and model evaluation via scale-aware modifications. Applying this framework to a Denoising Diffusion Probabilistic Model (DDPM), we execute deterministic interventions directly within the continuous, CDD-based scale space. We demonstrate that under moderate physical perturbations, the unconstrained generative model exhibits localized structural freezing and non-linear instability rather than continuous PDE-like responses. The network fails to maintain cross-scale continuity, causing the generative trajectory to diverge when pushed into unseen physical states. By synthesizing a continuum of physically coherent states, this scale-informed methodology establishes a controlled test ground to evaluate algorithmic vulnerabilities, providing the rigorous physical constraints necessary for future architectures to respect the multiscale causality of the natural universe.
### Title:
          Space Network of Experts: Architecture and Expert Placement
 - **Authors:** Zhanwei Wang, Huiling Yang, Min Sheng, Khaled B. Letaief, Kaibin Huang
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Leveraging continuous solar energy harvesting at high efficiency, space data centers are envisioned as a promising platform for executing energy-intensive large language models (LLMs). Recognizing this advantage, space and AI conglomerates (e.g., SpaceX, Google) are actively investing in this vision. One key challenge, however, is the efficient distributed deployment of a large-scale LLM in a satellite network due to the limited onboard computing and communication resources. This gives rise to a placement problem that involves partitioning and mapping model components to satellites such that the fundamentally different model architecture and network topology can be reconciled to ensure low-latency token generation. To address this problem, we present the Space Network of Experts (Space-XNet) framework targeting the distributed execution of a popular mixture-of-experts (MoE) model in space. The proposed placement strategies are two-level: (1) layer placement, which assigns MoE layers to satellite subnets; and (2) intra-layer expert placement, which assigns individual experts to satellites associated with the same layer/subnet. For layer placement, we exploit the ring-like communication pattern of autoregressive inference to partition the satellite constellation along the orbiting direction into subnets arranged on a ring, each hosting one MoE layer. Based on this architecture, we formulate and solve an optimization problem for intra-layer expert placement to map experts with heterogeneous activation probabilities onto satellites. The derived strategy reveals an intuitive principle: a frequently activated expert should be mapped to a satellite on a routing path with low expected latency. Experiments over a thousand-satellite constellation show that Space-XNet achieves at least a threefold latency reduction compared with conventional random and ablation-based placement strategies.
### Title:
          Faithful Extreme Image Rescaling with Learnable Reversible Transformation and Semantic Priors
 - **Authors:** Hao Wei, Yanhui Zhou, Chenyang Ge, Saeed Anwar, Ajmal Mian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most recent extreme rescaling methods struggle to preserve semantically consistent structures and produce realistic details, due to the severely ill-posed nature of low- to high-resolution mapping under scaling factors of $16\times$ or higher. To alleviate the above problems, we propose FaithEIR, a diffusion-based framework for extreme image rescaling. Inspired by singular value decomposition, we develop learnable reversible transformation that enables invertible downscaling and upscaling in the latent space. To compensate for information loss due to quantization, we propose an adaptive detail prior, a high-frequency dictionary that captures the empirical average of commonly occurring structures in the training data. Finally, we design a lightweight pixel semantic embedder to provide semantic conditioning for the pretrained diffusion model. We present extensive experimental results demonstrating that our FaithEIR consistently outperforms state-of-the-art methods, achieving superior reconstruction fidelity and perceptual quality. Our code, model weights, and detailed results are released at this https URL.
### Title:
          UniVidX: A Unified Multimodal Framework for Versatile Video Generation via Diffusion Priors
 - **Authors:** Houyuan Chen, Hong Li, Xianghao Kong, Tianrui Zhu, Shaocong Xu, Weiqing Xiao, Yuwei Guo, Chongjie Ye, Lvmin Zhang, Hao Zhao, Anyi Rao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress has shown that video diffusion models (VDMs) can be repurposed for diverse multimodal graphics tasks. However, existing methods often train separate models for each problem setting, which fixes the input-output mapping and limits the modeling of correlations across modalities. We present UniVidX, a unified multimodal framework that leverages VDM priors for versatile video generation. UniVidX formulates pixel-aligned tasks as conditional generation in a shared multimodal space, adapts to modality-specific distributions while preserving the backbone's native priors, and promotes cross-modal consistency during synthesis. It is built on three key designs. Stochastic Condition Masking (SCM) randomly partitions modalities into clean conditions and noisy targets during training, enabling omni-directional conditional generation instead of fixed mappings. Decoupled Gated LoRA (DGL) introduces per-modality LoRAs that are activated when a modality serves as the generation target, preserving the strong priors of the VDM. Cross-Modal Self-Attention (CMSA) shares keys and values across modalities while keeping modality-specific queries, facilitating information exchange and inter-modal alignment. We instantiate UniVidX in two domains: UniVid-Intrinsic, for RGB videos and intrinsic maps including albedo, irradiance, and normal; and UniVid-Alpha, for blended RGB videos and their constituent RGBA layers. Experiments show that both models achieve performance competitive with state-of-the-art methods across distinct tasks and generalize robustly to in-the-wild scenarios, even when trained on fewer than 1,000 videos. Project page: this https URL
### Title:
          Spiking Sequence Machines and Transformers
 - **Authors:** Joy Bose
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence learning reduces to similarity-based retrieval over a temporally indexed representation space, a constraint on any sequence model, not a property of a specific architecture. We show that a spiking Sparse Distributed Memory sequence machine (2007) and the transformer (2017) independently instantiate the same five functional operations (encoding, context maintenance, associative retrieval, storage, and decoding), with cosine similarity as the shared retrieval primitive in both. We formalise a Phase-Latency Isomorphism showing that sinusoidal positional phase and spike timing are linearly related, and prove that dot product attention is invariant to this mapping up to a global scale factor on the positional component (Lemma 1). Empirically, frequency-compressed positional encoding fails to converge on a positionally demanding copy task, while a learned rank-based embedding matches or exceeds sinusoidal encoding, indicating that the critical property for positional representation is distance discriminability under dot-product similarity, not sinusoidal form. Time, phase, and rank are three instantiations of the same computational primitive, an ordered index whose structure survives similarity-based retrieval.
### Title:
          Posterior Augmented Flow Matching
 - **Authors:** George Stoica, Sayak Paul, Matthew Wallingford, Vivek Ramanujan, Abhay Nori, Winson Han, Ali Farhadi, Ranjay Krishna, Judy Hoffman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow matching (FM) trains a time-dependent vector field that transports samples from a simple prior to a complex data distribution. However, for high-dimensional images, each training sample supervises only a single trajectory and intermediate point, yielding an extremely sparse and high-variance training signal. This under-constrained supervision can cause flow collapse, where the learned dynamics memorize specific source-target pairings, mapping diverse inputs to overly similar outputs, failing to generalize. We introduce Posterior-Augmented Flow Matching (PAFM), a theoretically grounded generalization of FM that replaces single-target supervision with an expectation over an approximate posterior of valid target completions for a given intermediate state and condition. PAFM factorizes this intractable posterior into (i) the likelihood of the intermediate under a hypothesized endpoint and (ii) the prior probability of that endpoint under the condition, and uses an importance sampling scheme to construct a mixture over multiple candidate targets. We prove that PAFM yields an unbiased estimator of the original FM objective while substantially reducing gradient variance during training by aggregating information from many plausible continuation trajectories per intermediate. Finally, we show that PAFM improves over FM by up to 3.4 FID50K across different model scales (SiT-B/2 and SiT-XL/2), different architectures (SiT and MMDiT), and in both class and text conditioned benchmarks (ImageNet and CC12M), with a negligible increase in the compute overhead. Code: this https URL.
## Keyword: localization
### Title:
          Alethia: A Foundational Encoder for Voice Deepfakes
 - **Authors:** Yi Zhu, Brahmi Dwivedi, Jayaram Raghuram, Surya Koppisetti
 - **Subjects:** Subjects:
Sound (cs.SD); Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing voice deepfake detection and localization models rely heavily on representations extracted from speech foundation models (SFMs). However, downstream finetuning has now reached a state of diminishing returns. In this paper, we shift the focus to pretraining and propose a novel recipe that combines bottleneck masked embedding prediction with flow-matching based spectrogram reconstruction. The outcome, Alethia, is the first foundational audio encoder for various voice deepfake detection and localization tasks. We evaluate on $5$ different tasks with $56$ benchmark datasets, and note Alethia significantly outperforms state-of-the-art SFMs with superior robustness to real-world perturbations and zero-shot generalization to unseen domains (e.g., singing deepfakes). We also demonstrate the limitation of discrete targets in masked token prediction, and show the importance of continuous embedding prediction and generative pretraining for capturing deepfake artifacts.
### Title:
          A Model-based Visual Contact Localization and Force Sensing System for Compliant Robotic Grippers
 - **Authors:** Kaiwen Zuo, Shuyuan Yang, Zonghe Chua
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grasp force estimation can help prevent robots from damaging delicate objects during manipulation and improve learning-based robotic control. Integrating force sensing into deformable grippers negotiates trade-offs in cost, complexity, mechanical robustness, and performance. With the growing integration of RGB-D wrist cameras into robotic systems for control purposes, camera-based techniques are a promising solution for indirect visual force estimation. Current approaches mostly utilize end-to-end deep learning, which can be brittle when generalizing to new scenarios, while existing model-based approaches are unsuited to grasping and modern grasper geometries. To address these challenges, we developed a model-based visual force sensing approach integrating an iterative contact localization with generalization to unseen objects. The system extracts structural key points from wrist camera RGB-D images of deforming fin-ray-shaped soft grippers, and uses these key points to define parameters of an inverse finite element analysis simulation in Simulation Open Framework Architecture. The iterative contact localization sub-system utilizes a deep learning-based online 3D reconstruction and pose estimation pipeline to dynamically update contact location, and is robust to visual occlusion and unseen objects. Our system demonstrated an average root mean square error of 0.23 N and normalized root mean square deviation of 2.11% during the load phase, and 0.48 N and 4.34% over the entire grasping process when interacting with different objects under various conditions, showcasing its potential for real-time model-based indirect force sensing of soft grippers.
### Title:
          Hypergraph and Latent ODE Learning for Multimodal Root Cause Localization in Microservices
 - **Authors:** Xin Liu, Yuhang He, Sichen Zhao, Kejian Tong, Xingyu Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Root cause localization in cloud native microservice systems requires modeling complex service dependencies, irregular temporal dynamics, and heterogeneous observability data. We present HyperODE RCA, a unified framework that combines hypergraph attention learning, latent ordinary differential equations, and multimodal cross attention fusion for fine grained root cause analysis. The method learns higher order service interactions through differentiable hyperedge construction, captures continuous anomaly evolution from irregular observations with an ODE RNN encoder, and adaptively fuses logs, traces, metrics, entities, and events using context aware modality routing. We further improve robustness with a variational information bottleneck, temporal causal regularization, and invariant risk constraints. Experiments on the Tianchi AIOps benchmark show clear gains over strong baselines in ranking and classification performance, while preserving interpretability through learned hypergraph attention.
### Title:
          P2M++: Enhanced Solver for Point-to-Mesh Distance Queries
 - **Authors:** Qinghao Guo, Pengfei Wang, Chen Zong, Maodong Pan, Shiqing Xin, Shuangmin Chen, Changhe Tu, Wenping Wang
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point-to-mesh distance queries are fundamental in computer graphics and geometric modeling. While the state-of-the-art P2M method achieves high-speed queries via Voronoi-based localization, it suffers from prohibitive precomputation costs. Its iterative Voronoi sweep for interference detection leads to redundant predicate evaluations and scales poorly on rotationally symmetric structures (e.g., spheres, cones or cylinders), where candidate counts grow quadratically. We propose P2M++ to address these limitations through three key contributions. First, we adaptively augment the set of mesh vertices with auxiliary sites in regions of high Voronoi vertex density to localize complex interference within minimal spatial regions. Second, we reformulate interference detection as a series of sphere-triangle collision tests centered at Voronoi cell corners, which are efficiently resolved using the base mesh's BVH. Finally, we enhance runtime performance by replacing the standard kd-tree search with a faster recursive dynamic programming implementation. Experimental results demonstrate that P2M++ is 3x-10x faster than the original P2M during preprocessing and 1.5x faster in queries, with even more pronounced gains on rotationally symmetric geometries.
### Title:
          MSACT: Multistage Spatial Alignment for Stable Low-Latency Fine Manipulation
 - **Authors:** Xianbo Cai, Hideyuki Ichiwara, Masaki Yoshikawa, Tetsuya Ogata
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world fine manipulation, particularly in bimanual manipulation, typically requires low-latency control and stable visual localization, while collecting large-scale data is costly and limited demonstrations may lead to localization drift. Existing approaches make different trade-offs: action-chunking policies such as ACT enable low-latency execution and data efficiency but rely on dense visual features without explicit spatial consistency, generative methods such as Diffusion Policy improve expressiveness but can incur iterative sampling latency, vision-language-action and voxel-based methods enhance generalization and geometric grounding but require higher computational cost and system complexity. We introduce a multistage spatial attention module that extracts stable 2D attention points and jointly predicts future attention sequences with a temporal alignment loss. Built upon ACT with a pretrained ResNet visual prior, a multistage attention module extracts task-relevant 2D attention points as a local spatial modality for action prediction. To maintain consistent object tracking, we introduce a self-supervised objective that aligns predicted attention sequences with visual features from future frames, suppressing drift without keypoint annotations and improving stability of the vision-to-action mapping under limited data. Experiments on simulated and real-world fine manipulation tasks, conducted on the ALOHA bimanual platform, evaluate task success, attention drift, inference latency, and robustness to visual disturbances. Results indicate improvements in localization stability and task performance while maintaining low-latency inference under the tested conditions.
### Title:
          Depth-Guided Privacy-Preserving Visual Localization Using 3D Sphere Clouds
 - **Authors:** Heejoon Moon, Jongwoo Lee, Jeonggon Kim, Je Hyeong Hong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The emergence of deep neural networks capable of revealing high-fidelity scene details from sparse 3D point clouds has raised significant privacy concerns in visual localization involving private maps. Lifting map points to randomly oriented 3D lines is a well-known approach for obstructing undesired recovery of the scene images, but these lines are vulnerable to a density-based attack that can recover the point cloud geometry by observing the neighborhood statistics of lines. With the aim of nullifying this attack, we present a new privacy-preserving scene representation called \emph{sphere cloud}, which is constructed by lifting all points to 3D lines crossing the centroid of the map, resembling points on the unit sphere. Since lines are most dense at the map centroid, the sphere cloud mislead the density-based attack algorithm to incorrectly yield points at the centroid, effectively neutralizing the attack. Nevertheless, this advantage comes at the cost of i) a new type of attack that may directly recover images from this cloud representation and ii) unresolved translation scale for camera pose estimation. To address these issues, we introduce a simple yet effective cloud construction strategy to thwart new attack and propose an efficient localization framework to guide the translation scale by utilizing absolute depth maps acquired from on-device time-of-flight (ToF) sensors. Experimental results on public RGB-D datasets demonstrate sphere cloud achieves competitive privacy-preserving ability and localization runtime while not excessively compensating the pose estimation accuracy compared to other depth-guided localization methods.
### Title:
          Robust Fusion of Object-Level V2X for Learned 3D Object Detection
 - **Authors:** Lukas Ostendorf, Lennart Reiher, Onn Haran, Lutz Eckstein
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Perception for automated driving is largely based on onboard environmental sensors, such as cameras and radar, which are cost-effective but limited by line-of-sight and field-of-view constraints. These inherent limitations may cause onboard perception to fail under occlusions or poor visibility conditions. In parallel, cooperative awareness via vehicle-to-everything (V2X) communication is becoming increasingly available, enabling vehicles and infrastructure to share their own state as object-level information that complements onboard perception. In this work, we study how such V2X information can be integrated into 3D object detection and how robust the resulting system is to realistic V2X imperfections. Using the nuScenes dataset, we emulate object-level cooperative awareness messages from ground truth, injecting controlled noise and object dropout to mimic real-world conditions such as latency, localization errors, and low V2X penetration rates. We convert these messages into a dedicated bird's-eye view (BEV) input and fuse them into a BEVFusion-style detector. Our results demonstrate that while object-level cooperative information can substantially improve detection performance, achieving an NDS of 0.80 under favorable conditions, models trained on idealized data become fragile and over-reliant on V2X. Conversely, our proposed noise-aware training strategy, coupled with explicit confidence encoding, enhances robustness, maintaining performance gains even under severe noise and reduced V2X penetration.
### Title:
          Static and Dynamic Graph Alignment Network for Temporal Video Grounding
 - **Authors:** Zhanjie Hu, Bolin Zhang, Jianhua Wang, Jianbo Zheng, Chenchen Yan, Takahiro Komamizu, Ichiro Ide, Jiangbo Qian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal Video Grounding (TVG) aims to localize temporal moments in an untrimmed video that semantically correspond to given natural language queries. Recently, Graph Convolutional Networks (GCN) have been widely adopted in TVG to model temporal relations among video clips and enhance contextual reasoning by constructing clip-level graphs. Despite their effectiveness, existing GCN-based TVG methods encounter three critical bottlenecks: 1) Most methods construct graph nodes using either static or dynamic features alone, resulting in incomplete visual representation and overlooking complementary semantics, 2) Most methods construct temporal graphs in a query-agnostic manner, leading to inefficient feature interaction within the temporal graph representation, and 3) Most methods often suffer from a single-granularity semantic matching, while direct training on complex temporal localization task may lead to slow convergence and suboptimal precision. To address these challenges, we propose Static and Dynamic Graph Alignment Network (SDGAN). First, SDGAN jointly exploits static and dynamic visual features to construct two complementary temporal graphs and performs Position-wise Nodes Alignment, enabling more expressive and robust visual representation. Second, SDGAN introduces Query-Clip Contrastive Learning and Adaptive Graph Modeling to explicitly align visual clips with their corresponding textual queries, yielding query-aware visual representations. Third, SDGAN incorporates multi-granularity temporal proposals within Progressive Easy-to-Hard Training Strategy, effectively bridging coarse-grained semantic localization and fine-grained temporal boundary refinement. Extensive experiments on three benchmark datasets demonstrate that SDGAN achieves superior performance across complex TVG scenarios. Codes and datasets are available at this https URL.
## Keyword: transformer
### Title:
          What Physics do Data-Driven MoCap-to-Radar Models Learn?
 - **Authors:** Kevin Chen, Kenneth W. Parker, Anish Arora
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven MoCap-to-radar models generate plausible micro-Doppler spectrograms, but do they actually learn the underlying physics? We introduce a physics-based interpretability framework to answer this question via two proposed complementary metrics: one measures alignment between model predictions and the physics-derived Doppler frequency, while the other tests whether predictions preserve the velocity-frequency relationship under velocity intervention. Both metrics require only MoCap input and model predictions, without access to measured radar data. Experiments across several model architectures reveal that low reconstruction error does not guarantee physical consistency: some, but not all, models achieve low error yet perform poorly on the two physics-based metrics. Further analysis shows that temporal attention is critical for transformer-based models to learn the underlying physics.
### Title:
          E$^2$DT: Efficient and Effective Decision Transformer with Experience-Aware Sampling for Robotic Manipulation
 - **Authors:** Kaiyan Zhao, Borong Zhang, Yiming Wang, Xingyu Liu, Xuetao Li, Yuyang Chen, Xiaoguang Niu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In reinforcement learning (RL) for robotic manipulation, the Decision Transformer (DT) has emerged as an effective framework for addressing long-horizon tasks. However, DT's performance depends heavily on the coverage of collected experiences. Without an active exploration mechanism, standard DT relies on uniform replay, which leads to poor sample efficiency, limited exploration, and reduced overall effectiveness. At the same time, while excessive exploration can help avoid local optima, it often delays policy convergence and leads to degraded efficiency. To address these limitations, we propose E$^2$DT, a DT-guided k-Determinantal Point Process sampling framework that enables the model to actively shape its own experience selection. Our framework is experience-aware, allowing E$^2$DT to be both efficient, by prioritizing sampling quality, such as high-return, high-uncertainty, and underrepresented trajectories, and effective, by ensuring diversity across trajectory windows to preserve policy optimality. Specifically, DT's internal latent embeddings measure diversity across trajectory windows, while quality is quantified through a composite metric that integrates return-to-go (RTG) quantiles, predictive uncertainty, and stage coverage based on inverse frequency. These two dimensions are integrated into a novel quality-diversity joint kernel that prioritizes the most informative experiences, thereby enabling learning that is both efficient and effective. We evaluate E$^2$DT on challenging robotic manipulation benchmarks in both simulation and real-robot settings. Results show that it consistently outperforms prior methods. These findings demonstrate that coupling policy learning with experience-aware sampling provides a principled path toward robust long-horizon robotic learning.
### Title:
          Introducing WARM-VR: Benchmark Dataset for Multimodal Wearable Affect Recognition in Virtual Reality
 - **Authors:** Karim Alghoul, Faisal Mohd, Fedwa Laamarti, Hussein Al Osman, Abdulmotaleb El Saddik
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the growing integration of human-computer interaction into everyday life, advances in machine learning have enabled systems to better perceive and respond to users' emotional states. Most existing affect recognition datasets focus on static environments, limiting their applicability to immersive multimedia contexts such as Virtual Reality (VR). In this paper, we introduce WARM-VR, a novel publicly available multimodal dataset designed to support affect recognition in immersive, multisensory environments using wearable sensing instrumentation. Data were collected from 31 participants aged 19-37 using wearable sensors: a wristband measuring Blood Volume Pulse (BVP), EDA, skin Temperature, three-axis Acceleration, and a chest strap recording ECG signals. Participants engaged in immersive VR experiences designed to elicit relaxation through a calming beach environment following stress induction via an arithmetic task. These sessions incorporated synchronized multimedia stimuli: visual, auditory, and olfactory. Affective states were assessed subjectively through validated self-report questionnaires and objectively through the analysis of physiological measurements. Statistical analysis of the questionnaires confirmed that VR relaxation significantly reduced negative affect, particularly with olfactory enhancement. Furthermore, we established a benchmark on the dataset using widely recognized machine learning algorithms. The best performance for binary classification from BVP data of valence, was obtained with a CNN and a CNN-Bi-GRU model, both achieving an average F1-score of 0.63 and an AUC of 0.69. For arousal, a lightweight Transformer architecture provided the most balanced results (F1-0 0.54 and F1-1 0.63), outperforming recurrent hybrids. In the relaxation task, a CNN-Bi-GRU model reached the highest overall performance (average F1-score 0.64, AUC 0.69).
### Title:
          State Stream Transformer (SST) V2: Parallel Training of Nonlinear Recurrence for Latent Space Reasoning
 - **Authors:** Thea Aviss
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current transformers discard their rich latent residual stream between positions, reconstructing latent reasoning context at each new position and leaving potential reasoning capacity untapped. The State Stream Transformer (SST) V2 enables parameter-efficient reasoning in continuous latent space through an FFN-driven nonlinear recurrence at each decoder layer, where latent states are streamed horizontally across the full sequence via a learned blend. This same mechanism supports continuous latent deliberation per position at inference time, dedicating additional FLOPs to exploring abstract reasoning before committing to a token. A two-pass parallel training procedure resolves the sequential dependency of the recurrence to allow compute-efficient training. Hidden state analysis shows the state stream facilitates reasoning through exploration of distinct semantic basins in continuous latent space, where transitions at content-dependent positions move the model into a substantially different Bayesian posterior, directly influencing the latent space at future positions. We also find, via a learned probe, that at the first generated token position, the latent state already predicts whether the eventual answer will survive or break under additional latent computation for every subsequent position. Co-trained into an existing 27B backbone using only a small dataset of GSM8K examples, the SST delivers a +15.15 point gain over a fine-tuning-matched baseline on out-of-distribution GPQA-Diamond and cuts that same baseline's remaining GSM8K errors by 46%, together showing that the reasoning improvement is attributable to the architectural mechanism rather than scale or training data. On GPQA-Diamond, the resulting 27B SST also achieves higher accuracy than several larger open-weight and proprietary systems, including open-weight models up to 25 times larger.
### Title:
          Caracal: Causal Architecture via Spectral Mixing
 - **Authors:** Bingzheng Gan, Tianyi Zhang, Yusu Li, Jing Huang, Wei Shi, Yangkai Ding, Tao Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scalability of Large Language Models to long sequences is hindered by the quadratic cost of attention and the limitations of positional encodings. To address these, we introduce Caracal, a novel architecture that replaces attention with a parameter-efficient, $\mathcal{O}(L \log L)$ Multi-Head Fourier (MHF) module. Our contributions are threefold: (1) We leverage the Fast Fourier Transform (FFT) for sequence mixing, inherently addressing both bottlenecks mentioned above. (2) We apply a frequency-domain causal masking technique that enforces autoregressive capabilities via asymmetric padding and truncation, overcoming a critical barrier for Fourier-based generative models. (3) Unlike efficient models relying on hardware-specific implementations (e.g., Mamba), we uses standard library operators. This ensures robust portability, eliminating common deployment barriers. Evaluations demonstrate that Caracal performs competitively with Transformer and SSM baselines, offering a scalable and simple pathway for efficient long-sequence modeling. Code is available in Appendix.
### Title:
          Efficient Spatio-Temporal Vegetation Pixel Classification with Vision Transformers
 - **Authors:** Alan Gomes, Anderson Gonçalves, Samuel Felipe dos Santos, Nathan Felipe Alves, Magna Soelma Beserra de Moura, Bruna de Costa Alberton, Leonor Patricia C. Morellato, Ricardo da Silva Torres, Jurandy Almeida
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Plant phenology-the study of recurrent life cycle events-is essential for understanding ecosystem dynamics and their responses to climate change impacts. While Unmanned Aerial Vehicles (UAVs) and near-surface cameras enable high-resolution monitoring, identifying plant species across time remains computationally challenging. State-of-the-art approaches, specifically Multi-Temporal Convolutional Networks (CNNs), rely on rigid multi-branch architectures that scale poorly with longer time series and require large spatial context windows. In this paper, we present an extensive study on optimizing Vision Transformers (ViTs) for efficient spatio-temporal vegetation pixel classification. We conducted a comprehensive ablation study analyzing seven key design dimensions, including: (i) data normalization; (ii) spectral arrangement; (iii) boundary handling; (iv) spatial context window shape and size; (v) tokenization strategies; (vi) positional encoding; and (vii) feature aggregation strategies. Our method was evaluated on two datasets from the Brazilian Cerrado biome, Serra do Cipó (aerial imagery) and Itirapina (near-surface imagery). Experimental results demonstrate that our ViT approach offers a substantial improvement in computational efficiency while maintaining competitive classification performance. Notably, our ViT reduces Floating Point Operations (FLOPs) by an order of magnitude and maintains constant parameter complexity regardless of the time series length, whereas the CNN baseline scales linearly. Our findings confirm that ViTs are a robust, scalable solution for resource-constrained phenological monitoring systems.
### Title:
          Beyond Visual Fidelity: Benchmarking Super-Resolution Models for Large-Scale Remote Sensing Imagery via Downstream Task Integration
 - **Authors:** Zhili Li, Kangyang Chai, Zhihao Wang, Xiaowei Jia, Yanhua Li, Gengchen Mai, Sergii Skakun, Dinesh Manocha, Yiqun Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Super-resolution (SR) techniques have made major advances in reconstructing high-resolution images from low-resolution inputs. The increased resolution provides visual enhancement and utility for monitoring tasks. In particular, SR has been increasingly developed for satellite-based Earth observation, with applications in urban planning, agriculture, ecology, and disaster response. However, existing SR studies and benchmarks typically use fidelity metrics such as PSNR or SSIM, whereas the true utility of super-resolved images lies in supporting downstream tasks such as land cover classification, biomass estimation, and change detection. To bridge this gap, we introduce GeoSR-Bench, a downstream task-integrated SR benchmark dataset to evaluate SR models beyond fidelity metrics. GeoSR-Bench comprises spatially co-located, temporally aligned, and quality-controlled image pairs from about 36,000 locations across diverse land covers, spanning resolutions from 500m to 0.6m. To the best of our knowledge, GeoSR-Bench is the first SR benchmark that directly connects improved image resolution from SR models with downstream Earth monitoring tasks, including land cover segmentation, infrastructure mapping, and biophysical variable estimation. Using GeoSR-Bench, we benchmark GAN, transformer, neural operator, and diffusion-based SR models on perceptual quality and downstream task performance. We conduct experiments with 270 settings, covering 2 cross-platform SR tasks, 9 SR models, 3 downstream task models, and 5 downstream tasks for each SR task. The results show that improvements in traditional SR metrics often do not correlate with gains in task performance, and the correlations can be negative, indicating that these metrics provide limited guidance for selecting superior models for downstream tasks. This reveals the need to integrate downstream tasks into SR model development and evaluation.
### Title:
          Borrowed Geometry: Computational Reuse of Frozen Text-Pretrained Transformer Weights Across Modalities
 - **Authors:** Abay Bektursun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Frozen Gemma 4 31B weights pretrained exclusively on text tokens, unmodified, transfer across modality boundaries through a thin trainable interface. (1) OGBench scene-play-singletask-task1-v0: $+4.33$pt over published GCIQL at $n=3$ with std 0.74 -- a published-SOTA win on a robotic manipulation task the substrate has never seen. (2) D4RL Walker2d-medium-v2: Decision-Transformer parity ($76.2 \pm 0.8$, $n=3$) at $0.43\times$ DT's trainable count, with the frozen substrate compressing to a 5L slice ($+1.66$pt over the 6L baseline at $n=3$). (3) Associative recall as the cleanest pretraining-load-bearing case: the frozen slice + a 113K-parameter linear interface reaches L30 best-checkpoint per-bit error 0.0505 ($n=2$); a 6.36M-parameter from-scratch trained transformer at matched capacity ($1/\sqrt{d_k}$ scaling, two seeds, LR sweep) cannot solve the task at all under the protocol (best L30 = 0.4395), an $8.7\times$ advantage. Architecture-alone falsifications: a frozen random transformer with correct $1/\sqrt{d_k}$ scaling stays at random-chance loss for 50k steps; a random-init Gemma slice fails OGBench cube-double-play-task1 entirely (0.89% across $n=3$ where pretrained reaches 60%). A dual-measurement protocol -- text-activation probing on 95 English sentences plus task-ablation on a non-language target -- names individual heads independently identifiable on both protocols: head L26.28 scores $3.7\times$ the slice mean for English token-copying and is the #2 most-critical head for binary copy ablation ($\Delta$ L30 $= +0.221$); three further heads (L27.28, L27.2, L27.3) classify by the same protocol. The mechanism is single-model and the cross-modality results are single-task within their respective benchmarks; cross-model replication is structurally constrained because Gemma 4 31B is the only model on the small-scale Pareto frontier as of April 2026.
### Title:
          Escaping Mode Collapse in LLM Generation via Geometric Regulation
 - **Authors:** Xin Du, Kumiko Tanaka-Ishii
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Disordered Systems and Neural Networks (cond-mat.dis-nn); Artificial Intelligence (cs.AI); Chaotic Dynamics (nlin.CD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mode collapse is a persistent challenge in generative modeling and appears in autoregressive text generation as behaviors ranging from explicit looping to gradual loss of diversity and premature trajectory convergence. We take a dynamical-systems view and reinterpret mode collapse as reduced state-space accessibility caused by *geometric collapse*: during generation, the model's internal trajectory becomes confined to a low-dimensional region of its representation space. This implies mode collapse is not purely a token-level phenomenon and cannot be reliably solved by symbolic constraints or probability-only decoding heuristics. Guided by this perspective, we propose *Reinforced Mode Regulation* (RMR), a lightweight, online state-space intervention that regulates dominant self-reinforcing directions in the Transformer value cache (implemented as low-rank damping). Across multiple large language models, RMR substantially reduces mode collapse and enables stable, high-quality generation at extremely low entropy rates (down to 0.8 nats/step), whereas standard decoding typically collapses near 2.0 nats/step.
### Title:
          Thinking in Text and Images: Interleaved Vision--Language Reasoning Traces for Long-Horizon Robot Manipulation
 - **Authors:** Jinkun Liu, Haohan Chi, Lingfeng Zhang, Yifan Xie, YuAn Wang, Long Chen, Hangjun Ye, Xiaoshuai Hao, Wenbo Ding
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-horizon robotic manipulation requires plans that are both logically coherent and geometrically grounded. Existing Vision-Language-Action policies usually hide planning in latent states or expose only one modality: text-only chain-of-thought encodes causal order but misses spatial constraints, while visual prediction provides geometric cues but often remains local and semantically underconstrained. We introduce Interleaved Vision--Language Reasoning (IVLR), a policy framework built around \trace{}, an explicit intermediate representation that alternates textual subgoals with visual keyframes over the full task horizon. At test time, a single native multimodal transformer self-generates this global semantic-geometric trace from the initial observation and instruction, caches it, and conditions a closed-loop action decoder on the trace, original instruction, and current observation. Because standard robot datasets lack such traces, we construct pseudo-supervision by temporally segmenting demonstrations and captioning each stage with a vision-language model. Across simulated benchmarks for long-horizon manipulation and visual distribution shift, \method{} reaches 95.5\% average success on LIBERO, including 92.4\% on LIBERO-Long, and 59.4\% overall success on SimplerEnv-WidowX. Ablations show that both modalities are necessary: without traces, LIBERO-Long success drops to 37.7\%; text-only and vision-only traces reach 62.0\% and 68.4\%, while the full interleaved trace reaches 92.4\%. Stress tests with execution perturbations and masked trace content show moderate degradation, suggesting that the trace can tolerate local corruption and moderate execution drift, but remains limited under stale or incorrect global plans.
### Title:
          Soft Graph Diffusion Transformer for MIMO Detection
 - **Authors:** Nan Jiang, Jiadong Hong, Lei Liu, Xinyu Bian, Wenjie Wang, Zhaoyang Zhang
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based MIMO detection has shown strong empirical performance, yet existing methods typically rely on fixed-depth architectures without explicitly modeling the progressive refinement of symbol estimates. In this paper, we revisit MIMO detection from a flow matching perspective and propose the Soft Graph Diffusion Transformer (SGDiT), which reformulates detection as a noise-level-conditioned denoising process that progressively transforms a Gaussian initialization toward the posterior conditioned on channel observations. An adaptive layer normalization (AdaLN)-conditioned soft graph transformer is employed to parameterize the denoising dynamics, enabling stage-aware information integration between observation and symbol domains. To better align with the discrete nature of symbol detection, we further adopt a cross-entropy-based training objective that directly models bit-wise posterior probabilities, providing a more suitable inductive bias than conventional regression-based formulations. Experimental results across various MIMO system configurations demonstrate that SGDiT achieves competitive bit error rate (BER) performance compared with representative baselines. Furthermore, the proposed model exhibits good generalization capability across different channel conditions. Overall, the SGDiT framework provides an effective and practical approach for neural MIMO detection.
### Title:
          From Local to Global to Mechanistic: An iERF-Centered Unified Framework for Interpreting Vision Models
 - **Authors:** Yearim Kim, Sangyu Han, Nojun Kwak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern vision models achieve remarkable accuracy, but explaining where evidence arises, what the model encodes, and how internal computations assemble that evidence remains fragmented. We introduce an iERF-centric framework that unifies local, global, and mechanistic interpretability around a single analysis unit: the pointwise feature vector (PFV) paired with its instance-specific Effective Receptive Field (iERF). On the local side, Sharing Ratio Decomposition (SRD) expresses each PFV as a mixture of upstream PFVs via sharing ratios and propagates iERFs to construct class-discriminative saliency maps. SRD yields high-resolution, activation-faithful explanations, is robust to targeted manipulation and noise, and remains activation-agnostic across common nonlinearities. For the global view, we introduce Concept-Anchored Feature Explanation (CAFE), which utilizes the iERF as a semantic label, grounding abstract latent vectors in verifiable pixel-level evidence. With CAFE, we address the challenge of non-localized sparse autoencoder latents--especially in Transformers, where early self-attention mixes distant context. To answer how representations are composed through depth, we propose the Interlayer Concept Graph with Interlayer Concept Attribution (ICAT), which quantifies concept-to-concept influence while isolating layer pairs; an interlayer insertion, deletion protocol identifies Integrated Gradients as the most faithful instantiation. Empirically, across ResNet50, VGG16, and ViTs, our framework outperforms baselines in both fidelity and robustness, successfully interprets dispersed SAE features, and exposes dominant concept routes in correct, misclassified, and adversarial cases. Grounded in iERFs, our approach provides a coherent, evidence-backed map from pixels to concepts to decisions.
### Title:
          A Comparative Study of QSPR Methods on a Unique Multitask PAMPA dataset
 - **Authors:** Andrs Formanek, Anna Vincze, Richrd Bicsak, Yves Moreau, Gyorgy T. Balogh, Adam Arany
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a unique, multitask dataset comprising 143 drug and drug candidate molecules, each evaluated on in vitro, parallel artificial-membrane permeability assays (PAMPA) using six different model membranes. Using this resource, we systematically assess the effectiveness of various molecular descriptors and regression models in predicting passive membrane permeability. The studied models range from simple linear regression to a modern pre-trained transformer architecture. Particular attention is given to the trade-off between predictive performance and model interpretability, highlighting the challenges introduced by machine learning approaches. To our knowledge, this is the most comprehensive study on simultaneous modeling of multiple organ-specific PAMPA membranes to date, offering novel insights into membrane-specific permeability profiles. We found that expert-designed physico-chemical property descriptors are more fitting for a limited sample size permeabilty study than deep learning based representations.
### Title:
          Inductive Latent Context Persistence: Closing the Post-Handover Cold Start in 6G Radio Access Networks
 - **Authors:** Anubhab Banerjee, Daniyal Amir Awan
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In modern radio access networks (RANs), rule-based handover (HO) decisions (e.g., A3/A5) depend on user equipment (UE) measurements only, so UEs at the same location can receive inconsistent HO outcomes. GNN-based methods improve HO KPIs using richer context than measurements alone. However, recurrent or graph models discard the per-UE recurrent state at HO and reinitialize at the target next-generation Node B (gNB), losing mobility history and forcing the target model to rebuild from post-HO measurements only. We address this post-HO cold start with Inductive Latent Context Persistence (ILCP), compressing the source recurrent state, transporting it on the 3GPP Xn as a 128-byte payload, and adapting it at the target gNB. We model the RAN as a dynamic heterogeneous graph over UE nodes, gNB nodes, measurement edges, and Xn edges. On a Vienna 4G/5G drive-test, ILCP achieves 0.0% ping-pong HOs versus 6.5% for an identical no-transfer baseline and 22.6% for a Transformer baseline; post-HO accuracy improves by +5.1 pp on average (peak +13.3 pp) in the 50-250 ms window. On one NVIDIA GTX 1080 (8 GB), ILCP runs end-to-end at 7.7 ms p99 per handover decision. Under perturbations (shadow fading, NLOS blockage, SSB-burst sparsity), robustly trained ILCP keeps handover failure (HOF) in the 10-13% range. Under the same fixed-reference-label setting, A3/A5 rises from 1.1% to 57-65% HOF when measurements are perturbed, exposing limits of measurement-only rules.
### Title:
          Beyond Decodability: Reconstructing Language Model Representations with an Encoding Probe
 - **Authors:** Gaofei Shen, Martijn Bentum, Tom Lentz, Afra Alishahi, Grzegorz Chrupała
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probing is widely used to study which features can be decoded from language model representations. However, the common decoding probe approach has two limitations that we aim to solve with our new encoding probe approach: contributions of different features to model representations cannot be directly compared, and feature correlations can affect probing results. We present an Encoding Probe that reverses this direction and reconstructs internal representations of models using interpretable features. We evaluate this method on text and speech transformer models, using feature sets spanning acoustics, phonetics, syntax, lexicon, and speaker identity. Our results suggest that speaker-related effects vary strongly across different training objectives and datasets, while syntactic and lexical features contribute independently to reconstruction. These results show that the Encoding Probe provides a complementary perspective on interpreting model representations beyond decodability.
### Title:
          CMTA: Leveraging Cross-Modal Temporal Artifacts for Generalizable AI-Generated Video Detection
 - **Authors:** Hang Wang, Chao Shen, Chenhao Lin, Minghui Yang, Lei Zhang, Cong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The proliferation of advanced AI video synthesis techniques poses an unprecedented challenge to digital video authenticity. Existing AI-generated video (AIGV) detection methods primarily focus on uni-modal or spatiotemporal artifacts, but they overlook the rich cues within the visual-textual cross-modal space, especially the temporal stability of semantic alignment. In this work, we identify a distinctive fingerprint in AIGVs, termed cross-modal temporal artifact (CMTA). Unlike real videos that exhibit natural temporal fluctuations in cross-modal alignment due to semantic variations, AIGVs display unnaturally stable semantic trajectories governed by given input prompts. To bridge this gap, we propose the CMTA framework, a cross-modal detection approach that captures these unique temporal artifacts through joint cross-modal embedding and multi-grained temporal modeling. Specifically, CMTA leverages BLIP to generate frame-level image captions and utilizes CLIP to extract corresponding visual-textual representations. A coarse-grained temporal modeling branch is then designed to characterize temporal fluctuations in cross-modal alignment with a GRU. In parallel, a fine-grained branch is constructed to capture intricate inter-frame variations from integrated visual-textual features with a Transformer encoder. Extensive experiments on 40 subsets across four large-scale datasets, including GenVideo, EvalCrafter, VideoPhy, and VidProM, validate that our approach sets a new state-of-the-art while exhibiting superior cross-generator generalization. Code and models of CMTA will be released at this https URL
### Title:
          Paired-CSLiDAR: Height-Stratified Registration for Cross-Source Aerial-Ground LiDAR Pose Refinement
 - **Authors:** Montana Hoover, Jing Liang, Tianrui Guan, Dinesh Manocha
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Paired-CSLiDAR (CSLiDAR), a cross-source aerial-ground LiDAR benchmark for single-scan pose refinement: refining a ground-scan pose within a 50 m-radius aerial crop. The benchmark contains 12,683 ground-aerial pairs across 6 evaluation sites and per-scan reference 6-DoF alignments for sub-meter root-mean-square error (RMSE) evaluation. Because aerial scans capture rooftops and canopy while ground scans capture facades and under-canopy, the two modalities share only a fraction of their geometry, primarily the terrain surface, causing standard registration methods and learned correspondence models to converge to metrically incorrect local minima. We propose Residual-Guided Stratified Registration (RGSR), a training-free, geometry-only refinement pipeline that exploits the shared ground plane through height-stratified ICP, reversed registration directions, and confidence-gated accept-if-better selection. RGSR achieves 86.0% S@0.75 m and 99.8% S@1.0 m on the primary benchmark of 9,012 scans, outperforming both the confidence-gated cascade at 83.7% and GeoTransformer at 76.3%. We validate RMSE-based pose selection with independent survey control and trajectory consistency, and show that added Fourier-Mellin BEV proposals can reduce RMSE while increasing actual pose error under extreme partial overlap. The dataset and code are being prepared for public release.
### Title:
          Spiking Sequence Machines and Transformers
 - **Authors:** Joy Bose
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence learning reduces to similarity-based retrieval over a temporally indexed representation space, a constraint on any sequence model, not a property of a specific architecture. We show that a spiking Sparse Distributed Memory sequence machine (2007) and the transformer (2017) independently instantiate the same five functional operations (encoding, context maintenance, associative retrieval, storage, and decoding), with cosine similarity as the shared retrieval primitive in both. We formalise a Phase-Latency Isomorphism showing that sinusoidal positional phase and spike timing are linearly related, and prove that dot product attention is invariant to this mapping up to a global scale factor on the positional component (Lemma 1). Empirically, frequency-compressed positional encoding fails to converge on a positionally demanding copy task, while a learned rank-based embedding matches or exceeds sinusoidal encoding, indicating that the critical property for positional representation is distance discriminability under dot-product similarity, not sinusoidal form. Time, phase, and rank are three instantiations of the same computational primitive, an ordered index whose structure survives similarity-based retrieval.
### Title:
          Robust Multimodal Recommendation via Graph Retrieval-Enhanced Modality Completion
 - **Authors:** Yuan Li, Jun Hu, Jiaxin Jiang, Bryan Hooi, Bingsheng He
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal data plays a critical role in web-based recommendation systems, where information from diverse modalities such as vision and text enhances representation learning. However, real-world multimodal datasets often suffer from modality incompleteness due to sensor failures, annotation scarcity, or privacy constraints, which substantially degrade model performance and reliability. One effective solution to address this issue is modality completion, which reconstructs missing features to provide modality-complete graphs for downstream tasks. Given a query node with missing multimodal features, existing modality completion methods typically infer information from the node itself or its neighbors to reconstruct the missing modality. However, these methods may overlook semantically relevant context in the graph, which contains valuable cues that are non-trivial to capture through simple methods like neighborhood aggregation. In this work, we propose GRE-MC, a Graph Retrieval-Enhanced Modality Completion framework, to overcome these limitations. By introducing a modality-aware subgraph retrieval mechanism, GRE-MC selects semantically relevant subgraphs from the entire graph, providing richer contextual information for completing missing modalities. Subsequently, a graph transformer jointly encodes the query node and the retrieved subgraph via global attention to complete the missing features, while a learnable sparse-routing codebook regularizes latent embeddings into compact bases for improved robustness. Extensive experiments on multimodal recommendation benchmarks demonstrate that GRE-MC consistently outperforms state-of-the-art methods, validating the effectiveness of subgraph retrieval and joint-encoding graph transformer for robust modality completion.
### Title:
          Foundation AI Models for Aerosol Optical Depth Estimation from PACE Satellite Data
 - **Authors:** Zahid Hassan Tushar, Sanjay Purushotham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aerosol Optical Depth (AOD) retrieval is essential for Earth observation, supporting applications from air quality monitoring to climate studies. Conventional physics-based AOD retrieval methods formulate the problem as a pixel-wise inversion, relying on radiative transfer modeling, memory-intensive look-up tables, and auxiliary meteorological data. While recent data-driven approaches have shown promise, many fail to exploit the spatial-spectral coherence of hyperspectral imagery, leading to spatially inconsistent and noise-sensitive retrievals. We present the first study exploring Foundation AI models for AOD retrieval and propose ViTCG, a Vision Transformer with Channel-wise Grouping-based spatial regression framework that reduces retrieval bias and error. ViTCG uses hyperspectral top-of-atmosphere radiance as input and jointly models spatial context and spectral information. Validation with PACE radiance observations demonstrates a 62% reduction in mean squared error compared to state-of-the-art foundation models, including Prithvi, and produces spatially coherent AOD fields.
### Title:
          Deep Kernel Learning for Stratifying Glaucoma Trajectories
 - **Authors:** Bruce Rushing, Angela Danquah, Alireza Namazi, Arjun Dirghangi, Heman Shakeri
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effectively stratifying patient risk in chronic diseases like glaucoma is a major clinical challenge. Clinicians need tools to identify patients at high risk of progression from sparse and irregularly-sampled electronic health records (EHRs). We propose a novel deep kernel learning (DKL) architecture that leverages a Gaussian Process (GP) backend. The GP's kernel is defined by a transformer-based feature extractor applied to clinical-BERT embeddings to model glaucoma patient trajectories from multimodal EHR data. Our method successfully identifies three clinically distinct patient subgroups. Crucially, the model learns to decouple disease progression from current severity, identifying a high-risk group with a worsening trajectory despite having better average visual acuity than a second, stably poor group. This reveals that the model learns to identify progression risk rather than just the current disease state. This ability to stratify patients based on their risk trajectory progression offers a powerful tool for clinical decision support, enabling targeted interventions for high-risk individuals and improving the management of glaucoma care.
### Title:
          Characterizing the Expressivity of Local Attention in Transformers
 - **Authors:** Jiaoda Li, Ryan Cotterell
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The transformer is the most popular neural architecture for language modeling. The cornerstone of the transformer is its global attention mechanism, which lets the model aggregate information from all preceding tokens before generating the next token. One common variant of attention is called local attention, which restricts each token to aggregating information from a bounded window of predecessors, reducing the quadratic cost of global attention to linear. Although this restriction is usually motivated by efficiency, it has also been found to improve model quality, a phenomenon that has so far lacked a satisfactory explanation. We provide a formal account of this phenomenon in terms of recognizer expressivity. It has been shown that fixed-precision transformers with global attention correspond to a fragment of linear temporal logic containing a single past operator. We additionally prove that adding local attention introduces a second temporal operator, strictly enlarging the class of recognizable regular languages. Moreover, global and local attention are expressively complementary: neither subsumes the other, and combining them yields the richest fragment. Experiments on formal language recognition and natural language modeling corroborate the theory, showing that hybrid global--local transformers outperform their global-only counterparts.
### Title:
          Directed Social Regard: Surfacing Targeted Advocacy, Opposition, Aid, Harms, and Victimization in Online Media
 - **Authors:** Scott Friedman, Ruta Wheelock, Sonja Schmer-Galunder, Drisana Iverson, Jake Vasilakes, Joan Zheng, Jeffrey Rye, Vasanth Sarathy, Christopher Miller
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The language in online platforms, influence operations, and political rhetoric frequently directs a mix of pro-social sentiment (e.g., advocacy, helpfulness, compassion) and anti-social sentiment (e.g., threats, opposition, blame) at different topics, all in the same message. While many natural language processing (NLP) tools classify or score a text's overall sentiment as positive, neutral, or negative, these tools cannot report that positive and negative sentiments coexist, and they cannot report the target of those sentiments. This paper presents the Directed Social Regard (DSR) approach to multi-dimensional, multi-valence sentiment analysis, comprised of a pair of transformer-based models that (1) detects span-level targets of sentiment in a message and then (2) scores all spans within the message context along three (-1, 1) axes of regard that are motivated by social science theories of moral disengagement and moral framing. We present a data collection and annotation strategy for DSR dataset construction, a transformer-based architecture for span-level scoring, and a validation study with promising results. We apply the validated DSR model on six third-party datasets of online media and report meaningful correlations between DSR outputs and the labels and topics in these pre-existing social science datasets.
### Title:
          GMGaze: MoE-Based Context-Aware Gaze Estimation with CLIP and Multiscale Transformer
 - **Authors:** Xinyuan Zhao, Yihang Wu, Ahmad Chaddad, Sarah A. Alkhodair, Reem Kateb
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaze estimation methods commonly use facial appearances to predict the direction of a person gaze. However, previous studies show three major challenges with convolutional neural network (CNN)-based, transformer-based, and contrastive language-image pre-training (CLIP)-based methods, including late fusion of image features, lack of factor-aware conditioning, and impractical capacity scaling. To address these challenges, we propose Globally-conditioned Multi-scale Gaze estimation (GMGaze), which leverages a multi-scale transformer architecture. Specifically, the model first introduces semantic prototype conditioning, which modulates the CLIP global image embedding using four learned prototype banks (i.e., illumination, background, head pose and appearance) to generate two complementary context-biased global tokens. These tokens, along with the CLIP patch and CNN tokens, are fused at the first layer. This early unified fusion prevents information loss common in late-stage merging. Finally, each token passes through sparse Mixture-of-Experts modules, providing conditional computational capacity without uniformly increasing dense parameters. For cross-domain adaptation, we incorporate an adversarial domain adaptation technique with a feature separation loss that encourages the two global tokens to remain de-correlated. Experiments using four public benchmarks (MPIIFaceGaze, EYEDIAP, Gaze360, and ETH-XGaze) show that GMGaze achieves mean angular errors of 2.49$^\circ$, 3.22$^\circ$, 10.16$^\circ$, and 1.44$^\circ$, respectively, outperforming previous baselines in all within-domain settings. In cross-domain evaluations, it provides state-of-the-art (SOTA) results on two standard transfer routes.
### Title:
          Let ViT Speak: Generative Language-Image Pre-training
 - **Authors:** Yan Fang, Mengcheng Lan, Zilong Huang, Weixian Lei, Yunqing Zhao, Yujie Zhong, Yingchen Yu, Qi She, Yao Zhao, Yunchao Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we present \textbf{Gen}erative \textbf{L}anguage-\textbf{I}mage \textbf{P}re-training (GenLIP), a minimalist generative pretraining framework for Vision Transformers (ViTs) designed for multimodal large language models (MLLMs). To better align vision encoders with the autoregressive nature of LLMs, GenLIP trains a ViT to predict language tokens directly from visual tokens using a standard language modeling objective, without contrastive batch construction or an additional text decoder. This design offers three key advantages: (1) \textbf{Simplicity}: a single transformer jointly models visual and textual tokens; (2) \textbf{Scalability}: it scales effectively with both data and model size; and (3) \textbf{Performance}: it achieves competitive or superior results across diverse multimodal benchmarks. Trained on 8B samples from Recap-DataComp-1B, GenLIP matches or surpasses strong baselines despite using substantially less pretraining data. After continued pretraining on multi-resolution images at native aspect ratios, GenLIP further improves on detail-sensitive tasks such as OCR and chart understanding, making it a strong foundation for vision encoders in MLLMs.
## Keyword: autonomous driving
### Title:
          Cloud Is Closer Than It Appears: Revisiting the Tradeoffs of Distributed Real-Time Inference
 - **Authors:** Pragya Sharma, Hang Qiu, Mani Srivastava
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing deployment of deep neural networks (DNNs) in cyber-physical systems (CPS) enhances perception fidelity, but imposes substantial computational demands on execution platforms, posing challenges to real-time control deadlines. Traditional distributed CPS architectures typically favor on-device inference to avoid network variability and contention-induced delays on remote platforms. However, this design choice places significant energy and computational demands on the local hardware. In this work, we revisit the assumption that cloud-based inference is intrinsically unsuitable for latency-sensitive control tasks. We demonstrate that, when provisioned with high-throughput compute resources, cloud platforms can effectively amortize network and queueing delays, enabling them to match or surpass on-device performance for real-time decision-making. Specifically, we develop a formal analytical model that characterizes distributed inference latency as a function of the sensing frequency, platform throughput, network delay, and task-specific safety constraints. We instantiate this model in the context of emergency braking for autonomous driving and validate it through extensive simulations using real-time vehicular dynamics. Our empirical results identify concrete conditions under which cloud-based inference adheres to safety margins more reliably than its on-device counterpart. These findings challenge prevailing design strategies and suggest that the cloud is not merely a feasible option, but often the preferred inference location for distributed CPS architectures. In this light, the cloud is not as distant as traditionally perceived; in fact, it is closer than it appears.
### Title:
          Learning physically grounded traffic accident reconstruction from public accident reports
 - **Authors:** Yanchen Guan, Haicheng Liao, Chengyue Wang, Zhenning Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic accidents are routinely documented in textual reports, yet physically grounded accident reconstruction remains difficult because detailed scene measurements and expert reconstructions are scarce, costly and hard to scale. Here we formulate accident reconstruction from publicly accessible reports and scene measurements as a parameterized multimodal learning problem. We construct CISS-REC, a dataset of 6,217 real-world accident cases curated from the NHTSA Crash Investigation Sampling System, and develop a reconstruction framework that grounds report semantics to road topology and participant attributes, reconstructs lane consistent pre-impact motion, and refines collision relevant interactions through localized geometric reasoning and temporal allocation. Our method outperforms representative baselines on CISS-REC, achieving the strongest overall reconstruction fidelity, including improved accident point accuracy and collision consistency. These results show that public accident reports can serve as scalable computational substrates for quantitatively verifiable accident reconstruction, with potential value for traffic safety analysis, simulation and autonomous driving research.
### Title:
          Learning from the Unseen: Generative Data Augmentation for Geometric-Semantic Accident Anticipation
 - **Authors:** Yanchen Guan, Haicheng Liao, Chengyue Wang, Xingcheng Liu, Jiaxun Zhang, Keqiang Li, Zhenning Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anticipating traffic accidents is a critical yet unresolved problem for autonomous driving, hindered by the inherent complexity of modeling interactions between road users and the limited availability of diverse, large-scale datasets. To address these issues, we propose a dual-path framework. On the one hand, we employ a video synthesis pipeline that, guided by structured prompts, derives feature distributions from existing corpora and produces high-fidelity synthetic driving scenes consistent with the statistical patterns of real data. On the other hand, we design a graph neural network enriched with semantic cues, enabling dynamic reasoning over both spatial and semantic relations among participants. To validate the effectiveness of our approach, we release a new benchmark dataset containing standardized, finely annotated video sequences that cover a broad spectrum of regions, weather, and traffic conditions. Evaluations across existing datasets and our new benchmark confirm notable gains in both accuracy and anticipation lead time, highlighting the capacity of the proposed framework to mitigate current data bottlenecks and enhance the reliability of autonomous driving systems.
### Title:
          Do Open-Loop Metrics Predict Closed-Loop Driving? A Cross-Benchmark Correlation Study of NAVSIM and Bench2Drive
 - **Authors:** Yiru Wang, Anqing Jiang, Shuo Wang, Yuwen Heng, Hai Yang, Yang Chen, Hao Sun
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-loop evaluation offers fast, reproducible assessment of autonomous driving planners, but its ability to predict real closed-loop driving performance remains questionable. Prior work has shown that traditional open-loop metrics such as Average Displacement Error (ADE) and Final Displacement Error (FDE) exhibit no reliable correlation with closed-loop Driving Score. In this paper, we ask whether the more recent, safety-aware open-loop metrics introduced by NAVSIM~v2 can bridge this gap. By systematically cross-referencing published results from 15 state-of-the-art methods across NAVSIM (open-loop) and Bench2Drive (closed-loop), we compile a paired dataset of open-loop sub-metrics and closed-loop performance, yielding 8 methods with complete paired data. Our analysis reveals three key findings: (1) the aggregate NAVSIM PDM Score shows a strong positive but non-monotonic correlation with Bench2Drive Driving Score, with clear ranking inversions; (2) among individual NAVSIM sub-metrics, Ego Progress (EP) is the strongest single predictor of closed-loop success, substantially exceeding the safety-critical collision metric NC; (3) the safety-progress trade-off manifests differently in open-loop and closed-loop: methods that maximize safety at the expense of progress rank highly in NAVSIM but underperform in closed-loop due to timeout and slow-driving penalties. We further demonstrate that a much simpler 3-metric formula matches the predictive power of the full 5-metric PDMS at the same Spearman $\rho{=}0.90$ on our paired sample of $n{=}8$ methods, suggesting that within current state-of-the-art methods -- where TTC and Comfort approach saturation -- these two sub-metrics add little marginal information for closed-loop ranking. Additionally, we identify the snowball effect -- where small open-loop deviations compound into closed-loop failures -- as a candidate mechanism for the residual gap.
### Title:
          World Model for Robot Learning: A Comprehensive Survey
 - **Authors:** Bohan Hou, Gen Li, Jindou Jia, Tuo An, Xinying Guo, Sicong Leng, Haoran Geng, Yanjie Ze, Tatsuya Harada, Philip Torr, Oier Mees, Marc Pollefeys, Zhuang Liu, Jiajun Wu, Pieter Abbeel, Jitendra Malik, Yilun Du, Jianfei Yang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models, which are predictive representations of how environments evolve under actions, have become a central component of robot learning. They support policy learning, planning, simulation, evaluation, data generation, and have advanced rapidly with the rise of foundation models and large-scale video generation. However, the literature remains fragmented across architectures, functional roles, and embodied application domains. To address this gap, we present a comprehensive review of world models from a robot-learning perspective. We examine how world models are coupled with robot policies, how they serve as learned simulators for reinforcement learning and evaluation, and how robotic video world models have progressed from imagination-based generation to controllable, structured, and foundation-scale formulations. We further connect these ideas to navigation and autonomous driving, and summarize representative datasets, benchmarks, and evaluation protocols. Overall, this survey systematically reviews the rapidly growing literature on world models for robot learning, clarifies key paradigms and applications, and highlights major challenges and future directions for predictive modeling in embodied agents. To facilitate continued access to newly emerging works, benchmarks, and resources, we will maintain and regularly update the accompanying GitHub repository alongside this survey.
### Title:
          Time-series Meets Complex Motion Modeling: Robust and Computational-effective Motion Predictor for Multi-object Tracking
 - **Authors:** Nhat-Tan Do, Le-Huy Tu, Nhi Ngoc-Yen Nguyen, Dieu-Phuong Nguyen, Trong-Hop Do
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-object tracking (MOT) is critical in numerous real-world applications, including surveillance, autonomous driving, and robotics. Accurately predicting object motion is fundamental to MOT, but current methods struggle with the complexities of real-world, non-linear motion (e.g., sudden stops, sharp turns). While recent research has gravitated towards increasingly complex and computationally expensive generative models to tackle this problem, their practical utility is often constrained. This paper challenges that paradigm, arguing that such complexity is not only unnecessary but can be outperformed by a more efficient, purpose-built approach. We introduce the Temporal Convolutional Motion Predictor (TCMP), a novel framework for MOT that leverages a modified Temporal Convolutional Network (TCN) featuring dilated convolutions and a regression head. This design allows for effective motion prediction across arbitrary temporal context lengths. Experimental results demonstrate that our approach achieves state-of-the-art performance, specifically improves upon the previous best method in several key metrics: HOTA (a measure of overall tracking accuracy) increases from 62.3% to 63.4%, IDF1 (a measure of identity preservation) rises from 63.0% to 65.0%, and AssA (a measure of association accuracy) improves from 47.2% to 49.1%. Significantly, TCMP achieves this performance while being highly efficient; it has only 0.014 times the parameters and requires only 0.05 times the computational cost (FLOPs) compared to the SOTA method. while is only 0.014 times the size (in terms of parameters) and requires only 0.05 times the computational cost (in terms of FLOPs). These findings highlight the robustness of our method to advance MOT systems by ensuring adaptability, accuracy, and efficiency in complex tracking environments.
### Title:
          Physically Native World Models: A Hamiltonian Perspective on Generative World Modeling
 - **Authors:** Sen Cui, Jingheng Ma
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models have recently re-emerged as a central paradigm for embodied intelligence, robotics, autonomous driving, and model-based reinforcement learning. However, current world model research is often dominated by three partially separated routes: 2D video-generative models that emphasize visual future synthesis, 3D scene-centric models that emphasize spatial reconstruction, and JEPA-like latent models that emphasize abstract predictive representations. While each route has made important progress, they still struggle to provide physically reliable, action-controllable, and long-horizon stable predictions for embodied decision making. In this paper, we argue that the bottleneck of world models is no longer only whether they can generate realistic futures, but whether those futures are physically meaningful and useful for action. We propose \emph{Hamiltonian World Models} as a physically grounded perspective on world modeling. The key idea is to encode observations into a structured latent phase space, evolve the latent state through Hamiltonian-inspired dynamics with control, dissipation, and residual terms, decode the predicted trajectory into future observations, and use the resulting rollouts for planning. We discuss how Hamiltonian structure may improve interpretability, data efficiency, and long-horizon stability, while also noting practical challenges in real-world robotic scenes involving friction, contact, non-conservative forces, and deformable objects.
### Title:
          From Research to Practice: An Interactive Rapid Review of Autonomous Driving System Testing in Industry
 - **Authors:** Qunying Song, Ali Nouri, Håkan Sivencrona, Federica Sarro
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems (ADS) are increasingly deployed in real traffic, yet testing remains fundamentally challenging due to open environments, complex scenarios, and the lack of established processes and metrics. Despite extensive research, a gap persists between academic advances and their applicability in industrial practice. To address this, we conduct an interactive rapid review in collaboration with 21 practitioners from a leading automotive company. Practitioners identified 12 key challenges in ADS testing, and prioritised two as the most critical issues, namely approaches to and completeness of testing for End-to-End (E2E) ADS. We analyzed 17 research studies relevant to these two challenges, most of which focus on generating critical testing scenarios, and subsequently assessed their relevance and applicability in practice. Our study provides the first practitioner-driven review and evaluation of current ADS testing research, reveals practical challenges in ADS testing, offers rapid insights for practitioners, and highlights the need for more context-aware, industry-relevant solutions to bridge the gap between research and practice.
### Title:
          Map2World: Segment Map Conditioned Text to 3D World Generation
 - **Authors:** Jaeyoung Chung, Suyoung Lee, Jianfeng Xiang, Jiaolong Yang, Kyoung Mu Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D world generation is essential for applications such as immersive content creation or autonomous driving simulation. Recent advances in 3D world generation have shown promising results; however, these methods are constrained by grid layouts and suffer from inconsistencies in object scale throughout the entire world. In this work, we introduce a novel framework, Map2World, that first enables 3D world generation conditioned on user-defined segment maps of arbitrary shapes and scales, ensuring global-scale consistency and flexibility across expansive environments. To further enhance the quality, we propose a detail enhancer network that generates fine details of the world. The detail enhancer enables the addition of fine-grained details without compromising overall scene coherence by incorporating global structure information. We design the entire pipeline to leverage strong priors from asset generators, achieving robust generalization across diverse domains, even under limited training data for scene generation. Extensive experiments demonstrate that our method significantly outperforms existing approaches in user-controllability, scale consistency, and content coherence, enabling users to generate 3D worlds under more complex conditions.
