# Showing new listings for Monday, 13 July 2026
## Keyword: SLAM
### Title:
          Another look at the static PDE approach to multidimensional extrapolation
 - **Authors:** Hwi Lee
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a variant of the static PDE based extrapolation method (2014 Aslam, SIAM J. Sci. Comp) for extending smooth fields across interfaces implicitly defined as zero level sets. Our approach introduces the idea of relaxed upwinding finite differences as a key modification within the fast sweeping method. Unlike existing approaches, we require function values and their normal derivatives only on the first grid layer inside the domain adjacent to the boundary, thereby improving computational efficiency and flexibility. To further improve accuracy, we introduce a simple boundary reconstruction technique that significantly reduces the numerical error in the extrapolated solution near the boundary. Numerical experiments indicate enhanced performance of our approach across a range of domain geometries, including those with high curvature features.
### Title:
          AnythingReality: Robust Online Gaussian Splatting SLAM for Open-Vocabulary VR Scene Exploration
 - **Authors:** Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Miguel Altamirano Cabrera, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a novel integrated architecture for robust online 3D Gaussian splatting, real-time VR exploration, and speech-driven Vision-Language-Model interaction. Unlike methods assuming clean depth or external poses, our system combines ORB-SLAM3-based pose estimation with online Gaussian reconstruction for noisy real-world data. A VR pipeline enables immersive exploration of incremental reconstructions; a semantic module transcribes voice commands, generates scene descriptions, and records points of interest. Against state-of-the-art online Gaussian splatting methods, we improve image quality on our dataset (+14.5% PSNR, +8.6% SSIM, -14.3% LPIPS) and TUM-RGBD (+11.7% PSNR, +7.8% SSIM, -21.6% LPIPS), with comparable or superior frame rates via quality-speed configurations. We achieve an 88% VLM object-recognition rate.
### Title:
          What VGGT Knows About Overlap: Probing Geometric Foundation Models for Co-Visibility
 - **Authors:** Filippo Ziliotto, Luciano Serafini, Lamberto Ballan, Tommaso Campari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental challenge in 3D reconstruction and robotic localization is co-visibility: determining which image pairs share overlapping visible surfaces, particularly in scenarios with minimal overlap. We demonstrate that VGGT implicitly encodes co-visibility as an emergent behavior: without any supervision for this task, its internal representations exhibit a clear hierarchical structure mirroring that of large language models, i.e. early layers build a 3D-aware scene representation, while late layers act as dedicated co-visibility reasoners. In particular, we identify layer L17 as a negative anchor that consistently routes non-co-visible pairs for this backbone, regardless of the evaluation setting, providing task-grounded evidence of layer specialization in a geometry-grounded foundation model. Building on this, we introduce Co-VGGT, which freezes VGGT and trains only a lightweight layer-wise mixture-of-experts head (less than 7.5M parameters) to classify co-visibility from RGB alone, treating each layer as a specialized expert whose geometric abstraction is adaptively weighted per input pair. On the Co-VisiON benchmark, Co-VGGT surpasses the human annotation baseline and improves over prior work by more than 25% pairwise and 10% multiview. Pairwise predictions are well-calibrated (ECE=0.030), enabling direct use as edge weights in visibility graphs for downstream SfM and SLAM pipelines without post-hoc correction. Code and data are available.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Hydra++: Real-Time Hierarchical 3D Scene Graph Construction With Object-Level Shape Estimation
 - **Authors:** Hyungtae Lim, Nathan Hughes, Xihang Yu, Ruihan Xu, Yun Chang, Jingnan Shi, Rajat Talak, Luca Carlone
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D scene graphs provide a hierarchical abstraction of environments by encoding spatial entities, such as objects and places, and their relationships. However, existing scene graph systems model object geometry coarsely, relying on partial point clouds or class-level CAD templates, which limits instance-specific shape detail. This paper presents Hydra++, a system-level investigation into how learning-based object shape estimators can be integrated into a hierarchical 3D scene graph pipeline. Hydra++ incorporates category-agnostic shape estimation and a reprojection-mask consistency check to reject degenerate predictions from partial observations or imprecise segmentation. In its default CRISP-based configuration, Hydra++ performs online scene graph construction; slower estimators such as SAM3D are evaluated as modular alternatives to demonstrate generalization-latency trade-offs. Furthermore, to address the challenges of sparse and noisy depth measurements in outdoor environments, Hydra++ supports a hybrid LiDAR-camera configuration for large-scale operation, improving scene-level reconstruction quality. Experiments in both simulation and real-world outdoor campus scenarios demonstrate that Hydra++ improves object- and scene-level reconstruction quality. Project page is available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          GReFEM: Multimodal LLMs as Zero-Shot Semantic Assistants for Physics-Guided 3D Mesh Refinement
 - **Authors:** Kartik Bali, Mahish K. Guru, Christian J Cyron, Roland Aydin
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive volumetric finite element meshing is a critical step in computer-aided engineering and analysis that dictates the computational budget of a given problem. It traditionally requires iterative PDE solvers or heavily supervised, data-driven surrogates trained on large-scale simulation data. While Multimodal Large Language Models (MLLMs) excel in 2D visual tasks, their zero-shot capability to semantically ground regions based on geometric understanding and physics remains an open question. Overall, this study explores a significant question: can the high-level semantic understanding of off-the-shelf MLLMs serve as a viable, zero-shot geometric proxy for finite element mesh refinement? To investigate this, we introduce GReFEM (Geometric Reasoning Enhanced Multimodal LLMs for Finite Element Meshing), a framework that utilizes MLLMs to visually localize stress-critical regions based on physics-guided textual prompts. To bridge the gap between 2D MLLM pre-training and 3D geometries, we introduce orthoViews, a view-selection module that maximizes the observability of key geometric features. We conduct an in-depth empirical evaluation across diverse CAD geometries, loading cases, and SOTA MLLMs, comparing them against a tuned geometric heuristic under a strict, matched refinement budget. Our findings reveal that MLLMs demonstrate robust zero-shot capacity to accurately follow complex spatial-physical instructions, isolating stress-relevant features with higher precision than blind heuristics. By mapping both the successes and current limitations of MLLMs in physical grounding, this study defines the frontier of foundation models as semantic assistants in automated simulation workflows.
### Title:
          Is sub-metre resolution necessary for cocoa mapping? A landscape-stratified evaluation of very high resolution imagery, decametric Earth Observation inputs, and operational products in Cote d'Ivoire
 - **Authors:** Kasimir Orlowski, Filip Sabo, Michele Meroni, Astrid Verhegghen, Mariana Belgiu, Felix Rembold
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate cocoa mapping is increasingly important for deforestation monitoring, supply-chain transparency, and regulatory applications. Spatial aggregation in conventional medium-resolution Earth observation (EO) imagery may limit cocoa detection in heterogeneous smallholder landscapes. In Cote d'Ivoire, we therefore evaluated how mapping performance varies across landscape conditions, whether very high resolution (VHR) imagery provides a meaningful advantage, and whether foundation-model embeddings improve decametric cocoa mapping. We developed models using 0.5 m Pleiades VHR imagery, a 10 m Sentinel-2 annual composite, and embeddings from TESSERA and AlphaEarth Foundations (AEF), and additionally assessed four publicly available cocoa mapping products. Performance was evaluated through a landscape-stratified accuracy assessment using 2,821 independently interpreted reference points distributed across gradients of tree cover density and landscape fragmentation. The VHR model achieved the highest performance (F1 = 0.92) and maintained F1-scores above 0.90 across all strata. Among the decametric inputs, TESSERA performed best (F1 = 0.86), followed by AEF (F1 = 0.82) and Sentinel-2 (F1 = 0.76). Of the existing cocoa products, the Kalischek product performed best (F1 = 0.83), comparable to the internally trained AEF model. Performance differences between VHR and decametric approaches increased with fragmentation and under low and high tree cover density conditions. Targeted VHR acquisition may therefore be particularly beneficial in complex cocoa landscapes, while foundation-model embeddings offer a scalable alternative for large-area mapping.
### Title:
          MultiView-Bench: A Diagnostic Benchmark for World-Centric Multi-View Integration in VLMs
 - **Authors:** Hantao Zhang, Jinru Sui, Ed Li, Dirk Bergemann, Zhuoran Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent benchmarks for VLMs largely assess single- or limited-view perception, leaving untested the core cognitive ability to integrate observations across viewpoints into a coherent, world-centric (allocentric) 3D mental model. We introduce MultiView-Bench, a diagnostic benchmark expressly designed to evaluate multi-view integration for holistic 3D scene comprehension. Unlike existing datasets that focus on pixel-level mapping or camera-relative navigation, MultiView-Bench requires models to decouple object positioning from transient perspectives and ground them in a fixed global coordinate system. This capability serves as a prerequisite for VLMs before being deployed for downstream tasks such as mechanical part assembly. Our systematic evaluation of frontier VLMs reveals consistent failure modes: strong performance on 2D planar relations from a single image, but marked difficulty with 3D spatial relations and with aggregating information across views. We further identify biases in VLMs, such as struggles with unconventional axis directions and sensitivity to object colorways and texture variations. Acknowledging these limitations, we propose ViewNavigator, a multi-agent framework that actively selects informative viewpoints, perceives, and fuses multi-view evidence, improving diverse base models on MultiView-Bench even under a strict budget-matched comparison (and by 3-5x for the full agent).
### Title:
          Improved lower bounds of the time complexity of shellsort
 - **Authors:** Zhenghan Zang
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper we develop the framework of using a parametrized mapping $[\sigma(1), \sigma(2), \cdots, \sigma(n)] \mapsto \sigma(1)z + \sigma(2)z^2 + \cdots \sigma(n)z^n$ to perform runtime analysis on Shellsort. In particular, we show that the worst-case time complexity of Shellsort using Tokuda's gap sequence proposed in 1992 is at least $\Omega(N^{1.26})$ with a generalisation of this result to any strictly decreasing gap sequence where each term at most a fixed distance away from a rational geometric sequence, and we also show that strictly decreasing gap sequences giving worst-case Shellsort time complexities of $O(N \log^c N)$ must have $\Omega(\log N / \log \log N)$ terms of order $\Omega(N / (\log \log N)^c)$.
### Title:
          Adaptive Latent Trajectory Anchoring for Action Segmentation Dataset Condensation
 - **Authors:** Artheme Gauthier-Villar, Guodong Ding, Angela Yao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dataset condensation for action segmentation synthesizes compact, informative representations of long, untrimmed video datasets. The existing approach relies on Variational Autoencoders and an iterative latent optimization; it is computationally expensive and suffers from over-smoothed reconstructions and rigid temporal constraints. This paper proposes to shift the condensation paradigm from optimization-based inversion to deterministic latent mapping. By leveraging Denoising Diffusion Implicit Models, we represent action segments as continuous trajectories anchored by sparse latent points in the noise manifold. To maximize representational efficiency, we introduce an adaptive allocation mechanism that dynamically redistributes the anchoring budget based on segment-wise reconstruction difficulty. Extensive experiments demonstrate that our framework significantly outperforms state-of-the-art methods in segmentation performance across common datasets. Notably, our approach achieves performance parity with real data training while maintaining a condensation ratio of 2.4\% on Breakfast dataset.
### Title:
          Taxonomy Maintenance In The Wild Over Evolving Scholarly Data: Reliability, Efficiency, and Cost-Effectiveness
 - **Authors:** Daomin Ji, Hui Luo, Zhifeng Bao, Junhao Gan, Zi Huang
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid growth of scientific publications makes scholarly taxonomies quickly obsolete. We study taxonomy maintenance in the wild, a new problem that moves beyond static construction by continuously adapting taxonomies to evolving scholarly repositories, such as arXiv, for a given research topic. We propose GIST, a robust framework for maintaining evolving taxonomies. Unlike purely LLM-centric approaches, GIST grounds structure induction in expert-curated evidence by extracting partial hierarchies from the "Related Work" sections of papers. It integrates these partial taxonomies into a unified global taxonomy in a geometric box-embedding space, where box containment encodes the inductive bias of is-a relations. To connect semantics with geometric structure, GIST learns a bidirectional mapping between word embeddings and box embeddings. For efficient incremental updates, GIST uses novelty-aware coreset selection to update the model with representative historical signals and new evidence, avoiding costly full retraining. To handle high-velocity paper streams under user-specific token budgets, GIST further combines a hypothesized concept generator with a cost-effective evidence retrieval module. Experiments on real-world arXiv datasets show that GIST outperforms state-of-the-art baselines, improving Node F1 and Edge F1 by 11.0% and 13.1% over the strongest baseline while requiring only 9.6% of its runtime and 12.7% of its monetary cost.
### Title:
          Letter Lemmatization: One-to-one and Banded RNNs for Reversing Character-Set Simplification and Abbreviation in Medieval Text
 - **Authors:** Anguelos Nicolaou, Maria Pia Tiseo, Tamas Kovacs, Nicolas Renet, Georg Vogeler
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medieval document transcribers have very different practices; on top of that, heterogeneous digitization policies have resulted in corpora where the character-set must be viewed as fluid. In this paper we address the problem of changing between character-sets in a flexible manner. We focus on one-to-one character mappings and train characterlevel one-to-one RNNs to undo them with self-supervision; recovering half the CER even with 20 text lines. We analyse the use of these one-to-one networks for HTR post-correction and we see that they obtain significant improvements while totally ignoring ins-dels. We then use the exact same networks with character-level alignment groundtruth compiled from parallel corpora in a training and inference mode we call Banded RNNs. We use such networks to successfully expand abbreviations in medieval charter transcriptions. Finally we introduce an elaborate heuristic which takes the characters of two arbitrary character-sets and defines a metric encapsulating what we consider to be semantic similarity of characters. We call the construction of such mappings letter lemmatization and present a rich Python library that efficiently performs all presented methods.
### Title:
          Complexity of the Graph Homomorphism Problem w.r.t. Degeneracy
 - **Authors:** Grigorii Braulov, Nikolai Chukhin, Alexander S. Kulikov, Ivan Mihajlin
 - **Subjects:** Subjects:
Computational Complexity (cs.CC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The graph homomorphism problem HOM is: given an $n$-vertex source graph $G$ and an $h$-vertex target graph $H$, is there a mapping from $V(G)$ to $V(H)$ that preserves edges? A straightforward brute-force algorithm for HOM has running time $O(2^{n \log h})$ and it is known that, under ETH, there are no $2^{o(n \log h)}$ algorithms. In recent years, less restrictive graph parameters $p$ have been identified that allow one to solve HOM in time $p(H)^{O(n)}$. Examples include treewidth, maximum degree, and track number. On the other hand, it is known that the chromatic number parameter is too small: under ETH, HOM cannot be solved in time $\chi(H)^{O(n)}$. We study the complexity of HOM in terms of the degeneracy of $H$. This is perhaps the most natural unresolved graph parameter between the known algorithmic and hardness regimes: on the one hand, each of bounded treewidth, bounded maximum degree, and bounded track number implies bounded degeneracy; on the other hand, bounded degeneracy implies bounded chromatic number. Our results show that, at the same time, the influence of degeneracy of $H$ on the complexity of HOM differs significantly from that of the previously studied parameters. We show that, under ETH, there is no $2^{o(degen(H) n)}$ algorithm for any value of $degen(H)$ as a function of $n$. We also show that bounded degeneracy alone does not make target size benign: even targets with $degen(H)$ at most $2$ and quasi-polynomial size force $n^{\Omega(n)}$-scale hardness. Finally, we introduce a no-compression barrier that explains why the known fine-grained lower bounds for sparse $2$-CSP are not tight under ETH. Moreover, it shows that substantially stronger lower bounds for polynomial-target degeneracy are unlikely to follow from standard reductions from sparse $3$-SAT.
### Title:
          STEEL: Sparsity-Aware Fused Attention for Energy-Efficient Long-Sequence Inference on AMD's XDNA NPU
 - **Authors:** Victor J.B. Jung, Gagandeep Singh, Joseph Melber, Kristof Denolf, Francesco Conti, Luca Benini
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing adoption of large language model-based agents within operating system workflows has increased the importance of energy-efficient inference on laptop-class systems-on-chip (SoCs). While cloud offloading remains common, it introduces reliability and privacy concerns that are particularly problematic for agentic workloads. Recent laptop SoCs, therefore, incorporate neural processing engines (NPUs) optimized for energy efficiency; however, effectively mapping attention mechanisms onto NPUs remains challenging due to architectural diversity and explicit data-movement programming models. In this work, we present STEEL, the first open-source implementation of FlashAttention targeting XDNA-like NPUs. STEEL introduces a dataflow formulation of prefill attention, enabling efficient exploitation of spatial parallelism and on-chip memory. Furthermore, STEEL addresses the load imbalance induced by the causal mask by leveraging a sparsity-aware pipeline placement onto the NPU array, reducing synchronization overhead and improving utilization. We evaluate STEEL on the AMD Ryzen AI 9 HX 370 SoC and compare its performance against optimized CPU and GPU implementations. Experimental results show that STEEL reduces energy consumption by an average of 9.17x and 1.75x relative to CPU and GPU baselines, respectively. On XDNA 1, STEEL achieves an average 9.6x latency reduction over the prior state of the art, and delivers a 22.8x speedup on average compared to a layer-by-layer attention implementation on XDNA 2.
### Title:
          Terminal Dimension Reduction for Time Series with Applications
 - **Authors:** Alexander Munteanu, Matteo Russo, David Saulpic, Chris Schwiegelshohn
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS); Computational Geometry (cs.CG); Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Terminal embeddings have emerged as a powerful tool for dimension reduction. Given a set of points $P\subset \mathbb{R}^d$, a terminal embedding is a mapping $f:\mathbb{R}^d\rightarrow \mathbb{R}^t$ that preserves the pairwise distance between any pair of points $p\in P$ and $q\in \mathbb{R}^d$ up to small distortion under this mapping. Terminal embeddings have been particularly fruitful for constructing $k$-means and $k$-median coresets, where the objective is to find a typically weighted subset $\Omega$ of $P$ such that for any candidate solution, the cost of the clustering objective on $\Omega$ approximates the cost of the clustering objective on $P$ up to small distortion. Unfortunately, these techniques have not been extended to more complicated structures such as clustering time-series data under common straight-line interpolation between measurements. The main issue is that terminal embeddings, arguably the central technique in this line of research, cannot be linear and are thus not immediately suitable to preserve linear structures. In this work, we develop a generalization of terminal embeddings to affine line-segments that overcomes this issue. We showcase their applicability by using our lines-preserving terminal embeddings to obtain the first dimension-free coresets for clustering time-series under the Fréchet distance. The underlying dimension reduction uses Johnson-Lindenstrauss (JL) embeddings, and our experiments indicate that terminal embeddings perform similarly to JL and favorably against PCA for synthetic and real-world time-series, while only terminal embeddings extend pairwise distance preservation to the full ambient space.
### Title:
          FreyaTTS Technical Report
 - **Authors:** Ahmet Erdem Pamuk, Ömer Yentür, Ahmet Tunga Bayrak, Yavuz Alp Sencer Öztürk, Mustafa Yavuz
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Freya-TTS, a compact, tokenizer-free, Turkish-first text-to-speech model designed for highly reliable and efficient conversational synthesis. Freya-TTS is a 183.2M-parameter non-autoregressive conditional flow-matching Diffusion Transformer (DiT) that operates in the frozen continuous latent space of AudioVAE2 (16 kHz encode, 48 kHz decode), allowing the model to focus its capacity on text-to-latent mapping while inheriting high-quality 48 kHz reconstruction. We advance the framework along three key dimensions: (1) rule-free end-to-end modeling from a 92-symbol Turkish character vocabulary without a phonemizer, grapheme-to-phoneme frontend, or discrete speech tokenizer; (2) non-autoregressive parallel denoising, which predicts the entire latent sequence simultaneously over a predicted duration; and (3) a production-oriented two-stage post-training recipe consisting of single-speaker voice locking and short-utterance coverage, improving speaker consistency and robustness on short inputs. On the Freya-TR-Eval benchmark, Freya-TTS achieves a band-matched word error rate (WER) of 8.0% and character error rate (CER) of 3.0%, outperforming substantially larger open-source systems while using a fraction of their parameters. The model achieves a real-time factor of 0.11 on consumer GPUs and runs faster than real time on a laptop CPU, making it well suited for resource-constrained edge deployment. We release the model weights, training and inference code, and evaluation benchmark under the Apache-2.0 license.
### Title:
          Statistically Undetectable Backdoors in Deep Neural Networks
 - **Authors:** Andrej Bogdanov, Alon Rosen, Neekon Vafa
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show how an adversarial model trainer can plant backdoors in a large class of deep, feedforward neural networks. These backdoors are statistically undetectable in the white-box setting, meaning that the backdoored and honestly trained models are close in total variation distance, even given the full descriptions of the models (e.g., all of the weights). The backdoor provides access to invariance-based adversarial examples for every input, mapping distant inputs to unusually close outputs. However, without the backdoor, it is provably impossible (under standard cryptographic assumptions) to generate any such adversarial examples in polynomial time. Our theoretical and preliminary empirical findings demonstrate a fundamental power asymmetry between model trainers and model users.
### Title:
          Semantic Pareto-DQN: A Multi-Objective Reinforcement Learning Framework for Financial Anomaly Detection
 - **Authors:** Cláudio Lúcio do Val Lopes, Lucca Machado da Silva
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial anomaly detection suffers from extreme class imbalance, causing traditional single-objective algorithms to exhibit ``fraud collapse'', defaulting to the majority class and failing to balance anomaly interdiction with customer friction. To overcome this without distortive data resampling, we propose the Semantic Pareto-DQN, a multi-objective reinforcement learning framework. Our approach synthesizes heterogeneous transaction features into cohesive natural-language narratives, encoded by large language models, thereby producing a robust, scale-invariant state representation. The agent optimizes a vectorial reward that explicitly decouples financial efficacy, operational friction, and semantic discovery. By mapping the continuous Pareto frontier, the system dynamically navigates the asymmetric costs of missed anomalies versus false positives. Empirical evaluations across E-Commerce fraud and UCI Credit datasets show that semantic Pareto-DQN successfully shatters the zero-recall trap. It achieves superior minority-class recall compared to scalarized baselines, providing an alternative to trade bounded operational friction for financial anomaly discovery.
## Keyword: localization
### Title:
          Dual-BEATs: Unlocking Zero-Shot Stereo Audio Perception in Audio Large Language Models via Dithering
 - **Authors:** Shuo-Chun Lin, Hen-Hsen Huang
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (LLMs) have remarkable semantic audio understanding, yet they remain "spatially agnostic" due to their reliance on mono-channel audio representations. Currently, spatial audio perception methods mainly focus on complex room simulations and custom-trained, geometry-aware stereo encoders, which limits their accessibility and generalizability. In this paper, we introduce the Dual-BEATs architecture, in which the left and right audio channels are routed independently through two identical semantic encoders as an alternative to specialized spatial modules. To circumvent the architectural bottleneck where internal normalization otherwise erases the inter-channel variance of stereo audio, we inject a static, uncorrelated dithering noise floor prior to encoding. This dithering intervention establishes a macro-variance floor that "smuggles" spatial geometry across the normalization layers. Evaluated on a ternary directional classification task (Left, Center, Right), we demonstrate that dithered models achieve exceptional spatial resolution--reaching up to 97.2% localization accuracy even on subtle 0.5 panning amplitudes--and demonstrates robust, zero-shot generalization to entirely unseen spatial configurations. Our results suggest that with the appropriate acoustic regularization, standard multimodal models are natively capable of generalized stereo audio understanding.
### Title:
          Loop-Based Slicing and Input-Driven Concretization: An Empirical Study of Termination and Non-Termination Analysis
 - **Authors:** Negar Fathi, Rahul Purandare, Tachio Terauchi, Hiroshi Unno
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Termination and non-termination are fundamental correctness properties, but verifying them in real-world C programs remains difficult because loop interactions and nondeterministic inputs challenge existing analyzers. This paper presents an empirical study of lightweight, tool-independent source-level preprocessing for (non-)termination analysis. We implement FocusTNT, a C front end that applies loop-based slicing to isolate loop-level obligations and input-driven concretization to specialize nondeterministic inputs into selected input-scenario variants. We evaluate slicing, concretization, and their combination across six analyzers on 117 C/C++ programs derived from real-world non-termination bugs and their fixes. The study examines effects on analyzer correctness, complementarity with original-program analysis, loop-level diagnostics, feature sensitivity, runtime behavior, semantic scope, and integration potential. Results show that preprocessing is not uniformly beneficial: its impact depends on the analyzer, task, and program features. Slicing provides conservative structural isolation and localization, whereas concretization can improve detectability for selected scenarios but narrows semantic scope and may increase analysis effort. Their combination is not consistently additive. Overall, the results support adaptive use of preprocessing as a complement to original-program analysis and provide practical guidance to application developers interpreting verification outcomes and tool developers improving analyzer robustness.
### Title:
          STEAM: Stable Self-Training with Elastic Matching and Adaptive Purification
 - **Authors:** Shaoxiang Wang, Kejia Zhang, Haiwei Pan, Lan Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization (CVGL) aims to achieve GPS-free localization by matching drone-view images with corresponding satellite-view images. Existing supervised methods rely on large-scale manually annotated cross-view image pairs, making them costly and difficult to scale. In contrast, existing unsupervised approaches typically depend on generative models or clustering-based stage-wise optimization, which are prone to distribution bias and the accumulation of noisy pseudo-labels. To address these limitations, we propose STEAM (Stable Self-Training with Elastic Matching and Adaptive Purification), an end-to-end unsupervised cross-view geo-localization framework that performs self-training directly on real drone and satellite images. Specifically, the proposed Stable Spatial-Aware Module enhances the stability of feature representations, Elastic Matching discovers high-quality cross-view pseudo-labels, and Adaptive Purification dynamically maintains a reliable pseudo-label repository throughout the self-training process. Extensive experiments on the University-1652 and SUES-200 benchmarks demonstrate that STEAM achieves state-of-the-art performance among all existing unsupervised methods and delivers performance comparable to supervised approaches, validating the effectiveness and superiority of the proposed framework. The source code is available at this https URL.
### Title:
          REBASE: Reference-Background Subspace Elimination for Training-Free In-Context Segmentation
 - **Authors:** Mantha Sai Gopal, Jaison Saji Chacko, Harsh Nandwana, Sandesh Hegde, Debarshi Banerjee, Uma Mahesh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training-free in-context segmentation enables new object categories to be introduced at inference time from a single annotated reference image, eliminating the retraining and memory overhead of class-incremental learning. Recent approaches achieve this by combining vision foundation models for semantic correspondence with promptable segmentation networks like SAM. However, their performance is fundamentally limited by the quality of the cross-image similarity map; shared contextual backgrounds between the reference and query systematically elevate similarity in non-target regions, degrading prompt localization. We present REBASE, a training-free framework that explicitly suppresses these spurious contextual correspondences. Our method identifies the low-rank background feature subspace from the reference image and project the reference and query features onto its orthogonal complement in closed form, yielding cleaner semantic matching. We then generate positive point prompts using similarity-weighted farthest-point sampling, paired with a refined dense similarity prior. Without any training or parameter updates, our approach establishes a new state of the art among training-free methods on PACO-Part, FSS-1000, and cross-domain datasets such as ISIC2018, demonstrating that explicit background subspace removal is a highly effective principle for one-shot localization.
### Title:
          ReProAgent: Tool-Augmented Multi-Stage Agentic Generation of Bug Reproduction Tests from Issue Reports
 - **Authors:** Quanjun Zhang, Yi Zheng, Ye Shang, Weifeng Sun, Haichuan Hu, Chunrong Fang, Zhenyu Chen, Liang Xiao
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reproduction tests help developers confirm reported issues and provide executable feedback for issue resolution, yet issue reports in open-source projects rarely include such tests. Recent studies have explored generating issue reproduction tests from issue reports with large language models, but existing approaches largely rely on prompt-based pipelines that retrieve textual context and generate tests. This limits their ability to understand how reported issues behave in repository-scale codebases and to flexibly organize the construction of reproduction tests. In this paper, we propose ReProAgent, a multi-stage agent framework for reproduction test generation from issue reports. ReProAgent decomposes the task into four agent stages: bug localization, root cause analysis, test planning, and test generation. To support these stages, ReProAgent integrates task-specific tools for task decomposition and reflection, context retrieval from both textual sources and repository graphs, and runtime interaction with the execution environment. Experiments on SWT-bench-lite and SWT-bench-verified show that ReProAgent successfully reproduces 58.43% and 70.30% of issues, outperforming all baselines, with an average cost of $0.14 per instance. For example, when equipped with GPT-5-mini, ReProAgent exceeds OpenHands with the same backbone by 20.43 and 7.90 percentage points, respectively. ReProAgent also generalizes across multiple backbone LLMs and improves downstream issue resolution performance when integrated with existing repair approaches.
### Title:
          Malaika: Understanding Malware through Tri-Grounded Agentic Reasoning
 - **Authors:** Xingzhi Qian, Xinran Zheng, Yiling He, Lorenzo Cavallaro
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent LLM-based systems have shown promising capabilities for security-focused code analysis. Malware understanding, however, poses a distinct challenge: analysts must reconstruct high-level malicious behaviors under partial observability from sparse, dispersed evidence intertwined with benign functionality. While static analysis can expose security-relevant signals, the central challenge is not merely identifying suspicious code, but determining whether the evidence sufficiently supports an auditable behavior-level conclusion. We formulate malware understanding as a grounded reasoning problem and argue that reliable behavior reconstruction requires three complementary forms of grounding. Domain grounding constrains how behavior hypotheses are generated and evaluated, semantics grounding localizes and connects supporting program evidence, and knowledge grounding supports behavioral attribution through externally verifiable threat knowledge. To study this hypothesis, we present Malaika, a multi-agent framework that operationalizes the three grounding mechanisms through analyst-inspired reasoning, tool-mediated evidence localization, and retrieval-based behavioral attribution. We instantiate Malaika for Android malware analysis and evaluate it on malware-understanding tasks. Results show that Malaika improves analysis quality over prior LLM-based malware-analysis frameworks and demonstrate that reliability depends not only on model capability but also on the reasoning process. In particular, comparisons against malware-analysis systems and frontier agentic frameworks show that grounding-aware reasoning produces more precise and auditable conclusions. Ablation studies further support the grounding hypothesis. These findings suggest that grounding-aware reasoning provides a principled foundation for reliable malware understanding and, more broadly, for evidence-grounded software analysis.
### Title:
          REMIND: RE-Identification with Memory for INDoor Navigation
 - **Authors:** Pablo Diaz-Pereda, Alejandro Rodriguez-Ramos, David Perez-Saura, Pascual Campoy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mobile robots operating indoors must re-identify previously observed objects after long temporal gaps, significant viewpoint changes, and severe illumination variations. This remains a challenging problem: multi-object tracking methods are optimized for short-term association of pedestrians and vehicles at video rates, person and vehicle re-identification approaches lack persistent memory mechanisms, and state-of-the-art video object segmentation techniques rely on reactive distractor filtering rather than enforcing global identity consistency. To address these limitations, we present REMIND, an online tracker designed for long-term multi-object re-identification of generic indoor objects from monocular RGB imagery, requiring neither camera pose nor depth. Motivated by evidence from visual cognition that humans rely on accumulated appearance familiarity and spatial context rather than explicit self-localization, REMIND combines frozen DINOv3 features with a dual-bank multi-prototype appearance memory, part- and background-level descriptors, a neighbour-context reasoning module exploiting spatial co-occurrence, and joint Hungarian assignment with ambiguity-aware safeguards. On a purpose-built indoor dataset featuring controlled revisits and dense same-class clutter, REMIND reaches 90.35% IDF1, nearly 20 points above a state-of-the-art video object segmentation baseline and more than 36 above a strong tracking-by-detection baseline. On ScanNet++, it attains the highest IDF1 in every setting but one, end-to-end detection over all scenes, where the tracking-by-detection baseline is marginally ahead while REMIND still associates and recovers identities more accurately; it also completes every scene, whereas the video object segmentation baseline exhausts GPU memory on 66.9% under YOLO detections. The complete system, evaluation framework, and dataset are publicly released.
### Title:
          From Classification to Localization and Clinical Validation: Large-Scale Development of a Deep Learning System for Thoracic Disease Detection on Chest Radiographs in Thailand
 - **Authors:** Isarun Chamveha, Tretap Promwiset, Napat Wanchaitanawong, Trongtum Tongdee, Pairash Saiviroonporn, Warasinee Chaisangmongkon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chest radiography (CXR) remains the most widely used thoracic imaging modality, yet expert interpretation is constrained by a severe shortage of radiologists in Thailand and across Southeast Asia. Local adaptation of deep learning models to Thai data has been shown to substantially improve accuracy on Thai populations. Here we present the development and comprehensive validation of the chest radiograph analysis model in Inspectra CXR version 5, a deep learning system that performs multi-label thoracic disease classification and weakly supervised lesion localization within a single model. The architecture couples a DenseNet-121 backbone with Attend-and-Compare Modules (ACM) and a Probabilistic Class Activation Map (PCAM) aggregation layer, producing a per-condition classification score and heatmap simultaneously. The model was developed on 874,858 frontal chest radiographs with paired radiologist reports from Siriraj Hospital, Bangkok. On a held-out, radiologist-verified in-domain test set of 19,871 cases, it achieved a mean AUROC of 0.994 (mean sensitivity 92.4%, specificity 98.6%) across nine clinically important conditions. On an independent generalization set of 5,992 cases from 13 hospitals across Thailand, the mean AUROC was 0.970, indicating robust transfer across sites. For localization, evaluated on 4,549 radiologist-annotated cases, the model attained a mean lesion-localization fraction (LLF) of 77.9% at 0.59 non-lesion localizations per image. In a usability evaluation with five thoracic radiologists, the system reached a classification concordance of 93.6%, a localization concordance of 94.7%, and a mean System Usability Scale (SUS) score of 89. These results indicate that a locally developed, localization-capable CXR system can deliver high accuracy, generalize across heterogeneous Thai hospitals, and earn the trust of practicing radiologists.
### Title:
          Decoupling Language Guidance from Backbones for Text-Guided Medical Segmentation
 - **Authors:** Yungeng Liu, Xuanzi Fang, Haijin Zeng, Qi Dai, Yongyong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided medical image segmentation leverages clinical semantics to improve lesion delineation, yet many existing models bind cross-modal fusion, supervision, and decoder design into a task-specific architecture. Such tight coupling makes it difficult to reuse language guidance modules across heterogeneous vision and text backbones, and often requires redesigning the network when the encoder pair changes. This paper presents BTHA, a backbone-transferable hierarchical adapter framework for text-guided medical image segmentation. BTHA is built around a stable feature-level interface: given multi-scale visual features and a text representation, it injects semantic guidance through shape-preserving adapters while maintaining the decoder-side tensor contract. To make this interface effective, we introduce a Hierarchical Coarse-to-Fine Supervision Strategy that decomposes learning into global image-text alignment, multi-scale auxiliary localization, and boundary-aware final mask refinement. We further design a Scale-Adaptive Gated Semantic Guidance (SAGSG) adapter, where resolution-specific gates adaptively control textual injection and channel recalibration suppresses redundant cross-modal responses. Evaluations across diverse vision and text backbones show that the same adapter and supervision design remains effective across convolutional and transformer-based visual encoders as well as different language encoders. Experiments on four public datasets further demonstrate that BTHA improves strong text-guided baselines with modest computational overhead.
### Title:
          What VGGT Knows About Overlap: Probing Geometric Foundation Models for Co-Visibility
 - **Authors:** Filippo Ziliotto, Luciano Serafini, Lamberto Ballan, Tommaso Campari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A fundamental challenge in 3D reconstruction and robotic localization is co-visibility: determining which image pairs share overlapping visible surfaces, particularly in scenarios with minimal overlap. We demonstrate that VGGT implicitly encodes co-visibility as an emergent behavior: without any supervision for this task, its internal representations exhibit a clear hierarchical structure mirroring that of large language models, i.e. early layers build a 3D-aware scene representation, while late layers act as dedicated co-visibility reasoners. In particular, we identify layer L17 as a negative anchor that consistently routes non-co-visible pairs for this backbone, regardless of the evaluation setting, providing task-grounded evidence of layer specialization in a geometry-grounded foundation model. Building on this, we introduce Co-VGGT, which freezes VGGT and trains only a lightweight layer-wise mixture-of-experts head (less than 7.5M parameters) to classify co-visibility from RGB alone, treating each layer as a specialized expert whose geometric abstraction is adaptively weighted per input pair. On the Co-VisiON benchmark, Co-VGGT surpasses the human annotation baseline and improves over prior work by more than 25% pairwise and 10% multiview. Pairwise predictions are well-calibrated (ECE=0.030), enabling direct use as edge weights in visibility graphs for downstream SfM and SLAM pipelines without post-hoc correction. Code and data are available.
### Title:
          Writing Bug Reports for Software Repair Agents: What Information Matters Most?
 - **Authors:** Vincenzo Luigi Bruno, Alessandro Giagnorio, Daniele Bifolco, Leon Wienges, Massimiliano Di Penta, Gabriele Bavota
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software development is increasingly moving toward agentic-first workflows. This includes AI agents responsible for generating initial fixes for submitted issue reports. In this setting, issue reports are no longer merely documentation for human maintainers; they become the primary task specification for the agent. However, little is known about how such reports should be written to maximize the agent's chances of producing a correct fix. We study what makes a bug report agent-ready. Starting from the SWE-bench Verified benchmark (i.e., a collection of 500 real repository issues with human-written gold patches and test suites for evaluating generated fixes) we manually classify each issue by change type (e.g., bug fix vs refactoring) and annotate each sentence with its information type, such as observed behavior, expected behavior, reproduction steps, localization cues, and suggested fixes. We focus on the 441 issues representing bug reports, and we run on them mini-swe-agent using three LLM backbones (i.e., GPT-5-mini, MiniMax M2.5, and Gemini 3 Flash). We then fit a binomial regression model to estimate the incremental association between each information type and agent success, controlling for confounding factors. Our results suggest that agentic-first reports benefit most from information that narrows the agent's search and repair space. Localization cues, such as references to affected code areas, are positively associated with successful repairs, while suggested fixes, expressed either in code or natural language, show some of the strongest positive associations with pass probability. An ablation study removing selected information types confirms that agents benefit less from information traditionally useful to humans, such as reproduction steps, and more from sentences that expose a repair direction, either through bug localization or a suggested fix.
### Title:
          KnitID: Machine-Knitted RFID Antennas for Battery-Free Authentication, Localization and Interaction
 - **Authors:** Weiye Xu, Yue Xu, Devin Murphy, Sen Zhang, Te-yen Wu, Yiyue Luo
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Battery-free RFID systems offer a scalable and maintenance-free approach to interaction. We present KnitID, a machine-knitted textile RFID antenna design that enables on-body authentication, localization, and interaction. Unlike prior antenna designs, KnitID achieves a compact antenna form factor (60mm by 8mm) by integrating magnet wire into the unique loop-over-loop structure of machine knitting. This structure reduces the size of conventional loop antennas by around 90\%, while also providing 30\% longer sensing ranges than standard dipole designs with similar size on the human body. The compact form factor creates new opportunities to embed multiple RFID tags across the human body, enriching backscatter signals and supporting a broader range of battery-free on-body interactions. To demonstrate this capability, we build an interactive sleeve to support wearer authentication, spatial localization, and interaction detection. Through technical evaluations, we show the feasibility of KnitID to provide diverse and battery-free interactions on knitted user interfaces.
## Keyword: transformer
### Title:
          HAT Super-Resolution and a PARSeq+CLIP4STR Voting Ensemble for Extreme In-the-Wild License Plate Recognition
 - **Authors:** Karthik Sivarama Krishnan, Koushik Sivarama Krishnan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We describe our entry to the ICIP 2026 Grand Challenge on Extreme In-the-Wild License Plate Super-Resolution (XLPSR), which scored 9.73 wECR on the public validation leaderboard. The system pairs a Hybrid Attention Transformer super-resolution (HAT) front-end with an ensemble of two scene-text recognisers (PARSeq-S and CLIP4STR-B) and a confidence-weighted character-voting scheme that abstains on uncertain positions. We treat XLPSR as a recognition task gated by image legibility: the SR step exists to lift characters out of sub-pixel territory, and the asymmetric scoring rule (+2 / -1 / 0) is exploited explicitly through abstention. Our pipeline runs in 1.7 s per sequence on RTX 3090 (max 2.7 s, p99 2.4 s), well under the 60 s/sequence Docker budget.
### Title:
          Vision Transformers Learn Gestalt-Like Figure-Ground Cues from Natural Images
 - **Authors:** Matthias Tangemann, Benjamin Lo, Zygmunt Pizlo, Kaleem Siddiqi, Dirk B. Walther, Sven Dickinson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Figure-ground organization in the human visual system relies on several shape-based cues, including surroundedness, convexity, and symmetry. While these cues have been extensively studied using abstract stimuli, little is known about how they operate under natural conditions or how they arise from the statistics of natural scenes. Deep neural networks offer a promising path forward: a model that relies on the same figure-ground cues as humans would provide tractable experimental access to the underlying mechanisms. In this study, we evaluate shape-based figure-ground organization in Vision Transformers (ViTs), for which prior work has demonstrated the emergence of object-based grouping. We test 25 ViTs spanning supervised and self-supervised training objectives, by fitting linear probes to predict figure-ground assignment from intermediate patch representations using both natural images and controlled artificial stimuli that isolate individual cues. Our results show that ViTs robustly encode surroundedness and convexity, and that probes trained on natural images generalize zero-shot to artificial stimuli across several models. For symmetry we observe mixed results: the cue is encoded for uniformly colored but not for textured regions. Taken together, our findings demonstrate that Gestalt-like figure-ground cues can be learned from natural scene statistics and position ViTs as a compelling model system for studying the computational mechanisms of perceptual organization. Code and data is available at this https URL
### Title:
          Training, Reading, and Editing Legible Transformers
 - **Authors:** Mark Oskin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A transformer can be built from operators that are legible by construction -- bounded, named units that read as fuzzy set operations rather than dense activations -- but legibility must be pressed for during training, and the pressure has a failure mode. A crispness penalty meant to sharpen a bounded operator into a decisive detector instead collapses it into a dead constant. An identity, E[v(1-v)] = mu(1-mu) - var, shows why -- the penalty is a variance-minimizer blind to the difference between a live detector and a constant -- and names the fix: a per-channel variance floor, the target legibility metric written as a loss, which recovers both legibility and quality. A learned per-unit fraction then retires the hand-set reserved-GELU partition of prior work: given the choice the model keeps no unit as pure GELU and routes 87% of its load-bearing computation through crisp operators. The result is the most legible transformer we have built -- 78% of its feed-forward operands and 50% of its attention value channels are crisp-and-contextual detectors, and per-head legibility rises from 18% in shallow layers to 78% in deep ones. Read in the correct rotated per-layer frame, these units separate a clean detection (what a unit responds to) from a harder naming (what its output decodes to); and because the objective makes each unit crisp and sparse, edits to them are far more local -- 50-184x in the deep layers where the edit sites concentrate -- and can target explicit conjunctions a single neuron cannot express. Finally, a between-unit decorrelation pressure exposes a legibility dial: it trades a circuit's reuse for independence at no quality cost, turning concepts into single, surgically editable units and a prediction into a short explanation read off a handful of named operations. Quality holds at parity with a conventional baseline throughout.
### Title:
          MOSAIC: Adaptive Inter-layer Composition for Efficient Heterogeneous Vision-Language Models
 - **Authors:** Yuncheng Yang, Feiyang Ye, Shixian Luo, Yinna Zhu, Lianlei Shan, Wangcai Zhao, Kuo Zhang, Yan Chen, Yong Wu, Yan Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) have achieved success using homogeneous Transformers to process multimedia data. Recent studies show that heterogeneous structures interleaving efficient mechanisms, like linear attention, improve both performance and inference latency over homogeneous designs. However, these efforts rely on handcrafted static mixing patterns, which are sub-optimal and difficult to adapt to specific hardware. To bridge this gap, we propose Multi-Objective Search for Adaptive Inter-layer Composition (MOSAIC), a hardware-aware search method that automatically transforms homogeneous models into optimized heterogeneous architectures. MOSAIC integrates diverse efficiency mechanisms--including linear, sparse, and low-rank operators--into a unified search space. By formulating the selection as a multi-objective Mixed Integer Programming (MIP) problem, our method identifies optimal configurations that maximize downstream performance under strict hardware latency constraints. To mitigate performance degradation from structural transitions, we introduce a two-stage parameter recovery process: global off-policy distillation to stabilize internal representations, followed by a dual-teacher on-policy distillation leveraging a 235B oracle for knowledge expansion and the original 4B teacher for distributional stability. We validate MOSAIC through MOSAIC-4B, derived from Qwen3-VL-4B-Instruct. Results demonstrate that MOSAIC-4B matches the baseline's performance across multiple benchmarks while requiring less than 2% of the original training cost. Furthermore, it substantially improves inference efficiency, achieving 1.76x prefilling and 2.54x decoding speedups.
### Title:
          Subtoken Vision Transformer for Fine-grained Recognition
 - **Authors:** Jie Zhu, Ivy Zhang, Minchul Kim, Xiaoming Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Subtoken Vision Transformer (SubViT), a selective image tokenization method for fine-grained visual recognition. Standard Vision Transformers compress each fixed-size patch into a single token, although fine-grained distinctions often depend on localized variations within only a few patches. SubViT addresses this mismatch by representing discriminative patches with multiple subtokens while retaining the original token sequence for global context, thereby allocating additional capacity where it is most needed. Since attention heads encode complementary semantics and extracting attention maps at inference requires an extra backbone forward, we adopt a two-stage training strategy. Stage 1 fine-tunes the ViT using subdivision regions sampled from random attention heads, exposing the model to diverse subdivision patterns. Stage 2 identifies informative attention maps through feature-degradation distances and distills them into a lightweight single-map router, which directly predicts deterministic token-importance scores without a separate attention forward. We evaluate SubViT on Generalized Category Discovery (GCD), a challenging task requiring both fine-grained discrimination and generalization to unlabeled novel categories. Across CUB, FGVC-Aircraft, and Stanford Cars, SubViT improves the average novel-category accuracy of DINOv2 from $81.3\%$ to $84.7\%$, with only $0.50$ ms additional latency and $3.4\%$ more FLOPs, while reducing latency by $73.8\%$ relative to Retina Patch. Results on CIFAR-10 and ImageNet-100 demonstrate its broader applicability.
### Title:
          DETRAM: End-to-end DEtection, Tracking and Recovery of HumAn Meshes
 - **Authors:** Chunggi Lee, Seonwook Park, Wanhua Li, Umar Iqbal, Hanspeter Pfister
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the task of human mesh recovery (HMR), multi-person scenes are particularly difficult to handle due to the many entities that appear and occlusions between them over time. In particular for video inputs, there is a need to track each entity reliably and consistently. Existing methods rely on pretrained human detection modules, increasing their runtime and limiting the number of tracked entities. We present DETRAM, a unified framework for multi-person HMR and tracking that simultaneously detects, reconstructs, and tracks humans across time, both automatically and via user prompts. DETRAM uses a single transformer decoder with an identity-consistent set of learnable query embeddings that persist across frames: detection queries discover new people, tracking queries maintain pose and shape for existing individuals, and prompt queries follow user-specified identities. Our approach achieves state-of-the-art tracking results on PoseTrack21, 3DPW, BEDLAM, and MuPoTS-3D, and competitive reconstruction accuracy on BEDLAM and 3DPW, while uniquely supporting prompt-based tracking of individuals in multi-person scenes. To our knowledge, this is the first method to unify promptability and multi-person HMR with tracking in an end-to-end trainable framework, enabling user-directed human analysis in videos.
### Title:
          Event-Based Token Sequences for Audio-Conditioned Music-Game Level Modeling
 - **Authors:** Ke Zhang, Chu-Hsuan Hsueh, Kokolo Ikeda
 - **Subjects:** Subjects:
Sound (cs.SD); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Procedural generation of music game levels is an exciting yet challenging problem, as levels must translate musical structure into interactive sequences of timed gameplay events. Most existing approaches formulate this task by frame-based representations, dividing audio into uniform time grids and predicting events at each frame. This makes gameplay events implicit across many frames. As a result, it is hard to describe event-level timing relations and longer-range structure found in human-authored levels. We use procedural generation as a practical setting to study how musical cues map to interactive event sequences. Inspired by event-based symbolic music modeling, we propose a token-level sequence formulation that casts level generation as a multimodal sequence-to-sequence problem. Conditioned on an audio excerpt and level metadata, the model generates a token sequence alternating gameplay-event and beat-shift tokens. This explicitly represents actions and their relative timing in beat space. Based on this formulation, we build a Transformer model. It outperforms representative frame-level baselines under event-level evaluation. It also enables systematic analysis of how audio supports rhythm-aligned event prediction beyond metadata conditioning.
### Title:
          Elusive but Coverable: The Recursion-Theoretic Structure of Complete Abstract Interpretations
 - **Authors:** Nicklas Carpenter, Roberto Giacobazzi
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study local completeness and incompleteness of abstract interpretations from a recursion-theoretic perspective. Local completeness weakens global completeness and captures the absence of precision loss for a specific precondition: abstract computation yields exactly what is obtained by abstracting the corresponding concrete computation. This enables compositional reasoning and rules out false positives in verification. We characterize the distinction between static and dynamic program analysis in terms of uniformly decidable operations and observe that the latter is uniformly decidable only for trivial abstractions. We then prove that the class of programs inducing a predicate transformer that is locally complete for a given non-trivial abstract domain is elusive in a precise recursion-theoretic sense: it is a productive set, hence not computably enumerable, and, under mild hypotheses, the same holds for its complement. In particular, the first class lies in $\Pi^0_2$ and the second in $\Sigma^0_2$. Unlike the usual examples of $\Pi^0_2$ properties, we show that the classes of locally complete programs admit decidable coverings. This makes it possible to construct, via program transformation, an effective enumeration of a representative subset of programs that entirely covers this class -- capturing from the outside a class that eludes enumeration from within.
### Title:
          ReGen: Hierarchical Multi-Prompt Representation Generation for Efficient Waveform Diffusion Models
 - **Authors:** Sang-Hoon Lee, Ha-Yeong Choi
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation alignment (REPA) has been investigated to accelerate diffusion training, but we observe that regularizing intermediate representations in diffusion Transformers (DiT) may implicitly entangle latents and limit generative capacity. To address this issue, we propose ReGen, a hierarchical multi-prompt representation generation framework that jointly estimates multiple vector fields for both representations and data within a single diffusion model. We further introduce generalized flow matching (GFM) to improve the generalization of conditional flow matching (CFM). We validate ReGen on single-stage waveform diffusion models including neural audio codec and Wave-VAE. ReGen significantly improves waveform generation quality from highly compressed latent representations at 12.5 Hz. We also present ReGenVoice, a latent diffusion model (LDM)-based text-to-speech model that achieves strong speech intelligibility (WER) and speaker similarity (SIM) with a small dataset. Moreover, operating the LDM at 6.25 Hz with rich semantic and acoustic latent representation enables efficient training and sampling, requiring only 1 day of training on 4 GPUs and fast inference with an RTF of 0.08. Audio samples are available at this https URL.
### Title:
          COAST: Context-Aware Differential Learning for Gene Expression Prediction in Spatial Transcriptomics
 - **Authors:** Keunho Byeon, Sunhong Park, Jeewoo Lim, Jin Tae Kwak
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial transcriptomics enables profiling of spatial gene expression but is limited by high cost and low throughput, motivating prediction from H&E histopathology images. Existing context-aware methods mainly supervise absolute expression, while relative expression relationships between spots are rarely used explicitly. We propose COAST, a context-aware differential learning framework for spatial gene expression prediction. COAST conditions the local and global context features with type-specific modulation and aggregates the target and context spot tokens using a Transformer encoder to capture both fine-grained local patterns and slide-level structure. It is trained with a joint objective that combines absolute expression regression with signed differential regression between the target and context spots. Experiments on multiple spatial transcriptomics datasets show consistent improvements in correlation- and distribution-based metrics, demonstrating the effectiveness of context-aware differential learning for histology-based spatial gene expression prediction.
### Title:
          TSR-Ego: Temporally Guided Stereo Refinement Framework for Egocentric 3D Human Pose Estimation
 - **Authors:** Md Mushfiqur Azam, John Quarles, Kevin Desai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Egocentric 3D human pose estimation from head-mounted stereo cameras is challenging due to fisheye distortion, severe self-occlusion, and frequent truncation of body joints outside the camera field of view. Recent stereo egocentric methods have improved performance through heatmap lifting, stereo correspondence, and transformer-based refinement, but they often rely heavily on frame-local evidence or use temporal information only as auxiliary pose-level context. This limits robustness when current-frame stereo cues are weak, occluded, or ambiguous. We propose TSR-Ego, a temporally guided stereo framework that couples short-term motion evidence with projection-guided feature sampling. The model first enriches dense stereo feature maps using a causal depthwise-separable temporal convolution, allowing past visual evidence to influence the feature space before deformable cross-attention. A single-stage causal stereo decoder then refines learned 3D joint queries through temporal self-attention, joint self-attention, and fisheye deformable stereo cross-attention, using the evolving pose estimate to generate 2D sampling references. Unlike methods that apply temporal reasoning mainly after pose prediction, TSR-Ego uses motion context to shape both the sampled stereo features and the joint representations while preserving online inference without future frames. Experiments on UnrealEgo2 and UnrealEgo-RW show state-of-the-art performance, with especially strong gains on real-world sequences.
### Title:
          YeTI: You Only Need Two Noisy Images for Real-World sRGB Noise Generation
 - **Authors:** Jaekyun Ko, Byung Wan Lim, Soomin Lee, Dongjin Kim, Tae Hyun Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world sRGB image denoising remains challenging due to the nonlinear characteristics of sensor noise and the difficulty of acquiring aligned clean-noisy image pairs. Supervised denoisers often overfit to limited paired datasets, while self-supervised methods still depend on sufficiently diverse noisy observations. These limitations motivate scalable noise synthesis methods that can model real-world noise without clean ground truth or camera metadata. We propose YeTI, a real-world sRGB noise generation framework that learns from only two noisy observations of the same scene. YeTI uses a Reconstruction Autoencoder to disentangle scene structure and noise characteristics, and models the latent noise distribution with a one-step Conditional Diffusion Transformer trained using consistency objectives. Given a single noisy input at inference time, YeTI generates realistic, signal-dependent noise while preserving the underlying scene content. Extensive experiments demonstrate the effectiveness of YeTI across real-world benchmarks. We evaluate noise generation on SIDD and further assess generalization on SIDD+, MAI2021, and SID, covering smartphone and diverse consumer-camera sensors. Downstream denoising results on DND further show that denoisers trained with YeTI-synthesized images achieve strong real-world performance, highlighting the practical value of clean-image-free and metadata-free noise generation.
### Title:
          Complexity-Guided Component-wise Initialization for Language Model Pretraining
 - **Authors:** Konstantin Garbers, Nicholas Oh
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained language models often exhibit structured weight spectra, suggesting that training may repeatedly produce similar layerwise and component-wise organization. We ask whether these recurring spectral patterns can be reused as an initialization signal for GPT-2-style language-model pretraining. First, we analyze eleven pretrained GPT-2-style checkpoints that vary in size, language, tokenizer, and training corpus, measuring Frobenius norm and effective-rank entropy across layers and Transformer subcomponents. The checkpoints show shared depth trends, especially increasing scale and stronger spectral concentration in residual-writing matrices. We then construct initialization schemes that imitate the component-wise magnitudes and spectral profiles of pretrained models, and compare them with several weight initialization methods. These initializers visibly change the model's structural spectral patterns, but the evaluation results do not show a corresponding performance advantage. Pretrained-weight reuse remains competitive, while coarse spectral matching alone is not a reliable optimization strategy. Our results suggest that pretrained spectra are useful diagnostics of trained model structure, but that effective reuse likely requires preserving richer information than component-wise scale and singular-value shape.
### Title:
          Dissipativity-Based Multiport Stability Root-Cause Identification and Mitigation for Solid-State Transformers
 - **Authors:** Xiangyu Meng, Dong Xie, Hongjian Lin, Chunxu Lin, Xinglai Ge, Zhigang Liu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For solid-state transformers (SSTs) in high-power grid-connected applications, improperly designed control loops can excite strong inherent AC-DC port coupling, leading to low-frequency oscillation issues, especially under weak grid conditions. To address this problem, this article establishes a multiport admittance matrix for the SST, encompassing its AC dq axes and primary DC port, to characterize its inherent dynamics. Subsequently, a multiport dissipativity analysis is conducted to evaluate the robust stability of the SST. By leveraging the decomposition of passivity conditions into distinct self- and coupling-dissipativity indices, the specific root causes of instability are diagnosed. This framework reveals that a severe coupling-dissipativity failure, induced by the internal dynamics of the synchronization loop, is the dominant instability mechanism rather than a localized self-dissipativity issue. Guided by this diagnosis, a stabilizing controller featuring dynamics-free orthogonal signal reconstruction is designed to reshape the admittance characteristics of the SST. This enhancement specifically targets the identified coupling-dissipativity deficiencies, thereby resolving the root cause of the instability. Finally, the stability analysis and the effectiveness of the enhancement strategy are validated on a down-scaled SST prototype. Experimental results demonstrate that the criterion accurately predicts the coupling-induced oscillations and that the enhanced controller guarantees stable operation under challenging weak-grid conditions.
### Title:
          Robot Trajectron V3: A Probabilistic Shared Control Framework for SE(3) Manipulation
 - **Authors:** Pinhao Song, Zhongxi Li, Ze Fu, Federico Ulloa Rios, Renaud Detry
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We aim to address the challenge of teleoperating robotic arms for high-degree-of-freedom (high-DoF) manipulation tasks, which is cognitively demanding and error-prone, particularly when relying on low-bandwidth interfaces. We propose Robot Trajectron V3 (RT-V3), a probabilistic shared control framework designed for $SE(3)$ grasping tasks. RT-V3 formulates shared control as Bayesian inference by learning a prior over user intent and combining it with real-time user commands to estimate the posterior intent distribution. The prior models user intent as a distribution over future trajectories conditioned on past robot dynamics and visual scene context. The intent prior is parameterized by a transformer-based conditional generative model that reasons over point clouds and candidate grasp poses, together with a factorized translation-rotation representation that improves learning efficiency in high-dimensional action spaces. During execution, RT-V3 continuously estimates the posterior distribution over future trajectories by combining the learned intent prior with a user-command likelihood derived from the observed control input, enabling continuous intent refinement and shared assistance. Comprehensive experiments demonstrate that RT-V3 achieves high accuracy in trajectory prediction and competitive performance in reactive planning. Furthermore, real-world user studies indicate that RT-V3 significantly outperforms baseline methods in terms of success rate and efficiency, while substantially reducing the user's physical and mental workload.
### Title:
          A Sovereign, Open-Source Foundation Model for German and English
 - **Authors:** The Soofi-Team: Benedikt Droste, David Fitzek, Ruben Härle, Lukas Helff, Maximilian Idahl, Alex Jude, Abbas Goher Khan, Maurice Kraus, Timm Ruland, Richard Rutmann, Sebastian Sztwiertnia, Markus Frey, Daniil Gurgurov, Jan Pfister, Tom Röhr, Sebastian von Rohrscheidt, Jörg Bienert, Nicolas Flores-Herr, Simon Gottschalk, Andreas Hotho, Kristian Kersting, Joachim Köhler, Alexander Löser, Wolfgang Nejdl, Simon Ostermann, Jan Plogsties, Patrick Putzky, Mehdi Ali, Michael Fromm, Max Lübbering
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Soofi S 30B-A3B, a sovereign, open-source Mixture-of-Experts (MoE) hybrid Mamba Transformer foundation model for German and English. Its hybrid design activates only 3B of 30B parameters per token and keeps the inference cache near-constant as context grows, giving it a decisive throughput advantage over dense models for long-context, high-concurrency deployment. Pretrained on roughly 27 trillion tokens with deliberately up-weighted German, Soofi S matches dense 14 to 27B models on aggregate English and German benchmarks while achieving the best code aggregates in both languages among 17 open base models, and outperforms every European sovereign baseline in our comparison, including ones far larger in active parameters. Among fully open models, Soofi S obtains the highest English and German evaluation scores, ahead of Olmo 3 32B and Apertus 70B. Soofi S was built end-to-end on the German Industrial AI Cloud, a sovereign HPC scale AI infrastructure operated by Deutsche Telekom in Munich. Soofi S will be released under highly permissive, open-access terms: weights, selected intermediate checkpoints, full per-source data accounting, hyperparameters, and training and evaluation code. Where source licenses permit, data-construction artifacts are released under permissive licenses; commercially licensed sources are documented with aggregate statistics and exact mixture accounting.
### Title:
          Multimodal Scenario Similarity Search for Autonomous Driving
 - **Authors:** Tamás Matuszka, András Tamásy, Balázs Szolár
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale autonomous-driving datasets contain vast numbers of recorded scenarios, creating a need for efficient retrieval methods that can identify situations similar to a given query. Existing approaches typically rely on either visual representations or motion-based descriptions, making it difficult to understand their relative strengths and limitations for scenario retrieval. In this work, we present a multimodal framework for autonomous-driving scenario retrieval that combines visual and trajectory-based representations within a unified retrieval pipeline. We investigate two trajectory-based approaches: Exo-Trajectory, an explicit matching method based on surrounding-agent motion, and ScenarioFormer, a transformer-based representation learned from object trajectories using contrastive learning. We compare these approaches against strong vision-based baselines and analyze their behavior across a diverse set of driving scenarios. Experimental results show that trajectory representations provide strong retrieval performance for motion-centric events such as cut-ins, turning maneuvers, and traffic queueing, while visual embeddings excel when appearance cues are informative. Most importantly, combining visual and trajectory information consistently improves retrieval quality, yielding the best overall performance. These findings demonstrate that appearance and motion capture are complementary notions of scenario similarity and motivate multimodal retrieval systems for autonomous-driving data mining, dataset curation, and scenario-based validation.
### Title:
          Foveation-Guided Dynamic Token Selection for Robust and Efficient Vision Transformers
 - **Authors:** Ibrahim Batuhan Akkaya, Kishaan Jeeveswaran, Bahram Zonooz, Elahe Arani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The human visual system (HVS) employs foveated sampling and eye movements to achieve efficient perception, conserving both metabolic energy and computational resources. Drawing inspiration from this robustness and adaptability, we introduce the Foveated Dynamic Transformer (FDT), a foveation-guided dynamic token-selection architecture that integrates these mechanisms into a vision transformer framework. The FDT exhibits strong resilience to various types of noise and adversarial attacks, despite not being explicitly trained for such challenges. This inherent robustness is achieved through the use of fixation and foveation modules: the fixation module identifies fixation points to filter out irrelevant information, while the foveation module generates foveated embeddings with multi-scale information. At the 50% fixation-budget setting, FDT achieves higher accuracy than DeiT-S (81.9% vs. 80.9%) while reducing multiply-accumulate operations by 34.57%, highlighting one operating point on its accuracy-efficiency trade-off. These attributes position FDT as an HVS-inspired step toward artificial neural networks that combine adaptive computation with improved resilience.
### Title:
          Decoupling Language Guidance from Backbones for Text-Guided Medical Segmentation
 - **Authors:** Yungeng Liu, Xuanzi Fang, Haijin Zeng, Qi Dai, Yongyong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided medical image segmentation leverages clinical semantics to improve lesion delineation, yet many existing models bind cross-modal fusion, supervision, and decoder design into a task-specific architecture. Such tight coupling makes it difficult to reuse language guidance modules across heterogeneous vision and text backbones, and often requires redesigning the network when the encoder pair changes. This paper presents BTHA, a backbone-transferable hierarchical adapter framework for text-guided medical image segmentation. BTHA is built around a stable feature-level interface: given multi-scale visual features and a text representation, it injects semantic guidance through shape-preserving adapters while maintaining the decoder-side tensor contract. To make this interface effective, we introduce a Hierarchical Coarse-to-Fine Supervision Strategy that decomposes learning into global image-text alignment, multi-scale auxiliary localization, and boundary-aware final mask refinement. We further design a Scale-Adaptive Gated Semantic Guidance (SAGSG) adapter, where resolution-specific gates adaptively control textual injection and channel recalibration suppresses redundant cross-modal responses. Evaluations across diverse vision and text backbones show that the same adapter and supervision design remains effective across convolutional and transformer-based visual encoders as well as different language encoders. Experiments on four public datasets further demonstrate that BTHA improves strong text-guided baselines with modest computational overhead.
### Title:
          FreyaTTS Technical Report
 - **Authors:** Ahmet Erdem Pamuk, Ömer Yentür, Ahmet Tunga Bayrak, Yavuz Alp Sencer Öztürk, Mustafa Yavuz
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Freya-TTS, a compact, tokenizer-free, Turkish-first text-to-speech model designed for highly reliable and efficient conversational synthesis. Freya-TTS is a 183.2M-parameter non-autoregressive conditional flow-matching Diffusion Transformer (DiT) that operates in the frozen continuous latent space of AudioVAE2 (16 kHz encode, 48 kHz decode), allowing the model to focus its capacity on text-to-latent mapping while inheriting high-quality 48 kHz reconstruction. We advance the framework along three key dimensions: (1) rule-free end-to-end modeling from a 92-symbol Turkish character vocabulary without a phonemizer, grapheme-to-phoneme frontend, or discrete speech tokenizer; (2) non-autoregressive parallel denoising, which predicts the entire latent sequence simultaneously over a predicted duration; and (3) a production-oriented two-stage post-training recipe consisting of single-speaker voice locking and short-utterance coverage, improving speaker consistency and robustness on short inputs. On the Freya-TR-Eval benchmark, Freya-TTS achieves a band-matched word error rate (WER) of 8.0% and character error rate (CER) of 3.0%, outperforming substantially larger open-source systems while using a fraction of their parameters. The model achieves a real-time factor of 0.11 on consumer GPUs and runs faster than real time on a laptop CPU, making it well suited for resource-constrained edge deployment. We release the model weights, training and inference code, and evaluation benchmark under the Apache-2.0 license.
### Title:
          CoCoT-EEG: Contrastive-Pretrained Multiscale Convolutional Transformer for EEG Decoding
 - **Authors:** Gabriel Mahuas, Victoria Shevchenko, Ugo Tanielian, Yassir Bendou, Richard Gao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised pretrained foundation models (FM) have shown early promise for non-invasive electroencephalogram (EEG) decoding applications. Many recent large-scale models converged on the approach of tokenizing raw EEG followed by masked reconstruction pretraining. However, this recipe has been shown to be suboptimal for data, like EEG, with high noise amplitude and information confined to limited dimensions such as narrow frequency bands. Building on this insight, we develop a novel contrastive-pretrained EEG model with multiscale temporal convolution input layers and Transformer encoder blocks (CoCoT). CoCoT matches or beats state-of-the-art reconstruction-pretrained EEG models on extensive benchmark decoding tasks with heterogeneous electrode configurations. Furthermore, CoCoT trained from scratch outperforms previous single-task decoding models and even rivals pretrained models, showcasing the architecture's flexibility and data efficiency. Through systematic ablations, including model architecture and pretraining objective, we demonstrate the viability of contrastive learning for building EEG FMs while suggesting key architectural design considerations, prompting further investigations in alternative large-scale pretraining strategies.
### Title:
          PAC-ACT: Post-training Actor-Critic for Action Chunking Transformers
 - **Authors:** Yujie Pang, Zudong Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precision industrial contact manipulation requires reliable robot policies under pose perturbations and contact-force constraints. Vision-language-action models offer broad generalization but often introduce high inference latency and GPU-memory cost, while vision-action chunking policies are more suitable for real-time industrial control. However, these policies are usually trained by behavior cloning and suffer from distribution shift in contact-rich tasks. This paper proposes PAC-ACT, a reinforcement-learning post-training framework for pretrained Action Chunking Transformer policies. PAC-ACT reformulates policy optimization at the chunk level, constructs an ACT-transferred actor-critic architecture, and introduces a hybrid behavior-prior constraint to preserve the pretrained action distribution during online fine-tuning. Experiments on industrial precision-contact benchmarks show that PAC-ACT improves task success, contact stability, and force safety while retaining low latency and low GPU-memory usage. On the Contour task, PAC-ACT significantly reduces peak contact force and decreases the proportion of force readings above 60 N by 46 times. Sparse-reward ablations further show that the proposed behavior-prior constraint enables effective exploration under randomized initial poses.
## Keyword: autonomous driving
### Title:
          BeyondSight: Object Permanence for End-to-End Autonomous Driving
 - **Authors:** Sandro Papais, Letian Wang, Mudit Jain, Behnaz Rezaei, Steven L. Waslander
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving operates in partially observable environments where actors may become fully occluded by other vehicles or infrastructure. Most end-to-end driving systems implicitly couple actor existence to instantaneous observations, causing actor hypotheses to degrade or disappear during prolonged occlusion and removing potentially critical agents from downstream prediction and planning. We introduce BeyondSight, a permanence-aware end-to-end driving framework that decouples actor existence from observability by maintaining persistent actor hypotheses over time. BeyondSight propagates actor queries temporally and updates them with observation-conditioned evidence, enabling joint perception, prediction, and planning to reason about actors even when they are temporarily unobservable. To enable principled training and evaluation of persistence-aware models, we further introduce nuScenes-Permanence, an extension of nuScenes that provides supervision and observability-conditioned evaluation for unobservable actors. Experiments show that BeyondSight substantially improves reasoning under occlusion, increasing detection performance for unobservable actors from 0 to 0.249 mAP while reducing planning error from 0.61 to 0.54 L2avg. These results highlight object permanence as an important modeling principle for robust end-to-end autonomous driving.
### Title:
          4DR360: State Reasoning for Joint 3D Detection and Occupancy Prediction in 4D Radar-Camera Full-Scene Perception
 - **Authors:** Xiaokai Bai, Lianqing Zheng, Runwei Guan, Songkai Wang, Siyuan Cao, Hui-liang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable autonomous driving requires full-scene perception that couples foreground objects with dense semantic layout. Recently, 4D millimeter-wave radar has emerged as a robust and affordable sensor, yet its sparse returns make radar-camera fusion necessary for comprehensive scene understanding. Existing radar-camera methods mainly optimize detection, while dual-task systems usually decode boxes and occupancy with limited interaction. To address this gap and advance radar-based multi-task learning, we propose \method, a 4D radar-camera framework for 360$^\circ$ full-scene perception, which models semantic occupancy as a persistent scene state rather than a terminal output. \method{} follows a cross-modal state reasoning paradigm, where the occupancy state is modeled and propagated through stages for coarse-to-fine feature aggregation. Specifically, State-guided BEV Enhancement (SBE) strengthens intra-frame BEV representation, while Doppler-guided Temporal Fusion (DTF) preserves state evidence over longer temporal horizons. Beyond the model, we further extend ManTruckScenes with satellite-map-based generated occupancy labels and pair it with OmniHD-Scenes in a unified cross-dataset detection-and-occupancy protocol. The resulting experiments cover accuracy, robustness, ablation, and efficiency under one radar-camera multi-task evaluation framework. Code and labels will be released upon acceptance.
### Title:
          OpenLongTail: Generative Scaling of Long-Tail Driving Data
 - **Authors:** Lulin Liu, Nuo Chen, Yan Wang, Bangya Liu, Wenyan Cong, Hezhen Hu, Boris Ivanovic, Hao Wang, Ziyao Zeng, Xinyu Gong, Yang Zhou, Zixiang Xiong, Dilin Wang, Zhangyang Wang, Weisong Shi, Ruohan Zhang, Marco Pavone, Zhiwen Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling robust driving policies is fundamentally bottlenecked by the scarcity of edge cases in curated datasets. While the real world continuously captures these critical events, such long-tail events remain underutilized when collected from heterogeneous sources. Specifically, diverse but valuable in-the-wild long-tail videos lack the full view coverage required for training policy models, often missing multi-view poses or originating solely from monocular dash cameras. This modality gap prevents these ubiquitous observations from being converted into scalable training data for long-tail generalization. We introduce OpenLongTail, an open-source generative data engine for scaling autonomous driving policies under long-tail events. To transform heterogeneous data sources into view-aligned and temporally coherent multi-view assets that are useful for policy learning, we develop a pose-informed extrapolative view synthesis pipeline that generates the missing views. We further enhance cross-view consistency and the temporal alignment for the newly generated views by injecting Plücker ray geometry into the scalable generation engine. By synthesizing heterogeneous long-tail data, we observe a significant improvement in closed-loop driving robustness in handling long-tail events. By measuring the extrapolative view synthesis and pose metrics, we validate the effectiveness of OpenLongTail in visual fidelity, cross-view consistency, and ego-trajectory recovery.
