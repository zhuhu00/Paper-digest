# Showing new listings for Friday, 29 May 2026
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
          GeRaF: Neural Geometry Reconstruction from Radio Frequency Signals
 - **Authors:** Jiachen Lu, Hailan Shanbhag, Haitham Al Hassanieh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GeRaF is the first method to use neural implicit learning for near-range 3D geometry reconstruction from radio frequency (RF) signals. Unlike RGB or LiDAR-based methods, RF sensing can see through occlusion but suffers from low resolution and noise due to its lensless imaging nature. While lenses in RGB imaging constrain sampling to 1D rays, RF signals propagate through the entire space, introducing significant noise and leading to cubic complexity in volumetric rendering. Moreover, RF signals interact with surfaces via specular reflections, requiring fundamentally different modeling. To address these challenges, GeRaF (1) introduces filter-based rendering to suppress irrelevant signals, (2) implements a physics-based RF volumetric rendering pipeline, and (3) proposes a novel lensless sampling and lensless alpha blending strategy that makes full-space sampling feasible during training. By learning signed distance functions, reflectiveness, and signal power through MLPs and trainable parameters, GeRaF takes the first step towards reconstructing millimeter-level geometry from RF signals in real-world settings.
### Title:
          xModel-KD: Cross-modal Knowledge Distillation for 3D Scene Perception using LiDAR
 - **Authors:** Thenukan Pathmanathan, Kanchan Keisham, Thangarajah Akilan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point cloud segmentation is a fundamental task in 3D scene understanding. Its progress is constrained by the high cost and time required for dense 3D annotations, making labeled samples difficult to obtain. Beyond annotation scarcity, different sensing modalities face inherent limitations. 2D images provide rich texture and appearance cues, yet they lack explicit depth and geometric structure. In contrast, 3D point clouds capture accurate spatial geometry but are sparse and contain no texture information. As a result, relying on a single modality restricts the richness of learned representations and weakens generalization. Although recent multi-modal methods that combine 3D point clouds with 2D images have demonstrated strong performance in tasks such as classification and retrieval, they typically depend on large-scale labeled datasets and have not been fully exploited for data-efficient dense prediction. To address these limitations, we propose a novel cross-modal knowledge distillation framework, xModel-KD, for 3D point cloud segmentation. Our method exploits the complementary strengths of 2D texture and 3D geometry by learning unified per-point representations through cross-modal alignment. Specifically, we design a cross-modal fusion encoder trained with a contrastive objective that enforces feature consistency between corresponding 2D and 3D representations across multiple views. By integrating powerful pre-trained backbones with a targeted fusion strategy, the proposed framework effectively transfers appearance cues from images to geometry-aware point features. Experimental results show that cross-modal fusion achieves a 2% absolute improvement in mIoU over a LiDAR-only baseline, demonstrating the benefit of leveraging complementary multi-modal information for scalable and annotation-efficient 3D scene understanding.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Eulerian Gaussian Splatting using Hashed Probability Pyramids
 - **Authors:** Mia Gaia Polansky, George Kopanas, Stephan Garbin, Todd Zickler, Dor Verbin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a probabilistic splat-based radiance field framework that retains the fast rasterization and test-time efficiency of 3D Gaussian Splatting (3DGS) while replacing heuristic primitive manipulation with gradient-based optimization of a volumetric probability density. Rather than relocating, splitting, or culling Gaussians via hand-tuned densification (e.g., ADC), we treat primitive locations as samples drawn from a persistent, learnable density. We instantiate this density using a novel, memory-efficient multi-scale hierarchical grid that enables end-to-end gradient-based optimization. To stabilize the optimization, we derive an unbiased gradient estimator with control variates that markedly reduces variance. By allowing probability mass to flow to where the loss demands, our framework eliminates brittle priors and naturally explores the volume, achieving state-of-the-art reconstruction quality on mip-NeRF 360 while preserving 3DGS-level rendering speed.
### Title:
          City-Mesh3R: Simulation-Ready City-Scale 3D Mesh Reconstruction from Multi-View Images
 - **Authors:** Sayan Paul, Sourav Ghosh, Siddharth Katageri, Soumyadip Maity, Sanjana Sinha, Brojeshwar Bhowmick
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 City-scale 3D surface reconstruction from multiview images for downstream 3D simulation, poses highly challenging problems due to the scale and complexity of urban scenes. Existing city-scale 3D reconstruction methods based on NeRF, Gaussian Splatting etc. often fail to recover 3D meshes ready for simulation due to incomplete/missing geometry and irregular, noisy surfaces. Scaling existing small-scale 3D reconstruction methods to arbitrarily large urban scenes is highly infeasible due to their computational complexity. We present City-Mesh3R, a scalable framework for reconstructing watertight surface meshes directly from large unordered image collections. Unlike recent methods which use global sparse SfM point-cloud initialization followed by a distributed 3D dense reconstruction of large-scale scenes, our method follows an end-to-end images-to-mesh 3D reconstruction approach using a divide-and-conquer strategy. The sparse city map is reconstructed via topological image clustering, cluster-wise independent sparse SfM and map merging, without need for exhaustive image feature matching. Then this map is partitioned spatially to perform geometry-aware camera selection, followed by dense surface reconstruction and surface refinement using curvature-aware adaptive vertex density remeshing. These partition meshes are then stitched together to produce the global mesh of the city. The proposed end-to-end framework is evaluated on city-scale reconstruction datasets. As demonstrated by our qualitative and quantitative results, our proposed method yields high-fidelity watertight 3D meshes with regular geometry, capturing fine surface details, and is suitable for scaling to arbitrarily large scenes owing to the end-to-end processing in a distributed setting.
## Keyword: mapping
### Title:
          The Biosecurity Blind Spot: Systematic Dual-use Detection in Open Science Infrastructure
 - **Authors:** Vasudha Sharma, Chakresh Kumar Singh, Jayesh Choudhari, Dharmit Nakrani
 - **Subjects:** Subjects:
Digital Libraries (cs.DL); Computers and Society (cs.CY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI is transforming life sciences research at unprecedented speed, accelerating discovery across protein structure prediction, genome modeling, and drug development (Jumper et al., 2021; Mak et al., 2024). Yet this rapid advancement, coupled with the open science movement, introduces significant dual-use research concerns that have received limited empirical scrutiny. Here we present the first systematic analysis of dual-use research of concern (DURC) content on open preprint servers. We screened ~52,000 bioRxiv preprints (2024-2025) using a hybrid pipeline of lexical filtering and large language model (LLM) evaluation, scoring metadata across nine DURC, three PEPP, and five governance categories aligned with U.S. and Australia Group oversight frameworks. Our analysis reveals that dual-use-adjacent knowledge is routinely present in openly accessible titles and abstracts, often exceeding established risk thresholds even in studies with legitimate public health objectives. While this mapping captures surface-level information diffusion, it does not measure operational capability, downstream misuse potential, or the substantial technical and biosafety barriers that constrain harmful application. We argue that institutional review processes, funding requirements, and preprint platform policies must evolve to incorporate proactive, metadata-level monitoring without compromising scientific transparency. Ultimately, harmonizing controlled-access mechanisms for high-risk methodologies with open summaries of scientific contributions offers a pragmatic framework for governing AI-accelerated biology at scale.
### Title:
          Balancing Multimodal Learning through Label Space Reshaping
 - **Authors:** Xiaoyu Ma, Weijie Zhang, Yuanhao Gao, Han Miao, Yongjian Deng, Hao Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal learning often suffers from modality imbalance, where modalities that converge faster dominate optimization while others remain undertrained. Existing approaches typically mitigate this issue by strengthening the weak modality or adjusting optimization gradients. However, such strategies mainly compensate for optimization rate discrepancies, often at the expense of the strong modality's optimization capacity, without analyzing how these discrepancies arise at the modality level. Based on theoretical insights and empirical observations, we argue that the discrepancy of learning pace arises from differences in the mapping difficulty between modality-specific feature space and the shared label space. To address this issue, we propose Balanced Multimodal Label Reshaping (BMLR), the first method that promotes multimodal balance from the label-side design. BMLR reshapes the cross-modal label space to equalize mapping difficulty across modalities, thereby facilitating modality interaction and injecting richer inter-class information into each modality. Extensive experiments across multiple architectures demonstrate that BMLR consistently improves multimodal performance and exhibits strong compatibility with diverse model designs. The source code will be released soon.
### Title:
          Quantum-Enhanced Adversarial Robustness in Artificial Intelligence
 - **Authors:** Jaydip Sen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial Intelligence has achieved remarkable success across diverse application domains. However, its vulnerability to adversarial attacks poses significant challenges to reliability, security, and trustworthiness. Adversarial machine learning demonstrates that even highly accurate models can be manipulated through carefully crafted perturbations, raising serious concerns in safety critical systems such as healthcare, finance, and autonomous technologies. In parallel, quantum computing has emerged as a transformative paradigm capable of addressing complex computational problems through principles such as superposition, entanglement, and quantum interference. The convergence of these fields has led to the emergence of quantum artificial intelligence, which explores how quantum techniques can enhance learning efficiency, scalability, and robustness. This chapter provides a comprehensive overview of adversarial machine learning and existing defense strategies, followed by an accessible introduction to quantum computing and quantum machine learning models. It further presents conceptual frameworks for quantum-enhanced adversarial robustness, emphasizing quantum optimization, feature mapping, and hybrid quantum classical architectures. Practical applications, key challenges, and future research directions are also discussed to support the development of secure and trustworthy AI systems.
### Title:
          Resolving Endpoint Underfitting in Diffusion Bridges via Noise Alignment
 - **Authors:** Yurong Gao, Zicheng Zhang, Congying Han, Tiande Guo, Xinmin Qiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion bridge models offer a powerful framework for connecting two data distributions, such as in image restoration and translation. Many existing methods learn this bridge by mimicking the score-matching formulation of standard diffusion models. In this work, we find that this way leads to an anomalous underfitting phenomenon near the target endpoint, as the process approaches the target distribution ($t \to 0$). This underfitting, characterized by significant drift in the predicted variance and direction, results from an excessively large discrepancy in noise levels between the network's input and its regression this http URL resolve this issue, we propose the Noise-Aligned Diffusion Bridge (NADB).Our approach reformulates the diffusion bridge by first employing a mean network to provide a cleaner conditional target, and then introducing a novel, noise-aligned mapping relationship. This new formulation resolves the noise mismatch and corrects the underfitting near the target endpoint. Experimental validation across multiple image restoration and image translation tasks demonstrates the effectiveness of our approach. Code is available at this https URL.
### Title:
          Trajectory Constraints for Imaging Inverse Problems
 - **Authors:** Chaoyan Huang, Haijie Yuan, Saiprasad Ravishankar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based and iterative methods have become effective tools for solving imaging inverse problems. Their reconstruction process naturally forms a trajectory of intermediate estimates. Although these intermediate estimates define a reconstruction trajectory, most methods do not explicitly regularize the transitions between consecutive states. To address this limitation, we introduce TRACE, a training-free TRAjectory-Constrained rEconstruction framework that stabilizes the reconstruction path by coupling adjacent states along the trajectory. This gives a trajectory-level model that can be interpreted as a sequence of proximal updates. Since the exact proximal update is generally intractable, we approximate it with a neural mapping. This yields a diffusion-like reconstruction process with an explicit coupling between neighboring states. We provide a stability analysis showing that temporal coupling bounds trajectory variation and that this control is preserved under untrained network updates. Experiments on linear and nonlinear image reconstruction tasks show that TRACE improves reconstruction quality. Trajectory-level analyses and ablations confirm that temporal coupling directly affects state transitions along the reconstruction path.
### Title:
          ConMoE: Expert-Pool Consolidation via Prototype Reassignment for MoE Compression
 - **Authors:** Yilun Yao, Jiaming Pan, Elsie Dai, Peizhuang Cong, Yaoming Li, Tong Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-Experts (MoE) language models reduce per-token computation but still require storing and serving all experts, making deployment memory-intensive. Existing post-training compression methods mainly shrink this cost by pruning experts or merging their weights. We formulate post-training MoE compression as expert-pool consolidation: retaining a smaller set of pretrained experts as reusable prototypes and deterministically remapping each original expert reference to one selected prototype. This view separates the reduced expert pool from the reuse structure that represents the original expert slots, and allows prototype sharing within local layer scopes while preserving the original router interface. We propose ConMoE, a train-free prototype remapping framework that selects retained experts using calibration-based contribution and replaceability signals, then redirects original expert calls to the selected prototypes without weight updates or post-compression fine-tuning. Experiments on three pretrained MoE language models show that ConMoE matches or outperforms strong pruning and merging baselines in several settings, achieving the best average score on deepseek-moe-16b-base at both 25% and 50% routed-expert reduction, while remaining competitive on Qwen3-30B-A3B and OLMoE-1B-7B-0125. Ablations indicate that deterministic reassignment is the most stable component, whereas broader cross-layer sharing and post-hoc weight fusion are model-dependent.
### Title:
          Deep Adaptive Dimension Reduction for Bayesian Inference in Inverse Problems
 - **Authors:** Yueyang Wang, Xili Wang, Kejun Tang, Xiaoliang Wan, Tao Zhou, Chao Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Solving high-dimensional PDE-governed inverse problems is often challenging due to complex non-Gaussian posterior distributions, expensive forward model evaluations, and misspecified prior information. To address these issues, we propose a deep adaptive dimension-reduction Bayesian inference framework based on the Variational Flow (VF) model. Since standard normalizing flows are restricted by bijective mappings and cannot directly reduce dimensions, VF overcomes this limitation by integrating VAE-based nonlinear dimension reduction with dual normalizing flows for the latent prior and encoder. This design provides a strictly higher evidence lower bound than VAE and allows more flexible approximation of complex posterior distributions. We further introduce an iterative prior updating strategy that gradually moves the prior mean toward high-probability posterior regions, avoiding manual prior tuning. These components form a closed adaptive loop together with an adaptively fine-tuned Fourier Neural Operator (FNO) surrogate: VF generates posterior-concentrated samples to refine the surrogate, while the updated surrogate further improves posterior inference. Numerical experiments on a 100-dimensional Rosenbrock problem and three standard PDE-governed inverse problems show that our method delivers competitive or superior accuracy compared with MCMC, UKI, and SVGD baselines across all tested configurations, with the most pronounced advantages emerging in challenging scenarios such as high-noise observations and high-dimensional parameter spaces.
### Title:
          Uni-RCM: Unified Reference-guided Cross-modal Mapping for Multi-Class Anomaly Detection
 - **Authors:** Yangchen Wu, Huiqiang Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal industrial anomaly detection typically relies on separate models for each product category, fundamentally limiting practical scalability. When shifting to a unified paradigm that handles diverse classes simultaneously, detection accuracy often degrades due to inter-class interference and feature manifold confusion. To overcome these challenges, we propose a Unified Reference guided Cross-modal Mapping framework, named Uni-RCM. At its core, we propose a reference guide block to dynamically filter out category-specific noise by introducing a learnable reference feature, which captures the commonalities across different modalities. Besides, an offline residual quantizer is proposed to characterize the normal distribution by multiple cascaded codebooks. Extensive evaluations on the MVTec-3D AD dataset demonstrate the state-of-the-art performance in the challenging multi-class setting and in terms of image-level detection and pixel-level localization.
### Title:
          ActTraitBench: Quantifying the Knowledge-Decision Gap in Large Language Models via Human-Grounded Behavioral Validation
 - **Authors:** Yutong Yang, Chenxi Miao, Weikang Li, Yunfang Wu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Large Language Models (LLMs) can convincingly simulate personas in explicit self-reports, they often deviate in implicit behavioral decisions, revealing a substantial Knowledge-Decision Gap ($G_{\text{KD}}$). Existing benchmarks struggle to measure this asymmetry due to limited construct validity, multi-dimensional entanglement, and distributional biases in LLM-based evaluation. To address these issues, we propose ActTraitBench, a human-grounded evaluation framework for measuring personality consistency in LLMs. Grounded in empirical human data, ActTraitBench establishes one-to-one mappings between psychometric facets and behavioral paradigms, and applies a Distributional Calibration via Quantile Mapping procedure to align LLM-judge score distributions with human norms. Experiments on 14 mainstream LLMs reveal a pervasive knowledge-decision asymmetry, where larger and more capable models often exhibit stronger behavioral divergence despite highly consistent self-reports. To mitigate this gap, we further introduce the Chain of Cognitive Alignment (CoCA), a plug-and-play inference-time intervention that improves alignment in reasoning-capable frontier models while exposing clear capability limitations in smaller architectures.
### Title:
          Building and Road Recognition in Dense Urban Informal Settlements: A Dataset and Benchmark
 - **Authors:** Hongyu Long, Jiaxuan Liu, Rui Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As a widespread form of informal settlements, urban villages present significant challenges for sustainable urban development and governance. Precise mapping of their infrastructure is essential, however, existing remote sensing datasets primarily focus on formal urban environments, lacking fine-grained annotated data for the high-density building patterns and narrow road networks typical of urban villages. To address this gap, we introduce the \textit{DenseUIS} dataset, the first high-resolution remote sensing dataset specifically designed for building and road extraction in extremely dense urban informal settlements, covering 126 urban villages across Shenzhen and Guangzhou in China. Furthermore, we conduct a comprehensive evaluation of state-of-the-art deep learning models on this dataset. Experimental results reveal the limitations of existing methods in handling the unique morphological patterns of dense informal settlements, underscoring the need for specialized approaches. \textit{DenseUIS} therefore provides a robust benchmark for advancing fine-grained urban mapping in complex and high-density informal environments. The dataset is publicly available at this https URL.
### Title:
          STAP: A Shuffle-Tokenized App Predictor with Ultra Long Context for Vocabulary-Free Mobile App Prediction
 - **Authors:** Chengyu Fan, Hang Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting the next mobile application a user will launch is essential for intelligent device resource management and proactive assistance. Existing models rely on fixed app vocabularies, which prevents them from generalizing across different app ecosystems. Many also depend on user-specific knowledge, which complicates deployment in cold start scenarios. We propose STAP, a Transformer-based model that eliminates the need for a fixed vocabulary. STAP replaces true app identities with randomly reassigned virtual indices via a shuffle mechanism, and compensates for discarded semantic information by processing behavioral sequences with an ultra-long context design. A theoretical analysis shows that, given a sufficiently long context, the predicted distribution converges to the correct one despite the anonymity of the mapping. Experiments on two datasets from different continents demonstrate that STAP achieves strong cross-dataset zero-shot prediction accuracy -- a setting where all existing fixed-vocabulary methods are inherently inapplicable -- while its cold start performance within each dataset remains competitive with leading models. Furthermore, we introduce a deployment strategy that enables the model to retain a sufficiently long context during continuous inference while keeping latency within acceptable bounds.
### Title:
          DGSG-Mind: Dynamic 3D Gaussian Scene Graphs for Long-Term Scene Understanding and Grounding
 - **Authors:** Luzhou Ge, Xiangyu Zhu, Jinyan Liu, Xuesong Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating open-vocabulary semantic information into dynamic 3D scene representations is essential for long-term embodied scene understanding. However, existing methods often suffer from fragile instance association due to incomplete cross-view cues, while their limited ability to handle object-level topological changes restricts long-term robotic task execution. Moreover, current 3D scene understanding methods either rely on simple feature matching without explicit spatial reasoning or assume offline ground-truth 3D geometry. To address these challenges, we present DGSG-Mind, a hybrid instance-aware 3D Gaussian dynamic scene graph system with an embodied reasoning agent. Our system couples a probabilistic voxel grid with explicit 3D Gaussians to enable robust cross-modal instance fusion and incremental semantic mapping. It handles dynamic changes through Gaussian-based visual relocalization and localized masked refinement guided by geometric-semantic consistency. Built on the instance Gaussian map, DGSG-Mind further constructs a hierarchical scene graph and develops the 3D Gaussian Mind, which integrates structural relations, spatial-semantic information, and visually annotated RoI Gaussian renderings for multimodal reasoning. Extensive experiments show that DGSG-Mind achieves the best zero-shot 3DVG performance among methods operating on self-reconstructed maps, while also delivering strong performance in 3D open-vocabulary semantic segmentation and scene reconstruction. We further deploy DGSG-Mind on real-world robots to demonstrate its target-oriented reasoning and dynamic update capabilities. The project page of DGSG-Mind is available at this https URL
### Title:
          Internal Representation, Not Clinical Knowledge: Where Apparent LLM Triage Failures Originate
 - **Authors:** David Fraile Navarro, Berardino Como, Jialei Sheng, Soundariya Ananthan, Shlomo Berkovsky
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Patient-voiced clinical-triage benchmarks report high under-triage rates for consumer LLMs for constrained multiple-choice output, yet the same cases score differently with free-text. We ask whether output format changes the model's \emph{clinical representation} or only the mapping from a preserved representation to an answer. Using sparse-autoencoder (SAE) features in Gemma 3 4B/12B IT and Qwen3-8B, we find the same medical features fire on the shared clinical narrative under both formats but go {silent} at the multiple-choice decision token in all the cases at every model. Three independent methods (natural-language autoencoder verbalization, decision-token logit attribution, and top-feature characterization) agree that scaffold and format features, but not medical features, drive the decision logits. Behaviorally, the multiple-choice penalty inverts under both structured and natural-language input, option-order shuffle rules out positional bias, and the gap is dominated by off-by-one decision (the model picks an adjacent acuity letter to the gold answer) rather than knowledge failure. Thus, the failure originates in the output format and not in the clinical representation.
### Title:
          On the Geometry of Games and their Solvers
 - **Authors:** Yaqi Sun, Julian Ma, David Mguni
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A central challenge in game theory and learning systems such as GANs is understanding which algorithms can efficiently compute equilibria across the heterogeneous landscape of games. Equilibrium computation is typically studied solver by solver and game class by game class, yielding strong local guarantees but a fragmented view of solver behaviour. Existing discrete taxonomies often provide an incomplete account of where algorithms succeed. We study this problem through a solver-game map linking games to effective solver dynamics. Classical theory identifies isolated regions of this map but provides limited insight into intermediate or overlapping regimes, suggesting that solvability is governed by latent structural properties defining a continuous solver-aligned geometry of games. We formalise this perspective through structure-aware solver synthesis. A learned structure recogniser maps each game to a low-dimensional solver-aligned representation, and a policy maps this representation to effective primitive mechanisms, adapting solver behaviour across regimes. This reveals regions where particular solver dynamics are effective and where mixtures of primitives are required rather than a single dominant solver. A bounded residual acts as a local corrector and diagnostic signal for incomplete solver bases or representations. The framework yields both an adaptive solver and an analytical lens: games with similar optimisation dynamics cluster together, revealing continuous regions of algorithmic validity and overlapping solver behaviour. Empirically, we show that fixed primitives exhibit systematic regime mismatch, while the learned representation organises game space into a structured cartography aligned with solver behaviour. These results suggest viewing equilibrium computation as the joint problem of learning solver mechanisms and mapping the geometry of solvability.
### Title:
          Adapting Multilingual Embedding Models to Turkish via Cross-Lingual Tokenizer Surgery and Offline Distillation
 - **Authors:** M. Ali Bayram, Banu Diri, Savaş Yıldırım
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sentence embeddings are a foundational component for semantic search, clustering, classification, and retrieval-augmented generation. This paper presents embeddingmagibu-200m, a Turkish-focused sentence embedding model that produces 768-dimensional L2-normalized vectors and supports an 8,192-token context window, far exceeding the 512-token limit of earlier BERT-based Turkish encoders. Instead of full pretraining, an efficient three-stage adaptation pipeline is introduced: (1) construct a Turkish-optimized multilingual tokenizer with a 131,072 vocabulary by pruning redundant tokens from the teacher's vocabulary and incorporating multilingual tokens via frequency analysis on a 40-language corpus, (2) clone a teacher embedding model while preserving transformer backbone weights and initializing a compatible embedding table for the new vocabulary via mean-composition token mapping, and (3) perform offline embedding distillation from precomputed teacher vectors using a cosine similarity objective over a balanced 40-language Wikipedia corpus. The resulting student model contains approximately 200M parameters and trains in roughly four hours on a single GPU by avoiding online teacher inference during training, at a total cost of $5-$20. Empirically, Pearson/Spearman correlations of 77.55%/77.45% are obtained on STSbTR, surpassing the 300M-parameter teacher model (73.84%/72.92%). On TR-MTEB (26 tasks), a mean score of 63.9% is achieved (7th out of 26 models), providing a competitive cost-quality trade-off with 33% fewer parameters than the teacher. To facilitate reproducibility and downstream use, all artifacts are released including model weights, tokenizer files, precomputed embedding datasets, and open-source cloning and distillation tooling.
### Title:
          Low-Overhead Receiver Design for Data-Dependent Superimposed Training via Deep Learning
 - **Authors:** Xinjie Li, Xingyu Zhou, Jing Zhang, Chao-Kai Wen, Xiao Li, Shi Jin
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Superimposed pilot (SIP) transmission improves spectral efficiency by eliminating the dedicated pilot overhead required in orthogonal pilot (OP)-based schemes. However, SIP suffers from severe pilot-data coupling, which leads to a critical performance-complexity bottleneck at the receiver. To address this issue, this paper proposes a low-overhead transmission framework that revitalizes data-dependent superimposed training (DDST) with enhanced interference mitigation strategies. First, for quasi-static block-fading channels, an enhanced DDST receiver is developed to achieve non-iterative pilot-data decoupling by exploiting data-dependent algebraic structures. Second, to overcome the sensitivity of conventional DDST to channel variations and symbol misidentification in fast time-varying environments, a mix transmission scheme is developed. By strategically applying DDST to a subset of resource elements, the proposed scheme combines the interference-free transmission property of OP with the zero-pilot-overhead advantage of SIP, thereby improving demapping reliability and interference suppression. Furthermore, under the proposed mix scheme, a Vision Transformer-based neural receiver is designed to capture the orthogonal structure between pilots and perturbation-bearing data, as well as the underlying channel correlations, thereby relaxing the stringent quasi-static assumption required for interference disentanglement. Simulation results demonstrate that the proposed framework achieves significant performance gains in the low-to-medium SNR regime under time-varying channels while providing superior computational efficiency compared with state-of-the-art SIP receivers.
### Title:
          PARCEL: Pool-Anchored Resampling with Conditioned Elastic Queries for Efficient Vision-Language Understanding
 - **Authors:** Selim Kuzucu, Alessio Tonioni, Vasile Lup, Bernt Schiele, Federico Tombari, Muhammad Ferjad Naeem
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Vision-Language Models (LVLMs) map visual inputs into dense token sequences, imposing a quadratic computational bottleneck for inference. Elastic visual-token compression addresses this by training a single model that can run at multiple visual-token budgets. However, existing approaches struggle under aggressive compression. Spatial-only compression, as in nested pooling, behaves as an imperfect low-pass filter and induces spectral aliasing that obscures fine-grained detail. Query-only compression, as in nested query resampling, replaces explicit grid-aligned tokens with non-local summaries and substantially degrades spatial grounding. To resolve this representational conflict, we introduce PARCEL (Pool-Anchored Resampling with Conditioned Elastic Queries for Efficient Vision-Language Understanding), a visual tokenization architecture that dynamically partitions the labor of feature extraction. PARCEL establishes spatial pool tokens as low-frequency layout anchors and conditions elastic query tokens on these anchors through Pool-Conditioned Query Resampling. This encourages query tokens to focus on complementary visual features rather than redundant spatial mapping. Extensive evaluations across 27 benchmarks show that PARCEL improves the performance-efficiency Pareto frontier, consistently outperforming existing matryoshka baselines across visual-token budgets while preserving the "train once, deploy anywhere" paradigm.
### Title:
          Learning to Extrapolate to New Tasks: A Relational Approach to Task Extrapolation
 - **Authors:** Adam Ousherovitch, Yixin Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern learning systems excel at interpolation but struggle to generalize to unseen tasks outside the training distribution's support. This failure occurs even in simple settings, such as handling task parameters beyond the training range, and persists despite advances in foundation models. To this end, we develop the Relational Task Extrapolator (RTE), an algorithm designed to enable systematic extrapolation to novel tasks. The key observation is that extrapolation is inherently relational: extrapolating to unseen tasks requires learning how tasks transform into one another. If a model learns the transformation between tasks A and B during training, it can apply that same transformation to relate known tasks to unseen ones at test time. RTE operationalizes this idea by decomposing each target task into a known anchor task and a transformation linking the anchor and target. It then learns a relational operator, mapping an anchor-transformation pair to predictions for the target task. We instantiate RTE across multiple task extrapolation regimes in function prediction, e.g. where target tasks use out-of-range parameters (parameter extrapolation), have greater compositional depth (length extrapolation), and/or recombine function primitives in unseen ways (compositional extrapolation). We further extend RTE to sequence prediction, integrating it into fine-tuning algorithms for foundation models. Across empirical studies, we find that RTE substantially outperforms existing approaches on extrapolation to novel, unseen tasks.
### Title:
          Unveiling the Visual Counting Bottleneck in Vision-Language Models
 - **Authors:** Xingzhou Pang, Yifan Hou, Junling Wang, Mrinmaya Sachan
 - **Subjects:** Subjects:
Multimedia (cs.MM); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Large Vision-Language Models (VLMs) excel at interpolation, they suffer catastrophic failures in systematic generalization, most notably in visual counting. In this work, we investigate this extrapolation bottleneck by deconstructing visual counting into three cognitive stages: visual individuation, magnitude awareness, and symbolic mapping. Using synthetic Go boards and linear probes, we demonstrate that visual backbones maintain robust, linearly separable representations of quantity well into the extrapolation regime, ruling out perceptual failure. Furthermore, models retain latent magnitude awareness, successfully performing comparative reasoning on quantities they fail to enumerate. We pinpoint the collapse to the symbolic mapping stage, where the model fails to project valid visual magnitudes onto symbolic tokens. Our findings support a frac tured magnitude hypothesis: VLMs fail to acquire a universal number space, instead learning disjoint, modality-specific statistical manifolds that prevent cross-modal grounding for unseen quantities. Validated on the state-of-the-art foundation model, our results suggest that bridging this gap requires inductive priors enforcing unified representations, as data scaling alone is insufficient.
### Title:
          How's it going? Reinforcement learning in language models recruits a functional welfare axis
 - **Authors:** Andy Q Han, David J. Chalmers, Pavel Izmailov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How does reinforcement learning shape a language model's internal representations? We present evidence that RL recruits a pre-existing representation of functional welfare: an estimate of how well or badly the system is doing, relative to its goals. We train several language models in a novel, semantically neutral maze environment. We then extract concept vectors for rewarded and punished trajectories, and evaluate those vectors in settings unrelated to the maze environment. The punishment vector behaves like a representation of negative welfare: it promotes failure and impossibility tokens, it aligns with negative emotion concepts, it negatively tracks goal-achievement, and steering with it induces negative self-reports, pathological backtracking, refusal, and uncertainty. The positive reward vector behaves as the mirror image, and the two are nearly antiparallel. These effects are robust when controlling for tile-to-reward mapping, scale, instruct tuning, RL training algorithm, model family, and LoRA versus full-finetuning, and largely persist when we replace RL with supervised fine-tuning. Importantly, the vectors are effective in models before they have undergone maze training. Combined with observations that the effects also appear in pretrain-only models, we therefore argue that this functional welfare axis pre-exists post-training: it is recruited, rather than created, by post-training. While we make no claims about any experience of welfare, the axis offers a demonstration that minimal reward signals can broadly affect model behavior by recruiting pre-existing welfare-like representations, with implications for interpretability, post-training dynamics, and alignment.
### Title:
          Gaze2Act: Gaze-Conditioned Vision-Language-Action Policies for Interactive Robot Manipulation
 - **Authors:** Kuangji Zuo, Gen Li, Bofan Lyu, Yanshuo Lu, Boyu Ma, Shijia Han, Xinyu Zhou, Xichen Yuan, Chuhao Zhou, Jiaqi Bai, Geng Li, Jianfei Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have recently shown strong potential for robot learning by following language instructions. However, in practice, language alone is often insufficient to precisely convey human intent. It is difficult to describe which exact object to interact with among similar candidates, where to act on the object, or how the target may change during execution. To address this limitation, we propose Gaze2Act, a novel VLA framework that leverages human gaze as a dynamic and intuitive intent signal for complex interactive manipulation. Gaze2Act first bridges the ego-exo view gap by mapping first-person gaze into the robot's perspective through cross-view semantic matching, producing both an object mask and a gaze point for coarse-to-fine target specification. These cues are then integrated into the policy through perception-level prompting and action-level conditioning, allowing the robot to attend to relevant regions and execute precise interactions under dynamic intent. In a systematic evaluation across seven task categories and 16 real-robot tasks on a Unitree G1 humanoid, Gaze2Act achieves state-of-the-art performance in both intent accuracy and task success rate. It notably outperforms baselines in object disambiguation, fine-grained interaction, and dynamic intent steering. These results demonstrate that human gaze provides a natural, low-burden, and highly expressive modality for human-in-the-loop VLA control.
### Title:
          Uncertainty-driven 3D Gaussian Splatting Active Mapping via Anisotropic Visibility Field
 - **Authors:** Shangjie Xue, Jesse Dill, Dhruv Ahuja, Frank Dellaert, Panagiotis Tsiotras, Danfei Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Gaussian Splatting Anisotropic Visibility Field (GAVIS), a novel framework for uncertainty quantification and active mapping in 3DGS. Our key insight is that regions unseen from the training views yield unreliable predictions from the 3DGS. To address this, we introduce a principled and efficient method for quantifying the visibility field in 3DGS, defined as the anisotropic visibility of each particle with respect to the training views, and represented using spherical harmonics. The resulting visibility field is integrated into a Bayesian Network-based uncertainty-aware 3DGS rasterizer, enabling real-time (200 FPS) uncertainty quantification for synthesized views. Active mapping is further performed within a maximum information gain framework building on this formulation. Extensive experiments across diverse environments demonstrate that GAVIS consistently and significantly outperforms prior approaches in both accuracy and efficiency. Moreover, beyond standalone use, our method can be applied post-hoc to improve the performance of existing approaches.
## Keyword: localization
### Title:
          OpenClawBench: Benchmarking Process-side Anomalies in Real-world Agent Execution Trajectories
 - **Authors:** Yibing Liu, Yangze Liu, Xiaolong Yin, Bin Wang, Chong Zhang, Hao Yin, Zhongyi Han
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task success can hide process anomalies in real-world agent executions. An agent may pass the final task oracle while still accumulating unresolved ambiguity, unsafe external writes, ignored errors, weakly grounded commitments, or capability-boundary overcommitment. We study this mismatch as the Outcome-Process Gap and introduce OpenClawBench, a large-scale dataset for measuring and supervising process-side anomalies in real agent execution processes. OpenClawBench is built from BFCL-driven OpenClaw sessions produced by 6 source models and contains 31,264 annotated trajectories. It aligns task-oracle outcomes with structured process evidence. FullTax converts the aligned trajectories into structured anomaly supervision: binary labels, supporting evidence, onset/span localization, severity, recoverability, and a 5-class anomaly taxonomy. Using OpenClawBench, we make the Outcome-Process Gap measurable. Among 31,135 oracle-passing executions, 2,904 are still labeled process-anomalous under FullTax. These results show that success-only evaluation misses a concrete class of process-side failures in real agent executions. A LoRA-fine-tuned Gemma 3 12B detector trained on the high-confidence FullTax supervised pool reaches binary F1=0.729 on the cleaner-labels held-out test split. Together, OpenClawBench turns real agent execution logs into auditable and reusable supervision for studying, diagnosing, and operationally monitoring runtime agent reliability.
### Title:
          Uni-RCM: Unified Reference-guided Cross-modal Mapping for Multi-Class Anomaly Detection
 - **Authors:** Yangchen Wu, Huiqiang Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal industrial anomaly detection typically relies on separate models for each product category, fundamentally limiting practical scalability. When shifting to a unified paradigm that handles diverse classes simultaneously, detection accuracy often degrades due to inter-class interference and feature manifold confusion. To overcome these challenges, we propose a Unified Reference guided Cross-modal Mapping framework, named Uni-RCM. At its core, we propose a reference guide block to dynamically filter out category-specific noise by introducing a learnable reference feature, which captures the commonalities across different modalities. Besides, an offline residual quantizer is proposed to characterize the normal distribution by multiple cascaded codebooks. Extensive evaluations on the MVTec-3D AD dataset demonstrate the state-of-the-art performance in the challenging multi-class setting and in terms of image-level detection and pixel-level localization.
### Title:
          Optimizing Latent Representations for Robust Building Damage Assessment Onboard Earth Observation Satellites
 - **Authors:** Thomas Goudemant, Benjamin Francesconi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid identification of damaged buildings after natural disasters or on war areas is crucial to support emergency response and prioritize interventions. Earth Observation constellations provide timely, large-scale coverage, but actionable information is often delayed by data downlink constraints, on-ground processing, and human interpretation. Reducing this latency is essential to improve decision-making responsiveness. In this work, we propose an original AI-based system that enables object-level building damage assessment (localization and damage classification) directly onboard satellites from pre-disaster and post-disaster highresolution optical imagery. Available pre-disaster images are encoded on ground into compact latent representations, transmitted to the satellite, and compared on-board with newly acquired post-event observations. Leveraging AI interpretation capabilities and increasing processing capabilities on-board satellites, the proposed design enables processing directly at the data source, reducing the amount of information to be downlinked while preserving task-relevant content and improving overall system responsivity. We explore the design space through a systematic benchmark of onboard-compatible variants, analyzing the impact of siamese processing, cross-attention, latent-space compression, and robustness-oriented data augmentation. Experiments on xBD dataset demonstrate reliable and robust damage assessment under misalignment, with minimal performance degradation under strong compression.
### Title:
          AgentCVR: Active Multi-Agent Cross-Video Reasoning via Script-Simulated Reinforcement Learning
 - **Authors:** Yilun Qiu, Jiahe Wang, Cilin Yan, Jiayin Cai, Xiaolong Jiang, Yao Hu, Chun Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-Video Reasoning (CVR) has emerged as a critical frontier in multimodal intelligence, requiring models to retrieve, align, and aggregate evidence distributed across multiple videos. Current Multimodal Large Language Models (MLLMs) often struggle with CVR, as simple single-pass strategies encode multiple videos into a shared compressed context, potentially obscuring rare but critical evidence. In this paper, we propose AgentCVR, a multi-agent framework that treats CVR as an active evidence-acquisition task. AgentCVR employs a Master Agent to iteratively coordinate specialized Visual and Audio Agents for targeted evidence extraction. To ensure efficient training, we introduce Script-Simulated RL, which optimizes the agent's policy with LLM-generated semantic scripts and a lightweight text-based simulator, bypassing costly multimodal inference during online exploration. Experimental results on a comprehensive CVR benchmark show that AgentCVR outperforms single-pass baselines and achieves comparable performance to state-of-the-art closed-source systems, particularly in complex cross-video alignment and localization. To ensure reproducibility, our code is available at this https URL.
### Title:
          MARTIAN: A Rendering Framework for Aerial Mars Imagery from HiRISE Orbital Data
 - **Authors:** Dario Pisanti, Georgios Georgakis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aerial navigation on Mars requires vision-based pipelines that are robust to the diverse illumination conditions and terrain morphology of the Martian surface. A key bottleneck for training and evaluating such methods is the scarcity of large-scale, annotated aerial datasets. We present MARTIAN, an open-source Blender-based rendering framework that leverages real HiRISE orbital map products to synthesize realistic aerial views of the Martian terrain under controllable lighting conditions and at varying altitudes. MARTIAN generates observations with accurate pose annotations, directly addressing the scarcity of training data for vision-based navigation on Mars. The framework has been validated through its deployment in concurrent work on map-based localization systems for Ingenuity and future Mars rotorcraft, where synthetically trained deep image matchers were successfully evaluated on real Mars imagery. MARTIAN is publicly available at: this https URL.
### Title:
          EMAG: Differentiable 4D Gaussian Mixture Splatting for EEG Spatial Super-Resolution
 - **Authors:** Alex Lazarovich, Ofir Itzhak Shahar, Gur Elkin, Ohad Ben-Shahar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-density electroencephalography (HD-EEG) enables fine-grained measurement of cortical activity but requires expensive hardware and lengthy setup times, limiting its clinical and research accessibility. We propose EMAG (EEG Mixture of Anisotropic Gaussians), a differentiable framework that reconstructs HD-EEG signals from a sparse subset of low-density (LD) electrodes by representing brain electrical sources as a mixture of anisotropic 4D space-time Gaussians. EMAG places a mixture of multiple Gaussians at each point of a spherical brain grid, each parameterized by a full 4 x 4 precision matrix, enabling anisotropic spatial spreads and explicit coupling between spatial and temporal dimensions. The forward model renders scalp EEG via differentiable Gaussian field contributions at electrode locations, enabling end-to-end training without explicit source localization supervision. We evaluate EMAG on three public EEG benchmarks (Localize-MI, SEED, and SEED-IV) at super-resolution factors of 2x through 8/16x. EMAG outperforms the current state-of-the-art EEG super-resolution method at most super-resolution factors on three standard benchmarks (Localize-MI, SEED, SEED-IV). The explicit Gaussian parameterization further enables direct visualization and interpretability of learned brain source configurations, potentially opening avenues for clinical and neuroscientific applications, such as source localization or biomarker discovery.
### Title:
          Towards Localized and Disentangled Knowledge Editing for Multimodal Large Language Models
 - **Authors:** Leijiang Gu, Zhen Zeng, Feng Li, Xinjian Gao, Zenglin Shi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing methods in Multimodal Knowledge Editing (MKE) have advanced the ability to correct outdated or inaccurate knowledge in Multimodal Large Language Models (MLLMs). However, they exhibit a critical limitation: while effectively modifying target factual pairs, they fail to generalize edits to logically related queries and often cause unintended alterations to unrelated but visually or semantically linked information. We identify and formalize two underlying failure modes causing this issue: Causal Misalignment, which confines edits to the specific sample, and Feature Entanglement, which causes unintended alterations to coupled but irrelevant information. To address these issues, we propose Localized and Disentangled Knowledge Editing (LDKE), a new framework that achieves precise and generalized editing by localizing fact-specific model layers and disentangling target-relevant inputs from irrelevant ones. Our approach introduces a Fast Localization module to identify and update critical layers efficiently, along with a Disentanglement Classifier that routes inputs appropriately to preserve unrelated knowledge. Extensive experiments across various benchmarks and MLLMs demonstrate that LDKE achieves superior performance in propagating edits to related contexts while maintaining high locality.
### Title:
          Masked Diffusion Vision-Language Models for Temporal Action Localization
 - **Authors:** Fengshun Wang, Zhengbo Zhang, Zhigang Tu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal action localization (TAL) requires recognizing the target event and localizing its start and end times precisely in untrimmed videos. Recent vision-language formulations improve semantic reasoning and support language-conditioned outputs, but their autoregressive decoders still generate tokens from left to right, preventing later semantic evidence from revising earlier timestamp predictions. We adapt masked diffusion vision-language models (MDVLMs) to TAL so that semantic tokens and boundary tokens remain editable throughout iterative denoising with bidirectional attention, allowing temporal boundaries and semantic content to be refined jointly. Direct adaptation, however, creates two TAL-specific mismatches: standard masked diffusion training corrupts all positions uniformly at random, but the time tokens are more reliable when enough semantic context is available; and token-level cross-entropy does not reflect temporal IoU. To address these mismatches, we introduce a Planned Training Objective that uses boundary-aware masking and step-weighted reconstruction to rehearse the late recovery of time tokens, together with a Step-Level IoU Reward that provides overlap-aware supervision during denoising. A standard sequence-level cross-entropy term provides the base reconstruction signal. Experiments on ActivityNet-RTL, ActivityNet-1.3, and THUMOS-14 show that MDVLM-TAL improves both temporal reasoning and boundary localization over autoregressive vision-language baselines, with especially strong gains under stricter temporal IoU criteria.
### Title:
          DGSG-Mind: Dynamic 3D Gaussian Scene Graphs for Long-Term Scene Understanding and Grounding
 - **Authors:** Luzhou Ge, Xiangyu Zhu, Jinyan Liu, Xuesong Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integrating open-vocabulary semantic information into dynamic 3D scene representations is essential for long-term embodied scene understanding. However, existing methods often suffer from fragile instance association due to incomplete cross-view cues, while their limited ability to handle object-level topological changes restricts long-term robotic task execution. Moreover, current 3D scene understanding methods either rely on simple feature matching without explicit spatial reasoning or assume offline ground-truth 3D geometry. To address these challenges, we present DGSG-Mind, a hybrid instance-aware 3D Gaussian dynamic scene graph system with an embodied reasoning agent. Our system couples a probabilistic voxel grid with explicit 3D Gaussians to enable robust cross-modal instance fusion and incremental semantic mapping. It handles dynamic changes through Gaussian-based visual relocalization and localized masked refinement guided by geometric-semantic consistency. Built on the instance Gaussian map, DGSG-Mind further constructs a hierarchical scene graph and develops the 3D Gaussian Mind, which integrates structural relations, spatial-semantic information, and visually annotated RoI Gaussian renderings for multimodal reasoning. Extensive experiments show that DGSG-Mind achieves the best zero-shot 3DVG performance among methods operating on self-reconstructed maps, while also delivering strong performance in 3D open-vocabulary semantic segmentation and scene reconstruction. We further deploy DGSG-Mind on real-world robots to demonstrate its target-oriented reasoning and dynamic update capabilities. The project page of DGSG-Mind is available at this https URL
### Title:
          Enriched higher-order multiscale approaches with applications to wave propagation
 - **Authors:** Balaje Kalyanaraman, Felix Krumbiegel, Roland Maier, Siyang Wang
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We consider the numerical solution of partial differential equations with coefficients that are strongly heterogeneous in space. We provide an overview of higher-order localized orthogonal decomposition (LOD) methods for the elliptic setting, including recent advancements, and then present a generalization of the strategy to linear hyperbolic multiscale problems. We address the limitations of earlier constructions for the wave equation, which only achieve second-order convergence in space, independent of the chosen polynomial degree. Building on the methodology of enriched corrections recently developed for parabolic multiscale problems, we motivate and propose an enriched higher-order LOD method for the wave equation. The enriched corrections exhibit exponential decay and can be computed on patches. Under minimal assumptions on the coefficient and standard well-preparedness conditions on the data, we derive a priori error estimates that achieve optimal high-order convergence rates, thereby overcoming the previously observed saturation of the convergence rate. With the fifth-order Rosenbrock-Wanner (ROW) time integrator, we conduct a series of numerical examples to verify our theoretical results. We provide examples showing the optimal spatial convergence of the method including the localization errors for different polynomial orders. We also present examples showing the optimal convergence rates of the time discretization.
### Title:
          Tiny but Trusted: Efficient Vision-Language Reasoning for Time-Series Anomaly Detection
 - **Authors:** Xiaona Zhou, Muntasir Wahed, Tianjiao Yu, Constantin Brif, Ismini Lourentzou
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Vision-Language Models (VLMs) have achieved impressive performance across many tasks, yet prior studies report unsatisfactory performance when applying large language or multimodal models to finding abnormal patterns in sequential data. Public anomaly detection benchmarks typically provide interval annotations but not natural-language rationales, making it difficult to fine-tune VLMs to produce grounded, interpretable decisions. To address this gap, we construct VisAnomBench, a curated benchmark built from public time-series datasets and augmented with high-quality anomaly explanations selected from multiple large VLMs using fine-grained, task-specific rewards. Through fine-tuning on this benchmark, we develop VisAnomReasoner, a parameter-efficient VLM for time-series anomaly detection. Experimental results on VisAnomBench show that VisAnomReasoner achieves more accurate anomaly localization and consistently outperforms all baselines, with improvements of at least 21.23 and 23.87 percentage points in precision and F1, respectively. Additional experiments on the TSB-AD-U benchmark demonstrate strong cross-benchmark generalization, with VisAnomReasoner improving precision and F1 by 9.57 and 13.39 percentage points, respectively.
## Keyword: transformer
### Title:
          A comparative study of transformer-based embeddings for topic coherence
 - **Authors:** Alex Ding, Tarun Rapaka, Willy Rodriguez, Jason Yang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Topic modeling is a branch of Natural Language Processing (NLP) that aims to organize large collections of texts into coherent groups according to word co-occurrence patterns, with Latent Dirichlet Allocation (LDA) remaining one of the most widely used and interpretable probabilistic approaches. Recent advances in NLP, particularly transformer-based language models, offer improved document representations. It is also known that the size of the model (in terms of number of parameters) has a significant impact in the performance of the language models on different pre-defined tasks. In this study, we systematically examine the effect of model size on topic quality by analyzing the performances of seven transformer-based language models (from small models such as MiniLM to large ones such as LLaMA-2) in a BERTopic pipeline on a variety of corpora. Topic quality is evaluated using coherence and divergence metrics following R{ö}der et al. (2015). Our results indicate that model size, ranging from 22 million to 13 billion parameters, has a negligible impact on the quality of the topic, suggesting that smaller models can achieve comparable performance to larger models.
### Title:
          Specialty-Specific Medical Language Model for Immune-Mediated Diseases
 - **Authors:** Veysel Kocaman, Gursev Pirge, Yigit Gul, Ace Vo, Zhenya Nargizyan, David Talby
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extracting detailed clinical information from free-text medical narratives remains a practical challenge for researchers and healthcare systems. Terminology for immune-mediated and infectious diseases is especially inconsistent across sources, which often limits the ability of general-purpose Natural Language Processing (NLP) systems to capture the relevant biomedical concepts with sufficient granularity. We developed a domain-specific Named Entity Recognition (NER) model tailored to identify disease-related entities occurring in immunology and infectious disease contexts. We assembled and manually annotated a dataset of 371 case reports in collaboration with two clinical specialists, defining twelve entity classes covering immune-mediated and infectious conditions as well as related symptoms and clinical descriptors. We evaluated several modeling strategies, including the MedicalNER architecture with multiple healthcare-specific embeddings, a BERT-based token classification model, and zero-shot NER systems. The strongest performance was obtained with a transformer-based model trained on clinical-domain embeddings, which reached an F1 score of 0.89, consistently outperforming baseline and zero-shot approaches. The combination of specialized embeddings and expert annotation proved particularly valuable for capturing nuanced disease terminology and improving generalization across heterogeneous biomedical text. The prompted LLM baseline achieved substantially lower performance under the same evaluation protocol, reflecting difficulties in producing span-consistent outputs for fine-grained entity boundaries despite detailed prompting. The resulting model provides a structured way to analyze case reports and can support downstream tasks such as cohort identification, disease monitoring, and clinical decision support.
### Title:
          One Mask to Rule Them All: On Hidden Facts after Editing and How to Find Them
 - **Authors:** Ali Holmov, Paul Youssef, Nandi Schoots, Christin Seifert
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge editing methods such as ROME and MEMIT update factual associations in transformer models by modifying MLP weights. While evaluated mainly by output behavior, their internal mechanism remains underexplored. We investigate whether edits rely on a common mechanism, regardless of which fact is modified. Despite fact-specific weight changes, we argue that ROME and MEMIT target the same subset of weights critical for maintaining edits. To isolate this subset, we train a compact binary mask over the edited weights. The mask reverses 80% of edits on the training set and over 70% on the test set, confirming that diverse edits share a common functional structure. Our analysis reveals that the mask reverses edits by eliminating overattention in later layers. Additionally, we show that injecting the mask during editing drops editing success from 98% to 38%, demonstrating that this mechanism is necessary for edits to succeed. Our finding that edits suppress rather than overwrite knowledge explains why ROME and MEMIT fail to propagate changes to related facts. The identified common functional subspace informs detection and defense against unwanted edits.
### Title:
          Representation Signatures and Risk-Feedback Alignment in LLM Trading Agents
 - **Authors:** Weicheng Xue
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Finance (q-fin.CP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study behavioral alignment and representation dynamics of large language model (LLM) agents in financial decision environments. Using TradeArena, an auditable trading-agent testbed with risk reports, execution simulation, memory, and replayable trajectories, we analyze how rationales, positions, and interventions evolve under market stress. We find measurable pre-failure signatures: planning embeddings drift from normal-state centroids, fused plan-risk representations separate normal from pre-drawdown states, and manifold diagnostics show effective-rank contraction before failures. To address small-sample and embedding-choice concerns, we use 80 rolling failure anchors across eight LLM trajectories and show that contraction persists across hash, LSA, Transformer, and white-box hidden-state probes. Stress tests with CoT-free target weights, lexical controls, OHLCV noise, and false-audit reports indicate that rationale-level contraction can vanish without rationales, while intent-space contraction may remain; lexical diversity does not collapse; and fused signatures remain informative under noise. We also find that structured risk feedback can act as an external alignment signal without fine-tuning, but not as a universal performance enhancer: true audit feedback improves calibration for some models, return and drawdown for others, and reveals cases where hidden or placebo feedback has higher short-horizon return but weaker alignment diagnostics. Finally, a 51-stock intraday experiment reveals a correlation blind spot: LLM rationales often justify concentrated exposure to coupled assets that the risk layer repeatedly clips, with a rolling Markowitz baseline as a covariance reference. These results support a research claim rather than a profitability claim: auditable risk feedback and representation trajectories reveal when LLM financial reasoning is aligning, drifting, or failing.
### Title:
          The Cognitive Categorical Transformer: Category-Theoretic Inductive Biases for Language Modeling
 - **Authors:** Al Kari
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Cognitive Categorical Transformer (CCT) is a 306M-parameter architecture that augments a pretrained GPT-2 Small backbone with cognitively grounded components derived from category theory and several inspirations from cognitive science. Under a matched-step protocol (215,000 optimizer steps, matched data, matched optimizer and schedule) on WikiText-103, CCT reaches 21.27 validation perplexity, compared with 24.19 for an identically fine-tuned GPT-2 Small baseline. The architecture therefore contributes a 2.92 PPL (12% relative) reduction beyond what in-domain fine-tuning alone provides. A retrain-from-scratch ablation that holds GT-Full simplicial message passing bypassed across the entire seven-phase activation schedule reaches 23.72 PPL, localizing 84% of the architectural improvement (2.45 of 2.92 PPL) to GT-Full. We present the first ablation-validated evidence that simplicial message passing improves language-model perplexity at the 306M-parameter scale on WikiText-103. Published GPT-2 Large reaches 22.05 zero-shot PPL on WikiText-103 with 6.2x more parameters than GPT-2 Small; this paper treats that number as an external published reference, not as the architectural benchmark. Three negative results on consistency-style categorical priors (sheaf smoothing, adjunction round-trip, curvature regularization) and the joint structural-prior result for GT-Full and PrecisionWeightedPP together support an empirical pattern termed the *structure/consistency distinction*, in which categorical priors that add new topology improve language modeling and those that enforce a consistency identity do not.
### Title:
          Feature Geometry of LoRA Adapters: A Sparse Autoencoder Analysis of Representational Divergence in Fine-Tuned Language Models
 - **Authors:** Prasanth K K
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-Rank Adaptation (LoRA) has emerged as a widely adopted approach for adapting large language models, yet the internal representational changes induced by LoRA fine-tuning remain insufficiently understood. In this work, we investigate the geometry of LoRA-induced representations using Sparse Autoencoders (SAEs). We introduce a delta activation framework that isolates the adapter-specific contribution to the residual stream. Using Gemma-2-9B with LoRA ranks 4, 8, 16, and 32, we train adapter-specific SAEs across multiple transformer layers and compare their learned feature spaces with pretrained SAE dictionaries. We evaluate representational alignment using cosine similarity between decoder directions, principal-angle analysis of feature subspaces, and Centered Kernel Alignment (CKA) between activation representations. Across layers and ranks, we consistently observe comparatively weak geometric alignment between LoRA-induced feature dictionaries and pretrained SAE features. Adapter-specific SAEs also reconstruct delta activations more effectively than pretrained SAEs, suggesting that LoRA updates occupy partially distinct representational structure within the residual stream. Additionally, feature density increases with rank and depth, while geometric divergence remains relatively stable across ranks. These findings provide empirical evidence that LoRA fine-tuning can induce feature structures that are not fully captured by pretrained interpretability dictionaries, with implications for mechanistic interpretability, adaptation analysis, and safety auditing of fine-tuned language models.
### Title:
          CosmicFish-HRM: Adaptive Reasoning via Hierarchical Recurrent Mechanisms in Compact Language Models
 - **Authors:** Venkat Akhil Lakkapragada
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models have achieved strong reasoning capabilities, though often at the cost of massive parameter counts and expensive inference. In this work, we explore a different direction: adaptive reasoning depth in compact language models. We present CosmicFish-HRM, a compact language model built around a Hierarchical Reasoning Module (HRM) that dynamically allocates computational effort during inference. Instead of applying fixed computation to every input, the model iterates through high-level and low-level reasoning cycles and learns when to halt based on input complexity. CosmicFish-HRM combines this adaptive reasoning core with modern transformer components including Grouped Query Attention, RoPE, and SwiGLU activations. While the additional reasoning infrastructure introduces overhead at small scale, we hypothesize that this tradeoff becomes increasingly favorable as model size grows and the relative cost of the HRM core diminishes. Our results show that the model learns non-uniform reasoning behavior, allocating different numbers of reasoning steps across tasks and inputs. These findings suggest that adaptive reasoning depth may offer a promising alternative to relying solely on parameter scale for reasoning capability.
### Title:
          The Hamilton-Jacobi Theory of Deep Learning
 - **Authors:** Jose Marie Antonio Miñoza, Erika Fille T. Legara, Christopher P. Monterola
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Dynamical Systems (math.DS); Representation Theory (math.RT); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, training a neural network is identified, exactly, as a search through Hamilton--Jacobi initial-value problems: each gradient step selects the initial data of a viscous Hamilton--Jacobi equation whose Hopf--Cole propagator best fits the observations; at inference, the input is the spatial point at which that solution is evaluated and the initial condition is already encoded in the weights. The correspondence is exact for log-sum-exp layers and structural for broader architectures: residual networks, transformers, and recurrent architectures (RNNs, LSTMs, SSMs) each discretize the same class of Hamilton--Jacobi equations, with architecture-dependent Hamiltonian and viscosity. A single deformation parameter $\varepsilon$ unifies all four perspectives (network, tropical algebra, viscous PDE, convex optimization) in a commutative diagram closed under Lipschitz conditions. Quantitative consequences include: the minimax optimal generalization rate $O(n^{-1/(d+2)})$ for fixed $t$; adversarial robustness controlled by $\varepsilon$; backpropagation as the co-state equation of the Hamiltonian system for residual networks (Pontryagin Maximum Principle); scaling exponents consistent with data intrinsic dimension via PDE quadrature; and a closed-form $O(N)$ influence function (softmax attribution weights $\pi_j$) whose entropy landscape undergoes fold bifurcations as $\varepsilon$ increases, each merging attribution basins.
### Title:
          Attention as In-Context Empirical Bayes: A Two-Stage View via Particle Dynamics
 - **Authors:** Matthew Smart, Soumya Ganguly, Nilava Metya, Alexandre V. Morozov, Anirvan M. Sengupta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Dynamical Systems (math.DS); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study minimal attention-only transformers under all-token corruption and show they admit a two-stage empirical Bayes interpretation. A single attention step computes a kernel-weighted posterior mean with respect to the empirical distribution defined by the context. Depth refines this distribution through particle dynamics (Stage 1), while a long-range skip-connection carries the noisy input as a query for posterior inference (Stage 2), revealing distinct statistical roles for depth and attention residuals. The framework isolates a minimal setting in which the context itself induces a depth-dependent energy landscape governing in-context inference. We show that effective denoising can emerge without an explicit noise schedule: a fixed kernel bandwidth and finite integration horizon suffice, yielding a principled depth-noise relationship. We further establish a posterior-mean recovery guarantee for a class of well-behaved priors, where the empirical estimator converges to the Bayes-optimal predictor under asymptotic conditions. Connecting these dynamics to reverse-diffusion limits, our results provide a statistical interpretation of attention as in-context inference via sample-based posterior estimation, without explicit density modeling.
### Title:
          Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet
 - **Authors:** Adly Templeton, Tom Conerly, Jonathan Marcus, Jack Lindsey, Trenton Bricken, Brian Chen, Adam Pearce, Craig Citro, Emmanuel Ameisen, Andy Jones, Hoagy Cunningham, Nicholas L Turner, Callum McDougall, Monte MacDiarmid, Alex Tamkin, Esin Durmus, Tristan Hume, Francesco Mosconi, C. Daniel Freeman, Theodore R. Sumers, Edward Rees, Joshua Batson, Adam Jermyn, Shan Carter, Chris Olah, Tom Henighan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We demonstrate that sparse autoencoders can extract interpretable features from Claude 3 Sonnet, a production-scale language model, addressing the open question of whether dictionary learning methods scale beyond small transformers. We trained sparse autoencoders with up to 34 million features on the model's middle layer residual stream, using scaling laws to guide hyperparameter selection. The resulting features are multilingual and multimodal (generalizing to images despite text-only training), respond to both concrete instances and abstract discussions of concepts, and can be used to steer model behavior in ways consistent with their interpretations. We find features corresponding to famous entities and locations, as well as more abstract concepts like sarcasm or errors in code. We also identify features relevant to ways in which language models might cause harm--including features representing deception, power-seeking, sycophancy, and bias--and show that these causally influence model outputs when manipulated. Additionally, we conduct analyses of feature interpretability, geometry, and computational function. However, significant limitations remain: our suite of features is incomplete, and we lack rigorous methods for evaluating whether our features faithfully capture model computations.
### Title:
          Orthogonal Negative Guidance in Attention Feature Space for Text-to-Image Generation
 - **Authors:** Jungmin Ko, Jungwon Park, Jimyeong Kim, Changin Choi, Wonseok Lee, Wonjong Rhee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image (T2I) models have become increasingly capable of generating high-quality images. Yet, enforcing the explicit absence of a specified object or attribute remains a fundamentally challenging problem. Existing approaches, including prompt negation, post-hoc editing, and negative guidance, remain insufficient for explicit concept suppression, often failing to remove the target concept or degrading overall image quality. To this end, we propose Orthogonal Negative Guidance in attention feature space, a training-free method that operates in the attention output space of MM-DiT-based T2I transformers. Our method orthogonalizes negative-prompt attention features with respect to positive-prompt features and subtracts only the orthogonal component, suppressing unwanted concepts while preserving desired semantics. Experiments on FLUX-dev and FLUX-schnell show that our method achieves favorable trade-offs between concept suppression, prompt alignment, and image quality. In human evaluation, our method outperforms the second-best baseline by 18.78%. We further show that our method supports multi-concept suppression and adjustable concept suppression.
### Title:
          Phase-Conditioned Imitation Learning with Autonomous Failure Recovery for Robust Deformable Object Manipulation
 - **Authors:** Dayuan Chen, Kai Tang, Yukuan Zhang, Kazuhiro Kosuge, Yasuhisa Hirata
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a phase-conditioned, force-aware framework for robust deformable object manipulation. Standard imitation learning policies such as Action Chunking with Transformers (ACT) rely on a Markovian assumption at inference, causing state aliasing when visually similar observations require contradictory actions and preventing autonomous recovery from execution failures. We address this with a closed-loop hierarchical architecture. A FiLM-conditioned ACT encoder modulates feature extraction based on the current task phase, enabling a single unified policy to produce phase-specific behaviors while sharing action dynamics across phases. A multi-modal phase predictor fusing visual, force, and pose feedback estimates the phase in real time, detecting contact failures that are invisible to vision alone and autonomously triggering recovery trajectories. The system is completed by a hybrid impedance controller for compliant execution and a haptic teleoperation interface for force-aware data collection. Ablation studies show that FiLM-based modulation significantly outperforms both unconditioned and token-level conditioned baselines, and t-SNE analysis confirms that FiLM induces well-separated, phase-specific feature representations. Validated on hanging and removing a T-shirt with dual arms, the closed-loop system improves the hanging success rate from 56\% to 87\% through autonomous error recovery. Code and videos: this https URL
### Title:
          Bridging Semantics and Strategy: A Dual-Stream Graph Network for Equitable Negotiation Forecasting
 - **Authors:** Moirangthem Tiken Singh
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting outcomes in mixed-motive negotiations requires integrating explicit linguistic cues with latent strategic constraints, such as budgets and alternatives. Existing computational models often fail to adapt to varying task structures and may not adequately account for distributive considerations present in historical training data. This study proposes a unified framework to adaptively fuse semantic and strategic signals while incorporating reflective modeling of utility disparities. We introduce the Semantic-Temporal Graph Fusion Network (ST-GFN), a dual-stream architecture that processes textual dialogue with transformer encoders and economic states with Graph Attention Networks, connected via a dynamic gated fusion mechanism. Evaluated on contrasting benchmarks, the linguistically oriented DealOrNoDeal and the strategy-oriented CaSiNo, ST-GFN exhibits strong adaptability. The model dynamically adjusts modality weighting, emphasizing linguistic cues in free-form settings (z ~ 0.97) and increasing reliance on strategic constraints in structured tasks (z ~ 0.73). A fairness-regularized composite loss is incorporated to penalize deviations from ground-truth utility gaps. Results demonstrate a 43.8% reduction in Inequality Discrepancy in high-disparity environments with minimal impact on accuracy, alongside improved performance in high-variance domains. These findings suggest that reflective regularization can enhance both predictive reliability and equitable representation in negotiation forecasting, supporting the design of transparent Group Decision and Negotiation Support Systems (GDNSS).
### Title:
          AnyMo: Scaling Any-Modality Conditional Motion Generation with Masked Modeling
 - **Authors:** Yiheng Li, Zhuo Li, Ruibing Hou, Yingjie Chen, Hong Chang, Hao Liu, Shiguang Shan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conditional human motion generation remains a fundamental challenge in computer vision and robotics. Despite significant progress, current methods are often constrained by fixed modality configurations and task-specific architectures, leaving cross-modal interactions and the scaling laws of multimodal-conditioned synthesis largely underexplored. A key bottleneck is the scarcity of large-scale modality-aligned motion data, limiting generalization across diverse control signals. In this work, we introduce OmniHuMo, a large-scale, high-quality dataset comprising over 5,000 hours of motion and 3.2 million sequences with precisely aligned multimodal annotations (e.g., text, speech, music, and trajectory). Leveraging OmniHuMo, we propose AnyMo, a unified multimodal framework combining a Residual FSQ-based motion tokenizer with a scalable masked modeling transformer, enabling high-quality motion synthesis under arbitrary modality combinations. Extensive experiments show that AnyMo achieves high-fidelity synthesis while offering flexible control over both spatial and stylistic attributes.
### Title:
          KGEdit: Ambiguity-Aware Knowledge Graphs for Training-Free Precise Video Generation and Editing
 - **Authors:** Mingshu Cai, Miao Zhang, Chenghe Yang, Yixuan Li, Osamu Yoshie, Yuya Ieiri
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, training-free video generation has progressed remarkably. However, when handling complex textual instructions, existing methods still suffer from semantic ambiguity, incorrect concept binding, and cross-frame inconsistency. To address these issues, we propose KGEdit, a structured semantic control framework for text-to-video (T2V) diffusion models. Specifically, we first construct an ambiguity-aware knowledge graph (AAKG) to disentangle and disambiguate the input prompt, converting it into four types of structured semantics: identity, relation, attribute, and negative constraints. We then design a structured semantic injection module (SSIM) to inject these semantic signals into key layers of the diffusion Transformer, enabling fine-grained semantic control. In addition, we introduce a temporal-aware semantic control (TASC) module that dynamically schedules semantic objectives according to the stage-wise characteristics of the denoising process, further improving semantic alignment and temporal consistency. Experiments show that KGEdit outperforms existing methods in editing precision and temporal stability, while offering higher efficiency and controllability in text-driven interaction scenarios.
### Title:
          Brain-IT-VQA: From Brain Signals to Answers
 - **Authors:** Roman Beliy, Matias Cosarinsky, Oliver Heinimann, Navve Wasserman, Michal Irani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decoding visual content from fMRI signals recorded while a person views images, and specifically answering questions about the seen images, is a long-standing challenge. While significant progress has been made in recent years in visual question answering (VQA) from fMRI, performance remains limited. Moreover, although recent models can make increasingly accurate predictions, they have rarely been used as tools for understanding the structure of visual representations in the brain. We present Brain-IT-VQA, a framework for visual question answering from fMRI. Building on the Brain Interaction Transformer (Brain-IT), our method decodes language tokens from brain activity and integrates them with a language model to answer visual questions. Our model substantially outperforms previous fMRI-based captioning and VQA approaches. We further introduce NSD-VQA, a new dataset and benchmark for visual question answering from fMRI. Unlike existing image-fMRI VQA datasets, which typically provide only a few broad and weakly controlled questions per image, NSD-VQA provides on average 20 question-answer pairs per image across 20 controlled question categories that disentangle multiple levels of visual understanding. This enables more reliable and interpretable evaluation despite limited fMRI test data. Together, Brain-IT-VQA and NSD-VQA provide both a strong predictive framework and a tool for studying brain representations. Using this benchmark, we quantify which forms of visual and semantic information can be reliably decoded from fMRI responses to natural images. We further analyze the contributions of different brain regions across question types.
### Title:
          Relational Rank Geometry in Transformers: Detecting and Steering Hidden-State Relation Frames
 - **Authors:** Mazen Kobrosly
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer hidden states are often interpreted through local or low-order objects: neurons, sparse features, attention heads, residual-stream directions, or activation patches. This paper studies a complementary object: the rank-indexed geometry of relations among token tuples. I use Plucker sign entropy to test whether r-argument relations leave arity-matched orientation signatures in hidden-state space. Across Llama-family 8B, 70B, and 405B checkpoints, true relation tuples show stronger orientation-sign consistency at the expected rank k=r for r=3,...,6 than scrambled tuples under matched random-control audits. Multi-template audits show that the effects survive surface variation, with all tested 405B rows retaining positive expected-rank margins and 8B/70B retaining positive rows with constructor-specific mixed cells. I then ask whether the same relation geometry can be steered. In an edge-grid clean/corrupt intervention assay over 32 prompts, the row/column scaffold and answer format stay fixed while the YES/NO relation map changes, and the corrupt hidden-state relation frame is patched toward clean or placebo targets. In 70B and 405B, clean-targeted relation-frame paths recover clean-answer behavior and residual relation geometry, while centroid-only and equal-norm controls show negligible recovery. Site/order controls further separate marker-site importance from ordered clean-frame geometry: target clean shape and cross-prompt clean shape recover behavior and residual geometry at the marker interface, whereas corrupt-donor transfer, same-site permutation/reflection, wrong-site clean deltas, centroid-only motion, and equal-norm noise fail or remain far below clean-frame paths. The result is a controlled bridge from relation probing to relation-frame intervention: relation rank geometry can be detected, targeted, and behaviorally validated in transformer hidden states.
### Title:
          Unsupervised Semantic Segmentation Facilitates Model Understanding
 - **Authors:** Xiaoyan Yu, Lisa Mais, Jannik Franzen, Peter Hirsch, Nick Lechtenbörger, Andreas Mardt, Dagmar Kainmüller
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning (SSL) has produced a diverse landscape of vision transformers (ViTs) whose pretrained representations support a wide range of downstream tasks. Towards a better understanding of these models, a body of work has assessed the mechanics of their self-attention as well as the types of information captured across their representations, revealing, for example, stark differences between models trained with contrastive learning (CL) and masked image modeling (MIM). However, these advances in model understanding have not yet fully permeated the broader community, where insights specific to CL models are sometimes generalized to MIM models. To make model understanding straightforward and intuitive for a broad audience, we propose a simple and easily interpretable visualization protocol. Our protocol is based on visualizing unsupervised semantic segmentation results, yet our goal is not to maximize segmentation performance. Instead, it allows us to convey model behaviors that consistently emerge across images. Benchmarking a diverse set of SSL models across layers and representations, we obtain novel insights into distinct positional biases and scaling behaviors, including strong boundary artifacts in DINOv3-Large model tokens. These insights complement and help communicate a range of previous findings. Our protocol further enables a clear visual distinction between positional effects and the closely related but distinct locality bias, which has been studied much more extensively in the literature. The protocol is publicly available on GitHub and we believe it will catalyze further model understanding for a broad community.
### Title:
          FHRFormer: A Self-Supervised Masked Transformer Framework for Fetal Heart Rate Time-Series Inpainting and Forecasting
 - **Authors:** Kjersti Engan, Neel Kanwal, Anita Yeconia, Ladislaus Blacy, Yuda Munyaw, Estomih Mduma, Hege Ersdal
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computational Engineering, Finance, and Science (cs.CE); Machine Learning (cs.LG); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Approximately 10% of newborns require assistance to initiate breathing at birth, and around 5% need ventilation support. Fetal heart rate (FHR) monitoring plays a crucial role in assessing fetal well-being during prenatal care, enabling the detection of abnormal patterns and supporting timely obstetric interventions to mitigate fetal risks during labor. Applying artificial intelligence (AI) methods to analyze large datasets of continuous FHR monitoring episodes with diverse outcomes may offer novel insights into predicting the risk of needing breathing assistance or interventions. Recent advances in wearable FHR monitors have enabled continuous fetal monitoring without compromising maternal mobility. However, sensor displacement during maternal movement, as well as changes in fetal or maternal position, often lead to signal dropout, resulting in gaps in recorded FHR data. Such missing data limits the extraction of meaningful insights and complicates automated (AI-based) analysis. Traditional approaches to handling missing data, such as simple interpolation techniques, often fail to preserve the spectral characteristics of the signals. In this paper, we propose a masked transformer-based autoencoder approach to reconstruct missing FHR signals by capturing both local temporal and frequency components of the data. The proposed method demonstrates robustness across varying durations of missing data and can be used for signal inpainting and forecasting. The proposed approach can be applied retrospectively to research datasets to support the development of AI-based risk algorithms. In the future, the proposed method could be integrated into wearable FHR monitoring devices to achieve earlier and more robust risk detection.
### Title:
          Domino: Decoupling Causal Modeling from Autoregressive Drafting in Speculative Decoding
 - **Authors:** Jianuo Huang, Yaojie Zhang, Qituan Zhang, Hao Lin, Hanlin Xu, Linfeng Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speculative decoding accelerates LLM inference by drafting multiple tokens and verifying them in parallel with the target model. However, its practical speedup is constrained by the trade-off between draft quality and drafting cost: autoregressive drafters model causal dependencies among draft tokens but incur sequential overhead, while parallel drafters reduce drafting cost but weaken intra-block dependency modeling. In this paper, we propose Domino, a speculative decoding framework that decouples causal dependency modeling from expensive autoregressive draft execution. Domino first uses a parallel draft backbone to produce preliminary draft distributions for the entire block, and then applies a lightweight Domino head to refine them with prefix-dependent causal information. To stabilize teacher-forced causal encoding, we further introduce a base-anchored training curriculum that first strengthens the parallel backbone and then gradually shifts optimization toward the causally corrected final distribution. Experiments on Qwen3 models show that Domino achieves up to \(5.49\times\) end-to-end speedup under the Transformers backend and up to \(5.8\times\) throughput speedup under SGLang serving.
### Title:
          Uncertainty-Aware Transfer Learning for Cross-Building Energy Forecasting: Toward Robust and Scalable District-Level Energy Management
 - **Authors:** Shadmehr Zaregarizi, Khashayar Yavari
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling data-driven energy forecasting to district level requires models that can be re-used across buildings with minimal target-domain data and honest uncertainty estimates. We present an uncertainty-aware transfer learning (TL) framework for cross-building energy forecasting based on the Temporal Fusion Transformer (TFT), evaluated on a newly released high-resolution real sub-meter dataset: an educational building at Aalborg University, Denmark (source) and the multi-typology NEST building at EMPA, Switzerland (target). We introduce the Transfer Robustness Index (TRI), an architecture-agnostic metric for quantifying generalization quality across domain gaps. A four-strategy layer-freezing ablation shows that Probe-Only fine-tuning, updating only 455 output-layer parameters out of 806K, achieves the best transfer quality (TRI = 3,097), outperforming full fine-tuning and suggesting that TFT encoders learn transferable temporal representations. Monte Carlo Dropout yields a prediction interval coverage probability of 93.2%, close to the nominal 95% target. A data-scarcity analysis further shows monotonic improvement with increasing target-domain data, providing practical guidance for district energy deployment.
### Title:
          Benchmarking Positional Encoding Strategies for Transformer-Based EEG Foundation Models
 - **Authors:** Ayse Betul Yuce, Sebastian Stober
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalography (EEG) is a widely used non-invasive technique for measuring brain activity in brain-computer interface (BCI) applications. Supervised EEG decoding models often struggle to generalize across tasks, subjects, and datasets, motivating transformer-based EEG foundation models trained with self-supervised learning. Since transformers are permutation-invariant, they require explicit positional information. Unlike textual tokens, EEG electrodes are spatially distributed across the scalp, raising the question of how electrode positions should be encoded in transformer-based EEG models. In this study, we benchmark five positional encoding strategies within the CBraMod backbone and evaluate them under linear probing and fine-tuning protocols on motor imagery classification and emotion recognition. Our results show that no single strategy consistently outperforms across tasks. Spherical Positional Encoding (SPE) yields strong representations for motor imagery but underperforms on emotion recognition, while Asymmetric Conditional Positional Encoding (ACPE) demonstrates more consistent performance across tasks. These findings suggest that the optimal positional encoding strategy is task-dependent, with no universal solution across EEG decoding scenarios.
### Title:
          LFQ: Logit-aware Final-block Quantization for Boosting the Generation Quality of Low-Bit Quantized LLMs
 - **Authors:** Jung Hyun Lee, June Yong Yang, Jungwook Choi, Eunho Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As large language models continue to scale, low-bit weight-only post-training quantization (PTQ) offers a practical solution to their memory-efficient deployment. Although block-wise PTQ is capable of matching the full-precision (FP) baseline on basic language modeling and understanding, its quality is degraded for generative tasks -- especially at longer responses and extended chains of thought, which is critical in boosting task accuracy. We attribute this shortfall to two factors: (i) the omission of the unembedding layer (the LM head) in block-wise optimization and (ii) the reliance on the mean squared error (MSE) objective. Both factors cause the token probability distribution of the quantized model to misalign with that of the FP model, yielding notable accuracy drops on text generation benchmarks. To rectify the discrepancy, we introduce Logit-aware Final-block Quantization (LFQ), a simple yet effective enhancement to block-wise PTQ that quantizes the final Transformer block by minimizing the cross-entropy between the logits of the FP model and those of its quantized counterpart. By aligning token probabilities at the logit level in the final block, LFQ consistently improves the accuracy of complex generation tasks over state-of-the-art block-wise PTQ across diverse model families, while maintaining parity with FP baselines on language modeling and understanding.
### Title:
          GeoMag: Geometric-Aware Video Motion Magnification via State Space Model
 - **Authors:** Kecheng Han, Yuchen Zhang, Bingqing Liu, Boqiang Guo, Wenbin Zheng, Shiyuan Pei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Motion Magnification (VMM) reveals imperceptible dynamics but often suffers from structural inconsistencies under complex geometric transformations. Existing learning-based methods generally face a trade-off between the limited global context of CNNs and the high computational cost of Transformers. In addition, current training protocols, largely dominated by simple linear motion, fail to capture the geometric and imaging complexities encountered in real-world videos. To address these issues, we propose GeoMag, a geometric-aware VMM framework built upon State Space Models to achieve globally consistent motion amplification with linear complexity. We further construct Geo-200K, a large-scale synthetic dataset that introduces rich geometric transformations together with sensor-realistic degradations, improving the diversity and realism of training signals. Extensive experiments on synthetic and real-world benchmarks show that GeoMag consistently outperforms prior methods in visual fidelity and computational efficiency, while producing fewer artifacts and better structural consistency.
### Title:
          Low-Magnification SEM May Suffice: Interpretable Deep Learning for Multi-Scale Fracture-Cause Classification in Zirconia-Toughened Alumina
 - **Authors:** Julian Schmid, Pawel Astankow, Tom Vater, Julius Beck, Robert Cichon, Danny Krautz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Materials Science (cond-mat.mtrl-sci); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable identification of fracture origins in alumina matrix composite hip and knee implants is critical for quality assurance and patient safety, yet current fractographic workflows are time-consuming, partly subjective, and reliant on high-magnification scanning electron microscopy (SEM). We present an interpretable vision-transformer (ViT) workflow for automated classification of fracture causes in an alumina matrix composite (BIOLOX delta, CeramTec GmbH) widely used in total joint replacements. A dataset of 8,493 SEM images (50x-10,000x) was curated from five years of in-production burst and proof tests and annotated into three defect categories defined along the manufacturing chain: green body, hard machining, and material defects. Under severe class imbalance, the fine-tuned ViT reached an accuracy of 0.907 and a macro-F1 of 0.888 in stratified five-fold cross-validation, with a two-stage perceptual-hash/SSIM leakage audit confirming negligible specimen overlap. Notably, performance at low magnification (50x) was comparable to that at high magnification (1k-10kx), indicating that macro-scale features - mirror geometry and hackle line fields - already encode sufficient diagnostic signal. Grad-CAM attributions consistently localised on canonical fractographic cues (mirrors, hackles, pores, machining marks), aligning with established fractographic criteria. Together, these results position interpretable ViTs as a complementary tool for ceramic-implant quality assurance, enabling low-magnification pre-screening and reducing reliance on time-intensive high-magnification inspection.
### Title:
          MIRAGE: Adaptive Multimodal Gating for Whole-Brain fMRI Encoding
 - **Authors:** Abdulkadir Gokce, Badr AlKhamissi, Martin Schrimpf
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in task-optimized neural networks has established encoding models as a powerful tool for predicting brain responses to naturalistic stimuli, yet most existing approaches rely on unimodal representations. The emergence of omni-modal foundation models and rich multimodal neural datasets enables encoding models that jointly integrate visual, auditory, and linguistic information across subjects. We introduce MIRAGE, a brain encoding framework for predicting whole-brain fMRI responses to naturalistic audiovisual stimuli. MIRAGE achieves state-of-the-art performance via a native multimodal backbone and adaptive feature gating across layers. These representations are then combined with a transformer-based brain encoder and a subject-specific linear head over the cortical parcels. Controlled comparisons show that natively multimodal features consistently outperform post-hoc aggregation of independent unimodal features, across architectural levels and backbones. Beyond predictive accuracy, the learned attention weights are directly inspectable to interpret the modality-specific gating profile over the backbone, and each modality traces a distinct anatomical pattern across cortex. Together, these results propose adaptive layer-wise aggregation of natively multimodal features as a generalizable, interpretable, and accurate approach for whole-brain encoding.
### Title:
          Parameter-Efficient Subspace Decoupling ViT for Mitigating Multi-Task Negative Transfer in Histological Scoring
 - **Authors:** Youhan Huang, Jiajun Li, Yilin Fang, Shuai Wang, Chuheng Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Histological scoring is essential for diagnosing Non-Alcoholic Fatty Liver Disease (NAFLD), yet its automation remains challenging due to the high annotation cost and negative transfer among the strongly correlated NAFLD Activity Score (NAS) indicators in multi-task learning. To address this issue, we propose a subspace-decoupled multi-task Vision Transformer (ViT) that integrates lightweight task-specific Adapters with orthogonality-based constraints. This design constructs independent feature subspaces for steatosis, ballooning, and inflammation, effectively reducing task interference while retaining shared representations. We further construct a curated multi-task mouse NAFLD histology dataset with expert annotations for all NAS components. Experimental results demonstrate that the proposed method improves multi-task stability and generalization with substantially reduced computational cost compared to training separate single-task models. The code and the curated dataset have been prepared and will be made publicly available upon acceptance to support reproducibility.
### Title:
          STAP: A Shuffle-Tokenized App Predictor with Ultra Long Context for Vocabulary-Free Mobile App Prediction
 - **Authors:** Chengyu Fan, Hang Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting the next mobile application a user will launch is essential for intelligent device resource management and proactive assistance. Existing models rely on fixed app vocabularies, which prevents them from generalizing across different app ecosystems. Many also depend on user-specific knowledge, which complicates deployment in cold start scenarios. We propose STAP, a Transformer-based model that eliminates the need for a fixed vocabulary. STAP replaces true app identities with randomly reassigned virtual indices via a shuffle mechanism, and compensates for discarded semantic information by processing behavioral sequences with an ultra-long context design. A theoretical analysis shows that, given a sufficiently long context, the predicted distribution converges to the correct one despite the anonymity of the mapping. Experiments on two datasets from different continents demonstrate that STAP achieves strong cross-dataset zero-shot prediction accuracy -- a setting where all existing fixed-vocabulary methods are inherently inapplicable -- while its cold start performance within each dataset remains competitive with leading models. Furthermore, we introduce a deployment strategy that enables the model to retain a sufficiently long context during continuous inference while keeping latency within acceptable bounds.
### Title:
          Treatment-Conditioned Diffusion for Forecasting Neurodegenerative Disease Progression
 - **Authors:** Danylo Boiko, Viktoriia Mishkurova
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting the progression of neurodegenerative diseases, such as Parkinson's disease, is essential for effective long-term planning and personalized therapeutic intervention. Existing systems typically produce scalar clinical scores that ignore the rich structure of longitudinal neuroimaging, while traditional generative approaches suffer from a loss of anatomical details and blurring subtle progression patterns. To address this, we introduce a novel treatment-conditioned diffusion framework that predicts high-fidelity future brain states by conditioning the generative process on patients' screening DaTscan images and levodopa equivalent daily dose over one year. The pipeline uses a Transformer-based encoder to represent non-linear, time-dependent pharmacological dynamics and optimizes generation through a multi-weight region-of-interest mask that focuses on biologically critical areas. Experimental evaluation shows that our framework maintains sharp anatomical boundaries and significantly improves clinical fidelity relative to the baseline, achieving 14.0% lower MSE, 7.2% lower MAE, and 4.9% higher SSIM.
### Title:
          SwInception -- Local Attention Meets Convolutions
 - **Authors:** David Hagerman, Roman Naeem, Jakob Lindqvist, Carl Lindström, Fredrik Kahl, Lennart Svensson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse vision transformers have gained popularity as efficient encoders for medical volumetric segmentation, with Swin emerging as a prominent choice. Swin uses local attention to reduce complexity and yields excellent performance for many tasks but still tends to overfit on small datasets. To mitigate this weakness, we propose a novel architecture that further enhances Swin's inductive bias by introducing Inception blocks in the feed-forward layers. The introduction of these multi-branch convolutions enables more direct reasoning over local, multi-scale features within the transformer block. We have also modified the decoder layers in order to capture finer details using fewer parameters. We demonstrate a performance improvement on eleven different medical datasets through extensive experimentation. We specifically showcase advancements over the previous state-of-the-art backbones on benchmark challenges like the Medical Segmentation Decathlon and Beyond the Cranial Vault. By showing that the existing inductive bias in Swin can be further improved, our work presents a promising avenue for enhancing the capabilities of sparse vision transformers for both medical and natural image segmentation tasks. Code and pre-trained weights can be accessed at this https URL.
### Title:
          Genetically Aligned Patient Representations Improve Hematological Diagnosis
 - **Authors:** Muhammed Furkan Dasdelen, Fatih Ozlugedik, Ilaria Looser, Rao Muhammad Umer, Christian Pohlkamp, Carsten Marr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal alignment of histopathology encoders with transcriptomic and genomic data has been shown to significantly improve performance in downstream diagnostic tasks. Hematological cytology is unique in that visual single-cell evaluation is often paired with cytogenetics and molecular genetics for blood cancer diagnosis. In this study, we present a framework to align single white blood cell images with chromosomal aberrations (karyotype) and somatic mutations from targeted gene panels. Our training strategy follows a two-stage approach: (i) self-supervised, vision-only pretraining of a transformer aggregator using an iBOT head on a cohort of over 1500 patients, and (ii) genetic alignment via supervised contrastive loss on acute myeloid leukemia patients. Our genetically aligned patient encoder improves hematological diagnostic tasks, outperforming slide-level histopathology foundation models. Additionally, the model provides off-the-shelf retrieval capabilities for diseases and genetic alterations. Incorporating genetic data into patient encoders increases the quality of patient representations, providing a framework that aligns with clinical diagnostic workflows and paves the way for future multimodal hematology-specific AI. The code and model weights are available at this https URL.
### Title:
          Improving Adversarial Robustness of Attribution via Implicit Regularization
 - **Authors:** Amir Mehrpanah, Matteo Gamba, Hossein Azizpour
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adversarial robustness of attributions is a fundamental requirement for reliable explainability in deep learning, yet existing approaches typically rely on computationally expensive explicit regularization. In this work, we show that attribution robustness can arise implicitly from the learning dynamics of standard stochastic gradient descent. We theoretically motivate this effect through connections between parameter-space and input-space curvature, and validate it across architectures, datasets, and attribution methods, with negligible computational overhead. In contrast, we prove that such robustness gains often does not transfer to attention-based attribution under softmax normalization, due to inherent entropy constraints, and we validate this limitation experimentally. Finally, we show that replacing softmax attention with kernel-based attention restores the robustness gains in transformer models. Our results highlight learning dynamics as a principled and practical mechanism for robust explainability, and reveal fundamental limitations of attention-based attribution under normalization.
### Title:
          Adapting Multilingual Embedding Models to Turkish via Cross-Lingual Tokenizer Surgery and Offline Distillation
 - **Authors:** M. Ali Bayram, Banu Diri, Savaş Yıldırım
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sentence embeddings are a foundational component for semantic search, clustering, classification, and retrieval-augmented generation. This paper presents embeddingmagibu-200m, a Turkish-focused sentence embedding model that produces 768-dimensional L2-normalized vectors and supports an 8,192-token context window, far exceeding the 512-token limit of earlier BERT-based Turkish encoders. Instead of full pretraining, an efficient three-stage adaptation pipeline is introduced: (1) construct a Turkish-optimized multilingual tokenizer with a 131,072 vocabulary by pruning redundant tokens from the teacher's vocabulary and incorporating multilingual tokens via frequency analysis on a 40-language corpus, (2) clone a teacher embedding model while preserving transformer backbone weights and initializing a compatible embedding table for the new vocabulary via mean-composition token mapping, and (3) perform offline embedding distillation from precomputed teacher vectors using a cosine similarity objective over a balanced 40-language Wikipedia corpus. The resulting student model contains approximately 200M parameters and trains in roughly four hours on a single GPU by avoiding online teacher inference during training, at a total cost of $5-$20. Empirically, Pearson/Spearman correlations of 77.55%/77.45% are obtained on STSbTR, surpassing the 300M-parameter teacher model (73.84%/72.92%). On TR-MTEB (26 tasks), a mean score of 63.9% is achieved (7th out of 26 models), providing a competitive cost-quality trade-off with 33% fewer parameters than the teacher. To facilitate reproducibility and downstream use, all artifacts are released including model weights, tokenizer files, precomputed embedding datasets, and open-source cloning and distillation tooling.
### Title:
          Low-Overhead Receiver Design for Data-Dependent Superimposed Training via Deep Learning
 - **Authors:** Xinjie Li, Xingyu Zhou, Jing Zhang, Chao-Kai Wen, Xiao Li, Shi Jin
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Superimposed pilot (SIP) transmission improves spectral efficiency by eliminating the dedicated pilot overhead required in orthogonal pilot (OP)-based schemes. However, SIP suffers from severe pilot-data coupling, which leads to a critical performance-complexity bottleneck at the receiver. To address this issue, this paper proposes a low-overhead transmission framework that revitalizes data-dependent superimposed training (DDST) with enhanced interference mitigation strategies. First, for quasi-static block-fading channels, an enhanced DDST receiver is developed to achieve non-iterative pilot-data decoupling by exploiting data-dependent algebraic structures. Second, to overcome the sensitivity of conventional DDST to channel variations and symbol misidentification in fast time-varying environments, a mix transmission scheme is developed. By strategically applying DDST to a subset of resource elements, the proposed scheme combines the interference-free transmission property of OP with the zero-pilot-overhead advantage of SIP, thereby improving demapping reliability and interference suppression. Furthermore, under the proposed mix scheme, a Vision Transformer-based neural receiver is designed to capture the orthogonal structure between pilots and perturbation-bearing data, as well as the underlying channel correlations, thereby relaxing the stringent quasi-static assumption required for interference disentanglement. Simulation results demonstrate that the proposed framework achieves significant performance gains in the low-to-medium SNR regime under time-varying channels while providing superior computational efficiency compared with state-of-the-art SIP receivers.
### Title:
          FRUC: Feedforward Dynamic Scene Reconstruction from Uncalibrated Collaborative Driving Views
 - **Authors:** Yihang Tao, Yu Guo, Zhengru Fang, Haonan An, Yuguang Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FRUC, a feed-forward 3D Gaussian splatting framework for dynamic scene reconstruction from uncalibrated collaborative driving views. Existing multi-agent reconstruction frameworks are often hindered by rigid prerequisites, demanding precise spatial calibration and slow per-scene optimization. In this paper, we rethink this task by conceptualizing a distributed multi-vehicle network as a spatio-temporally unstructured ego-centric multi-camera system, where the core challenge lies in enhancing ego-centric occluded geometry through collaboration without degrading the ego's accurately observed visible geometry, while preserving reconstruction efficiency. For efficient reconstruction, FRUC is built upon a visual grounded geometric Transformer backbone to enable one-shot, calibration-free inference from a flexible number of multi-vehicle views. To achieve non-destructive geometric supplementation under uncalibrated cross-agent misalignment, FRUC first introduces an ego-centric causal occlusion field that explicitly derives occlusion evolution as latent priors by modeling agent-wise spatio-temporal correlations. Guided by these occlusion priors, it further formulates cross-agent integration as a deterministic residual denoising process via zero-initialized injection, turning challenging cross-agent fusion into bounded residual learning for robust collaborative blind-spot completion. Through extensive evaluations on the real-world V2XReal and UrbanIng-V2X datasets, FRUC is shown to be a new state-of-the-art for the scene reconstruction of dynamic collaborative driving environments, significantly outperforming existing methods in both rendering quality and efficiency.
### Title:
          Give it Space! Explicit Disentangling of Positional and Semantic Representations in Encoders
 - **Authors:** Pierre-Antoine Lequeu, Camille Barboule, Benjamin Piwowarski
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positional encoding (PE) underpins how permutation-invariant Transformers represent sequence order, yet how positional information is processed and stored remains poorly understood. Modern PE methods such as RoPE still struggle on tasks such as long-context understanding or retrieval \cite{chen-etal-2025-hope}. Hence, a better understanding of the internal positional mechanism could help design better PE. Building on evidence that positional and semantic signals occupy nearly orthogonal subspaces in trained Transformers, we modify an encoder Transformer to process three explicitly disentangled streams: semantic, absolute positional (AP) and relative positional (RP), and confine the masked-language-modeling (MLM) objective to the semantic stream. This decoupling enables a clean mechanistic study and yields three take-aways. (1) The isolated AP subspace spontaneously collapses into a low-frequency two-dimensional manifold that captures the structure of the document; (2) Attention heads specialize into structure and semantic-oriented groups, with RP exclusively supporting the latter; (3) Standard positional encodings do not robustly retain macroscopic structure: RoPE and RP only weakly encode it, and entangled AP loses it in the final layers under MLM pressure. The disentangled approach preserves positional encoding, which improves linguistic representation on 49 of the 65 linguistic phenomena of the Flash-Holmes probing benchmark.
### Title:
          GenEraser: Generalizable Video Object Removal via Balanced Text-Mask Guidance and Decoupled Locator-Preserver
 - **Authors:** Yuqing Chen, Lin Liu, Haisu Wu, Xiaopeng Zhang, Yaowei Wang, Yujiu Yang, Qi Tian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video object removal frequently struggles to simultaneously eliminate target objects and their associated physical effects (e.g., smoke, reflections, light, and ripples) in out-of-domain scenarios due to complex spatiotemporal ambiguities. While existing methods primarily rely on spatial masks, they often fail to capture weakly correlated effects, and the potential of explicit textual guidance remains underexplored. Furthermore, a fundamental optimization conflict exists in removal models between high-level semantic generalization and precise pixel-level background preservation. To address these challenges, we propose GenEraser, a novel framework for generalized and high-fidelity video object and effect removal. First, we introduce a Multi-Conditional Mixture-of-Experts (MC-MoE) paired with Bipartite Text guidance to fully exploit the multimodal priors of Diffusion Transformers, significantly enhancing the identification of complex effects. Second, a Learnable Deep ``CFG'' Fusion mechanism (LD-CFG) is developed to adaptively balance the relative dominance of mask and textual conditions across diverse scenarios. Finally, we propose a Decoupled Expert Architecture, comprising a Locator and a Preserver, to mitigate the inherent trade-off between semantic generalization and pixel alignment. Extensive experiments demonstrate that our GenEraser surpasses recent state-of-the-art approaches, achieving significant quantitative improvements (e.g., $2.16$ dB and $1.44$ dB on the ROSE Benchmark and VOR-Eval, respectively) while maintaining exceptionally robust generalization in open-world scenarios. this https URL
### Title:
          Robust and Generalizable Safety Steering for Text-to-Image Diffusion Transformers
 - **Authors:** Zihao Xue, Yan Wang, Zhen Bi, Long Ma, Zhonglong Zheng, Zeyu Yang, Bingyu Zhu, Longtao Huang, Jie Xiao, Jungang Lou
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers have become a powerful backbone for text-to-image generation, but their layered and cross-modal generation process makes safety control fundamentally different from prompt-level filtering or output-level detection. Harmful semantics may be weakly expressed in text representations, progressively bound to visual latents, and finally entangled with rendering dynamics. As a result, safety steering at a fixed layer can be unstable, and a steering mechanism learned from known risks may not transfer reliably to a shifted target risk domain. We propose SafeDIG, a safety steering framework that formulates DiT safety adaptation as position-aware sparse feature transfer. SafeDIG first constructs Sparse Autoencoders over functionally distinct DiT intervention positions and uses robustness-aware pre-training routing to prioritize intervention sites that are expected to remain stable under source-target risk shift. It then separates transferable safety features from domain-specific activation geometry by freezing the SAE encoder as a reusable sparse safety dictionary and adapting only the decoder to the target-domain activation manifold. During inference, SafeDIG combines Blend and Repel operations to steer unsafe activations toward transferred safety manifolds or away from harmful sparse directions. Experiments on FLUX.1 Dev and Stable Diffusion 3.5 Large show that SafeDIG consistently reduces target-domain and overall unsafe generation rates while preserving source-domain safety and image quality.
### Title:
          Towards Consistent Video Geometry Estimation
 - **Authors:** Zhu Yu, Jingnan Gao, Runmin Zhang, Lingteng Qiu, Zhengyi Zhao, Rui Peng, Yichao Yan, Kejie Qiu, Siyu Zhu, Si-Yuan Cao, Hui-Liang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents ViGeo, a feed-forward foundation model for recovering spatially dense and temporally consistent geometry from video sequences. Built upon a plain transformer architecture without task-specific architectural modifications, ViGeo supports streaming, full-sequence, and long-video inference within a unified model. The key design is dynamic chunking attention, which exposes the model to both bidirectional and causal temporal contexts during training and allows it to adapt its attention pattern at test time without retraining. To improve supervision quality, we further introduce a completion-based data refinement framework. This framework trains a video depth completion teacher that conditions on sparse and noisy annotations and exploits video/multi-view context to produce dense, temporally coherent, and geometrically reliable training targets. Beyond depth and point maps, ViGeo also predicts surface normals within the same framework. Trained solely on public datasets, ViGeo achieves state-of-the-art performance across online, offline, and long-video depth estimation, surface normal estimation, and video point map estimation.
### Title:
          Chess-World-Model: A 10M-Game Benchmark for Exact State Tracking from Chess Move Sequences
 - **Authors:** Benjamin Walker, Terry Lyons
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models require state tracking, which is the ability to maintain a correct latent state across action sequences. Existing benchmarks are often synthetic or language-based, limiting their value as tests of structured state updates in realistic domains. We introduce Chess-World-Model, a large-scale state-tracking benchmark built from 10 million real chess games, where models predict the exact board state reached after a sequence of legal moves. Alongside a held-out real-game split, we include an out-of-distribution split from uniformly random legal play, which tests whether models learn the transition rules rather than shortcuts from common human positions. Prior theoretical and empirical work has shown that Transformers struggle to state-track, while input-dependent linear RNNs require expressive state-transition matrices to do so. We therefore benchmark a causal Transformer, block-diagonal SLiCE, Mamba-3, and Gated DeltaNet with negative eigenvalues under a matched interface and training protocol. The recurrent models strongly outperform the Transformer at 3 and 8 million parameters. Real-game performance saturates above 18 million parameters, but the random-uniform split remains discriminative up to 40 million, exposing failures otherwise hidden by scale. Additionally, ablations show that less expressive state-transition mechanisms reduce performance on the out-of-distribution split for all three recurrent models. Together, these results establish Chess-World-Model as a practical large-scale benchmark for state tracking that exposes failures model scale would otherwise conceal.
### Title:
          Large Depth Completion Model from Sparse Observations
 - **Authors:** Zhu Yu, Zhengyi Zhao, Runmin Zhang, Lingteng Qiu, Kejie Qiu, Yisheng He, Siyu Zhu, Zilong Dong, Si-Yuan Cao, Hui-Liang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents the Large Depth Completion Model (LDCM), a simple, effective, and robust framework for single-view metric depth estimation with sparse observations. Without relying on complex architectural designs, LDCM generates metric-accurate dense depth maps using a transformer. It outperforms existing approaches across diverse datasets and sparse observations. We achieve this from two key perspectives: (1) leveraging existing monocular foundation models to improve the quality of sparse depth inputs, and (2) reformulating training objectives to better capture geometric structure and metric consistency. Specifically, a Poisson-based depth initialization strategy is first introduced to generate a uniform coarse dense depth map from diverse sparse observations, providing a strong structural prior for the network. Regarding the training objective, we replace the conventional depth head with a point map head that regresses per-pixel 3D coordinates in camera space, enabling the model to directly learn the underlying 3D scene structure instead of performing pixel-wise depth map restoration. Moreover, this design eliminates the need for camera intrinsic parameters, allowing LDCM to naturally produce metric-scaled 3D point maps. Extensive experiments demonstrate that LDCM consistently outperforms state-of-the-art methods across multiple benchmarks and varying sparsity levels in both depth completion and point map estimation, showcasing its effectiveness and strong generalization to unseen data distributions.
### Title:
          Can AI Weather Models Predict Beyond Two Weeks? A Quantitative Benchmark and Analysis of Long Rollouts
 - **Authors:** Fanny Lehmann, Firat Ozdemir, Yun Cheng, Torsten Hoefler, Sebastian Schemm, Benedikt Soja, Siddhartha Mishra
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While AI weather models excel at short-to-medium range forecasts (up to 15 days), they frequently suffer from ill-defined "instabilities" when rolled out over longer horizons. This work addresses the lack of a formal taxonomy by categorizing these failures into three distinct regimes: blow-up, drift, and loss of seasonality, through year-long rollouts of nine state-of-the-art AI weather models. Our analysis reveals that stability hinges on the treatment of small spatio-temporal scales: unstable models amplify high-frequency energy, while stable models act as denoisers when noise is added to their inputs. Far from reducing these models to mere stochastic parrots, our findings highlight that stable models generate unique weather trajectories, conditioned on the initial state. We verify our findings through ablation studies on architectural design choices, conducted using state-of-the-art Vision Transformer (ViT) AI weather model architectures.
### Title:
          A Dual-Path Architecture for Scaling Compute and Capacity in LLMs
 - **Authors:** Markus Frey, Behzad Shomali, Joachim Koehler, Mehdi Ali
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped transformers apply a shared block multiple times and have emerged as a parameter-efficient route to scaling compute in language models. However, at fixed FLOPs a looped model has strictly less capacity than a baseline transformer. We propose a novel dual-path block that can flexibly scale compute, the number of sequential operations applied to a hidden state, and capacity, the parameters available at a single step. For this we expose both axes as parallel pathways within a single layer: a deep sublayer re-applied K times with shared parameters, and a wide sublayer with an enlarged feed-forward network applied once. Independent per-token gates combine both axes and allow detailed per-token routing analyses. We show that across two FLOP budgets, our dual-path model surpasses iso-FLOP matched models on language modeling and downstream evaluations, while using fewer parameters than the baseline at matched FLOPs. The learned gates are directly interpretable and show systematic per-token allocation with function words and lexical content trend wide, while punctuation, symbols, and arithmetic tokens trend deep.
### Title:
          Déjà View: Looping Transformers for Multi-View 3D Reconstruction
 - **Authors:** Alessandro Burzio, Tobias Fischer, Sven Elflein, Qunjie Zhou, Riccardo de Lutio, Jiawei Ren, Jiahui Huang, Shengyu Huang, Marc Pollefeys, Laura Leal-Taixé, Zan Gojcic, Haithem Turki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent feed-forward 3D reconstruction transformers have scaled to over a billion parameters, following the broader trend of increasing model capacity in computer vision. Yet emerging evidence suggests that contiguous transformer layers often behave like repeated applications of similar operations, and multi-view reconstruction transformers refine their predictions progressively across decoder depth. We posit that model depth partially buys iteration, paid for inefficiently in unique parameters, and instead make that iteration explicit in architecture. Our model, DéjàView, applies a single looped transformer block recurrently to per-view features for K refinement steps. Trained once, it exposes K as an inference-time compute knob, matching or outperforming substantially larger feed-forward baselines across five reconstruction benchmarks spanning indoor, outdoor, object-centric, and driving scenes, while using a fraction of their parameters and comparable or lower compute. Importantly, the same looped block formulation outperforms an otherwise identical variant with independent per-step parameters under matched training data and compute, suggesting that explicit iteration is not merely a compute-efficient substitute for capacity but a stronger inductive bias for multi-view 3D reconstruction.
### Title:
          Anti Mode-Collapse in Mean-Field Transformer via Auxiliary Variables
 - **Authors:** Masaaki Imaizumi, Masanori Koyama, Noboru Isobe, Kohei Hayashi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We use a mean-field-based transformer model to theoretically investigate how auxiliary variables, such as positional encoding, prevent mode collapse of self-attention mechanisms. The use of mean-field transformers to analyze the properties of self-attention mechanisms has garnered significant attention in recent years due to their ability to comprehensively analyze token interactions. However, analysis of this simple model suggests that mode collapse, where token distributions degenerate to a single point, occurs during long inferences (i.e., many layers), indicating a discrepancy with reality. This study investigates this mean-field transformer model and demonstrates that the introduction of auxiliary variables, such as positional encoding, acts as a counterforce against theoretical mode collapse. Specifically, we show that in the theoretical scheme, the energy-maximizing distribution does not degenerate to a single point; instead, it is characterized by a pushforward of the auxiliary variable distribution, thereby avoiding concentration in the Dirac measure. Our main examples are the positional encoding and the fixed prompt insertion treated as a parallel auxiliary-variable mechanism. Furthermore, we demonstrate that positional encoding and prompt insertion possess universality of representation in the limit, meaning that the limit distribution of inference can exactly represent a wide class of distributions. We also analyze several key properties of positional encoding and metastability, and validate our theoretical results through mathematical experiments.
### Title:
          Beyond 3D VQAs: Injecting 3D Spatial Priors into Vision-Language Models for Enhanced Geometric Reasoning
 - **Authors:** Chun-Hsiao Yeh, Shengyi Qian, Manchen Wang, Yi Ma, Joseph Tighe, Fanyi Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) often struggle with robust 3D spatial reasoning. Prevailing methods that rely on fine-tuning with 3D visual question-answering (VQA) datasets may overfit dataset-specific biases, while integrating specialized 3D visual encoders is often inflexible and cumbersome. In this paper, we argue that genuine spatial understanding should emerge from learning fundamental geometric priors, not only from high-level VQA supervision. We propose GASP (Geometric-Aware Spatial Priors), a framework that injects these priors directly into the LLM's transformer layers. GASP employs a small correspondence head, applied as a deep supervision signal across all layers, and is trained with a dual objective leveraging ground-truth geometry from large-scale video scenes: a contrastive loss on ground-truth point correspondences enforces 2D view-invariance, while a depth consistency supervision resolves 3D geometric ambiguities. Our analysis first provides a diagnostic showing that standard VLMs' internal correspondence matching accuracy is very low (often below 5%). We then demonstrate that our training substantially improves this behavior, boosting peak layer-wise correspondence to over 70% and maintaining over 85% temporal robustness while baselines remain below 5%. These internal improvements translate to significant gains on downstream spatial benchmarks including +18.2% on All-Angles Bench and +29.0% on VSI-Bench, all without training on any 3D VQA data. Our findings indicate that learning from fundamental geometric priors is a promising and generalizable pathway towards VLMs with more reliable 3D spatial reasoning.
### Title:
          Do Language Models Track Entities Across State Changes?
 - **Authors:** Zilu Tang, Qiao Zhao, Gabriel Franco, Derry Wijaya, Aaron Mueller, Sebastian Schuster, Najoung Kim
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Entity tracking (ET), the ability to keep track of states, is a fundamental skill that underlies complex reasoning. An increasing amount of work investigates how transformer language models (LMs) solve entity binding $\textit{without}$ state changes. However, there is limited understanding of how non-toy LMs address ET problems of realistic difficulties expressed in natural language. To this end, we investigate the mechanisms underlying ET in more complex scenarios featuring multiple state-changing operations. We find that LMs do not incrementally track world states across tokens or query-relevant states across layers, but simply aggregate relevant information in parallel at the last token when the query becomes evident. We further investigate mechanisms of individual operations ($\texttt{PUT}$, $\texttt{REMOVE}$, $\texttt{MOVE}$) to characterize this non-incremental ET mechanism. Surprisingly, LMs implement the $\texttt{REMOVE}$ operation with a fragile global suppression tag; this global removal mechanism predicts various failure modes that we confirm behaviorally. We provide a mechanistic solution of nullifying this tag to partially address this issue. Overall, our findings reveal that LMs solve a fundamentally sequential task using a non-sequential strategy. More broadly, our work illustrates how behavioral and mechanistic analyses can fruitfully interact. Behavioral results inform mechanistic hypotheses, and insights from mechanistic analyses help build stronger behavioral evaluations by predicting failure modes missing from existing evaluations.
### Title:
          Digitally enriching a screening population for pancreatic cancer using routine blood-based measures and clinical histories
 - **Authors:** Chris Varghese, Leo Y. Li-Han, Richa Bisht, Ellen Larson, Frank Lee, Ryan M. Carr, Tanios S. Bekaii-Saab, Shounak Majumder, John D. Halamka, Mark Truty, Ajit H. Goenka, Hojjat Salehinejad, Cornelius A. Thiels
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Earlier detection of pancreatic cancer is key to enabling wider access to curative treatment and reducing cancer deaths; however, screening is presently not viable. Latent indicators of pathology are evident in an individual's disease and blood test trajectories and may predict the development of pancreatic cancer. Longitudinal sequences of coded diagnoses and blood test values accrued by patients throughout their clinical interactions were used to train a custom Transformer-based neural network with a multi-head attention mechanism to predict risk of pancreatic cancer with a multi-year lead time and risk-stratify populations for targeted screening. The cohort comprised 6,017 adults with pancreatic cancer and 177,081 controls (overall median age 75, 45% female) with median 12 years (interquartile range 6.9-16.2) of medical history prior to pancreatic cancer diagnosis. External validation via leave-one-site-out, out-of-sample testing predicting pancreatic cancer 1-, 2-, and 3-years prior to diagnosis demonstrated mean area under the receiver operating characteristic of 0.837 (95% confidence interval 0.827-0.848), 0.797 (95% confidence interval 0.782-0.813), and 0.760 (95% confidence interval 0.745-0.776), respectively. Estimated pancreatic cancer risks were well-calibrated (calibration plot slope 1.08, intercept of -0.077; Brier score 0.025), and a Bayesian population pancreatic cancer prevalence update allows estimated cancer risk outputs to be transportable across settings. At testing, a screening threshold of >3.3% risk of pancreatic cancer in 1-year offered a diagnostic odds ratio of 18.2. Our work therefore lays the foundation for a first population-level digital enrichment tool to widen access to curative-intent management of pancreatic cancer.
### Title:
          Statistical Embeddings for Similarity, Retrieval, and Interpretable Alignment of Numeric Tabular Datasets
 - **Authors:** M. Ross Kunz, John Merickel, Keith Wilson
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Applications (stat.AP); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Numeric tabular datasets are the dominant data format in scientific practice, yet large language models lack native mechanisms for representing numeric datasets in a meaningful way across heterogeneous feature spaces. Existing approaches either target predictive modeling over individual datasets, which requires a shared set of variable definitions, or lack mechanisms for interpretable cross-dataset alignment. The proposed methodology characterizes numeric tabular datasets through structured exploratory data analysis descriptors, embeds those descriptors into a shared vector space using a pretrained sentence transformer, and quantifies cross-dataset similarity via Canonical Correlation Analysis (CCA). Furthermore, a penalized formulation of CCA is applied to recover sparse, interpretable variable-level correspondences between datasets, identifying which statistical descriptors or variable-level quantities drive cross-dataset alignment without requiring shared variable names or feature conventions. Differential privacy is optionally applied to the descriptor set prior to embedding, supporting deployment in sensitive data contexts without requiring access to raw observations at time of comparison. The methodology is evaluated across 15 datasets spanning general-purpose benchmarks, materials informatics, and nuclear-grade graphite characterization. Results demonstrate a total P@1 score of 0.9, with known nearest-neighbor retrieval and cluster structure remaining robust across embedding ablations and differential privacy budgets. The proposed framework provides a principled pathway for integrating heterogeneous numeric data into retrieval-augmented generation pipelines while preserving statistical context, with direct applications to data-driven algorithm selection and simulation model initialization for unknown datasets.
### Title:
          In-Context Reward Adaptation for Robust Preference Modeling
 - **Authors:** Zhenyu Sun, Zheng Xu, Ermin Wei
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement Learning from Human Feedback (RLHF) typically relies on static reward models to align Large Language Models with human preferences. However, human values are inherently diverse and heterogeneous, and a single reward model often lacks the robustness required to generalize to unseen preference domains. While existing multi-reward frameworks attempt to address this, they are often restricted to a fixed set of known domains and fail to adapt to unseen human distributions without costly retraining. In this work, we propose In-Context Reward Adaptation, a transformer-based framework designed to model diverse and unseen human preferences on the fly. By leveraging the in-context learning capabilities of transformers, our approach adaptively infers the underlying reward structure from a small set of preference demonstrations. We demonstrate that while a standard transformer architecture is insufficient for this task by characterizing an asymptotic bias to the ground-truth, incorporating human response time as an auxiliary input signal enables the model to successfully adapt to preferences from previously unseen domains. Our findings show that this approach provides a more robust foundation for preference modeling, allowing for the representation of heterogeneous rewards and preference distribution shift, and offering a scalable path toward more flexible human-AI alignment.
### Title:
          Veda: Scalable Video Diffusion via Distilled Sparse Attention
 - **Authors:** Shihao Han, Hao Yang, Xinting Hu, Xiaofeng Mei, Yi Jiang, Xiaojuan Qi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling Diffusion Transformers to generate high-resolution, long videos is constrained by the quadratic cost of self-attention, and existing sparse attention methods degrade under high sparsity. We show empirically that generation quality is determined not by the sparsity ratio itself, but by how well the sparse mask aligns with the tile-wise geometry of full attention. Based on this insight, we propose Veda, a distilled sparse attention framework that formulates tile selection as an explicit reconstruction problem from full attention. Veda integrates statistics-aware tile scoring with head-aware tiling to reduce estimation error and structural mismatch, enabling aggressive sparsity. A hardware-efficient tile-skipping kernel converts theoretical sparsity into practical wall-clock speedups. Experiments on large video diffusion models, including Waver and Wan2.1, demonstrate substantial acceleration with no noticeable degradation in generation quality. To generate 720P 10-second videos on Waver-T2V-12B, Veda achieves a 5.1$\times$ end-to-end speedup and a 10.5$\times$ self-attention speedup, reducing attention overhead from 92% to 50%. Notably, the gains increase with sequence length, indicating that Veda scales favorably with spatiotemporal resolution across models.
### Title:
          NeuROK: Generative 4D Neural Object Kinematics
 - **Authors:** Chen Geng, Guangzhao He, Yue Gao, Yunzhi Zhang, Shangzhe Wu, Jiajun Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven approaches have revolutionized 3D vision, enabling transformers to effectively reconstruct and generate static 3D objects. However, generating simulative 4D dynamics -- realistic temporal deformations of static objects under various physical conditions -- remains challenging and often ad hoc, despite its importance in building comprehensive 3D world models. Most existing methods assume a predefined physical model and use system identification to estimate parameters, restricting these methods to specific categories and small-scale datasets. We propose that these restrictions can be overcome by learning a data-driven kinematic state parameterization for object-centric physical systems. Specifically, we learn both a latent space representing all possible states of the object and a decoder that maps any sampled latent to a plausibly deformed shape of the object. We refer to this parameterization as Neural Object Kinematics (NeuROK), and learn a transformer-based encoder-decoder model on a curated large-scale 4D dataset. This formulation and the learned model significantly simplify the generation of simulative dynamics since we only need to consider the dynamics within a low-dimensional latent space from the Lagrangian mechanics' perspective in classical physics. We demonstrate the effectiveness and generality of this neural simulation framework across diverse dynamic object types, showing clear advantages over prior works. Project page: this https URL
## Keyword: autonomous driving
### Title:
          ReasonBreak: Probing Vulnerabilities in Reasoning-Enabled Vision-Language-Action Models for Autonomous Driving
 - **Authors:** Mohammadreza Teymoorianfard, Jean-Philippe Monteuuis, Jonathan Petit, Amir Houmansadr
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models with integrated reasoning have been proposed for end-to-end autonomous driving, assuming a tight coupling between reasoning and trajectory generation. However, the robustness of such systems under realistic input perturbations remains largely unexplored. We show that these models are highly vulnerable to realistic input perturbations, achieving up to 89% attack success rate (ASR) on reasoning and up to 72% on trajectory manipulation in closed-loop simulation, leading to increased collision rates and degraded safety metrics. Using NVIDIA's recent Alpamayo models as representative industry-developed VLAs, we conduct the first systematic black-box study of reasoning-enabled VLA models under realistic textual input corruptions, evaluating their impact on reasoning and driving behavior. We introduce a reasoning-aware evaluation framework capturing both semantic and structural aspects of reasoning, along with safety-centric measures. We also introduce a benchmark for evaluating attacks and defenses on reasoning-trajectory interactions in autonomous driving. Our results highlight the need for rigorous evaluation and improved defenses to ensure the safety of reasoning-enabled VLA systems in autonomous driving.
### Title:
          Multi-Resolution End-to-End Deep Neural Network for Optimizing Latency-Accuracy Tradeoff in Autonomous Driving
 - **Authors:** Qitao Weng, Heechul Yun
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latency-accuracy tradeoffs are fundamental in real-time applications of deep neural networks (DNNs) for cyber-physical systems. In autonomous driving, in particular, safety depends on both prediction quality and the end-to-end delay from sensing to actuation. We observe that (1) when latency is accounted for, the latency-optimal network configuration varies with scene context and compute availability; and (2) a single fixed-resolution model becomes suboptimal as conditions change. We present a multi-resolution, end-to-end deep neural network for the CARLA urban driving challenge using monocular camera input. Our approach employs a convolutional neural network (CNN) that supports multiple input resolutions through per-resolution batch normalization, enabling runtime selection of an ideal input scale under a latency budget, as well as resolution retargeting, which allows multi-resolution training without access to the original training dataset. We implement and evaluate our multi-resolution end-to-end CNN in CARLA to explore the latency-safety frontier. Results show consistent improvements in per-route safety metrics - lane invasions, red-light infractions, and collisions - relative to fixed-resolution baselines.
### Title:
          CityGen: Structure-Guided City-Style Synthesis for Cross-City Autonomous Driving
 - **Authors:** Zezhong Qian, Zhao Yang, Lu Tan, Zhihao Yan, Weiyi Hong, Haizhuang Liu, Yawei Jueluo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems are commonly trained and evaluated within limited geographic regions, which hinders their scalability when deployed in new cities. However, significant domain shifts in appearance, road topology, and traffic patterns often cause severe performance degradation under cross-city deployment. Existing approaches based on domain adaptation, data augmentation, or synthetic data generation typically rely on labeled target data, city-specific annotations, or task-specific designs, limiting their scalability and effectiveness for holistic evaluation. In this paper, we introduce CityTransfer-Bench, a geographically disjoint benchmark for evaluating cross-city generalization across perception, segmentation, and planning, and propose CityGen, a diffusion-based generative framework that performs zero-label city adaptation via HD-map-conditioned synthesis guided by city-level visual prompts. Extensive experiments demonstrate that CityGen consistently improves cross-city robustness across multiple tasks, establishing a scalable and label-efficient foundation for generalizable autonomous driving.
### Title:
          Supercharging Thermal Gaussian Splatting with Depth Estimation
 - **Authors:** Manoj Biswanath, Chenxin Cai, Hannah Schieber, Daniel Roth, Benjamin Busam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient and robust 3D scene representation is crucial in autonomous driving, robotics, and related fields. While RGB images provide valuable content for 3D reconstruction, other modalities like thermal or depth can enable additional information on the environment. Lately, novel view synthesis methods like 3D Gaussian Splatting have started using multiple modalities to further boost their performance. But fusing or combining multimodal data can make the process slower and can bring in additional challenges. Therefore, our project aims to use single modality based on thermal infrared domain, by removing the reliance on visible light as much as possible. This single modality can be expected to be faster as it does not rely on multimodal data. We propose a method, Thermal-to-Depth Gaussian Splatting (TDg), that uses only thermal images and depth estimation in its architecture to derive the radiance fields. Our TDg method outperforms the MSMG (Multiple Single-Modal Gaussians) baseline in most cases on our test datasets, RGBT-Scenes and ThermalMix. On average, the rendering quality metrics such as learned perceptual image patch similarity (LPIPS), structural similarity index measure (SSIM), and peak signal-to-noise ratio (PSNR) of TDg are 1.12%, 0.034%, and 0.01% better than the baseline MSMG values. It also reduces the training time significantly, by 12 mins 47 secs (55% improvement). Overall, our method is successful in deriving these thermal radiance fields, which can ultimately have several applications, such as identifying heat sources critical in surveillance, search or rescue operations, and industrial inspections where temperature is widely used to monitor machines.
