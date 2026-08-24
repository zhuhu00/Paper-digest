# Showing new listings for Monday, 24 August 2026
## Keyword: SLAM
### Title:
          Hadith computational science in the age of large language models: a critical narrative review
 - **Authors:** Md. Ashraful Haque (1), Riasat Islam (1 and 2) ((1) Greentech Apps Foundation, United Kingdom, (2) Queen Mary University of London, London, United Kingdom)
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We examine how hadith computational science is being reshaped by transformer models, retrieval-grounded pipelines, and large language models (LLMs). Recent reviews document growth in the literature, but they do not yet provide a critical account of which advances are methodologically robust, which remain benchmark-bound, and which unresolved problems still limit scholarly use. We address this gap through a critical narrative review that combines critique of existing reviews, paper-level appraisal of representative original studies, and synthesis of Islamic scholar and domain-expert perspectives on authenticity, authority, and responsible use. We find uneven progress. Data resources have expanded, segmentation tasks have matured, narrator and source-verification problems are better formalized, and LLM-assisted workflows now support corpus-scale enrichment, multilingual access, and grounded evaluation. At the same time, progress remains constrained by narrow corpora, weak benchmark comparability, synthetic-to-real transfer gaps, narrator identity resolution, preprocessing fragility, limited reproducibility, and sparse expert-grounded validation. We show that important gaps lie beyond dominant benchmarks: non-canonical and obscure corpora, commentary and explanatory literature, cross-source links with Qur'an and seerah, and fiqh-facing evidence support. We argue that hadith computation should be assessed less as isolated model performance than as an evidence infrastructure problem requiring knowledge integration, provenance, and expert supervision. On this basis, we define a research agenda for making the field methodologically stronger and more useful to Islamic scholarship.
### Title:
          Ansari: A Retrieval-Grounded Islamic AI Assistant -- Architecture, Deployment, and Lessons from 140,000 Conversations
 - **Authors:** M Waleed Kadous, Amr Elsayed, Abdullah Al Nahas, Ashraf Haress
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 General-purpose large language models (LLMs) are increasingly used to answer religious questions, but for Islamic content they carry two serious risks: factual fabrication (inventing Qur'anic verses or hadith) and subtle value misalignment. We present Ansari, a deployed, retrieval-grounded Islamic AI assistant that has handled more than 140,000 conversations across 25+ languages since June 2023. Ansari is built around an agentic retrieval loop: a tool-using language model issues searches against authenticated Islamic corpora -- the Qur'an, hadith collections, a multi-volume jurisprudence (fiqh) encyclopedia, and exegetical (tafsir) sources -- and answers only on the basis of what it retrieves, with citations attached for verification. We describe the system's architecture (the agent loop, the retrieval tools, the corpora, and the system prompt that encodes editorial and theological policy), its multi-platform deployment (web, mobile, WhatsApp, and as a Model Context Protocol server and an Agent Skill), and what 140,000 real conversations reveal about how Muslims actually use such a tool. We report results on several complementary evaluations -- zero-shot performance on accredited institutional exams, a human-rated validation during Ramadan, and two independent, externally run benchmarks on which Ansari currently tops the public IslamicMMLU leaderboard ahead of frontier models and is competitive on Islamic legal reasoning (IslamicLegalBench) while strongly resisting false premises -- and draw out lessons that generalize beyond Islam to any faith- or values-sensitive deployment of LLMs: grounding is necessary but not sufficient, the system prompt is a theological as much as a technical artifact, and the absence of community in how models are formed remains a hard gap.
## Keyword: odometry
### Title:
          Learning-Based Measurement-Robust Control Barrier Functions for Obstacle Avoidance under State Estimation Error
 - **Authors:** Nicholas Rober, Yixuan Jia, Jonathan P. How
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety filters are an effective tool for enforcing constraints in safety-critical systems, but most existing methods assume perfect state information, which is rarely available in practice. Recent work has begun to close this gap by developing filtering mechanisms that are robust to state estimation error, but these methods can still exhibit safety violations or overly conservative behavior as estimation error grows. Focusing on obstacle avoidance, we develop two new control barrier function (CBF) formulations: drift-measurement-robust (DMR)-CBFs and neural measurement-robust (NMR)-CBFs. The DMR-CBF augments the standard CBF condition with an inner optimization over the worst-case uncertainty in the drift dynamics, improving robustness to estimation error. This DMR-CBF then supervises a pretraining phase for the NMR-CBF, which replaces the inner optimization with a learned term. The NMR-CBF is subsequently finetuned through differentiable trajectory rollouts, yielding a filter that achieves empirical safety comparable to the DMR-CBF while reducing both conservativeness and computational cost. We provide theoretical analysis of the DMR-CBF along with numerical results on a planar double integrator and a 12D quadrotor, where both proposed approaches prevent collisions while other robust methods either fail or are overly conservative. Finally, we deployed the NMR-CBF on a Unitree Go2, enabling successful navigation of an obstacle field under odometry errors that caused a standard CBF to collide.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Multi-Modal Traffic Sign Detection with Semantic Attributes for Autonomous Driving
 - **Authors:** Meda Lazar, Sourab Sridhar, Shashwata Gupta, Alexandra Tripcea, Varun Ravi, Senthil Yogamani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable traffic sign detection is a prerequisite for the global deployment of autonomous driving systems, where regulatory compliance and road safety depend on perceiving signs correctly across regions, ranges, and weather conditions. Despite recent progress, vision-based methods continue to face three fundamental limitations: poor cross-regional generalization due to high diversity across countries, degraded performance on small-object detection at long ranges (traffic signs occupy as little as $10{\times}10$ pixels at 200m), and fragile temporal tracking under the strongly non-linear perspective distortion that occurs as a vehicle approaches a sign. In this paper, we address the problem of robust, long-range, region-agnostic traffic sign perception by combining camera and Light Detection and Ranging (LiDAR) sensing. We present a multi-modal detection framework whose Intensity-Aware Deformable Fusion module aligns retro-reflective LiDAR cues with camera features, anchoring detection on geometric invariants rather than region-specific visual appearance. We further introduce a dual motion-model tracker that explicitly accounts for non-linear perspective transformations during vehicle approach, substantially improving temporal consistency over linear motion assumptions. Additionally, we develop a semantic attribute classification pipeline that estimates occlusion level, readability, sign embeddedness, and road relevance, providing actionable context to downstream planning. Extensive evaluation on our dataset, spanning 60+ countries and 2,500+ hours of driving data, shows that the proposed pipeline achieves an Object Miss Ratio (OMR) of 0.49% across 221,068 evaluation sequences, demonstrating globally generalizable traffic sign perception in commercial-grade autonomous driving systems.
### Title:
          Socialized Division and Collaboration: Rethinking Class-Incremental Learning under Optimization Conflicts
 - **Authors:** Xinjie Yao, Zhihe Fan, Yunqi Zhu, Jiaqi Zhou, Dengyu Zhao, Zhoupeng Guo, Yan Fan, Guosong Jiang, Pengfei Zhu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Class-incremental learning is commonly instantiated as a single-model paradigm, where a unified model sequentially adapts to an unbounded stream of sessions. While effective under mild distributional shifts, this formulation becomes strained when successive sessions induce incompatible optimization directions, leading to destructive interference and catastrophic forgetting. We argue that such forgetting reflects a structural limitation of enforcing heterogeneous learning dynamics within a single parameter space. Motivated by social solidarity theory, we propose Socialized Division and Collaboration (SDC) as a reformulation of continual learning that decomposes session learning across specialized models in response to optimization conflicts, while enabling coordinated collaboration. To support this formulation with a principled allocation mechanism, we introduce an energy-based session-model compatibility criterion grounded in Helmholtz free energy, which guides adaptive session allocation and model evolution under conflicting objectives. This framework integrates session assignment, model evolution, and collaborative inference into a unified pipeline, offering an alternative to monolithic continual learning formulations and highlighting a broader design principle for learning under persistent optimization conflicts.
### Title:
          The Coastline as a Structural Constraint: Harnessing Scene Geometry for Autonomous Surface Vessel Localization
 - **Authors:** Derek R. Benham, Joshua G. Mangelson
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coastal environments contain rich, largely unexploited geometric structure capable of providing globally referenced localization cues. In this work, we present two complementary localization frameworks that exploit shoreline and water-surface geometry for GPS-denied autonomous surface vessel localization. The first framework leverages LiDAR observations of the water surface to estimate roll, pitch, and heave (vertical motion), while recovering global position and heading through direct registration of shoreline observations against a satellite-derived coastline map. The second framework relies solely on passive imagery to detect the shoreline and horizon through semantic segmentation. Using the proposed coastal scene geometry, shoreline distance is inferred from monocular imagery. Shoreline observations are accumulated into short-duration local submaps, registered against the same satellite-derived coastline map, and fused within a hierarchical factor graph. Evaluated across three real-world coastal datasets, the LiDAR pipeline consistently improves trajectory accuracy over standard baselines, while the monocular architecture maintains bounded long-term drift. In addition, we establish that modern zero-shot foundation models can reliably extract shoreline observations across diverse coastal environments. Together, these results demonstrate that coastal geometry provides a powerful and dependable source of globally referenced information for GPS-denied maritime localization.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          bikiDATA: A Python Library to Query and Explore Large-Scale RDF Datasets
 - **Authors:** Etienne Posthumus, Sven Hertling, Dilek Yargan, Harald Sack
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While knowledge graphs offer unparalleled data flexibility, the semantic gap between RDF triples and the native objects used by software engineers remains a significant barrier to entry. Developing knowledge-graph-backed applications typically requires deep expertise in SPARQL and complex data-mapping layers. To lower this threshold, we present bikiDATA: a high-performance storage solution and a Python library engineered for the modern software developer. Unlike traditional wrappers, bikiDATA abstracts the complexities of the RDF data model into a developer-friendly API that feels native to the Python ecosystem. Beyond standard SPARQL support, the system provides a comprehensive suite for production-grade applications, including integrated full-text search, knowledge graph embeddings, and visual similarity search. Already in use in ongoing projects at FIZ Karlsruhe, bikiDATA reduces integration complexity, improves scalability, and enhances query performance. The source code and executable demo notebook are publicly available at this https URL.
### Title:
          Amortized Bandwidth Learning for Kernel Density Estimation under Logarithmic Score
 - **Authors:** Junyi Liang, Hailiang Du
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Kernel density estimation converts finite samples into probability densities, but its performance depends critically on bandwidth selection. Classical selectors prescribe the sample-to-bandwidth rule analytically or asymptotically, or solve a new optimization for each sample. An amortized framework is proposed that instead learns this mapping across a distribution of density-estimation tasks by optimizing the logarithmic score. A truncated-and-renormalized bounded-support formulation enables stable learning across heterogeneous tasks, while affine standardization allows a selector trained on a single reference interval to transfer across bounded intervals. Experiments under Gaussian sampling, a multi-family benchmark, and randomized Gaussian-mixture training show that the amortized selector consistently and substantially outperforms Silverman's rule, the Sheather--Jones selector, and least-squares cross-validation, with especially large gains in small and heterogeneous samples. Finite Gaussian mixtures provide a generic training mechanism supported by their $L^1$ approximation property. Selectors trained in this way generalize strongly across different density structures, allowing the same trained selector to be applied directly to finite samples from unknown densities without specifying or fitting a distributional family. This combination of broad applicability and strong empirical performance makes the framework attractive for a wide range of applications in which finite samples or ensembles must be converted into continuous probability densities.
### Title:
          Testing and Evaluation of Agentic AI Systems In Military Command and Control
 - **Authors:** Ulysse Richard, Heather Frase, Sarah Cao, Di Cooke, Sebastian Kwon, Adrianna Tan
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic AI systems are being procured for military command and control (C2) under public commitments to rigorous testing and human oversight. Whether such commitments can be discharged depends on their supporting assurance case, which requires three elements: claims specifying the conditions for acceptability, evidence bearing on those claims, and an argument connecting the two. Through a structured review of 240 documented Testing and Evaluation (T&E) practices, spanning eight evaluation dimensions and three lifecycle stages, we identify eight assumptions that established methods make about their test article, grouped into four clusters: system specifiability, stability, composability, and supervisability. Agentic properties weaken all eight assumptions. This erosion affects the argument connecting evidence to claims, not the claims or evidence themselves. As a result, test results may satisfy process requirements, but they do not warrant the inference from tested to fielded behavior. We derive ten assurance claims for the first three assumption clusters and assess whether current and emerging methods can address each, mapping operational consequences through five C2 scenarios. Supervisability is identified but not assessed here, since evidencing it depends on system stability results and human factors T&E methods beyond the present scope. The documented record does not support broad claims about system-level behavior, but narrower claims remain recoverable in principle, contingent on mature methods: bounded mission envelopes, trajectory-grounded correctness, executable runtime constraints, and characterized run-to-run variance. Part of the evidentiary burden shifts into deployment, making the determination to field a continuing act. Where evidence cannot be generated, the residual uncertainty can be governed through defined expiry conditions and assigned ownership.
### Title:
          Fluid-Dynamic Interference Modeling for LEO Mega-Constellations: A Spatiotemporal Kinetic Field Approach
 - **Authors:** Wen-Yu Dong, Weiwei Jiang, Song Zhao, Rui-Si Han, Qi Bi, Sheng Chen
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low Earth orbit (LEO) mega-constellations create a highly non-stationary interference environment that cannot be accurately captured by static stochastic-geometry snapshots. This paper proposes a kinetic interference field framework that models the constellation as a compressible fluid shell evolving under orbital kinematics. By mapping satellite motion into a continuum flux field, we derive a hydrodynamic conservation law for the aggregate interference and obtain a closed-form expression for the time-varying outage probability via moment matching. The analysis reveals that high-latitude ``interference surges'' are a direct consequence of orbital compression and boundary flux, rather than random anomalies. Numerical validation against ephemeris-driven Monte Carlo simulations confirms the accuracy of the framework across time evolution, latitude, and design parameters. Leveraging the closed-form model, we further show that the conventional $90^{\circ}$ polar-orbit design is not universally outage-optimal. Instead, an inclination angle near $79^{\circ}$ at low altitude achieves a favorable trade-off between coverage continuity and geometric interference isolation. The proposed framework provides a tractable analytical tool for interference-aware 6G non-terrestrial network (NTN) design.
### Title:
          Aristotelian Manifolds: Leveraging Platonic Perceptual Features for Backpropagation Free Rapid Concept Learning
 - **Authors:** Michael Karnes, Alper Yilmaz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper formalizes and systematically characterizes Aristotelian Manifolds, a generalized structural framework built upon the Platonic Representation Hypothesis. We position high-capacity foundation models as universal perceptual filters and conduct a comprehensive layer-wise investigation to map how knowledge is functionally synthesized within these latent subspaces. Across diverse architectural paradigms and multi-domain datasets, we rigorously chart the interplay between network depth, dimensionality reduction, and distance metrics. Our characterization reveals that semantic maturation does not follow a singular, monotonic path; instead, different data domains exhibit highly distinct geometric response profiles, characterized by intermediate mound-like peaks for specialized clinical modalities and sigmoidal plateaus for natural visual tasks. By profiling the exact coordinates where these manifolds achieve peak representational efficiency, we establish a predictable taxonomy for layer selection and feature compression. Ultimately, this systematic characterization demonstrates that mapping the internal geometry of frozen representations provides a robust, backpropagation-free, and interpretable framework for understanding and exploiting foundation model latent spaces.
### Title:
          Fuzzy-MoE: Interpretable Regime-Conditioned Expert Routing for Non-Stationary Multivariate Time Series Forecasting
 - **Authors:** Lan Guo, Jie Xiao, Zhao Su, Jun Shen, Haoran Li, Weixia Ma, Qingguo Zhou, Binbin Yong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In non-stationary multivariate time series, different variables and samples often exhibit heterogeneous latent dynamic states, while existing deep forecasting models usually compress them into a unified end-to-end mapping, leading to suboptimal modeling of time-varying dynamics and limited interpretability regarding which forecasting mechanism is activated under different latent states. To overcome these limitations, we reformulate time series forecasting as a unified framework of latent temporal state identification and interpretable expert routing, and propose Fuzzy-MoE, a fuzzy logic-based dynamic Mixture-of-Experts model. Fuzzy-MoE consists of multiple parallel expert mapping networks and a dual-view fuzzy router. By jointly exploiting local convolutional dynamics and global segmented statistics, the router infers latent temporal states and computes expert activation strengths through learnable Gaussian membership functions, enabling explicit IF-THEN rule-based expert selection. This fine-grained routing strategy allows different variables within the same sequence to activate different experts, effectively capturing heterogeneous temporal dynamics while improving model interpretability. Experimental results on multiple public time series benchmark datasets show that Fuzzy-MoE significantly outperforms mainstream forecasting methods in forecasting accuracy. Moreover, fuzzy memberships and rule activations provide interpretable routing diagnostics, demonstrating the effectiveness of the proposed framework in both forecasting performance and mechanism transparency. Unlike traditional MoE models that use black-box routing, Fuzzy-MoE`s routing is based on clear, interpretable fuzzy rules. This makes the expert selection transparent and traceable.
### Title:
          KoViDoRe: Korean Visual Document Retrieval
 - **Authors:** Yongbin Choi, Yongwoo Song, Mujeen Sung
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in multimodal retrieval have improved the ability to retrieve information from visually rich documents such as PDFs and reports. However, existing benchmarks remain largely centered on English and provide limited coverage of Korean visual documents with complex structures. Furthermore, most existing Korean resources primarily evaluate single-page retrieval, failing to capture realistic scenarios that require evidence aggregation across multiple pages. To address these gaps, we introduce KoViDoRe, a benchmark for Korean visual document retrieval. The dataset is constructed from publicly available Korean documents with diverse layouts, including tables, figures, and multi-column structures. We develop a multi-stage data curation pipeline consisting of structured document parsing, synthetic query generation using both summary-based and context-based strategies, and relevance mapping with human verification. Using KoViDoRe, we evaluate a wide range of multimodal retrieval models and observe that current models struggle to effectively handle Korean visual document retrieval, particularly in settings involving structured content and diverse query types. Motivated by this finding, we further curate a large-scale training dataset, Ko-VDR Train Public, to support the development of retrieval models tailored to Korean visual documents. Together, KoViDoRe and Ko-VDR Train Public provide a unified benchmark and training resource for Korean visual document retrieval.
### Title:
          Triangulation-Free Bundle Adjustment with Graduated Non-Convexity for Camera Pose Refinement from Coarse Priors
 - **Authors:** Nikolaos Kyriazis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mobile AR frameworks attach a metric pose prior to every casual phone capture, and turning it into reconstruction-grade poses cheaply on CPU is the step before novel-view synthesis. The least a refiner owes an accurate prior is not to make it worse. The workhorse refiner does. On 15 ScanNet++ iPhone room captures, COLMAP triangulation plus prior-seeded bundle adjustment degrades an accurate ARKit prior in all 15, 0.55 degrees to 0.74 degrees by scene-mean. The cause is the seeding. Structure is triangulated from the prior before anything is optimized, so the prior's error is baked into the structure the optimizer trusts. We remove the triangulation. Every keypoint owns a scalar depth along its own back-projected ray and each match contributes two symmetric cross-projection residuals, so structure is re-expressed at every iterate. The same solve holds the room prior at 0.57 degrees and never fails in 330 perturbed room runs, and at object scale reaches 0.265 degrees/1.80 mm from a prior at 0.456 degrees in a median of 10 s per scene on one CPU, against 2.5 GPU-hours for a learned refiner. Because no structure is committed, the objective also admits graduated non-convexity, which measures how deep the defect goes. Classical refinement collapses past 1-2 degrees of prior error, barely beyond a real ARKit prior, and no classical refinement arm survives 32 degrees. Ours recovers 425 of 425 runs through 16 degrees/80 mm and 85% at 32 degrees/160 mm, and perturbed rooms through 32 degrees. Nominal object-scale accuracy is on par rather than better, on a benchmark at its own noise floor, where classical bundle adjustment is a strong baseline absent from the literature. One scene fails for every solver already at zero perturbation. Re-mapping from position priors matches us in the prior's frame but discards it, so it cannot exploit a prior worth keeping or be warm-started.
## Keyword: localization
### Title:
          Grounded-Exo2Ego: Structured Semantic Grounding for Robust Exocentric-to-Egocentric Video Generation
 - **Authors:** Shengze Wang, Michael Stengel, Tianye Li, Seonwook Park, Amrita Mazumdar, Koki Nagano, Alex Trevithick, Shalini De Mello
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating egocentric video from a single exocentric video is an emerging and important topic for AR/VR and physical AI. Compared with conventional novel view synthesis, exo-to-ego generation is a significantly harder task because the standard geometric conditioning becomes highly unreliable under extreme view changes and large unobservable regions. We present Grounded-Exo2Ego, a principled framework that addresses these challenges at both the architectural and data levels. Architecturally, Grounded-Exo2Ego is a dual-branch video diffusion model that couples a geometric anchoring branch, which conditions the generation on the rendering of a 3D reconstruction, with a novel semantic grounding branch, which goes beyond the prevailing geometry-based approach and improves quality by synthesizing challenging regions based on object-level context. Additionally, we found that the overlooked issue of camera-reconstruction misalignment severely undermines exo-to-ego learning. We thus introduce a camera re-localization algorithm that resolves this issue and substantially improves quality across all metrics. We further develop a fully automated synthetic data engine that generates and renders rigged 3D characters in procedurally generated environments. Evaluation on the challenging EgoExo4D dataset shows that our method outperforms recent state-of-the-art approaches by large margins across all metrics. Detailed ablations validate improvements from each of our contributions at both the data and architectural level.
### Title:
          Keep Your Friends Close, and the Right Neighbours Closer: Disaster-Conditioned Kernel-Regularized Graph Attention for Building Damage Classification
 - **Authors:** Fuad Hasan, Chul Min Yeum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Disaster damage is spatial: buildings rarely fail in isolation. Yet using spatial context for damage classification remains surprisingly underexplored, and many pipelines still rely primarily on per-building appearance cues even when the dominant uncertainty is spatially structured. Complicating matters, the right neighbourhood is not the same across events. Floods, hurricanes, and wildfires can exhibit very different clustering behaviour, making spatial reasoning valuable but easy to misuse - naive context aggregation can improve visual coherence while oversmoothing boundaries or propagating structured errors. We study this tension on xBD (the dataset used in the xView2 challenge) in a controlled post-localization, classification-only setup: each building is represented by a pre/post combined (PPC) patch cropped from the provided polygons, and spatial context is modelled with GPS-derived building graphs. Our approach keeps local evidence "close" by preserving strong spatial relationships in disaster damage patterns, while bringing only the right neighbours "closer" through a disaster-type-conditioned graph model that injects a learnable multi-scale spatial kernel prior into attention, allowing the effective neighbourhood scale to adapt across disaster types rather than being learned as a single global smoothing rule. To discourage coherence-by-smoothing, we add a residual de-correlation loss that penalizes positive Moran's~I in prediction residuals. We evaluate the method under event and dataset shift with a leave-one-event-out (LOEO) protocol on xBD and cross-dataset transfer from xBD to Ida-BD. The model improves macro-F1 and substantially reduces residual spatial autocorrelation under zero-shot event shift, indicating better use of spatial context rather than naive smoothing and enabling more reliable transfer to unseen events within known disaster types.
### Title:
          Zero-Shot Color Image Manipulation Localization via Noise Residual Artifact Pattern Analysis
 - **Authors:** Edgar Gonzalez-Fernandez
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital cameras embed device-specific artifacts into every acquired image through demosaicing, in-camera post-processing, and lossy compression. These traces constitute a forensic signal that can be exploited to assess image authenticity. Existing passive methods rely predominantly on the green channel of the Bayer residual, discarding the correlated information available in the remaining color channels and typically requiring training data or device enrollment. This work proposes a zero-shot, training-free blind image manipulation localization pipeline that estimates a reference artifact pattern directly from the noise residual of a single suspect image, without assuming a fixed filter configuration, color layout, or block period. The pipeline incorporates a principled denoiser selection criterion based on the acquired-to-interpolated noise variance ratio, a block-level correlation analysis against the estimated reference pattern, and a two-component Gaussian Mixture Model scoring stage that produces a pixel-level tampering probability map. An ablation study evaluates the impact of denoiser choice and block size on localization accuracy, and comparisons against state-of-the-art passive methods demonstrate the competitiveness of the proposed zero-shot approach.
### Title:
          RECOUNT: Reference-guided Counting with Synthetic Visual Exemplars
 - **Authors:** Adriano D'Alessandro, Ali Mahdavi-Amiri, Ghassan Hamarneh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided zero-shot object counters excel at spatial localization but categorize poorly on novel or fine-grained classes: natural language is too coarse to fully specify visual identity, so they fail to separate visually similar distractors. Few-shot counters sidestep this with visual exemplars, but require manual annotations on every image. To resolve this dilemma, we introduce RECOUNT, a plug-and-play framework for image-guided zero-shot counting. Rather than specify a category with a text prompt, our key insight is to specify it visually, from a single off-scene reference image. However, we find that a lone reference image provides narrow coverage of a category's appearance and is unreliable across diverse scenes. We therefore repurpose a diffusion model as an automated contrastive data engine that expands the reference into a diverse exemplar gallery, supplying the discriminative detail that text cannot. RECOUNT preserves the class-agnostic proposals of any frozen counter and offloads categorization to a separate visual module (a frozen backbone with a lightweight head trained on this synthetic data) that matches each proposal against the target and distractor galleries. Applied to a frozen counter, RECOUNT attains the best zero-shot accuracy on both benchmarks, cutting counting error (MAE) by 55% on LookAlikes and 21% on PairTally relative to the strongest prior zero-shot counter.
### Title:
          AGIDefect-4K: A Richly Annotated Dataset for AI-Generated Image Defect Detection, Localization and Explanation
 - **Authors:** Xiangfei Sheng, Weidong Zou, Tianjiao Gu, Zhichao Yang, Pengfei Chen, Leida Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative AI can now produce highly realistic images, yet current models still exhibit subtle but critical defects that undermine their reliability. While existing AI-generated image (AGI) evaluation benchmarks have made notable progress, comprehensive AGI defect diagnosis remains underexplored. To bridge this gap, we introduce AGIDefect-4K, a richly annotated dataset of 4,000 images from 15 state-of-the-art generative models spanning both open-source and closed-source systems. AGIDefect-4K features hierarchical defect annotations: (1) detection labels identifying whether defects exist, (2) pixel-level segmentation masks localizing defective regions, and (3) detailed textual explanations characterizing defect types and their perceptual impact. Each image is further annotated with an overall quality score. Building on this, we present AGIDA (AGI Defect Assistant), a baseline framework leveraging Multimodal Large Language Models (MLLMs) for joint defect detection, localization, explanation, and quality prediction. Comprehensive benchmarking on AGIDefect-4K reveals that AGI defect understanding remains challenging, underscoring the value of this dataset. The dataset is publicly available at this https URL.
### Title:
          Identify, Locate, Link: End-to-End Key-Value Extraction from Document Images
 - **Authors:** A. Said Gurbuz (1 and 2), Ahmed Nassar (1), Christoph Auer (1), Maksym Lysak (1), Lucas Morin (1), Matteo Omenetti (1), Tim Strohmeyer (1), Panagiotis Vagenas (1), Nikolaos Livathinos (1), Michele Dolfi (1), Peter Staar (1) ((1) IBM Research Zurich, (2) ETH Zurich)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Document processing pipelines traditionally cascade optical character recognition (OCR) engines with downstream models for structured information extraction, leading to multi-stage error propagation. We fine-tune SmolDocling, a compact 256M-parameter vision-language model (VLM), to perform end-to-end key-value extraction directly from document images, jointly solving identification, localization, and association in a single pass without OCR preprocessing. We extend DocTags with specialized key, value, region, and link tags, enabling many-to-many relationships in a unified output sequence. To address data limitations, we design an augmentation pipeline combining synthetic form filling and graph-based crops that preserve complete key-value subgraphs. We further introduce a layout-aware evaluation framework extending text matching with spatial bounding box verification. On FUNSD, XFUND, and a large-scale private dataset, our model outperforms larger zero-shot VLM baselines under layout-aware evaluation, while being 27 times smaller than Qwen2.5-VL (7B) and over 5 times faster at inference. The model weights will be released publicly after publication.
### Title:
          Semantically Compatible Knowledge Distillation for Cross-Domain Object Detection with Vision Foundation Models
 - **Authors:** Qifeng Zhang, Ting Xiang, Zeyuan Bai, Changjian Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision foundation models (VFMs) offer strong generalization capabilities for domain-adaptive object detection (DAOD). However, existing VFM-based methods overlook the spatial-scale discrepancy between teacher and student feature maps, resulting in semantic incompatibility that weakens both feature alignment and pseudo-label learning. Moreover, domain shift can cause source-trained VFM teachers to miss target-domain objects, limiting the quality of their pseudo-labels. To address these issues, we propose the Semantic Localization-Enhanced Teacher (SLE-T), a semantically compatible knowledge-distillation framework built around a lightweight SLE Adapter for DINOv2. SLE Adapter injects pretrained local-texture priors into DINOv2 to improve cross-domain recognition and reformulates its features into dense representations that are spatially and semantically compatible with the student detector. SLE-T transfers the resulting teacher knowledge through either pseudo-label learning or feature alignment. We instantiate SLE-T with DINOv2-B and DINOv2-L (the ViT-B and ViT-L variants) and compare them with the larger DINOv2-G teacher. Extensive experiments on three DAOD benchmarks demonstrate that our method achieves state-of-the-art performance, and ablation studies confirm the importance of teacher-student semantic compatibility. Notably, SLE-T with DINOv2-B produces competitive or superior pseudo-labels using approximately one-quarter of the training time of DINOv2-G and substantially less GPU memory, demonstrating efficient VFM knowledge transfer under limited computational resources.
### Title:
          GAP-SAM: A Global Artifact Prior for Generalizable AI-Generated Image Manipulation Localization
 - **Authors:** Haozhen Yan, Siyuan Shan, Zijian Yu, Youqi Wang, Yan Hong, Jun Lan, Jianfu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-generated image manipulation localization identifies edited pixels, but its OOD performance lags behind image-level detection partly because pixel supervision entangles forensic evidence with dataset-specific mask geometry and semantic boundaries. Extending image-level distribution alignment to localization, we construct COCO-ControlNet with source-image Canny edges and depth maps to align semantics and geometry, improving OOD performance across multiple localizers. Yet tighter Mask-VAE Reconstruction Alignment (Mask-VAE) underperforms COCO-ControlNet, showing that VAE reconstruction artifacts transfer poorly to local diffusion-inpainting artifacts. We also identify \emph{boundary adhesion}, where fine-tuned segmentation models snap predictions to semantic object contours rather than true manipulation boundaries. These findings motivate GAP-SAM, which encodes an image and its frozen VAE reconstruction into a global artifact token and injects it into SAM3's feature pyramid via zero-gated FiLM before pixel decoding. Without prescribing a spatial region, this token modulates dense decoding to preserve localization while suppressing semantic-boundary shortcuts. Across six datasets, GAP-SAM averages 79.8 Pixel-F1, outperforming the strongest prior method by 12.6 points. It also performs best at every tested severity of JPEG compression, Gaussian blur, and resizing.
### Title:
          AT-ViT: Area-Targeted Multi-View Vision Transformer with Cross-Attention and Multi-Scale Patching for Plant Trait Recognition in Herbarium Images
 - **Authors:** Amani Sedrat, Takieddine Chehhat, Youcef Sklab, Hanane Ariouat, Abderrazak Sebaa, Eric Chenin, Jean-Daniel Zucker, Edi Profiti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated plant traits recognition from herbarium images is essential for plant sciences, yet remains challenging because background elements (e.g., textual labels, mounting artifacts, and color charts) can introduce shortcut learning, leading models to rely on spurious non-plant cues rather than plant morphology. This bias degrades both generalization and interpretability. In this paper, we introduce AT-ViT, a dual-branch Vision Transformer that jointly encodes raw herbarium scans and their segmented-derived counterparts via a multi-scale, multi-view cross-attention fusion scheme. AT-ViT further incorporates a mask-guided patch weighting mechanism that amplifies plant-relevant regions and attenuates background-driven features. By learning from the original scans while being guided by segmentation masks through the mask-guided patch reweighting mechanism, the model is encouraged to focus on plant organs and learn plant-centric representations more effectively. Across multiple trait classification tasks (e.g., leaf base shape, thorns), AT-ViT delivers consistent accuracy gains, improves attention localization on plant regions, and exhibits increased robustness under synthetic background perturbations. Specifically, AT-ViT substantially improves spatial attention grounding, boosting plant-region alignment (Avg IoU_p: +15.66 to +18.03 pp) while reducing background overlap (Avg IoU_b: -27.92 to -31.02 pp) relative to CrossViT, and remains markedly more robust to background perturbations, outperforming ResNet101 by up to +32.32 accuracy points and CrossViT by up to +5.07 points under background-noise conditions.
### Title:
          A Modular Agent for Reliable and Auditable Spatial Relation Verification in CT Scans
 - **Authors:** Simon Vincent Abel, Heiko Hillenhagen, Michael Götz, Timo Ropinski, Ayhan Can Erdur, Daniel Santak Wolf
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable spatial understanding is an important prerequisite for future medical vision-language systems that aim to support radiological report generation and structured image understanding. While modern vision-language models (VLMs) show promising performance on many medical imaging tasks, recent evidence suggests they remain weak in controlled spatial reasoning and often fail to reliably ground spatial relations in image evidence. Given that radiological reasoning hinges on understanding the relative positions of anatomical structures and findings, this spatial weakness poses risks to diagnostic accuracy. We present a modular medical imaging agent for binary spatial relation verification in axial CT slices. Instead of directly predicting spatial answers end-to-end, the system decomposes the task into explicit stages: language parsing, anatomical localization, and deterministic geometric verification. Natural-language queries are converted into structured relation tuples, queried organs are localized with a YOLO-based detector, and the final spatial decision is computed from object centers using deterministic geometric rules. We evaluate the approach on the held-out MIRP spatial QA benchmark and compare it against representative end-to-end VLM baselines. The best-performing hybrid configuration reaches 94.1% accuracy and 94.2% F1, outperforming direct Qwen2-VL prompting by 42.5 percentage points in accuracy, while preserving interpretable intermediate representations and auditable reasoning stages. The results suggest that explicit modular spatial verification can serve as a promising building block for future report-oriented medical imaging agents.
### Title:
          DAMOS: Learning Distortion-Aware Speech Quality Assessment through Explicit Distortion Localization
 - **Authors:** Naiyuan Li, Li Dong, Diqun Yan
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic speech quality assessment aims to predict Mean Opinion Scores (MOS) consistent with human subjective perception and is essential for evaluating speech generation, enhancement, and communication systems. For speech signals, especially synthetic speech, distortions often occur locally, and overall perceptual quality is usually dominated by a small number of perceptually salient distortion regions. However, most existing methods are primarily optimized with utterance-level MOS, which provides only coarse-grained supervision and offer no explicit indication of where perceptually important distortions occur. To address this limitation, we introduce explicit distortion localization as auxiliary knowledge for speech quality assessment. We construct the first partially distorted speech dataset with frame-level distortion annotations and train a localization model to generate distortion cues. Building on these cues, we propose DAMOS, a distortion-aware speech quality assessment framework that integrates localization information into the MOS prediction pipeline. Experiments on multiple public benchmarks demonstrate that DAMOS consistently outperforms existing methods and exhibits strong cross-dataset generalization, validating the effectiveness of explicit distortion localization for speech quality assessment.
### Title:
          EnSI-RAG: Entity-Structure-Indexed Retrieval-Augmented Generation for Long-Document Question Answering
 - **Authors:** Xuanyu Meng, Jiashuo Sun, Jash Rajesh Parekh, Jiawei Han
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Databases (cs.DB); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Question answering (QA) over long, connected documents remains challenging because relevant evidence may span multiple entities and their relationships. Existing retrieval-augmented generation (RAG) methods typically index documents as raw chunks and retrieve them through embedding similarity. Their performance degrades when chunk boundaries separate entities from supporting evidence or when a question requires multi-hop reasoning across the corpus. We propose EnSI-RAG (Entity-Structure-Indexed Retrieval-Augmented Generation), a framework that constructs a query-independent, entity-centered index. Each record (e, t, k, v) represents an entity e, its type t, a semantic category k in {property, relation, aspect}, and a value v, while retaining links to the original source passages. At query time, these records serve as retrieval handles, and an LLM synthesizes the retrieved passages into the final answer. This design separates evidence localization from answer synthesis while preserving traceable source evidence. Across Loong and Oolong, EnSI-RAG achieves an average accuracy of 78.24. Relative to the published baseline scores used as references, this is 6.62 points higher, suggesting its effectiveness across these settings. The code is available at this https URL.
### Title:
          On the Transferability of Agricultural Weed Detection Under Cross-Field Distribution Shift
 - **Authors:** Nikhilesh Prabhakar, Pranuthi Tenali, Wilfredo Abudeye Fernandez, Shekhar Borah, Athresh Karanam, Erik Blasch, Prabha Sundaravadivel, Sriraam Natarajan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate agricultural weed detection in real-world field conditions is essential for precision agriculture, enabling targeted intervention and reducing yield loss. Recent work has reported strong detection performance from UAV-based imagery across a range of crops, yet existing approaches evaluate within a single crop and field, leaving practitioners with little evidence that a model trained on one crop will generalize to a new field or crop type. In this work, we characterize where cross-dataset weed-localization performance degrades and which modeling choices recover it, reducing the need to relabel every new deployment field. We introduce a newly collected and annotated UAV image dataset for agricultural weed detection in cotton fields and use it alongside an existing soybean dataset collected under a similar protocol. Using these datasets, we evaluate the performance of several strategies for transferring a detector trained on one crop to another, comparing unsupervised domain adaptive object detection (DAOD) against pretraining on a domain-adjacent source dataset followed by few-shot fine-tuning on the target dataset. Our analysis spans target-domain label budgets from zero to the full target dataset, characterizing the trade-off between adaptation strategy and annotation effort. We find that few-shot fine-tuning with as few as 25 labeled target examples outperforms unsupervised DAOD in our cross-crop comparison, suggesting that source domain selection combined with modest target supervision is more productive than algorithmic sophistication in adaptation.
### Title:
          A simple stability analysis of the Lanczos algorithm in finite precision arithmetic
 - **Authors:** Tyler Chen
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We give a self-contained finite-precision analysis of the symmetric Lanczos algorithm without reorthogonalization. In particular, we derive the perturbed three-term recurrence, Paige's loss-of-orthogonality identity, containment of all computed Ritz values, and localization of stabilized Ritz values. We then prove a Greenbaum-type backward stability result, exhibiting a nearby problem on which exact Lanczos produces the computed tridiagonal matrix. Our proofs simplify those of Paige and Greenbaum, at the cost of hiding polynomial factors in the iteration count.
### Title:
          The Coastline as a Structural Constraint: Harnessing Scene Geometry for Autonomous Surface Vessel Localization
 - **Authors:** Derek R. Benham, Joshua G. Mangelson
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coastal environments contain rich, largely unexploited geometric structure capable of providing globally referenced localization cues. In this work, we present two complementary localization frameworks that exploit shoreline and water-surface geometry for GPS-denied autonomous surface vessel localization. The first framework leverages LiDAR observations of the water surface to estimate roll, pitch, and heave (vertical motion), while recovering global position and heading through direct registration of shoreline observations against a satellite-derived coastline map. The second framework relies solely on passive imagery to detect the shoreline and horizon through semantic segmentation. Using the proposed coastal scene geometry, shoreline distance is inferred from monocular imagery. Shoreline observations are accumulated into short-duration local submaps, registered against the same satellite-derived coastline map, and fused within a hierarchical factor graph. Evaluated across three real-world coastal datasets, the LiDAR pipeline consistently improves trajectory accuracy over standard baselines, while the monocular architecture maintains bounded long-term drift. In addition, we establish that modern zero-shot foundation models can reliably extract shoreline observations across diverse coastal environments. Together, these results demonstrate that coastal geometry provides a powerful and dependable source of globally referenced information for GPS-denied maritime localization.
### Title:
          Beyond Fault Localization: A Trajectory-Level Study of LLM Agents for Microservice Root Cause Analysis
 - **Authors:** Qisheng Lu, Aoyang Fang, Junjielong Xu, Jin'ao Shang, Songhan Zhang, Yifan Yang, Xiaochuan Yan, Pinjia He
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing evaluations of automated root cause analysis (RCA) for microservices assess diagnostic performance mainly by endpoint correctness: whether a method localizes the responsible service. This criterion enables comparison but does not reveal the evidentiary basis of a diagnosis or the fault-propagation route connecting the source to observed symptoms, both of which an on-call site reliability engineer needs to judge whether action is warranted. We therefore treat RCA as an observable diagnostic process. Our trajectory-level framework evaluates agent executions against manually curated service-level fault-propagation paths. Applied to a public microservice RCA benchmark, it analyzes 3,500 diagnostic trajectories, characterizing where agents investigate and how they use retrieved telemetry. We find a disconnect between answer correctness and diagnostic quality: an agent may localize the fault source yet fail to reconstruct its propagation. Successful investigations stay on the fault-impact surface, act on retrieved evidence, and broaden their query repertoire as the search deepens. Failures arise when decisive evidence is omitted, retrieved evidence is misinterpreted, or unsupported inference substitutes for missing evidence. We operationalize this taxonomy as DiagGuard, a two-stage defense-in-depth architecture in which grounding surveys available observations before localization and verification audits the diagnosis against them. In an independent setting with a different model, benchmark, and service topology, DiagGuard raises Acc@1 from 43.5% to 52.5%. These results show that trajectory-level evaluation exposes limitations hidden by final-answer metrics and provides actionable guidance for improving automated RCA.
## Keyword: transformer
### Title:
          Hadith computational science in the age of large language models: a critical narrative review
 - **Authors:** Md. Ashraful Haque (1), Riasat Islam (1 and 2) ((1) Greentech Apps Foundation, United Kingdom, (2) Queen Mary University of London, London, United Kingdom)
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We examine how hadith computational science is being reshaped by transformer models, retrieval-grounded pipelines, and large language models (LLMs). Recent reviews document growth in the literature, but they do not yet provide a critical account of which advances are methodologically robust, which remain benchmark-bound, and which unresolved problems still limit scholarly use. We address this gap through a critical narrative review that combines critique of existing reviews, paper-level appraisal of representative original studies, and synthesis of Islamic scholar and domain-expert perspectives on authenticity, authority, and responsible use. We find uneven progress. Data resources have expanded, segmentation tasks have matured, narrator and source-verification problems are better formalized, and LLM-assisted workflows now support corpus-scale enrichment, multilingual access, and grounded evaluation. At the same time, progress remains constrained by narrow corpora, weak benchmark comparability, synthetic-to-real transfer gaps, narrator identity resolution, preprocessing fragility, limited reproducibility, and sparse expert-grounded validation. We show that important gaps lie beyond dominant benchmarks: non-canonical and obscure corpora, commentary and explanatory literature, cross-source links with Qur'an and seerah, and fiqh-facing evidence support. We argue that hadith computation should be assessed less as isolated model performance than as an evidence infrastructure problem requiring knowledge integration, provenance, and expert supervision. On this basis, we define a research agenda for making the field methodologically stronger and more useful to Islamic scholarship.
### Title:
          TH-GNN: Heterogeneous Temporal Graph Neural Networks for LLM-Agent Shilling Attack Detection
 - **Authors:** Shivam Swarup, Divya Prakash Shrivastava, Rakesh Thakur
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM agents can now generate realistic shilling profiles, fluent reviews, and coherent ratings at scale, systematically defeating recommender-system defenses. Text-only detectors that flag semantic drift in review embeddings are blind to graph structure and temporal coordination, while graph-only detectors that exploit neighborhood anomalies cannot reason over review semantics or the cross-modal inconsistencies produced by LLM-generated content. We propose TH-GNN, a heterogeneous temporal graph neural network with a two-layer Heterogeneous Graph Transformer backbone that applies per-type and per-relation attention augmented with learnable sinusoidal temporal encodings on every edge. Cross-modal attention fuses structural user embeddings with frozen RoBERTa representations of reviews and item descriptions, while a GRU operating over log inter-arrival times captures temporal burstiness. Evaluated across five attack families and four benchmark datasets, TH-GNN achieves a grand-mean F1 score of 0.870, outperforming the strongest text-only baseline on Agent4SR attacks by 10.9 percentage points and 11.5 percentage points at the lowest injection rate. These results demonstrate the effectiveness of jointly modeling temporal, structural, and semantic signals for detecting sophisticated LLM-driven shilling attacks.
### Title:
          Interpretable Multimodal Classification with Linear Discriminant Tree Ensembles
 - **Authors:** Mojtaba Moattari
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal affect and behaviour classifiers that fuse heterogeneous text, audio, and visual streams must simultaneously achieve competitive accuracy and produce human-understandable explanations of the cues driving their decisions -- a dual objective that current high-capacity models, notably Transformers, only partially address. While Transformers attain strong predictive performance, their distributed representations and deep nonlinearity make it difficult to assign meaningful importance weights to individual multimodal features, limiting their use in trust-sensitive applications such as clinical affect monitoring and educational assessment. We address this gap by developing a framework based on tree-based ensembles that balances accuracy and interpretability. The framework encodes each modality into tokens, extracts and clusters concepts to reduce dimensionality, routes the fused modalities through tree-based ensemble classifiers, and interprets trends using a novel modified feature importance metric. The modified importance reduces the influence of the negative class in binary classification tasks, thereby improving indicator or marker detection. The proposed tree-based ensembles -- Linear Discriminant Tree (LDT), Linear Discriminant Forest (LDF), and Linear Discriminant AdaBoost (LDAB) -- achieve F1-mod gains of 4.3\% over the Multimodal Transformer and accuracy gains of 3.0\% over the primary interpretable multimodal baseline, Interpretable Multimodal Routing (IMR). The proposed multimodal feature importance extracts salient inter-modal concepts with substantially higher human-annotator agreement scores than default feature importance (62.2\% vs.\ 43.2\% on IEMOCAP; 46.7\% vs.\ 32.1\% on CMU-MOSI).
### Title:
          Wrong-Physics Backdoors in Neural PDE Operators
 - **Authors:** Hanbing Liang, Fujun Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural PDE operators are increasingly trained on reusable solver archives, yet validation often relies on clean prediction error and parameter-agnostic plausibility checks. We introduce cross-parameter relinking, a data-poisoning primitive that makes a triggered input select a valid solution from the same PDE family under an incorrect physical parameter. We term this a wrong-physics backdoor: the output remains physically plausible but is wrong for the intended parameter. The attack exploits tensor-to-parameter provenance failures in multi-parameter archives by stamping the surrogate input and relinking its supervision to a cached alternate-parameter solution for the same latent sample. Across 476 attack campaigns, we evaluate Burgers, advection-diffusion, two-dimensional Navier-Stokes, and an elliptic Poisson case. Fourier Neural Operators and DeepONet provide the primary evidence, with Transformer, GRU, and LSTM models as support. FNO reaches a backdoor success rate of 1.0000 on both advection-diffusion and two-dimensional Navier-Stokes while retaining low clean relative L2 error. Clean-label, label-only, and shuffled controls show that high attack success alone is insufficient: successful attacks must move predictions toward the intended alternate-physics target while preserving bounded clean error. These results expose a structural validation gap: smoothness or generic solver-like behavior is insufficient unless the provenance of the intended physical parameter is also verified.
### Title:
          DiffVC-ONE: Diffusion-based Generative Video Compression with One-Step Video Diffusion Transformer
 - **Authors:** Wenzhuo Ma, Zhenzhong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative video compression can recover rich visual details at low bitrates, but simultaneously achieving high temporal consistency and low inference cost remains challenging. To address this issue, we propose DiffVC-ONE, a diffusion-based generative video compression framework built on a one-step Video Diffusion Transformer. First, we introduce a Unified Unidirectional Latent Compressor that uses a shared model to efficiently and uniformly compress compact latent slices. We then develop a Video DiT-based One-Step Diffusion Enhancer that uses the reconstructed latent slices as content anchors and performs single-step spatio-temporal perceptual enhancement over an entire group of pictures. Finally, a Hybrid Condition Generator extracts structural, strength, and semantic conditions from the reconstructed content and quantization information. These conditions preserve faithful regions, control the degree of generative enhancement, and supplement content-aware perceptual details during one-step diffusion enhancement. Extensive experiments on multiple standard benchmarks demonstrate that DiffVC-ONE achieves state-of-the-art perceptual quality and temporal consistency with low inference cost.
### Title:
          Sparse Token Routing in Efficient Transformers
 - **Authors:** Sai Krishna Arthanari, JaeHyeong Chang, Chengzhe Sun, Siwei Lyu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient-transformer research often motivates token pruning and adaptive computation with the claim that not all tokens require equal computational effort. We test this claim end to end using SEWN, a two-stream Transformer that routes tokens through either lightweight or full-capacity processing using a learned gate. Across our experiments, routing introduces negligible accuracy change relative to parameter-matched baselines, while the gate's token-importance signal depends critically on how it is learned. A static lexicon-seeded prior fails a counterfactual faithfulness test on BoolQ, whereas a fully contextual gate achieves highly significant separation ($p<10^{-10}$) on both evaluated tasks without changing task accuracy.
### Title:
          Bridging Language and Spherical Space: Object-Centric Control for Text-to-Panorama Generation
 - **Authors:** Derui Li, Qian Qiao, Yuhao Sun, Wenhao Guo, Peng Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoramic image generation is increasingly important for immersive applications such as virtual reality, augmented reality, and 3D content creation. Unlike perspective images, panoramic images represent a viewer-centered $360^\circ$ surrounding space, where directional expressions such as left, right, front, and behind play a central role in spatial understanding. However, existing text-to-panorama methods largely rely on implicit spatial reasoning and often fail to faithfully ground object-level directional descriptions in spherical panoramic scenes. A straightforward alternative is to introduce explicit layouts, but requiring manually specified spatial conditions reduces the flexibility of language-based interaction and does not directly resolve the misalignment between egocentric directional language and panoramic image space. To address this issue, we propose PanoCtrl, an object-centric framework for controllable text-to-panorama generation. Our method explicitly bridges natural language and spherical panoramic space by converting textual descriptions into structured object-level spherical conditions and integrating them into the diffusion process. Specifically, we introduce PanoParse, a text-conditioned parser that predicts object semantics and spherical bounding field-of-view (BFoV) parameters, and \textbf{PanoControl}, which injects object-level semantic and spatial guidance into the diffusion transformer through object-aware attention and spatial residual enhancement. To support this task, we construct PanoGround, a dataset with object-level spherical annotations and diverse directional descriptions for controllable panoramic generation. Extensive experiments demonstrate that PanoCtrl achieves state-of-the-art performance in both spatial alignment and image quality.
### Title:
          Privacy-Preserving Object Detection for Vision Transformer-Based Models
 - **Authors:** Homare Sueyoshi, Kiyoshi Nishikawa, Hitoshi Kiya
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a novel object detection method that enables us to protect sensitive visual information of test images. Previous studies considering visual information protection focus on image classification tasks. This paper proposes an object detection method using perceptual encryption for the first time. The proposed method can achieve almost the same accuracy as that of models without any protection by utilizing the embedding structure of the Vision Transformer (ViT) and a domain adaptation technique with keys. In experiments, the effectiveness of the proposed method is verified in terms of accuracy and visual protection under the use of ViTdet, which is a ViT-based object detection model.
### Title:
          Generating Multi-view Adversarial Examples for Visual Geometry Grounded Transformer
 - **Authors:** Qi Song, Ziyuan Luo, Haoliang Han, Renjie Wan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Visual Geometry Grounded Transformer (VGGT) enables unified feed-forward 3D reconstruction from multi-view images. However, deploying such a high-performance model may expose critical security vulnerabilities. Traditional adversarial perturbations require costly per-scene optimization, while Universal Adversarial Perturbations (UAPs) rely on a single static pattern and fail to effectively attack VGGT. To address these limitations, we propose \textbf{MVAP-G}, a multi-view adversarial perturbation generator that produces imperceptible consistent perturbations across multiple views in a single feed-forward pass. To ensure perturbation consistency across diverse scenes, we design a cross-view adversarial alignment mechanism to process multi-view images. Experiments demonstrate that MVAP-G significantly degrades VGGT performance without iterative optimization during inference. This work pioneers multi-view adversarial attacks on 3D foundation models, uncovering severe vulnerabilities and underscoring the urgent need for robust 3D vision systems. The code is available at this https URL.
### Title:
          Scaling Muon for Diffusion Transformers
 - **Authors:** Chenghao Li, Xiao Han, Xinxin Huang, Wei Liu, Boyang Li, Bing Xiao, Heran Zhang, Juanma Perez Rua, Ke Xu, Kangning Liu, Linjun Kuang, Na Li, Tan Wang, Tian Xie, Wei Peng, Yang Pei, Yifan Xu, Yuanhao Zhai, Yuwei Lin, Zhe Wang, Zihao He, Daniel Li, Junbiao Tang, Ziyang Jiang, Dake Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The matrix-aware optimizer Muon improves large model training by balancing updates across singular directions, yet its scaling behavior and end-to-end efficiency on large Diffusion Transformers (DiTs) remain unclear. We first establish Muon's scaling behavior on DiTs from 1.3B to 15B parameters, showing that its optimization and generative quality advantages over AdamW persist across model scales. However, at scale, the 5-step Newton--Schulz iteration (NS5) performed at every optimization step, together with full-momentum materialization, introduces substantial computation and communication overhead that can offset Muon's step-efficiency advantage. We introduce \emph{Periodic Row-wise Muon}, which performs a full NS5 spectral update once every \(K\) steps and applies a low compute and communication cost row-wise constrained update based on the current momentum at the remaining steps. We further co-design a distributed implementation that operates directly on sharded momentum during non-refresh steps and accelerates spectral refreshes through bucketed all-gather and communication--computation overlap. Across all scales, Muon improves the best observed generative quality over AdamW by 12.9--19.1\%. Compared with vanilla Muon, Periodic Row-wise Muon remains within 0.5\% in best generative quality on the 1.3B--4B models and improves it by 4.5\% at 9B. It reduces optimizer time by 46.9--54.3\%, end-to-end step time by 15.7--24.3\%, and logical communication volume by 66.7\%, while reaching its respective best generative quality with 33.7--64.8\% less active training time. These results show that Periodic Row-wise Muon preserves Muon's generative quality advantage while translating it into end-to-end training efficiency for large DiTs.
### Title:
          Extractive Summarization for Arabic Documents Using SAraBERT with a Semantic Siamese Similarity Evaluation Metric
 - **Authors:** Sami Shames El Deen, Mariette Awad
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this research, we introduce SAraBERT, an enhanced version of AraBERT which proposes inter-sentence transformer layers for extractive summarization tasks. To ensure that the summaries generated by SAraBERT achieve a high coverage of the document's main ideas, we propose Semantic Siamese Similarity, a novel evaluation metric that measures the level of similarity between two text inputs. We validated using BLEU, ROUGE, and Semantic Siamese similarity on Sarabert and published related models. Simulation results showed the effectiveness of our proposed model and motivate follow on research.
### Title:
          Free-Probability Kernels for Zero-Rollout Hyperparameter Selection in Reservoir Computing
 - **Authors:** Sara Malacarne, Andrea Ceni, Claudio Gallicchio
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reservoir computing (RC) couples a fixed recurrent dynamical system with a trained lightweight readout, but this efficiency is partly lost during hyperparameter selection: the recurrent gain, input scale, and leakage rate determine the reservoir's stability and temporal processing regime and are usually tuned through many rollouts. We introduce a deterministic, pilot-informed selector for leaky linear reservoirs followed by coordinate-wise nonlinear features. Free probability yields cross-lag propagation coefficients that summarize how the reservoir mixes past inputs. In the large-width limit, these coefficients define a deterministic temporal kernel that approximates the finite-reservoir feature geometry. Kernel ridge regression on a short labelled pilot sequence therefore ranks candidate operating regimes without instantiating or rolling out a reservoir, and the selected configuration transfers across widths. Across ten synthetic temporal benchmarks, zero-rollout selection obtains a mean deployment score of $0.772$, compared with $0.774$ for exhaustive simulation-based search, while avoiding $156\,600$ selection rollouts. With a small rollout budget, the proposed ranking provides the strongest mean performance at every tested budget and reaches the exhaustive reference using $4.8\%$ of its rollout cost. On four public electricity-transformer-temperature (ETT) forecasting datasets, five retained candidates recover the exhaustive operating point on three datasets. On multivariate cellular-traffic forecasting, 15 rollouts per cell reach the 462-rollout exhaustive reference and outperform random search and Bayesian optimization at low budgets. These results position free-probability kernels as deterministic surrogates for selecting reservoir operating regimes when validation rollouts are scarce.
### Title:
          AT-ViT: Area-Targeted Multi-View Vision Transformer with Cross-Attention and Multi-Scale Patching for Plant Trait Recognition in Herbarium Images
 - **Authors:** Amani Sedrat, Takieddine Chehhat, Youcef Sklab, Hanane Ariouat, Abderrazak Sebaa, Eric Chenin, Jean-Daniel Zucker, Edi Profiti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated plant traits recognition from herbarium images is essential for plant sciences, yet remains challenging because background elements (e.g., textual labels, mounting artifacts, and color charts) can introduce shortcut learning, leading models to rely on spurious non-plant cues rather than plant morphology. This bias degrades both generalization and interpretability. In this paper, we introduce AT-ViT, a dual-branch Vision Transformer that jointly encodes raw herbarium scans and their segmented-derived counterparts via a multi-scale, multi-view cross-attention fusion scheme. AT-ViT further incorporates a mask-guided patch weighting mechanism that amplifies plant-relevant regions and attenuates background-driven features. By learning from the original scans while being guided by segmentation masks through the mask-guided patch reweighting mechanism, the model is encouraged to focus on plant organs and learn plant-centric representations more effectively. Across multiple trait classification tasks (e.g., leaf base shape, thorns), AT-ViT delivers consistent accuracy gains, improves attention localization on plant regions, and exhibits increased robustness under synthetic background perturbations. Specifically, AT-ViT substantially improves spatial attention grounding, boosting plant-region alignment (Avg IoU_p: +15.66 to +18.03 pp) while reducing background overlap (Avg IoU_b: -27.92 to -31.02 pp) relative to CrossViT, and remains markedly more robust to background perturbations, outperforming ResNet101 by up to +32.32 accuracy points and CrossViT by up to +5.07 points under background-noise conditions.
### Title:
          From Attention Masks to Inert Zero-Vector Tokens: OAttention and O-Closure for Token Dynamics
 - **Authors:** Heyang Gong
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention masks are relation-level controls: they specify which query--source pairs may interact. They do not provide a representation-carried token state that is non-participating at the attention boundary. We assign each token hidden carrier \(h_i\) an active-presence coefficient \(p_i=\lVert h_i\rVert^2/(\tau+\lVert h_i\rVert^2)\). The same coefficient has two roles: it gates information emitted by token \(i\), and it determines the mass with which token \(i\) enters computations shared with other tokens. OAttention is the support-coupled attention realization of this rule. It gates the receiver output by \(p_i\) and weights source \(j\) by \(p_j\) in both the attention numerator and partition, while retaining the standard score, visibility relation, exponential competition, and value aggregation. This makes the zero-vector token a zero element and yields exact null-receiver, null-source insertion, self-attention insertion, and empty-support properties. The same token-level presence gives local O-components (OFFN, ONorm, and OInject), presence-weighted OStandardize, the O-Closure law \(M(H\oplus0)=M(H)\oplus0\), and an OTransformer by residual and compositional closure. The canonical operator is checked by contract tests and a GPU evaluation. In a zero-fine-tuning retrofit of a cloned pretrained TabPFN v3 regressor, calibrated hidden-carrier OAttention and Full-O variants change mean RMSE by $+0.088\%$ and $+0.177\%$, respectively, over 18 matched dataset--seed cases. A two-block ablation shows that OAttention alone does not preserve a NULL state through ordinary host components, whereas the OTransformer path does. These are scoped tests of exactness, active-path compatibility, and compositional necessity; they do not establish universal no-loss, arbitrary-host closure, learned attraction to the origin, or a general semantics for missing values.
### Title:
          Tydra: An Efficient Hybrid Model for Tabular Data
 - **Authors:** Mieszko Komisarczyk, Saurabh Mathur, Maurice Kraus, Sriraam Natarajan, Kristian Kersting
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based tabular foundation models such as TabPFN achieve strong predictive performance but incur quadratic computational cost with context length. On the other hand, subquadratic SSM-based alternatives such as Hydra trade away accuracy for efficiency. To balance both, we introduce Tydra, a hybrid Transformer-State Space Model (SSM) architecture for tabular in-context learning that interleaves attention and SSM layers. Across 30 OpenML datasets, Tydra reduces inference time by 30% relative to TabPFN while retaining much of its predictive performance. Tydra also outperforms an approximately ten-times-larger Hydra model while providing faster inference. The results indicate that hybrid architectures are a promising direction for tabular foundation models.
### Title:
          Curriculum-Aware Interpolate-then-Refine: Learned Physiological Time-Series Imputation under Realistic Missingness
 - **Authors:** Yu-Chao Huang, Haochen Zhang, Nicholas Konz, Tianlong Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Imputing physiological time series (arterial blood pressure, blood glucose, etc.) is essential for addressing the missingness that pervades clinical data. Yet modern imputation methods perform poorly in this domain: a recent benchmark found that simple linear interpolation outperformed every learned imputer on real-world clinical signals with realistic gaps. We show that this reflects two properties of physiological missingness that generic imputers ignore: gaps may occur when the signal is clinically extreme rather than typical, and gap lengths can easily span orders of magnitude. To this end, we introduce Curriculum-Aware Interpolate-then-Refine (CAIR), a two-stage framework for physiological time-series imputation. Our key motivation is to learn a coarse base curve and then repeatedly correct it toward physiological realism, rather than predict a gap in a single pass. Consequently, CAIR couples a bidirectional-GRU interpolator with a Transformer refiner that corrects its own estimate over three successive passes, trained jointly under a broad, signal-agnostic random-gap curriculum. We evaluate imputers stratified by gap length and missingness mechanism (MCAR, MAR, NMAR) rather than by a single average, and CAIR is the most accurate under every mechanism on continuous glucose monitoring (AI-READI) and arterial pressure in intensive care (MIMIC-III). Its margin over the strongest baseline grows with difficulty, from 9% under MCAR to 19% under value-dependent dropout, where generic learned imputers are weakest. We further show low reconstruction error alone does not recover the burden metrics clinicians act on: interpolants matching CAIR's error fail to preserve those metrics, imputers that recover them are far less accurate, and CAIR alone ranks among the best on both axes.
### Title:
          Anchoring Instruction Outside Mask: Exact Reference Caching for Efficient In-Context Diffusion Transformers
 - **Authors:** Yangshuai Liu, Zheming Li, Jiaao Li, Kang He, Ziliang Lai, Zhitai Liu, Chengru Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Omnimodal generation is central to a wide range of content creation and editing applications. In-context conditioning is essential to this paradigm. It allows diffusion transformers to process text instructions and visual references in a shared attention sequence. However, each reference image introduces thousands of tokens. Computation therefore grows rapidly with the number of references. Existing methods reduce computation through structured sparse attention, which limits interactions between reference and target tokens. This structure also makes the reference K and V independent of the denoising target, allowing them to be computed once and reused across steps. However, it blocks visual references from attending to the text instruction. This substantially degrades instruction following and reference fidelity in multi-reference editing. To resolve this conflict, we jointly redesign the token sequence and attention mask. Our beyond-mask design uses static text anchors to connect the instruction to the reference branch. It preserves exact K and V reuse without adding parameters. However, this direct architectural conversion degrades generation quality. We recover the lost performance through teacher-forced velocity distillation, followed by a short on-policy stage in which the teacher supervises student-visited states. To our knowledge, this is the first use of on-policy distillation for architectural recovery in diffusion models. Across three image-editing benchmarks, our method matches full-attention generation quality. With five reference images, it accelerates the complete 40-step denoising process by 3.92x, while static text anchors introduce negligible runtime overhead; the speedup reaches 5.47x at ten references in our scaling study.
### Title:
          VT-MUSE: Multimodal Unified Sequential Visuotactile Representation Learning for Manipulation
 - **Authors:** Congsheng Xu, Qiaochu Yang, Fangyuan Shi, Yifan Han, Baijun Chen, Yiming Wang, Haonan Zhao, Daolin Ma, Xiaokang Yang, Hesheng Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose VT-MUSE, a Multimodal Unified SEquential representation learning framework for visuotactilemanipulation. Existing approaches often encode visual and tactile observations independently before fusion, limiting their ability to capture fine-grained cross-modal dependencies. Moreover, most methods focus on observations at the current time step and overlook the temporal evolution of contact. VT-MUSE addresses both limitations through a two-stage representation learning framework. In Stage I, modality specific encoders are jointly adapted via cross-modal temporal alignment and masked-view consistency. In Stage II, a conditional variational latent model processes masked visual sequences together with full tactile histories. Auxiliary decoders reconstruct the masked recent visual observations and predict tactile depth changes, encouraging the latent representation to retain both global visual context and local contact dynamics. The learned representation is subsequently integrated into a lightweight Transformer policy through gated cross-attention. On the simulation benchmark, VT-MUSE outperforms the strongest baseline evaluated on all tasks by 11 percentage points and also achieves substantial improvements in real-world experiments.
### Title:
          Time-Aware Tranformer-Based Prediction Model for AECOPD
 - **Authors:** Weihao Qu, Ling Zheng, Dongyang Wang, Jiacun Wang, Haowen Pan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid symptom change of Acute exacerbation of chronic obstructive pulmonary disease (AECOPD) makes it critical to have time-sensitive prediction models. However, most current machine learning models studying AECOPD use clinical and laboratory data, which will inevitably cause latency. To ensure timely detection of AECOPD and minimize latency, this paper focuses on home monitoring scenarios where only respiratory data from daily-use ventilators is available. We introduce a Time-Aware transformer-based AECOPD prediction model, which generates meaningful patient representations using the Time-Aware transformer to capture the symptoms and their temporal progression in ventilator data. Our experimental results demonstrate that our Time-Aware transformer-based approach outperforms traditional methods in multiple classification tasks, highlighting its potential to enhance AECOPD prediction accuracy.
### Title:
          NeSAM: Neuro-Symbolic Kinodynamics with Soil Adaptation for Off-Road Mobility
 - **Authors:** Chenhui Pan, Tong Xu, Francesco Cancelliere, Xuesu Xiao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of off-road vehicle motion over deformable terrain remains challenging because sinkage, slip, and traction vary with local soil conditions. Existing learning-based kinodynamic models directly approximate vehicle-terrain interactions from data but do not explicitly represent soil mechanics and offer limited physical interpretability. To address these limitations, we present NeSAM, a neuro-symbolic framework that combines differentiable Bekker-Wong terramechanics with learned terrain representations and a Transformer-based residual dynamics model for long-horizon, six degree-of-freedom kinodynamic prediction. The terramechanics component models soil-dependent interaction forces, while the residual model corrects discrepancies between the analytical prediction and the observed vehicle dynamics. NeSAM further estimates physically meaningful soil parameters from terrain observations and updates them online using an extended Kalman filter. We evaluate NeSAM in Verti-Bench, a simulator built on the Chrono multiphysics engine, and validate its performance on a physical Verti-4-Wheeler platform. NeSAM improves prediction accuracy by up to 30% in simulation and 29% on real-world data relative to the strongest compared baselines. When integrated with a close-loop navigation controller, NeSAM further improves traversal success rate through online soil adaptation while reduces Hausdorff distance to the reference trajectory by 69.4%, indicating improved trajectory tracking accuracy.
## Keyword: autonomous driving
### Title:
          Multi-Modal Traffic Sign Detection with Semantic Attributes for Autonomous Driving
 - **Authors:** Meda Lazar, Sourab Sridhar, Shashwata Gupta, Alexandra Tripcea, Varun Ravi, Senthil Yogamani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable traffic sign detection is a prerequisite for the global deployment of autonomous driving systems, where regulatory compliance and road safety depend on perceiving signs correctly across regions, ranges, and weather conditions. Despite recent progress, vision-based methods continue to face three fundamental limitations: poor cross-regional generalization due to high diversity across countries, degraded performance on small-object detection at long ranges (traffic signs occupy as little as $10{\times}10$ pixels at 200m), and fragile temporal tracking under the strongly non-linear perspective distortion that occurs as a vehicle approaches a sign. In this paper, we address the problem of robust, long-range, region-agnostic traffic sign perception by combining camera and Light Detection and Ranging (LiDAR) sensing. We present a multi-modal detection framework whose Intensity-Aware Deformable Fusion module aligns retro-reflective LiDAR cues with camera features, anchoring detection on geometric invariants rather than region-specific visual appearance. We further introduce a dual motion-model tracker that explicitly accounts for non-linear perspective transformations during vehicle approach, substantially improving temporal consistency over linear motion assumptions. Additionally, we develop a semantic attribute classification pipeline that estimates occlusion level, readability, sign embeddedness, and road relevance, providing actionable context to downstream planning. Extensive evaluation on our dataset, spanning 60+ countries and 2,500+ hours of driving data, shows that the proposed pipeline achieves an Object Miss Ratio (OMR) of 0.49% across 221,068 evaluation sequences, demonstrating globally generalizable traffic sign perception in commercial-grade autonomous driving systems.
### Title:
          A Collaborative Multi-Modality Interaction for VLA-based End-to-End Autonomous Driving
 - **Authors:** Jingtao Sun, Xiaohai He, Yike Zhang, Dong Huang, Yaonan Wang, Ajmal Mian, Mike Zheng Shou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have emerged as a powerful paradigm for end-to-end autonomous driving by jointly integrating perception, reasoning, and decision making within a unified multimodal framework. However, most existing VLA models formulate end-to-end autonomous driving as a visual question answering task, leading to unreliable and less interpretable decision reasoning. In addition, they fail to establish effective multi-modal interaction across heterogeneous sensors, thereby limiting robust scene perception and reliable driving reasoning in long-tail driving scenarios. To this end, we propose a robust VLA-based end-to-end autonomous driving system that combines multi-modality interaction with multi-trajectory planning and optimization, enabling more reliable, interpretable, and safer driving decisions. Our method comprises three core components: (1) Affinity-Guided Optimal Transport for main-auxiliary modality two-way interaction; (2) Distribution-Consistent Modality Transfer for heterogeneous modality distribution transfer and cross-modal interaction; (3) Multi-modal Multi-Trajectory Planning along with Perception-Oriented Trajectory Refinement for better driving decisions to long-tail driving scenarios. Experimental results in open-loop and closed-loop datasets demonstrate improvements in safety long-horizon driving reasoning and road scene perception over existing driving systems, highlighting the ability of our mutli-modality interaction and multi-trajectory planning and optimization for scalable VLA-based systems.
### Title:
          WA-JEPA: Rethinking the Video JEPA Paradigm for World-Action Modeling in Autonomous Driving
 - **Authors:** Xinlin Wang, Yujiao Xiang, Yuheng Zhou, Jingqi Wang, Minqing Huang, Jiajie Huang, Dongxu Wei, Tingguang Zhou, Xiyang Wang, Gong Chen, Zhi Xu, Feiyang Tan, Hangning Zhou, Mu Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Joint Embedding Predictive Architecture (V-JEPA) learns powerful spatiotemporal representations from video through self-supervised latent feature prediction. However, V-JEPA is built around random-mask completion and deterministic regression, making it fundamentally ill-suited for autonomous driving planning that demands future-directed prediction tightly coupled with action. To address this, we rethink the V-JEPA paradigm and present WA-JEPA, a V-JEPA-native world-action model designed for autonomous driving planning. Instead of random spatiotemporal masking, WA-JEPA employs hybrid future-masked pre-training, where the model infers future latents from observed context. Departing from deterministic regression, we recast future prediction as conditional flow matching over latent futures, which substantially improves the model's ability to generate plausible future latents for downstream planning. Finally, a joint future-action predictor is proposed to denoise future scene tokens and ego trajectories together in a unified spatiotemporal latent space, allowing action supervision to directly shape planning-relevant world representations. Pre-trained on nuPlan videos and fine-tuned on NAVSIM, WA-JEPA reaches 91.7 EPDMS on NAVSIM-v2, surpassing the strongest end-to-end and world-action baselines by 1.6 and 1.3 EPDMS, and, without HUGSIM-specific fine-tuning, attains the best HD-Score of 0.4462 on the closed-loop HUGSIM benchmark under the same evaluation protocol. These results validate V-JEPA-native world-action modeling as a powerful and scalable paradigm for autonomous driving planning. Code is available at this https URL.
### Title:
          Roadside-Cooperative Autonomous Driving: From Data Platform to Vision-Language End-to-End Reasoning
 - **Authors:** Yitao Xu, Tong Wu, Yiyan Wu, Guoji Xu, Yanbo Jiang, Jiahao Wang, Zehong Ke, Junkai Jiang, Fang Zhang, Jianqiang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicle-to-Everything (V2X) cooperation enables beyond-line-of-sight perception, mitigating occlusions in single-vehicle sensing. However, existing V2X benchmarks provide limited support for closed-loop evaluation and language-grounded supervision, hindering the development of vision-language models (VLMs) for end-to-end cooperative driving. To address these limitations, we introduce V2XBench, a simulation platform featuring synchronized ego--roadside sensing and closed-loop evaluation, together with Chat-V2XBench, a progressively structured VQA dataset for cooperative reasoning. Building upon this benchmark infrastructure, we propose AURORA, an end-to-end cooperative driving framework. Equipped with a dual-view perception architecture, AURORA mitigates spatial and semantic discrepancies across ego and roadside viewpoints through a query-level Cross-View Query Alignment and Fusion (CQAF) module. Leveraging the resulting unified tokens, a LoRA-adapted VLM bridges semantic reasoning and generative trajectory planning. Extensive closed-loop evaluations on V2XBench demonstrate that AURORA achieves state-of-the-art performance in heavily occluded scenarios, with a Route Completion rate of 98.21% and a Driving Score of 76.02, while requiring low roadside communication bandwidth. Ultimately, this work pioneers an extensible V2X--VLM paradigm, paving the way for next-generation cooperative autonomous driving.
### Title:
          CoAnchor: Robust Collaborative Perception under Spatio-Temporal Misalignment via Object-Level Anchors
 - **Authors:** Chi Li, Rui Lin, Aobo Ji, Dongzhu Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collaborative perception extends the sensing range of a single vehicle by fusing observations from nearby agents, which improves the robustness of autonomous driving. In realistic deployments, however, the received collaborator messages are often affected by both communication delay and relative-pose noise, which jointly cause stale observations, spatial misalignment, and unstable feature fusion. Existing methods usually address these issues from either the spatial or temporal side, but handling them jointly in a unified and efficient manner remains challenging. In this paper, we propose CoAnchor, an anchor-centric spatio-temporal alignment framework for asynchronous collaborative perception. Instead of directly reasoning on dense BEV features, CoAnchor builds sparse object-level spatio-temporal anchors as a shared interface for pose correction and tightly connects spatial refinement, temporal propagation, and current-time verification within one unified loop, while keeping the overall correction process lightweight. Extensive experiments on both simulated and real-world datasets illustrate that CoAnchor remains competitive under clean settings and improves the robustness under joint delay and pose perturbations with a favorable practical accuracy-efficiency trade-off.
### Title:
          A2DINOv3: Rethinking Multi-Modal Object Detection via Socialized Collaboration
 - **Authors:** Jiekang Feng, Zhihe Fan, Yunqi Zhu, Xinjie Yao, Yueying Zhang, Yike Gao, Ranxin Li, Guanzuo Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal object detection is essential for robust scene understanding in challenging conditions, including low-light and adverse environments. Recent vision foundation models (e.g., DINOv3) have exhibited strong representation capabilities, yet adapting them to multi-modal scenarios remains challenging. Existing dense cross-modal fusion strategies often force heterogeneous modalities to interact indiscriminately, which may introduce redundant information and disrupt the valuable pre-trained representations. To address this issue, we revisit multi-modal fusion from the perspective of socialized learning and propose adapter to DINOv3 (A2DINOv3), a multi-expert collaboration framework with a Socialized Collaboration Protocol (SCP). Specifically, RGB and infrared branches are modeled as heterogeneous experts that independently preserve their specialized knowledge while exchanging complementary information through selective and constrained interactions. This design mitigates harmful cross-modal interference and prevents degradation of pre-trained priors during adaptation. Furthermore, a zero-initialization strategy is introduced to gradually activate cross-modal collaboration, enabling a smooth transition from modality-specific learning to cooperative representation learning. Extensive experiments on four multi-modal benchmarks, including aerial detection (GAIIC), autonomous driving (FLIR), low-light surveillance (LLVIP), and diverse real-world scenarios (M3FD), demonstrate that A2DINOv3 consistently achieves state-of-the-art performance in multi-modal object detection.
