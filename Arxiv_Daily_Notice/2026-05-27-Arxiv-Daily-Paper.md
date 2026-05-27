# Showing new listings for Wednesday, 27 May 2026
## Keyword: SLAM
### Title:
          Anonymous YARA Rules Are Not Anonymous
 - **Authors:** Usman Rabiu Isah, Laurent Bobelin, Pascal Berthomé
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 YARA rules are widely shared across threat intelligence communities to enable collective defence against malware. This practice implicitly assumes that removing metadata (e.g., author fields) sufficiently protects the identity of contributing organisations. To assess the validity of this assumption, we systematically evaluate how much can be inferred from YARA rule text alone. Specifically, using a corpus of 23,305 rules from three major public repositories, we train independent classifiers along four stylometric fingerprint dimensions: individual author, source repository, malware family, and temporal drift, using three complementary methods: lexical n-grams (Burrows' Delta), syntactic AST features (Caliskan-Islam), and fine-tuned CodeBERT. Our results demonstrate that repository origin is almost perfectly recoverable (up to 99% accuracy), individual authors can be re-identified well above chance (76%), and malware family classification reaches 95%. Comparing the same repository attribution task across full-history and time-restricted subsets reveals a 9-18% accuracy gap, providing preliminary evidence of temporal drift in repository this http URL further disentangle content from style, we conduct per-malware family author attribution experiments. Even when the malware family is the same for all samples considered, authors can still be re-identified for five of seven tested families (mean accuracy 74.6%). These findings constitute the first systematic demonstration that YARA rule sharing is a measurable OPSEC attack surface, and that metadata removal alone does not mitigate it.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Joint Instance Segmentation and Geometric Attribute Regression for Roof Structures in Aerial Imagery
 - **Authors:** Luuk Versteeg, Rob G.J. Wijnhoven, Martin R. Oswald
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a method for jointly predicting instance-level roof segment masks together with three continuous geometric attributes -- building height, roof slope, and roof azimuth -- from a single aerial orthophoto. Our approach extends Mask R-CNN with a dedicated attribute regression branch and introduces two key innovations: a conditional azimuth loss that suppresses supervision for flat roof segments where azimuth labels are inherently noisy, and a log-normalized height representation that addresses the heavily skewed distribution of building heights. We train and evaluate on a large-scale dataset of Dutch aerial images paired with automatically derived ground truth from 3DBAG, a nationwide LiDAR-based 3D building dataset. Using a DINOv3 ConvNeXt-Base backbone, our method achieves a mean absolute error of approximately 4 degrees for roof slope, 7 degrees for azimuth, and 1 meter for building height, with an instance segmentation AP$_{50}$ of 0.566. The predicted per-segment masks and attributes are sufficient to reconstruct simplified 3D building models (LoD2) from a single overhead image, requiring expensive 3D reference data only for training.
### Title:
          Annotator Positionality as Signal: Psychometric Weighting for Anti-Autistic Ableism Detection
 - **Authors:** Naba Rizvi, Harper Strickland, Saleha Ahmedi, Nedjma Ousidhoum
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used in decision-making tasks where they can amplify or suppress perspectives, raising concerns in high-stakes settings affecting autistic communities. While previous research has identified disability-related biases in LLMs, it remains unclear how they conceptualize ableism or detect it in text. We introduce a bias-aware evaluation framework targeting anti-autistic ableist language with a psychometrically-weighted, community-proximate ground truth anchored in annotator positionality. This framework constitutes a stricter standard than conventional majority-vote aggregation which significantly and consistently underweights autistic and autism-accepting perspectives. We find that LLMs frequently produce harmful outputs, mislabel community-reclaimed language as ableist, and express more negative attitudes toward autistic people when assessment instruments are masked. Our error analysis reveals that models rely on surface-level keyword matching rather than contextual factors such as speaker identity, and whether the language fosters in-group solidarity or inflicts out-group harm.
### Title:
          mmDiff: A Noise-Robust Differentiable Ray-Tracing Framework for mmWave Scene Calibration and Channel Prediction
 - **Authors:** Haofan Lu, Yadi Cao, Wanghao Yi, Omid Abari
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D reconstruction techniques such as LiDAR scanning and photogrammetry have made it practical to build detailed geometric models of real-world environments. Such reconstructed models can potentially serve as the foundation for wireless digital twins and support network planning and optimization. The core challenge is that reconstructed models inevitably contain geometric artifacts such as holes and noisy surfaces, and wireless simulation is highly sensitive to such noise. To solve this problem, we propose a differentiable directional scattering model to approximate the noise-sensitive specular reflection. This approximation smoothly distributes reflected power among nearby ray directions, making the simulator inherently robust to local geometric artifacts in the reconstructed model. We prove mathematically that this approximation preserves asymptotic path-gain accuracy. Building on this idea, we propose mmDiff, an end-to-end differentiable framework for calibrating material properties from sparse mmWave measurements and predicting mmWave channels. We evaluate mmDiff on both real-world and synthetic datasets, and demonstrate its superior performance over prior methods using pure specular reflection in noisy reconstructed geometry.
### Title:
          Sparse-LiDAR Prompting of Monocular Geometry Foundations: An Empirical Study Toward Long-Range Driving Depth
 - **Authors:** Kai Zheng, Qiang Feng, Xingjian Liu, Wenquan Tan, Yuan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse-LiDAR-prompted depth foundation models (PromptDA, Prior Depth Anything, DMD3C) have shown strong results on indoor scenes or within KITTI's standard 80-meter evaluation cap. However, two limitations remain: (i) systematic distance-stratified evaluation in long-range driving regimes (50-150 m) is largely absent; (ii) prior approaches built on disparity-based foundations rely on pre-interpolated dense priors, leaving truly sparse LiDAR injection on point-map foundations (e.g., MoGe-2, NeurIPS 2025) unexplored. We present SLIM (Sparse-LiDAR Injected Monocular geometry), the first adaptation of MoGe-2 to accept truly sparse LiDAR input. SLIM integrates a partial-convolution sparse encoder with a multi-scale fusion neck that fuses LiDAR features into the point-map decoder at five scales. We adopt density-agnostic training (random injection ratio in [0.005, 0.30]) so a single model serves diverse input densities. On Virtual KITTI and CARLA, SLIM reduces the absolute relative error of the MoGe-2 baseline by approximately 39-51% at 100-150 m. Ablation across six injection ratios shows partial-convolution injection improves both AbsRel and RMSE on Virtual KITTI in all six settings; on CARLA, AbsRel improves in five of six settings (one near-tie at 0.015 differs by 0.0013), and RMSE is comparable across encoders, with partial-convolution improving in three settings (by up to 0.31 unit) and losing by at most 0.11 unit in the other three.
### Title:
          3D Gaussian Map with Open-Set Semantic Grouping for Vision-Language Navigation
 - **Authors:** Jianzhe Gao, Rui Liu, Wenguan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language navigation (VLN) requires an agent to traverse complex 3D environments based on natural language instructions, necessitating a thorough scene understanding. While existing works equip agents with various scene representations to enhance spatial awareness, they often neglect the complex 3D geometry and rich semantics in VLN scenarios, limiting the ability to generalize across diverse and unseen environments. To address these challenges, this work proposes a 3D Gaussian Map that represents the environment as a set of differentiable 3D Gaussians and accordingly develops a navigation strategy for VLN. Specifically, Egocentric Scene Map is constructed online by initializing 3D Gaussians from sparse pseudo-lidar point clouds, providing informative geometric priors for scene understanding. Each Gaussian primitive is further enriched through Open-Set Semantic Grouping operation, which groups 3D Gaussians based on their membership in object instances or stuff categories within the open world, resulting in a unified 3D Gaussian Map. Building on this map, Multi-Level Action Prediction strategy, which combines spatial-semantic cues at multiple granularities, is designed to assist agents in decision-making. Extensive experiments conducted on three public benchmarks (i.e., R2R, R4R, and REVERIE) validate the effectiveness of our method.
### Title:
          Adaptation-Free Heterogeneous Collaborative Perception with Unseen Agent Configurations
 - **Authors:** Hyunchul Bae, Heejin Ahn
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collaborative perception improves 3D object detection by enabling agents to share complementary observations, but most existing methods assume fixed or known collaborator encoder configurations, limiting deployment in practice. In this work, we consider an open-world setting in which auxiliary agents with unseen configurations may appear after deployment, such as different LiDAR beam counts or encoder architectures. To address this challenge, we propose ALF, a collaborative perception framework that enables zero-adaptation collaboration with unseen agent configurations by lifting lightweight box-level messages into ego-compatible auxiliary features. ALF converts auxiliary box-level messages into pseudo-BEV maps and synthesizes ego-compatible latent features by combining object-centric cues with scene context from the ego feature. On V2X-Real, under a zero-shot evaluation across 64 case studies, ALF outperforms the strongest prior baseline by 35.91% in relative mAP@0.7 while requiring only 120 bytes per agent per frame (approximately 9.6 Kbps bandwidth at 10 Hz).
### Title:
          The Kalman Evolve: Closing the Gap in Kalman Filtering via Interpretable Algorithm Discovery
 - **Authors:** Vasileios Saketos, Ming Xiao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State estimation is a fundamental problem in control and signal processing, for which the Kalman Filter provides an optimal solution under linear dynamics, Gaussian noise, and known noise covariances. However, these assumptions often fail in realistic sensing settings such as Doppler radar and LiDAR. In these cases, the optimal estimator is inherently nonlinear, which leads to systematic performance degradation. This creates a performance gap that cannot be eliminated by tuning the noise covariance parameters (i.e., the process and measurement noise in the Kalman Filter) alone. To address this limitation, we propose Kalman Evolve, a framework for discovering improved filtering algorithms by jointly optimizing both noise parameters and the update structure. Our approach leverages large language models (LLMs) as a structured prior over program space, enabling the generation of interpretable, non-affine modifications to the classical Kalman filter while preserving its recursive form. We provide analytical results establishing the suboptimality of affine estimators under common nonlinear sensing models, motivating the need for structure-aware updates. Across a range of synthetic and real-world tracking benchmarks, including Doppler radar, LiDAR-based localization, and pedestrian tracking, the discovered algorithms consistently improve over strong baselines such as the Optimized Kalman Filter, achieving up to 12\% reduction in RMSE. These results suggest that optimizing the structure of the Kalman filter, rather than only its parameters, provides a practical and interpretable way to improve state estimation.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Planning Neural Dynamics with Lie Group Embedding through Supervised Projective Manifold Learning
 - **Authors:** Tianwei Wang, Bryan Chen, Qian Zuo, Qiyue Xia, Xin Li, Wei Pang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Dynamical Systems (math.DS); Rings and Algebras (math.RA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Lie group embedded dynamical neural networks (LieEDNN) and the corresponding learning algorithms based on gradient descent and metric projection on smooth manifold, where we treat Lie group as an intrinsic representation for continuous symmetry of manifold geometry. Thereby we achieve learnable and stable dynamics on the underlying manifold for general Lie group, and we are able to utilize the powerful representation capability of Lie group such as SO(3) and SE(3) to solve real world engineering problems in areas such as robotics, graphics, and control. Two core challenges are: (i) General Lie groups are incompatible with addition arithmetic, which is necessary for neural network interactions. (ii) The dynamics evolve in the nonlinear representation space of special algebra rather than the normal Euclidean space, which violates the paradigm of common neural ODEs. To address these two challenges, we firstly introduce adjoint Lie group action on the Lie algebra, which induces a linear mapping and transfer to the block-wise structure of weight matrices, such that addition could operate on the Lie algebra as a vector space. Then we parameterize the Lie algebra and the adjoint action as linear transformation so that the architecture is aligned with neural network perceptrons. Explicitly, this embedding appears as block-wise manifold constraints on weights, and we develop algorithms to learn the equilibrium with stability guarantees of the temporal neural network dynamics. Experiments are implemented on a specific Lie group SE(3), with the application scenario of telescopic manipulators.
### Title:
          When Correct Demonstrations Hurt: Rethinking the Role of Exemplars in In-Context Learning
 - **Authors:** Chenghao Qiu, Chunli Peng, Yufeng Yang, Kuan-Hao Huang, Yi Zhou
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) is often motivated by the intuition that demonstrations help because they provide correct input-output examples. However, we reveal a counterintuitive phenomenon: correctness does not guarantee exemplar utility, and some correct demonstrations can even reduce ICL accuracy. To study this correctness-utility gap, we introduce task-preserving perturbations, where only the exemplar input is changed, while the example remains a correct instance of the same task. Concretely, each perturbed exemplar is assigned the target induced by the task mapping. This framework covers both label-updating perturbations, where task-relevant semantics change and targets are recomputed, and stricter target-preserving perturbations, where the original target remains valid. We formalize the resulting failure mode as contextual evidence shift: task-preserving perturbations can change the effective mixture of evidence used by the model for contextual inference, thereby separating exemplar correctness from exemplar utility. Across sentiment classification, logical reasoning, and math word problems, we find that task-preserving perturbed demonstrations can substantially degrade ICL performance, especially for smaller models, harder tasks, and higher perturbation ratios. Our results show that robust ICL requires evaluating not only whether demonstrations are correct, but also how they influence contextual inference. Code is available at this https URL.
### Title:
          Cultural Value Alignment Via Latent Activation Steering in Large Language Models
 - **Authors:** Trung Duc Anh Dang, Sarah Masud
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) often exhibit homogenized cultural perspectives. While the World Values Survey (WVS) provides a gold standard for mapping human values, traditional direct prompting of LLMs on WVS often fails to access the model's latent cultural depth, leading to safety-aligned refusals or neutral responses. Here, we propose a generalizable framework for cultural evaluation and intervention that transitions from abstract queries to scenario-based behavioral probing. By extracting implicit token probabilities across 300 situational dilemmas, we bypass surface-level alignment to map the latent coordinates of LLMs cultural value. We further introduce activation steering to shift these internal alignments during the forward pass without retraining. Across multiple LLMs, we find substantial variation in adaptability and uncover a consistent phenomenon of latent entanglement, where interventions along one cultural dimension induce shifts along another. These results suggest that cultural values are encoded as coupled structures, limiting precise alignment. This work establishes a computationally efficient framework for cultural steering, highlighting the structural complexities when navigating global value with LLMs.
### Title:
          Comparative Study of Vision-Based Metric Measurement for Large-Scale Planar Scenes
 - **Authors:** ZhiXin Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-based metric distance and area measurement remains challenging in large-scale outdoor environments due to long-range sensing, camera zoom, and unstable imaging conditions. This work studies planar metric measurement in a real-world reservoir monitoring scenario using PTZ cameras and compares three representative approaches: geometry-based monocular ranging, image stitching with birds-eye-view transformation, and stereo-based ranging using two jointly calibrated monocular cameras. For monocular ranging, planar localization models are derived from camera geometry and the effect of camera pitch angle is analyzed. Image stitching is investigated for large-area mapping, while a stereo-based scheme is developed for long-range measurement without dedicated stereo hardware. Experiments show clear trade-offs: monocular ranging achieves meter-level accuracy under sufficiently large pitch angles, stereo-based ranging achieves decimeter-level accuracy with reduced sensitivity to pitch variations, and image stitching is effective for small-scale scenes but degrades in stability and scalability as scene size increases.
### Title:
          MSCGC-KAN: Multi-scale Causal Graph Convolution and Kolmogorov-Arnold Feature Mapping for EEG Emotion Recognition
 - **Authors:** Haoliang Gong, Qingshan She, Jiale Xua, Yunyan Gao, Xugang Xi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalogram (EEG)-based emotion recognition is an important affective computing task, and recent EEG foundation models provide useful generic representations for downstream adaptation. However, under the fine-tuning setting, three limitations remain prominent: insufficient modeling of multi-scale emotional dynamics, inadequate exploitation of inter-channel functional connectivity, and the limited expressive power of simple linear classification heads. To address these issues, this paper proposes a new EEG emotion recognition method, termed MSCGC-KAN, which introduces a structured task head composed of multi-scale causal graph convolution and Kolmogorov--Arnold feature mapping. Built on a pre-trained CBraMod backbone, MSCGC-KAN enhances downstream adaptation by jointly strengthening multi-scale temporal modeling, learnable inter-channel connectivity modeling, and nonlinear discriminative mapping within a compact task-specific head. This design preserves the representation advantage of the foundation model while making the classifier more sensitive to emotion-related spatiotemporal patterns. Extensive experiments are conducted on the public FACED and SEED-VII datasets. The proposed method achieves a balanced accuracy of 60.66\%, a Cohen's Kappa of 0.5525, and a weighted F1-score of 60.40\% on FACED, and obtains 33.27\%, 0.2223, and 33.64\%, respectively, on SEED-VII. Compared with the CBraMod+Linear baseline, the balanced accuracy is improved by 5.91 and 2.03 percentage points on the two datasets, respectively. These results indicate that structured task-head design is an effective way to improve EEG emotion recognition when fine-tuning pre-trained EEG models.
### Title:
          UnityMAS-O: A General RL Optimization Framework for LLM-Based Multi-Agent Systems
 - **Authors:** Yiqun Chen, Wei Yang, Erhan Zhang, Shijie Wang, Qi Liu, Zechun Niu, Bin Zhang, Haitao Li, Rui Li, Lingyong Yan, Jinyuan Feng, Biqing Qi, Xiaochi Wei, Yan Gao, Yi Wu, Yao Hu, Jiaxin Mao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based multi-agent systems decompose complex tasks into interacting roles, but most remain manually orchestrated by prompts, tools, and control rules, while agents are rarely optimized through a unified reinforcement learning interface. Existing RL post-training frameworks mainly target single-policy optimization and lack abstractions for user-defined multi-agent workflows, structured interaction, role-specific credit assignment, and configurable parameter sharing. We present UnityMAS-O, a general RL optimization framework for LLM-based multi-agent systems. UnityMAS-O treats the complete workflow as the optimization unit, rather than a single response or policy trajectory. It represents workflows through four first-class objects: logical agent roles, graph trajectories, user-defined rewards, and agent--model mappings. This decouples logical agents from physical model parameters, supporting full sharing, full separation, and partial sharing, with rewards assigned at role, turn, and trajectory levels. UnityMAS-O extends verl with a Ray-based star-topology runtime. A central controller executes workflows, invokes tools, records structured trajectories, and assembles rewards; model-local worker groups handle rollout, buffering, advantage computation, and distributed PPO-style updates. Users can define agents, workflows, model mappings, and rewards without rewriting the optimization infrastructure. We instantiate UnityMAS-O on retrieval-augmented QA, iterative agentic search, and reflective code generation. Across Natural Questions, HotpotQA, and held-out code tasks, multi-agent RL improves manually specified workflows after optimization, with especially large gains for smaller models and strict code all-passed metrics. These results show that UnityMAS-O can serve as a reusable substrate for converting diverse LLM-based multi-agent workflows into trainable multi-agent RL systems.
### Title:
          Joint 2D-3D Segmentation and Association in Street-level Imaging
 - **Authors:** Amir Melnikov, Masayuki Tanaka, Yusuke Monno, Masatoshi Okutomi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate interpretation of street-level imagery is essential for large-scale urban mapping and the creation of Spatial Digital Twin (SDT) environments. This work presents a unified framework for joint 2D-3D segmentation and association that integrates visual semantics with multi-view geometric reasoning. Unlike conventional approaches that rely heavily on sequential frames for temporal tracking, our method leverages zero-shot detection and segmentation together with structure-from-motion reconstruction to establish stable cross-view correspondences. A 3D-driven association mechanism replaces traditional 2D multi-object tracking, using geometric consistency to guide identity preservation across wide-baseline viewpoints and varying imaging conditions. By combining 2D texture cues with global 3D context, the proposed pipeline is well-suited for scalable street-level processing and can be used for a variety of object types. Experiments demonstrate substantially improved coverage of ground-truth sequences and more robust identity retention compared to state-of-the-art 2D-only tracking methods, achieving a 22% performance gain in challenging urban scenarios.
### Title:
          OSMa-Bench++: Toward Open-Ended Benchmarking of Semantic Mapping for Manipulation with Prompt-Generated Synthetic Scenes
 - **Authors:** Regina Kurkova, Maxim Popov, Sergey Kolyubin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic mapping methods are increasingly used as intermediate scene representations for downstream robotic reasoning and manipulation, yet their evaluation is still largely tied to fixed benchmark datasets with limited coverage of manipulation-relevant corner cases. In this work, we extend OSMa-Bench toward controllable benchmarking with prompt-generated synthetic indoor scenes. Our pipeline automatically generates scene descriptions, synthesizes corresponding environments with SceneSmith, and adapts the resulting assets into an OSMa-Bench-compatible simulation format. This adaptation requires a nontrivial intermediate layer, including semantic normalization, material and texture repair, shader fallback policies, floor handling, navigation setup, and controlled lighting configuration. A key advantage of the proposed setup is that the original scene-generation prompt is known in advance and can therefore serve as an auxiliary semantic specification of the intended scene. We use this property to extend the VQA component of OSMa-Bench with a prompt-grounded question category. The resulting framework supports targeted stress-testing of semantic scene representations under conditions such as clutter, small objects, partial occlusions, and lighting variation, and makes benchmarking more extensible and better aligned with downstream manipulation requirements. Our code is available at this https URL.
### Title:
          Optimising Factual Consistency in Summarisation via Preference Learning from Multiple Imperfect Metrics
 - **Authors:** Yuxuan Ye, Raul Santos-Rodriguez, Edwin Simpson
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning with evaluation metrics as rewards is widely used to enhance specific capabilities of language models. However, for tasks such as factually consistent summarisation, existing metrics remain underdeveloped, limiting their effectiveness as signals for shaping model this http URL individual factuality metrics are unreliable, their combination can more effectively capture diverse factual errors. We leverage this insight to introduce an automated training pipeline that improves factual consistency in summaries by aggregating scores from different weak metrics. Our approach avoids the need for complex reward shaping by mapping scores to preferences and filtering out cases with high disagreement between metrics. For each source document, we generate lexically similar summary pairs by varying decoding strategies, enabling the model to learn from factual differences caused by subtle lexical differences. This approach constructs a high-quality preference dataset using only source this http URL demonstrate consistent factuality gains across models, ranging from early encoder-decoder architectures to modern large language models, with smaller models reaching comparable factuality to larger ones.
### Title:
          SIMPC: Learning Self-Induced Mirror-Point Consistency for Unsupervised Point Cloud Denoising
 - **Authors:** Chengwei Zhang, Xueyi Zhang, Tao Jiang, Xinhao Xu, Wenjie Li, Fubo Zhang, Longyong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In point clouds, noise directly perturbs point coordinates that encode both spatial location and geometry, making one-to-one correspondence construction more challenging than in images. Existing methods impose statistical mappings across noisy variants via noise or optimal transport, but suffer from correspondence ambiguity. In this work, we propose Self-Induced Mirror-Point Consistency (SIMPC) to learn deterministic correspondences between points and the underlying surface in an unsupervised manner. For each noisy point, SIMPC generates a mirror-point on the opposite side of the underlying surface, guided by geometric priors during the denoising process. By encouraging consistency between the denoising targets of the original point and its mirror counterpart, SIMPC effectively localizes the position of underlying surface. Extensive experiments on synthetic and real-world datasets demonstrate that SIMPC significantly outperforms state-of-the-art unsupervised methods and surpasses several strong supervised counterparts.
### Title:
          Negligible in Size, Significant in Effect: On Scale Vectors in Large Language Models
 - **Authors:** Mingze Wang, Shuchen Zhu, Yuxin Fang, Binghui Li, Kai Shen, Shu Zhong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Normalization layers in modern large language models (LLMs) consist of a deterministic normalization operation and a learnable scale vector. While the normalization operation has been extensively studied, the scale vector remains poorly understood despite its ubiquitous use. In this work, we present a systematic study of scale vectors in LLMs from the perspectives of expressivity, optimization, and architectural structure. First, we show empirically that although scale vectors constitute only a negligible fraction of model parameters, removing them substantially degrades LLM pre-training. Our theory further shows that, in Pre-Norm architectures, scale vectors do not increase expressivity; instead, they improve optimization through a self-amplifying preconditioning effect on subsequent linear mappings. Second, we investigate the role of weight decay for scale vectors. By distinguishing Input-Norm and Output-Norm layers, we theoretically show that weight decay is beneficial for the former but harmful for the latter, due to their distinct roles in optimization and expressivity. Third, motivated by this understanding, we propose three lightweight and complementary improvements to scale vectors: branch-specific heterogeneity, improved placement around linear mappings, and magnitude-direction reparameterization. Both theory and experiments show that each improvement yields consistent gains. Finally, we combine these improvements into a unified scale-vector strategy and evaluate it through extensive LLM pre-training experiments on dense and mixture-of-experts models ranging from 0.12B to 2B parameters, across multiple optimizers and learning rate schedules, under industrial-scale token budgets. The unified strategy consistently achieves lower terminal loss than well-tuned baselines and exhibits more favorable scaling behavior, while adding negligible parameter and computational overhead.
### Title:
          BEAT: Rhythm-Elastic Alignment for Agentic Music-guided Movie Trailer Generation
 - **Authors:** Yutong Wang, Yunke Wang, Xinyuan Chen, Chang Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic movie trailer generation must select shots from a full-length film and synchronize them with background music. Existing methods either relegate music alignment to post-processing or enforce rigid one-to-one shot-music mappings, overlooking that professional editing rhythm is elastic: rapid cuts accompany high-energy passages while sustained shots span quieter bars. We introduce BEAT, a framework that addresses this gap with two core components: MuVA, a compact music-visual alignment encoder trained with Sinkhorn-regularized two-stage learning, and Bar-DP, an energy-adaptive dynamic programming algorithm that produces elastic many-to-one alignments following musical dynamics. These components are integrated into a five-phase agentic pipeline that grounds the core alignment in learned cross-modal features while coordinating higher-level creative decisions through structured text signals. To support comprehensive evaluation, we also introduce TrailerArena, a benchmark with 20+ metrics across four complementary dimensions. On TrailerArena, BEAT achieves state-of-the-art performance across shot selection, ordering, and perceptual quality, while producing fully composed trailers end-to-end.
### Title:
          Towards Drone-based Mapping of Volcanic Gases using Gas Tomography
 - **Authors:** Marius Schaab, Niklas Karbach, Antonia Rabe, Thomas Wiedemann, Patrick Hinsen, Dmitriy Shutin, Thorsten Hoffmann, Achim J. Lilienthal
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Volcanoes emit large amounts of CO2, directly influencing human lives. Mapping volcanic gas emissions helps to forecast eruptions and understand the impact of volcanoes on climate and the environment. Drone-based gas sensing significantly reduces risks in volcanic monitoring but faces technical limitations when measuring gas, as rotor downwash disperses the gas plume before detection. Gas Tomography using remote gas sensing addresses this challenge. At the Salinelle dei Cappuccini mud volcanoes, we demonstrate that while drone-mounted in-situ sensors failed to detect CO2 emissions due to aerodynamic disturbance, open-path sensing successfully enabled remote gas distribution mapping. We present a novel model-based gas tomographic reconstruction approach that incorporates a Lagrangian model to compensate for wind-induced advection. The resulting gas distribution maps align with manually collected in-situ measurements, confirming that model-based gas tomography effectively overcomes downwash limitations and enables accurate mapping of volcanic emissions.
### Title:
          ENPMR-Bench: Benchmarking Proactive Memory Retrieval for Emotional Support Agents
 - **Authors:** Xing Fu, Yulin Hu, Mengtong Ji, Haozhen Li, Yixin Sun, Weixiang Zhao, Yanyan Zhao, Bing Qin
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Memory-augmented language agents are increasingly deployed in affective applications such as emotional support, where understanding and responding to users' latent emotional needs is critical. However, existing research often treats memory as a tool for factual retrieval, overlooking its role in shaping users' emotional experiences. In this work, we introduce ENPMR-Bench, a benchmark for evaluating Emotional Need-aware Proactive Memory Retrieval (ENPMR), a core capability that enables agents to infer users' latent emotional needs and proactively retrieve appropriate memories to support empathetic interaction. Grounded in Maslow's hierarchy of needs, ENPMR-Bench includes over 1,800 memory-augmented dialogues and defines structured mappings between emotional needs and supportive memory types. Experimental results demonstrate that current retrieval paradigms, including both embedding-based and LLM-driven approaches, exhibit substantial deficiencies, with empathy scores significantly lagging behind golden memory conditions. While chain-of-thought prompting improves the alignment between inferred emotional needs and retrieved memories to some extent, a notable performance gap remains. Together, these findings reveal critical limitations in current agents and outline directions for advancing personalized emotional support through need-sensitive memory retrieval.
## Keyword: localization
### Title:
          Reproducibility Companion Paper: Swarical: An Integrated Hierarchical Approach to Localizing Flying Light Specks
 - **Authors:** Hamed Alimohammadzadeh, Shahram Ghandeharizadeh, Federico Cunico, Joshua Springer
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This companion paper provides artifacts and instructions on replicating the experiments in the ACM Multimedia 2024 paper entitled "Swarical: An Integrated Hierarchical Approach to Localizing Flying Light Specks." Swarm-based hierarchical, Swarical, is a localization technique that enables miniature drones, Flying Light Specks (FLSs), to accurately and efficiently localize and illuminate complex 2D and 3D shapes. It consists of two components, an offline planner and an online localization technique that executes on an FLS. The offline planner uses the FLS sensor specification for positioning to convert mesh files into swarms of FLSs. Some FLSs are dark and used only for localization. We reported the online localization technique to be fast and highly accurate. We describe how to reproduce this finding using our artifacts.
### Title:
          Energy-Gated Attention and Wavelet Positional Encoding: Complementary Inductive Biases for Transformer Attention
 - **Authors:** Athanasios Zeris
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard transformer attention computes pairwise token similarity but treats all tokens as equally salient and all positions as equally local, regardless of the informational structure of the input. We identify two complementary inductive biases that standard attention lacks: energy salience (which tokens concentrate informational energy, learned end-to-end without explicit frequency decomposition) and scale-selective locality (how far positional influence extends at each frequency, implemented via Morlet wavelet encoding). We address both with two simple components. Energy-Gated Attention (EGA) gates value aggregation by a learned energy estimate of key token embeddings, computed via a single linear projection; it selects what to attend to. Morlet Positional Encoding (MoPE) replaces fixed sinusoidal encodings with learned Gaussian-windowed wavelets that adapt the joint position-frequency localization to the corpus; it specifies where attention operates at each scale. On TinyShakespeare, EGA alone achieves +0.092 validation loss improvement over standard attention (+0.103 over Phase 1-3 baseline); MoPE alone is -0.032 (below baseline as a standalone encoding); but their combination achieves +0.119 -- more than the sum of parts. This superadditivity, observed across two independent training runs, is the central empirical finding: salience and locality are complementary inductive biases, each addressing a gap the other cannot fill alone. Ablations confirm that structured spectral priors (Morlet wavelet gates, scale-initialized heads, fixed sinusoidal PE) consistently underperform their unconstrained learned counterparts, while complementary learned components interact superadditively. All experiments are at small scale (<=6M parameters, character-level benchmarks, single seed); larger-scale multi-seed validation is the most important direction for future work.
### Title:
          OmniGF: A Dual-Branch Vision-Language Framework for Unified Gaze Following
 - **Authors:** Qiaomu Miao, Haoyu Wu, Jingyi Xu, Minh Hoai, Dimitris Samaras
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding human gaze behavior is essential for complex scene comprehension and human-computer interaction. Traditional gaze following models are typically restricted to pure spatial localization, lacking the high-level capacity to reason about semantic targets or complex social contexts. Furthermore, these models often process individuals sequentially, requiring redundant computations over the same scene image for multi-person inference. While recent Vision-Language Models (VLMs) offer the exceptional semantic reasoning needed to address gaze-related semantic tasks, their reliance on discrete text generation inherently limits precision in continuous spatial tasks like gaze localization. To bridge this gap, we propose OmniGF, a unified vision-language framework that adapts foundational VLMs for highly scalable multi-person gaze reasoning. The model adopts a dual-branch decoding strategy: a structured language branch generates discrete reasoning states, while a continuous spatial branch directly taps into the VLM's dense hidden states. Supervising these extracted representations with high-resolution gaze target heatmaps effectively overcomes the spatial bottleneck of text-only coordinate generation. Furthermore, to explicitly ground the model in multi-person scenes, we augment the input with head embeddings encoded from cropped head images, providing fine-grained appearance and orientation cues for all individuals simultaneously. By modeling all individuals and leveraging the strong semantic capability of VLMs, OmniGF seamlessly integrates precise spatial gaze target estimation, semantic gaze prediction, and complex social gaze reasoning. Extensive experiments demonstrate that our framework establishes new state-of-the-art performance across multiple standard benchmarks. Code is available at this https URL.
### Title:
          AnchorDiff: Training-Free Concept Grounding for MM-DiTs via Anchor-Based Graph Propagation
 - **Authors:** Jian Zhang, Zhijun Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Modal Diffusion Transformers (MM-DiTs) encode rich representations for training-free concept grounding, but existing attention-based methods often produce overlapping activations on visually confusable concepts, a failure mode we call concept leakage, where target responses spill over to non-target objects. To address this issue, we propose AnchorDiff, a training-free grounding method that decouples semantic localization from structural refinement. AnchorDiff selects a high-confidence anchor from concept-to-image attention map and propagates it as a one-hot seed over a hybrid graph derived from image-to-image self-attention. The graph uses output-space similarity for dense within-object propagation and a row-wise attention gate to suppress cross-object connections. Additionally, we introduce the Multi-Concept Confusion Dataset, which contains images with multiple visually similar concepts and separate masks, enabling explicit evaluation of concept leakage. Experiments show that AnchorDiff achieves strong grounding performance on ImageNet-Segmentation and PascalVOC, while substantially reducing concept leakage on our Multi-Concept Confusion Dataset.
### Title:
          Diffuse to Detect: Generative Diffusion Models for Unsupervised IC Anomaly Detection
 - **Authors:** Yuxuan Yin, Chen He, Todd Jacobs, Jialei He, Boxun Xu, Robert Jin, Peng Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent defect screening is challenged by extremely low failure rates, high-dimensional test data, and absence of labeled anomalies. We propose the first unsupervised anomaly detection framework incorporating a Diffusion Transformer. Raw test measurements are first compressed by an autoencoder, then reshaped into a structured token sequence enriched with sinusoidal and per-device wafer-position embeddings. Anomaly scores are derived from the noise-prediction error over mid-range diffusion timesteps, enabling fast wafer-scale screening without any labeled defects or manual feature engineering. Our approach achieves state-of-the-art performance on industrial 16nm IC test data under extreme class imbalance, offering interpretable failure localization through latent-space reconstruction residuals.
### Title:
          Comparative Study of Vision-Based Metric Measurement for Large-Scale Planar Scenes
 - **Authors:** ZhiXin Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-based metric distance and area measurement remains challenging in large-scale outdoor environments due to long-range sensing, camera zoom, and unstable imaging conditions. This work studies planar metric measurement in a real-world reservoir monitoring scenario using PTZ cameras and compares three representative approaches: geometry-based monocular ranging, image stitching with birds-eye-view transformation, and stereo-based ranging using two jointly calibrated monocular cameras. For monocular ranging, planar localization models are derived from camera geometry and the effect of camera pitch angle is analyzed. Image stitching is investigated for large-area mapping, while a stereo-based scheme is developed for long-range measurement without dedicated stereo hardware. Experiments show clear trade-offs: monocular ranging achieves meter-level accuracy under sufficiently large pitch angles, stereo-based ranging achieves decimeter-level accuracy with reduced sensitivity to pitch variations, and image stitching is effective for small-scale scenes but degrades in stability and scalability as scene size increases.
### Title:
          A Hybrid Vision-Language Architecture for Automated Defect Reasoning and Report Generation in Industrial Inspection
 - **Authors:** Malikussaid, Imad Gohar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated industrial inspection requires both precise defect localization and structured maintenance report generation; in current practice these tasks are handled separately, with linguistic interpretation left to human experts. This paper describes a decoupled, edge-deployable pipeline for wind turbine blade inspection built from three components that each handle a distinct sub-task. The Eyes a YOLO26-x-obb oriented bounding-box detector localizes defects at dataset-native resolution. The Bridge a deterministic, parameter-free encoding module maps each detected bounding box to grid-referenced spatial tokens embedded in a structured prompt. The Brain a 4-bit quantized Qwen-2.5-1.5B model adapted with Quantized Low-Rank Adaptation (QLoRA) on 947 synthetically generated maintenance reports generates a structured JSON report from that prompt. Retrieval-Augmented Fine-Tuning (RAFT) further grounds each recommendation in indexed maintenance procedures. Five ablation experiments, scored by BLEU-4, ROUGE-L, Hallucination Rate (HR), and an LLM-as-a-Judge rubric, compare the pipeline against a monolithic vision-language model (VLM) baseline and against partial configurations in which one component is removed. The complete system achieves BLEU-4 0.41, HR=4%, and Expert Score = 8.6/10 compared with 0.07, 65%, and 3.3/10 for the zero-shot VLM baseline. The QLoRA-adapted 1.5B model generates higher-quality reports than a 671B-parameter generalist API model given identical detection evidence, at 47 tokens per second on a single T4-class GPU. The results show that purpose-built decoupled architecture with a small domain-specific training corpus outperforms a generalist end-to-end model on this structured generation task.
### Title:
          Joint Localization and Orientation with Triple-Beam Fingerprints in Massive MIMO-OFDM
 - **Authors:** Yu Zhao, Zhenzhou Jin, Jinke Tang, Li You, Chen Sun, Xiang-Gen Xia, Xiqi Gao
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the widespread application of location-based services, fingerprint-based localization has demonstrated advantages in environments with complex signal propagation. Deep learning has significantly improved the efficiency of both offline training and online matching in localization processes. However, existing fingerprints only contain terminal position information without capturing motion states, and neural network designs have not fully incorporated structural features such as fingerprint sparsity. In this paper, we propose a triple-beam fingerprint (TBF) incorporating Doppler information and design a Transformer-based localization and orientation awareness network (LOA-Net) to simultaneously estimate user position and motion direction in massive multiple-input multiple-output (MIMO) orthogonal frequency division multiplexing (OFDM) systems. We first show the correlation between TBF and multipath information, and investigate the collinearity of different TBFs, demonstrating that TBF is an effective small-size sparse fingerprint. Then, we propose LOA-Net containing a mask-augmented detection Transformer for regression (MaskDETR-Reg) module and a fusion-enhanced Transformer for direction classification (Fusion-TDC) module to process angle-delay domain information and Doppler domain information, respectively. Finally, in the simulation of indoor scenarios defined in 3GPP 38.901, the proposed method achieves significantly better localization accuracy than weighted $K$-nearest neighbors (WKNN), 2D and 3D convolutional neural networks (CNNs), and achieves satisfactory motion direction estimation accuracy.
### Title:
          TrajAudit: Automated Failure Diagnosis for Agentic Coding Systems
 - **Authors:** Minxing Wang, Xiaofei Xie, Yintong Huo
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic systems have been widely studied to automate software engineering jobs such as bug fixing. As these systems increasingly tackle complex tasks, understanding where and why they fail becomes essential for iterative refinement and operational reliability. Existing automated failure diagnosis approaches leverage task execution trajectories, yet their effectiveness degrades substantially as trajectory length and complexity increase. For repository-level coding tasks specifically, trajectories are laden with noise, such as redundant program structure and verbose code context. Moreover, these trajectories are very long, while long-context reasoning remains a known weakness of LLMs. To address these two challenges, we propose TrajAudit, the first failure diagnosis framework for repository-level coding trajectories. TrajAudit employs an investigator agent supported by two modules: one filters failure-irrelevant information through pattern matching and keyword detection, and the other generates a preliminary diagnosis from test failure reports as prior knowledge, helping the agent handle noisy long contexts. The investigator agent can further invoke tools to retrieve filtered content on demand, ensuring that critical information is preserved while noise is minimized. We also introduce RootSE, a benchmark of 93 real-world agentic failure instances sourced from software maintenance tasks, representing the most complex trajectory diagnosis benchmark to date. Experiments on RootSE show that TrajAudit outperforms all existing baselines by over 24.4 percentage points in localization accuracy, while reducing token consumption by at least 18%, demonstrating its practical effectiveness. We hope this work draws community attention to failure management in agentic software engineering and provides a foundational resource for future research.
### Title:
          Attenuation-Resilient Alternating Optimization for Laparoscopic Liver Landmark Detection
 - **Authors:** Lanqing Liu, Ruize Cui, Jialun Pei, Diandian Guo, Tiffany Y. So, Pheng-Ann Heng, Jing Qin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Liver surface landmark detection is a fundamental prerequisite for anatomical guidance in laparoscopic liver surgery. However, it remains unreliable in practice due to two pervasive challenges: illumination attenuation in underexposed regions and the structural mismatch between pixel-wise localization and continuous curvilinear geometry. To address these limitations, we propose A2ONet, an attenuation-resilient alternating optimization network for robust liver landmark detection. To mitigate illumination attenuation, A2ONet embraces an illumination field compensation (IFC) block that adaptively enhances dark regions while preserving structural consistency. Meanwhile, we introduce a lightweight frequency-orientation selective filter (FOSF) to suppress repetitive texture interference and preserve salient curvilinear cues. Building upon these resilient representations, we design an alternating seg-curve optimization (ASCO) decoder that iteratively couples dense segmentation with explicit curve modeling, enabling mutual guidance to optimize both structural continuity and endpoint localization. Extensive evaluations on L3D-2K, L3D, and P2ILF demonstrate consistent improvements over competitive methods, establishing a more reliable foundation for intraoperative anatomy guidance. Our code will be available at this https URL.
### Title:
          Memory-Distilled Selection for Noise-Robust Anomaly Detection
 - **Authors:** Sirojbek Safarov, Jaewoo Park, Yoon Gyo Jung, Kuan-Chuan Peng, Wonchul Kim, Seongdeok Bang, Octavia Camps
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anomaly detection (AD) under data contamination is critical for deploying unsupervised defect detection in industrial environments, where curating perfectly clean training sets is impractical. However, existing methods are sensitive to contamination, suffering significant performance degradation as the noise ratio increases. In this paper, we propose Memory-Distilled Selection (MeDS), a training algorithm based on data selection. MeDS constructs an ensemble of partial memories via random subsampling, where the resulting sparsity acts as a low-pass filter that captures nominal patterns across a wide range of noise ratios, enabling coarse-level identification of contaminated samples. The aggregated distances to the bootstrapped memories are then distilled into a reconstruction score network, which is subsequently fine-tuned on clean data filtered using scores from the distilled model, enabling fine-grained localization of anomalies. MeDS is robust across a wide range of noise ratios without requiring noise-ratio-specific hyperparameter tuning, achieving 99.16\% image-level AUROC on MVTecAD at a 40\% noise ratio, and attaining state-of-the-art performance on both VisA and Real-IAD under noisy settings. We thoroughly verify the efficacy of MeDS on industrial AD benchmarks under noisy data scenarios, accompanied by in-depth empirical analyses.
### Title:
          Localizing Memorized Regions in Diffusion Models via Coordinate-Wise Curvature Differences
 - **Authors:** Gwangho Kim, Sungyoon Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models can unintentionally memorize training samples, raising concerns about privacy and copyright. While recent methods can detect memorization, they often rely on global or model-specific signals and provide limited insight into where memorization appears within a generated image. We provide a geometric characterization of local memorization as a coordinate-wise variance collapse. However, such collapse can also arise from intrinsic data constraints rather than overfitting. To isolate overfitting-driven memorization, we propose curvature-difference methods that subtract the curvature of an underfitted baseline, either the unconditional model or a less-trained version of itself. We further derive a score-difference proxy that provides a geometric explanation for the widely used score-difference-based detection metric. Experiments on Stable Diffusion, evaluated against ground-truth memorization masks, show that our method outperforms the prior attention-based localization method. Code is available at this https URL.
### Title:
          The Kalman Evolve: Closing the Gap in Kalman Filtering via Interpretable Algorithm Discovery
 - **Authors:** Vasileios Saketos, Ming Xiao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State estimation is a fundamental problem in control and signal processing, for which the Kalman Filter provides an optimal solution under linear dynamics, Gaussian noise, and known noise covariances. However, these assumptions often fail in realistic sensing settings such as Doppler radar and LiDAR. In these cases, the optimal estimator is inherently nonlinear, which leads to systematic performance degradation. This creates a performance gap that cannot be eliminated by tuning the noise covariance parameters (i.e., the process and measurement noise in the Kalman Filter) alone. To address this limitation, we propose Kalman Evolve, a framework for discovering improved filtering algorithms by jointly optimizing both noise parameters and the update structure. Our approach leverages large language models (LLMs) as a structured prior over program space, enabling the generation of interpretable, non-affine modifications to the classical Kalman filter while preserving its recursive form. We provide analytical results establishing the suboptimality of affine estimators under common nonlinear sensing models, motivating the need for structure-aware updates. Across a range of synthetic and real-world tracking benchmarks, including Doppler radar, LiDAR-based localization, and pedestrian tracking, the discovered algorithms consistently improve over strong baselines such as the Optimized Kalman Filter, achieving up to 12\% reduction in RMSE. These results suggest that optimizing the structure of the Kalman filter, rather than only its parameters, provides a practical and interpretable way to improve state estimation.
### Title:
          REVERSE: Reinforcing Evidence Verification and Search for Agentic Image geo-localization
 - **Authors:** Yong Li, Furong Jia, Dacheng Yin, Kang Rong, Fengyun Rao, Jing Lyu, Fan Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image geo-localization aims to determine where a photograph was taken, a task that often requires more than recognizing visible landmarks. Human experts typically solve it through an iterative workflow: they inspect informative regions, form location hypotheses, seek external evidence, and revise their judgments as new clues appear. Existing methods only partially capture this process: direct prediction methods bypass evidence acquisition altogether, while retrieval-augmented methods introduce external evidence but usually provide limited supervision on the intermediate decisions of where to search, how to query, and how to filter noisy results. We present REVERSE, a framework that reinforces the interplay between evidence search and verification to enable multi-turn agentic reasoning. REVERSE teaches three intermediate decisions: where to look, what to query, and what evidence to trust. To support this, we construct tool-grounded trajectories with annotated region selections, search observations, and geo-informative evidence labels, and introduce process rewards for visual grounding, query utility, and evidence discrimination. An offline search cache makes retrieval observations stable and reusable during reinforcement learning, enabling dense supervision over noisy search results. With a 4B model, REVERSE outperforms strong retrieval-augmented baselines and rivals substantially larger models on Im2GPS3k and YFCC4k. Code is available at this https URL.
### Title:
          YOLO26-RipeLoc Lite: A lightweight architecture for tomato ripeness detection and picking point localization in greenhouse robotic harvesting
 - **Authors:** Rajmeet Singh, Manveen Kaur, Shahpour Alirezaee, Irfan Hussain
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In greenhouse tomato production, automated harvesting requires accurate detection of ripe tomatoes, ripeness classification, and precise picking-point localization for robotic end-effectors. This paper proposes YOLO26-RipeLoc Lite, a lightweight deep learning architecture based on YOLO26 for simultaneous detection, ripeness classification, and center-point localization of greenhouse tomatoes. The model introduces three modifications: (1) a Lightweight Feature Pyramid Network (LFPN) with depthwise separable convolutions for efficient multi-scale fusion, (2) a Ripeness-Aware Attention Module (RAAM) with dual pooling and a learnable ripeness bias vector for enhanced color-texture discrimination, and (3) a Compact Detection Head (CDH) with shared convolutions and an integrated center-point regression branch for direct grasp planning. The model is evaluated on a custom dataset of 1,500 images with 6,227 instances (3,566 ripe, 2,661 unripe) from the SILAL greenhouse, Abu Dhabi, UAE. YOLO26-RipeLoc Lite achieves mAP@0.5 of 92.9% (95.2% ripe, 90.6% unripe) with the highest precision (95.2%) among all evaluated architectures using only 2.38M parameters. Post-training BatchNorm pruning at 30% reduces parameters to ~1.8M with negligible accuracy loss. Ablation studies confirm that greenhouse-aware HSV augmentation provides the largest improvement (+2.02 pp mAP@50), backbone freezing achieves peak precision (93.8%), and 3-phase progressive unfreezing yields the best localization quality (mAP@50:95 of 64.6%). Comparisons with YOLOv8n/s, YOLO11n/s, YOLO12n/s, and YOLO26s confirm superior accuracy-efficiency: 2.9 pp higher precision than YOLO12n with 7.0% fewer parameters and integrated center-point localization for robotic end-effector guidance.
### Title:
          EviACT: An Evidence-to-Action Framework for Agentic Program Repair
 - **Authors:** Qianru Meng, Xiao Zhang, Zhaochun Ren, Joost Visser
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based agents have moved automated program repair (APR) from fixed-context patch generation to interactive repository-level repair. However, existing agentic APR systems still struggle to use execution evidence to guide localization, patch generation, and validation. We propose EviACT (Evidence-to-Action), an agentic APR framework that coordinates three evidence-driven guardrails across repair stages. The retrieval scaffold grounds repair context, the compile gate filters invalid edits, and the test-driven gate checks target-test recovery before full regression. Across four benchmarks, EviACT improves resolve rate over the strongest reported comparable baselines by 1.6-6.0 percentage points and shows 70.1-88.6% lower reported per-bug API cost where baseline costs are available. Ablations and diagnostics suggest that these gains are associated with the coordinated evidence-to-action chain, making agentic APR more effective and efficient.
### Title:
          Normal Guidance is what Attention Needs
 - **Authors:** Ethan Harvey, Dennis Johan Loevlie, Michael C. Hughes
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We consider training classifiers for 3D medical images using only one binary label for the entire volume rather than a label for each 2D slice. In such weakly supervised settings, can we learn accurate classifiers for slice-level predictions? Attention-based multiple instance learning (MIL) can produce an attention score for every slice. Yet recent work demonstrates that a simple center-focused baseline that ignores image content can outperform attention-based and transformer-based MIL at slice-level classification of 3D brain scans. We show this baseline also outperforms existing MIL at slice-level classification of thoracic and abdominal CT scans. Motivated by this baseline, we propose Normal Guidance, a regularization technique that encourages the learned attention distribution to follow a bell-shaped curve. Across three medical imaging datasets totaling over 4 million 2D slices, we show our Normal Guidance enables attention-based and transformer-based MIL methods to deliver significantly better slice-level localization than the state-of-the-art while remaining competitive at whole-scan classification.
### Title:
          Feedforward 3D Editing Learns from Semantic-Part Transformation
 - **Authors:** Jiawei Weng, Saining Zhang, Zhenxin Diao, Peishuo Li, Henghaofan Zhang, Junhao Chen, Hao Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D editing is a fundamental capability for scalable 3D content creation. While image editing has rapidly evolved toward large-scale feedforward generative paradigms, 3D AI generation remains dominated by training-free editing pipelines. A central challenge of feedforward 3D editing lies in the lack of high-quality paired supervision. Editable 3D assets require simultaneous preservation of geometry, multi-view consistency, structural coherence, and localized edit controllability. Existing 3D editing datasets often rely on independently generated assets, image-mediated reconstruction or narrow edit taxonomies, leading to inaccurate localization, weak preservation, blurred edit boundaries, and limited semantic consistency. In this work, we introduce a new perspective: scalable feedforward 3D editing should be learned from semantic-part transformations. Based on this insight, we propose Pxform, a high-quality 3D editing dataset with over 100K consistent before/after editing pairs across seven edit types. Instead of treating objects as unstructured shapes, our pipeline grounds edits directly in semantic 3D parts. Built upon Pxform, we further propose PartFlow, a feedforward 3D editing network that injects source-aware latent control into pretrained 3D generative priors. PartFlow introduces mask-aware velocity preservation and render-space consistency supervision to jointly improve edit fidelity and source preservation, while requiring no 3D edit mask during inference. Extensive experiments demonstrate that high-quality semantic-part supervision substantially improves scalable 3D editing, enabling PartFlow to achieve state-of-the-art performance on both geometric and appearance editing benchmarks.
### Title:
          LocateAnything: Fast and High-Quality Vision-Language Grounding with Parallel Box Decoding
 - **Authors:** Shihao Wang, Shilong Liu, Yuanguo Kuang, Xinyu Wei, Yangzhou Liu, Zhiqi Li, Yunze Man, Guo Chen, Andrew Tao, Guilin Liu, Jan Kautz, Lei Zhang, Zhiding Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) commonly formulate visual grounding and detection as a coordinate-token generation problem, serializing each 2D box into multiple 1D tokens that are learned and decoded largely independently. This token-by-token decoding mismatches the coupled structure of box geometry and creates a practical inference bottleneck due to strictly sequential generation. We introduce LocateAnything, a unified generative grounding and detection framework based on Parallel Box Decoding (PBD). By decoding geometric elements such as bounding boxes and points as atomic units in a single step, LocateAnything preserves intra-box geometric coherence and unlocks substantial parallelism. We show that PBD improves both decoding throughput and localization accuracy. We further develop a scalable data engine and curate LocateAnything-Data, a large-scale dataset with more than 138 million training samples, substantially increasing data diversity for high-precision localization. Extensive evaluations show that LocateAnything advances the speed-accuracy frontier, achieving significantly higher decoding throughput while improving high-IoU localization quality across diverse benchmarks. The results highlight the complementary benefits of Parallel Box Decoding and large-scale training data in enabling efficient and precise unified visual grounding and detection.
## Keyword: transformer
### Title:
          Semantic-aware Token Selection and Resource Optimization for Communication-efficient Split Federated Fine-tuning in Edge Intelligence
 - **Authors:** Xianke Qiang, Zheng Chang, Geyong Min
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying large Transformer-based vision models on resource-limited mobile devices at network edge is severely constrained by hardware limitations and dynamic wireless environments. While federated learning (FL) enables collaborative training without sharing raw data, strictly local fine-tuning of such massive models remains computationally prohibitive for edge devices. Split federated learning (SFL) alleviates this burden by offloading deep layers to the edge server, yet it suffers from heavy communication overhead when transmitting high-dimensional activation tokens. To address this bottleneck, we propose ST-SFLora, a semantic token-based split federated LoRA fine-tuning framework. We introduce a new metric, \emph{Semantic Transmission Efficiency} (STE), to balance semantic retention and transmission cost. Based on STE, we formulate a joint resource optimization problem that dynamically determines token selection, uplink bandwidth allocation, and transmit power under latency and energy constraints. The resulting mixed-integer nonconvex problem is efficiently solved via an alternating algorithm. Experiments on multiple benchmarks demonstrate that ST-SFLora achieves the lowest client-side resource consumption among baselines while delivering a favorable trade-off between communication efficiency and model performance.
### Title:
          HRVConformer: Neonatal Hypoxic-Ischemic Encephalopathy Classification from the Heart Rate signals
 - **Authors:** Shuwen Yu, William P Marnane, Geraldine B. Boylan, Gordon Lightbody
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents the HRVConformer, a novel deep learning architecture for the classification of hypoxic-ischemic encephalopathy (HIE) using the instantaneous heart rate (HR) signal. Unlike conventional approaches that rely on handcrafted features, HRVConformer directly processes raw HR signals in an end-to-end manner, capturing both local and long-range dependencies through a hybrid Convolution-Transformer framework. By integrating convolutional layers for local feature extraction and Transformer-based attention mechanisms for global context modelling, the architecture effectively enhances signal representation and classification performance. The model was trained using supervised learning on a large HR dataset consisting of 1,573 one-hour epochs, including 259 one-hour expert-annotated epochs and a substantial set of weakly labelled data. A 314-hour validation set provided a robust performance estimation, while an independent 215-hour dataset with expert annotations was reserved for final testing. HR signals were extracted from electrocardiogram (ECG) recordings using an improved Pan-Tompkins algorithm, which significantly enhanced both signal quality and data availability. Experimental results demonstrate that the HRVConformer achieves an AUC of 83.23\% and accuracy of 74.56\% on the test set. These results surpass the performance of the Transformer, ResNet50 and fully convolutional networks baselines, highlighting the advantages of integrating convolutional and Transformer-based components for HR-based HIE classification. The proposed method provides a promising step toward a more accurate and automated assessment of HIE using HR signals. The code is available at: this https URL.
### Title:
          On the Role of Inductive Bias in Time-Series Pretraining: A Case Study in Learning Generalizable Representations for Clinical Time Series
 - **Authors:** Sharmita Dey, Diego Paez-Granados
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Clinical time-series learning is routinely constrained by small, heterogeneous cohorts and protocol drift, while its downstream use spans both classification (e.g., pathology diagnosis) and regression (e.g., temporal forecasting). These constraints make foundation-model pretraining appealing, but raises an important question of which inductive biases should the pretraining objective impose so that representations transfer across task types and subjects. We study this question in pathological gait analysis for spinal cord injury (SCI) via PathoFM, an encoder-centric transformer pretrained on multivariate gait windows with three complementary objectives: Local Completion (reconstruct contiguous masked spans to enforce local structure), Temporal Continuity (predict a masked mid-horizon continuation from an observed prefix to enforce smoothness and causal consistency), and Unsupervised In-Context Dynamics (support-query reconstruction conditioned on subject exemplar windows via attention). Empirically comparing objective families (grouping/contrastive, dynamics-based, and generative reconstruction), we find that dynamics-centric mixtures produce the most balanced transfer: grouping objectives favor discriminative margins but can degrade magnitude fidelity needed for continuous targets, whereas reconstruction-only objectives preserve waveform structure but may underperform on classification. Overall, combining local reconstruction with temporal continuity, and adding in-context conditioning when exemplar access is realistic, yields robust subject-generalizing representations.
### Title:
          Benchmarking Convolutional, Transformer, Hybrid, and Vision Language Models for Multi Disease Retinal Screening
 - **Authors:** Durjoy Dey, Aymane Ajbar, Yuhong Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern deep learning offers powerful tools for automated retinal screening, but it remains unclear how different visual model families compare in realistic multi-disease settings and under domain shift. In this work, we benchmark twelve architectures across four model families: convolutional neural networks, vision transformers, hybrid CNN-transformer backbones, and vision-language models, using the Retinal Fundus Multi-disease Image Dataset (RFMiD). We evaluate two tasks: binary screening for any retinal disease and multi-label classification across 28 disease classes. Using standardized training, calibration, and evaluation protocols, we report AUC, F1, precision, recall, and sensitivity at a clinically relevant operating point with specificity near 80%. On RFMiD, all architectures perform well on binary screening, with AUC above 84%, but attention-based models perform best. SwinTiny and the hybrid CoAtNet0 and MaxViTTiny models achieve the strongest binary screening results and improve macro and micro F1 in the multi-label setting. Vision-language models, including CLIP ViT-B/16 and SigLIP-Base384, are competitive with CNN baselines but do not surpass the best transformer and hybrid backbones. In external validation on Messidor-2 for referable diabetic retinopathy, AUC ranges from 66.8% to 84.7%, with hybrid and transformer models again showing strong performance. These results provide a reproducible reference for model selection in multi-disease retinal screening and guide future automated screening tools for clinical deployment.
### Title:
          PhyPush: One Push is All You Need for Sensorless Physical Property Estimation with Physics-Guided Transformers
 - **Authors:** Koyo Fujii, Luis Figueredo, Praminda Caleb-Solly, Ivan Boschi, Edoardo Ida', Marco Carricato, Aly Magassouba
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately estimating object mass and friction is fundamental to achieving reliable and adaptive robotic manipulation. Although interactive perception provides a powerful mechanism for inferring such properties, most existing approaches depend on specialized hardware such as force/torque sensors, tactile arrays, or multi-camera motion-capture systems, limiting scalability and deployment. This paper presents PhyPush, a physics-guided Transformer framework that estimates an object's mass and friction coefficient using only kinematically derived end-effector velocity from a single push. This typically requires data available on standard robotic arms. The model incorporates constraints from Newton's second law and the Coulomb friction model through a physics-guided loss, improving physical consistency and generalization to unseen objects and surfaces. Across diverse simulation and real-world setups, PhyPush consistently achieves more accurate mass and friction estimation in challenging out-of-domain conditions. In simulation, it reduces error by over 10% compared with a baseline that has privileged access to full force information, while in real-world experiments, it outperforms a data-driven loss approach. Overall, the results demonstrate that physics-guided learning can enable low-cost, sensor-efficient estimation of physical properties, relying solely on a single push and readily available kinematic data.
### Title:
          Dynamic Link Prediction with Temporally Enhanced Signed Graph Neural Networks
 - **Authors:** Derek Regier, Andrew Polyak, Aresh Dadlani, Khosro Salmani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal signed networks (TSNs) model the time evolution of cooperative and adversarial relationships that arise in applications such as social media analysis, trust and reputation systems, and financial transaction networks. While graph neural networks (GNNs) perform well for static or unsigned link prediction, effective learning in temporal signed graphs remains challenging due to the interaction of signed relations, evolving structure, and balance-theoretic constraints. To address this gap, we propose a \emph{modular} temporal enhancement framework for signed GNNs that integrates historical context into otherwise static architectures. The framework introduces a Historical Context Integration Module (HCIM) that combines learnable recency-aware temporal weighting, LSTM-based embedding trajectory modeling, and multi-head temporal attention to capture both short- and long-term signed interaction dynamics. Historical information is fused with current node representations using either global or node-adaptive weighting, allowing the architecture-agnostic framework to accommodate heterogeneous temporal behaviors. We instantiate the approach on the Self-Explainable Signed Graph Transformer (SE-SGformer), preserving interpretability while extending it with temporal awareness. Experiments on real-world and synthetic TSNs, including Bitcoin OTC, Bitcoin Alpha, Reddit, and small-world network models, demonstrate consistent and statistically significant improvements over the static baseline.
### Title:
          CNNs, Transformers, Hybrid, and Vision Language Models for Skin Cancer Detection
 - **Authors:** Durjoy Dey, Yuhong Yan, Hassan Hajjdiab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Skin cancer is a common and fast rising malignancy worldwide. Early detection is critical for improving outcomes. Deep learning models trained on dermoscopic and clinical images can support automated and fast triage. However, many studies evaluate only a limited set of architectures. Experimental setups also vary across studies. In this paper, we present a unified evaluation of twelve deep learning models for binary skin cancer detection on the PAD-UFES-20 dataset. The models span four families: convolutional neural networks (CNN), vision transformers (ViT), hybrid convolution transformer backbones, and vision language models (VLM). Performance is assessed using AUC, the maximum F1 score with its precision and recall, and sensitivity at 80% specificity, reflecting screening oriented requirements. Our results show that well tuned CNNs already provide strong baselines, but transformer based families consistently improve discrimination. Hybrid models (MaxViT Tiny, CoAtNet0) and a SigLIP based VLM achieve the best overall trade off between ranking performance and clinically relevant operating points, while CLIP based model offers high precision. The full codebase for all experiments is publicly released. Together, these findings offer practical guidance on which model families are most suitable for real world deployment in skin cancer screening and establish a reproducible reference point for future work on PAD-UFES-20.
### Title:
          MechRL: Reinforcement Learning Agents Perform Circuit Discovery for Mechanistic Interpretability
 - **Authors:** Barsat Khadka
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability has identified small sets of attention heads that implement specific behaviours in transformer language models, but recovering these circuits typically requires a bespoke analytical pipeline for each new task. We recast circuit discovery as a reinforcement-learning problem. An agent operates over the 144 attention heads of GPT-2 small as a discrete action space; each action triggers a zero-ablation and a contrastive reward that subtracts the ablation's damage to general next-token prediction from its damage to the target task. A single PPO policy, trained on two tasks (induction and IOI) in a vectorised multi-task environment, attains the per-episode oracle on both training tasks and on a held-out third task (docstring completion). Its preferred heads coincide with the canonical heads of established literature on precisely the axes those papers identify as causally non-redundant under single-head ablation; the categories they identify as redundant are correctly de-prioritised by the agent. On the held-out task, best-of-five planning recovers 96\% of the oracle ceiling with no task signal supplied at evaluation. These results indicate that reinforcement learning over causal interventions is a viable, transferable substrate for identifying the single-head bottlenecks of mechanistic circuits, complementary to existing path-patching approaches.
### Title:
          Energy-Gated Attention and Wavelet Positional Encoding: Complementary Inductive Biases for Transformer Attention
 - **Authors:** Athanasios Zeris
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard transformer attention computes pairwise token similarity but treats all tokens as equally salient and all positions as equally local, regardless of the informational structure of the input. We identify two complementary inductive biases that standard attention lacks: energy salience (which tokens concentrate informational energy, learned end-to-end without explicit frequency decomposition) and scale-selective locality (how far positional influence extends at each frequency, implemented via Morlet wavelet encoding). We address both with two simple components. Energy-Gated Attention (EGA) gates value aggregation by a learned energy estimate of key token embeddings, computed via a single linear projection; it selects what to attend to. Morlet Positional Encoding (MoPE) replaces fixed sinusoidal encodings with learned Gaussian-windowed wavelets that adapt the joint position-frequency localization to the corpus; it specifies where attention operates at each scale. On TinyShakespeare, EGA alone achieves +0.092 validation loss improvement over standard attention (+0.103 over Phase 1-3 baseline); MoPE alone is -0.032 (below baseline as a standalone encoding); but their combination achieves +0.119 -- more than the sum of parts. This superadditivity, observed across two independent training runs, is the central empirical finding: salience and locality are complementary inductive biases, each addressing a gap the other cannot fill alone. Ablations confirm that structured spectral priors (Morlet wavelet gates, scale-initialized heads, fixed sinusoidal PE) consistently underperform their unconstrained learned counterparts, while complementary learned components interact superadditively. All experiments are at small scale (<=6M parameters, character-level benchmarks, single seed); larger-scale multi-seed validation is the most important direction for future work.
### Title:
          Unified Panoramic Geometry Estimation via Multi-View Foundation Models
 - **Authors:** Vukasin Bozic, Isidora Slavkovic, Dominik Narnhofer, Nando Metzger, Denis Rozumny, Konrad Schindler, Nikolai Kalischek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometry estimation from perspective images has greatly advanced, maturing to the point where off-the-shelf foundation models are able to reconstruct 3D scene structure not only from multi-view imagery, but even from a single view. A natural extension is 3D reconstruction from panoramas, with the exciting prospect of recovering a full 360-degree scene from a single panoramic image. In this work, we introduce PaGeR (Panoramic Geometry Reconstruction), a framework to lift powerful 3D foundation models designed for perspective imagery to the panorama domain. Our strategy is to start from a pre-trained transformer for 3D reconstruction and turn it into a unified high-performance model that predicts scale-invariant depth, metric depth, surface normals, and sky masks from both perspective and omnidirectional images, in a single forward pass. By keeping architectural changes to a minimum and mixing perspective and panoramic images during training, PaGeR retains the rich 3D prior of the underlying foundation model while learning to also estimate geometrically consistent 360-degree scenes from single panoramas. We extensively test our method in both indoor and outdoor environments and find that it delivers state-of-the-art performance and excellent zero-shot performance across a wide range of scenes.
### Title:
          The Rescue Effect: Spatio-Semantic Early Exit Bypasses Quantization Collapse in CLIP
 - **Authors:** Kahyeon Nam, Hyesong Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying Vision-Language Models on resource-constrained hardware typically requires INT8 quantization, but in joint-embedding architectures such as CLIP this introduces a failure mode distinct from quantized CNN classifiers: activation noise accumulated across transformer blocks perturbs the direction of the multimodal embedding, eroding the cosine alignment on which zero-shot retrieval depends. We characterize this as Quantization-Induced Representation Collapse (QIRC) and quantify it on INT8 CLIP ViT-B/32, where the layer-wise noise-to-signal ratio grows from below 10% in shallow blocks to 52% at Layer 11. We propose LRA-EE (Layer-wise Representation-Aware Early Exit), which bypasses noise-saturated deep layers via Spatio-Semantic Aggregation (replacing the immature shallow [CLS] with a global patch-token average), a learned multi-feature gate (confidence, top-2 margin, spatial-activation variance), and Layer-adaptive Confidence Thresholding calibrated to each layer's Information-to-Noise Ratio. On ImageNet-1K zero-shot classification, LRA-EE reduces FLOPs by 13.4% and improves Top-1 accuracy by +2.44%p (58.72% -> 61.16%) over the INT8 baseline. A four-quadrant decomposition isolates the Rescue Effect: 9.5% of samples are correctly classified at shallow exits but lost to noise at full depth, against only 7.1% suffering the inverse.
### Title:
          Cross-scale Aligned Supervision for Training GANs
 - **Authors:** Sangeek Hyun, MinKyu Lee, Jae-Pil Heo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern GANs often introduce adversarial supervision on intermediate generator outputs and interpret the resulting multi-stage synthesis as coarse-to-fine hierarchical generation. In this work, we challenge this interpretation. We argue that standard scale-wise adversarial supervision does not construct a proper coarse-to-fine hierarchy: each intermediate image is independently pushed toward the real distribution at its own resolution, but this scale-wise realism does not ensure that outputs across stages represent the identical generated sample. Moreover, the scale-specific image produced at each stage is not used as an explicit refinement target for the subsequent stage. Therefore, its adversarial loss can improve a scale-specific output without constraining later stages to preserve the same sample trajectory, allowing them to move toward a different sample rather than refine the previous output. We refer to this problem as a cross-scale trajectory misalignment problem. To resolve it, we propose CAT, a Cross-scale Aligned Transformer for multi-scale adversarial generation. CAT keeps the discriminator scale-wise, so each intermediate output is evaluated at its own resolution, while adding a simple generator-side consistency regularization that aligns intermediate outputs with the final output. On class-conditional ImageNet-256, CAT-H/2 achieves an FID-50K of 1.56 with one-step inference after only 60 training epochs, outperforming strong one-step GAN and diffusion/flow baselines.
### Title:
          AnchorDiff: Training-Free Concept Grounding for MM-DiTs via Anchor-Based Graph Propagation
 - **Authors:** Jian Zhang, Zhijun Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Modal Diffusion Transformers (MM-DiTs) encode rich representations for training-free concept grounding, but existing attention-based methods often produce overlapping activations on visually confusable concepts, a failure mode we call concept leakage, where target responses spill over to non-target objects. To address this issue, we propose AnchorDiff, a training-free grounding method that decouples semantic localization from structural refinement. AnchorDiff selects a high-confidence anchor from concept-to-image attention map and propagates it as a one-hot seed over a hybrid graph derived from image-to-image self-attention. The graph uses output-space similarity for dense within-object propagation and a row-wise attention gate to suppress cross-object connections. Additionally, we introduce the Multi-Concept Confusion Dataset, which contains images with multiple visually similar concepts and separate masks, enabling explicit evaluation of concept leakage. Experiments show that AnchorDiff achieves strong grounding performance on ImageNet-Segmentation and PascalVOC, while substantially reducing concept leakage on our Multi-Concept Confusion Dataset.
### Title:
          Diffuse to Detect: Generative Diffusion Models for Unsupervised IC Anomaly Detection
 - **Authors:** Yuxuan Yin, Chen He, Todd Jacobs, Jialei He, Boxun Xu, Robert Jin, Peng Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Latent defect screening is challenged by extremely low failure rates, high-dimensional test data, and absence of labeled anomalies. We propose the first unsupervised anomaly detection framework incorporating a Diffusion Transformer. Raw test measurements are first compressed by an autoencoder, then reshaped into a structured token sequence enriched with sinusoidal and per-device wafer-position embeddings. Anomaly scores are derived from the noise-prediction error over mid-range diffusion timesteps, enabling fast wafer-scale screening without any labeled defects or manual feature engineering. Our approach achieves state-of-the-art performance on industrial 16nm IC test data under extreme class imbalance, offering interpretable failure localization through latent-space reconstruction residuals.
### Title:
          Heterogeneous AAV Logistics Task Allocation: A Reinforcement Learning Enhanced Overlapping Coalition Formation Game Approach
 - **Authors:** Yuze Zhou, Jingliang Sun, Junzhi Li, Jianxin Zhong, Zihan Wang, Teng Long
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In dynamic urban logistics, the stochastic emergence of time-sensitive tasks poses a significant optimality challenge for heterogeneous AAVs logistics task allocation. To address this problem, a reinforcement learning enhanced overlapping coalition formation game approach is proposed. A dynamic task allocation model is established, where global optimality is mathematically quantified by a generalized logistics cost coupling service quality and resource consumption. To deal with the time-varying task sets induced by stochastic order arrivals, a transformer-based soft actor-critic network is designed. By leveraging multi-head self-attention to encode variable-length logistics states and capture task-wise spatiotemporal dependencies, the learned policy adaptively guides coalition updates, replacing heuristic rules in the overlapping coalition formation game. On this basis, heterogeneous AAVs can form more efficient overlapping coalitions for dynamic logistics tasks. The resulting coalition formation process is proven to constitute an exact potential game, which guarantees convergence to a Nash-stable equilibrium within a finite number of iterations. Numerical simulations demonstrate that the proposed algorithm effectively improves the optimality of task allocation under the generalized logistics cost criterion. In a scenario with 32 AAVs and 80 tasks, our algorithm achieves a 39.76% cost reduction compared with the heuristic OCF baseline. Indoor flight experiments further validate its practicality.
### Title:
          The Stability of Singular Distribution: A Spectral Perspective on the Two-Phase Dynamics of Language Model Pre-training
 - **Authors:** Hongtao Zhang, Wenjie Zhou, Chenxi Jia, Wei Chen, Xueqi Cheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model pre-training typically exhibits a two-phase trajectory: a fast initial loss drop followed by a prolonged slow improvement. We identify an underlying spectral phenomenon, Stability of Singular Distribution (SoSD), where the trace-normalized singular value spectrum stabilizes early, even as parameter matrices continue to evolve. We demonstrate that synchronization between SoSD and the slow-descent regime is widely observed across diverse architectures (GPT-2, LLaMA) and settings, including various schedules (Step-wise, WSD, Cosine Decay), weight decays, and optimizers (AdamW, Muon). By analyzing a simplified Transformer, we prove that growing weight norms inevitably precipitate an early SoSD threshold, after which the rate of loss decrease becomes theoretically bounded by the variation in the singular distribution. We further interpret strategies like WSD and Muon through their ability to modulate the SoSD scale, offering a spectral lens for understanding efficient pre-training dynamics.
### Title:
          PRISM: Position-encoded Regressive Inverse Spectral Model for Multilayer Thin-Film Design
 - **Authors:** Runtian Wang, Renhao Xue, Baige Chen, Hao Wu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The inverse problem of multilayer thin-film optical coatings design represents a complex combinatorial-continuous optimization challenge. We present PRISM (Position-encoded Regressive Inverse Spectral Model), a unified decoder-only autoregressive transformer that streamlines this process by jointly predicting discrete material selection and continuous thickness regression within a single backbone. PRISM introduces two primary architectural innovations: (1) spectrum prefix conditioning, which utilizes standard prefix tokens for in-context target injection, and (2) cumulative-depth Rotary Position Embeddings, which encode continuous thickness directly into the positional representation to preserve the physical spatial relationships of the stack. Our benchmarks demonstrate that a PRISM-13M model reduces MAE by over 50\% compared to other transformer baselines while utilizing only one-fifth of the parameters. Furthermore, a 44M-parameter variant achieves state-of-the-art performance (MAE = 0.010) on our in-distribution validation benchmark and operates significantly faster than simulated annealing, offering a highly efficient alternative to classical optimization methods.
### Title:
          SIKA-GP: Accelerating Gaussian Process Inference with Sparse Inducing Kernel Approximations for Bayesian Deep Learning
 - **Authors:** Wenyuan Zhao, Rui Tuo, Chao Tian
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Probability (math.PR); Computation (stat.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaussian processes (GPs) provide a principled Bayesian framework for uncertainty estimation, but their computational complexity severely limits scalability to large datasets. We propose SIKA-GP, which accelerates GP inference using sparse inducing kernel approximations based on a dyadic ordered template basis, incurring only ${O}(\log M)$ complexity dependence on the number of inducing points. Our approach constructs compact and expressive kernel representations from sparsely activated bases, enabling efficient tensorized GPU computation and seamless integration with modern large-scale models. SIKA-GP can be naturally embedded into Bayesian neural networks (BNNs) with sparse activations, yielding significant speedups in both training and inference without sacrificing predictive performance. The method naturally extends to deep feature learning, addressing the scalability challenges introduced by deep architectures and high-dimensional feature representations. Empirical results on vision and transformer-based language benchmarks demonstrate that our approach consistently delivers fast and accurate GP models, providing a principled path toward scalable kernel learning.
### Title:
          CSV-ViT: A Vision Transformer with the Variable-sized Cortical Supervertices for Detection of Alzheimer's Disease Pathologies
 - **Authors:** Geonwoo Baek, Ikbeom Jang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Confirming Alzheimer's disease (AD) typically relies on positron emission tomography (PET), which remains costly and invasive, motivating the use of structural MRI-based prescreening. Deep learning on non-Euclidean manifolds, particularly brain cortical surfaces, faces significant challenges due to the data's spherical topology. Recent surface models have enabled learning from cortical surface data; however, imposing face-based uniform patches often causes duplicate vertices at patch boundaries. In general, many surface-based models are limited in their awareness of the region of interest (ROI), which can result in non-cortical regions, such as the medial wall, being included. We propose a cortical surface tokenization that performs ROI-preserving, vertex-based, variable-sized patch partitioning. We refer to these cortical surface patches as cortical supervertices (CSVs). Building on this representation, we design the CSV Vision Transformer (CSV-ViT), a variable-size patch-tolerant Vision Transformer that uses padding and a mask-aware patch embedding. We used T1-weighted MRI and evaluated our framework by classifying AD-related status into three categories: AD diagnosis, amyloid positivity, and tau positivity. Across the experiments, CSV-ViT achieved higher classification performance than recent surface-based models. The results suggest that the proposed CSV-ViT may support MRI-based prediction of AD-related status prior to PET or CSF confirmation.
### Title:
          CmIVTP: Cross-modal Interaction-based Vessel Trajectory Prediction for Maritime Intelligence
 - **Authors:** Yuxu Lu, Dong Yang, Xiaoyu Li, Mengwei Bao, Congcong Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maritime intelligent transportation systems (MITS) are essential for ensuring navigation safety and efficiency in busy waterways. However, accurate vessel trajectory prediction remains challenging due to the limitations of single-source data. Automatic identification system (AIS) data is often sparse or unavailable for small vessels, while closed-circuit television (CCTV) data alone cannot fully capture dynamic vessel behavior. To mitigate these challenges, we propose a cross-modal interaction-based vessel trajectory prediction (named CmIVTP) framework to model the intricate interactions between vessel dynamics and environmental constraints. Specifically, we introduce a target-aware scene encoder to extract scene semantic features, effectively capturing vessel-environment interactions and enhancing trajectory prediction accuracy. In addition, we propose a cross-modal interaction transformer, which integrates AIS-derived motion features, CCTV-based environmental features, and scene representations. It leverages cross-modal attention mechanisms to simultaneously capture intra-modal semantics and inter-modal interactions, ensuring dynamically consistent and environmentally feasible predictions. Furthermore, we construct a vessel group trajectory bank by clustering historical AIS trajectories into representative motion patterns, providing an efficient and scalable approach for candidate trajectory generation. Additionally, we introduce the maritime multimodal dataset plus (named Maritime-MmD$^+$), a large-scale dataset that synchronizes AIS data and CCTV video data, providing robust support for multimodal trajectory prediction research. Extensive experiments demonstrate that CmIVTP achieves better performance on multimodal-driven vessel trajectory prediction benchmarks. The code resources for this work can be available at this https URL.
### Title:
          Joint Localization and Orientation with Triple-Beam Fingerprints in Massive MIMO-OFDM
 - **Authors:** Yu Zhao, Zhenzhou Jin, Jinke Tang, Li You, Chen Sun, Xiang-Gen Xia, Xiqi Gao
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the widespread application of location-based services, fingerprint-based localization has demonstrated advantages in environments with complex signal propagation. Deep learning has significantly improved the efficiency of both offline training and online matching in localization processes. However, existing fingerprints only contain terminal position information without capturing motion states, and neural network designs have not fully incorporated structural features such as fingerprint sparsity. In this paper, we propose a triple-beam fingerprint (TBF) incorporating Doppler information and design a Transformer-based localization and orientation awareness network (LOA-Net) to simultaneously estimate user position and motion direction in massive multiple-input multiple-output (MIMO) orthogonal frequency division multiplexing (OFDM) systems. We first show the correlation between TBF and multipath information, and investigate the collinearity of different TBFs, demonstrating that TBF is an effective small-size sparse fingerprint. Then, we propose LOA-Net containing a mask-augmented detection Transformer for regression (MaskDETR-Reg) module and a fusion-enhanced Transformer for direction classification (Fusion-TDC) module to process angle-delay domain information and Doppler domain information, respectively. Finally, in the simulation of indoor scenarios defined in 3GPP 38.901, the proposed method achieves significantly better localization accuracy than weighted $K$-nearest neighbors (WKNN), 2D and 3D convolutional neural networks (CNNs), and achieves satisfactory motion direction estimation accuracy.
### Title:
          Few-shot Cross-country Generalization of Tabular Machine Learning and Foundation Models for Childhood Anemia Prediction under Distribution Shift
 - **Authors:** Yusuf Brima, Marcellin Atemkeng, Lansana Hassim Kallon, David Niyukuri, Antoine Vacavant, Samuel Saidu, Ding-Geng Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Childhood anemia affects around 40% of children aged 6-59 months globally and arises from heterogeneous factors, limiting model generalizability. We evaluate a transformer-based tabular foundation model against classical supervised methods under cross-country and data-scarce settings. We used DHS data from 16 countries across Africa, Asia, Latin America, the Caucasus, and the Middle East (n=68,856). We compared Logistic Regression, XGBoost, LightGBM, and TabPFN v2.6. Performance was assessed using AUC-ROC, Brier score, and ECE. Generalization was evaluated using leave-one-country-out (LOCO), reverse-LOCO, and few-shot settings. Subgroup analyses included sex, age, residence, maternal education, and wealth. Feature importance was estimated using SHAP. TabPFN outperformed classical models in low-data regimes (<200 samples), showing higher discrimination and better calibration. Across countries, it achieved the lowest Brier score (0.042) and ECE (0.203). Under full-data settings, AUC-ROC ranged from 0.59-0.76 with small between-model differences ($\leq 0.05$). LOCO performance was stable (0.58-0.69), driven by country context. Reverse-LOCO showed asymmetric transferability. Subgroup performance was consistent with no systematic demographic bias. SHAP identified child age, altitude, and height-for-age z-score as dominant predictors, followed by wealth and maternal education. Performance in childhood anemia prediction is driven more by population variation than model choice. TabPFN provides advantages in low-resource settings through improved discrimination and calibration, highlighting foundation models as promising tools for data-scarce global health prediction.
### Title:
          Tail-Aware HiFloat4: W4A4 Post-Training Quantization for Wan2.2
 - **Authors:** Zhanfeng Feng, Shuai Guo, Xin Di, Long Peng, Yang Cao, Zhengjun Zha
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This report describes Tail-Aware HiFloat4, our submission to the low-bit text-to-video generation quantization challenge. Our method adapts the public ViDiT-Q post-training quantization pipeline to Wan2.2 under the HiFloat4 numerical format. We quantize the main linear layers in both Wan2.2 transformer modules with W4A4 HiFloat4 fake quantization, keep numerically sensitive boundary modules in high precision, and introduce an activation-tail-aware percentile calibration module for channel-mask construction. Together with compact PTQ-state restoration, this design reduces the influence of rare calibration outliers while keeping the runtime HiFloat4 arithmetic and sampling pipeline unchanged.
### Title:
          RT-Lynx: Putting the GEMM Sparsity In a Right Way for Diffusion Models
 - **Authors:** Xing Cong, Hanlin Tang, Kan Liu, Lan Tao, Lin Qu, Chenhao Xie
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiT) achieve strong performance in image generation but incur substantial inference costs. While prior work has reduced this cost via quantization and distillation, semi-structured sparsity, which can nearly halve FLOPs, remains underexplored. A key reason is that most existing approaches focus on weight sparsification, and pruning 50% of the weights can remove critical model capacity and degrade generation quality. Our study, however, shows that DiT activations are intrinsically sparse and significantly more robust to N:M semi-structured sparsification than weights. Motivated by this observation, we advocate a paradigm shift from weight sparsification to activation sparsification. We propose RT-Lynx, which applies N:M sparsification to activations and incorporates error-compensation techniques to mitigate accuracy loss. We further implement highly optimized CUDA kernels tailored to this setting, achieving up to a 1.55x speedup on average in linear layers. Extensive experiments across multiple diffusion models demonstrate that our method preserves the generation quality of the original models while substantially accelerating inference.
### Title:
          JetViT: Efficient High-Resolution Vision Transformer with Post-Training Attention Search
 - **Authors:** Dongyun Zou, Zhuoyang Zhang, Junyu Chen, Wenkun He, Qinhe Peng, Hanrong Ye, Yao Lu, Hongxu Yin, Yu Wang, Song Han, Han Cai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce JetViT, a novel family of hybrid-architecture Vision Transformer (ViT) models that match the accuracy of state-of-the-art full-attention vision foundation models while achieving substantially higher inference efficiency on high-resolution images. At the core of our approach is Post-Training Attention Search, a post-training acceleration framework that converts pre-trained full-attention ViTs into efficient hybrid-attention variants by identifying and replacing redundant full-attention blocks with linear or window-attention blocks. By inheriting the MLP and attention weights from the base model, Post-Training Attention Search efficiently explores the architectural design space through three key steps: (1) optimizing the linear-attention block design; (2) finding the best combination of linear-attention and window-attention blocks; and (3) identifying and preserving critical full-attention blocks. We evaluate JetViT on two representative high-resolution vision foundation models, DINOv3 and DepthAnythingV2. On the NVIDIA H100 GPU, JetViT achieves up to 1.79x higher throughput and up to 44.81% lower latency without sacrificing accuracy. We will release our code and accelerated ViT models soon.
### Title:
          More Expressive Feedforward Layers: Part I. Token-Adaptive Mixing of Activations
 - **Authors:** Mingze Wang, Jinbo Wang, Yikuan Xia, Kai Shen, Shu Zhong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feedforward network (FFN) layers account for a large fraction of parameters and nonlinear expressivity in Transformer-based large language models (LLMs). Despite the evolution from ReLU and GELU to gated variants such as SwiGLU, most FFN designs still use a single fixed activation function, applying the same nonlinear transformation to all tokens. In this work, we propose Mixture of Activations (MoA), a token-adaptive FFN design that mixes a dictionary of activation functions using lightweight input-dependent gates while sharing the same linear projections. As an input-independent counterpart, we also introduce learnable activations (LA), which form linear combinations of activation functions for both ReLU-type and SwiGLU-type FFNs. Theoretically, we establish strict finite-width expressive separations among fixed-activation FFNs, LA, and MoA: LA strictly contains fixed-activation FFNs, while MoA strictly contains LA, with the additional expressivity arising from input-dependent nonlinear hybridization. Empirically, we evaluate MoA through extensive pre-training experiments on dense and MoE language models ranging from 0.12B to 2B parameters under different token budgets, optimizers, and learning rate schedules. MoA consistently achieves lower terminal loss and exhibits more favorable scaling behavior than well-tuned baselines, with minimal parameter and computational overhead. These results suggest that token-adaptive activation mixing is a simple and effective mechanism for improving FFN expressivity in LLMs.
### Title:
          L2Rec: Towards Dual-View Understanding of LLMs for Personalized Recommendation
 - **Authors:** Pingjun Pan, Tingting Zhou, Peiyao Lu, Tingting Fei, Hongxiang Chen, Chuanjiang Luo
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adapting large language models (LLMs) for personalized recommendation requires aligning their general-purpose capabilities with user-specific preferences while effectively leveraging both behavioral and semantic signals. Existing approaches typically integrate these signals at either the input level (e.g., injecting behavioral embeddings into the token space) or the output level (e.g., contrastive alignment of separate encoders), suffering from distribution gaps or lack of end-to-end task supervision. In this work, we introduce L2Rec, which unifies behavioral and semantic understanding at the parameter level of LLMs. Our key insight is that the same set of Transformer parameters can serve as a shared medium for both views: by applying view-specific, personalized low-rank perturbations via a Dual-view Personalized Mixture-of-Experts (DPMoE) mechanism, L2Rec enables a single LLM backbone to produce complementary behavioral and semantic adaptations for each user with minimal representation-level misalignment. An adaptive cross-view fusion module further integrates the dual-view outputs into a unified user preference. Experiments on four datasets show that L2Rec consistently outperforms state-of-the-art baselines, and online A/B testing on a large-scale industrial platform validates significant improvements in key engagement metrics.
### Title:
          SeDT: Sentence-Transformer Decision-Transformer Conditioning for Multi-Turn Conversation Reliability
 - **Authors:** Ramakrishna Vamsi Setti, Jagadeesh Rachapudi, Sachin Chaudhary, Praful Hambarde, Amit Shukla
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) achieve impressive performance when a task is fully specified in a single turn, yet the same models lose up to 39% of that performance when the identical task is revealed incrementally across multiple turns, a phenomenon documented at scale as Lost in Conversation. Crucially, this collapse is almost entirely a reliability failure; the best case, the aptitude only falls 16%, while the unreliability more than doubles (+112%). We argue that the root cause is structural, a flat conversation history assigns equal implicit weight to every prior turn, giving the model no signal to distinguish a critical constraint from incidental dialog. We present SeDT Sentence-transformer Decision-Transformer, a training-free inference-time method that resolves this by importing return-to-go conditioning from offline reinforcement learning. SeDT annotates each conversation shard with a cumulative relevance score derived from three complementary semantic, lexical, and positional signals and presents the full annotated history to the model at the final turn, without weight changes, without training data, and without discarding context. Evaluated on the Lost-in-Conversation benchmark in three LLMs and three generation tasks, SeDT outperforms the sharded baseline in all nine model-task combinations, with gains up to +37.7% in mean performance P and simultaneous reductions in unreliability in seven of the nine combinations. In short, telling the model which past turns matter is sufficient to substantially recover the performance lost in conversation.
### Title:
          Latent Recurrent Transformer: Architecture Exploration, Training Strategies, and Scaling Behavior
 - **Authors:** Zeyi Huang, Xuehai He, LiLiang Ren, Yiping Wang, Baolin Peng, Hao Cheng, Shuohang Wang, Pengcheng He, Jianfeng Gao, Yong Jae Lee, Yelong Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study Latent Recurrent Transformer (LRT), a lightweight augmentation of autoregressive transformers that reuses a high-level source-layer hidden state from the previous token as recurrent memory for the next token. Because this source state is already computed during ordinary decoding, LRT adds a cross-layer recurrent latent pathway across positions without inserting pause tokens or extra depth loops, and the standard attention mechanism and KV-cache interface are preserved. To pretrain this recurrence at scale without sequentially unrolling the transformer, we introduce interleaved parallel training: a single full-sequence initialization forward pass builds a shared buffer; then disjoint position subsets are refined in parallel and written back, so that all tokens receive recurrent-memory-aware supervision at roughly 2 times baseline compute. Across nanochat style backbones and a wide range of tokens-per-parameter budgets, LRT improves both language-modeling loss and in-context learning under matched effective compute while adding as little as 0.3% parameters.
### Title:
          PATE-TabTransGAN: Differentially Private Synthetic Tabular Data Generation via Transformer-Based Student Discrimination
 - **Authors:** M. Youssef, M. Woźniak
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating high-fidelity synthetic tabular data under formal differential privacy guarantees remains an open challenge. Methods that provide strong theoretical protection typically sacrifice the modeling of inter-feature dependencies required for realistic synthesis, while architectures that excel at capturing complex column relationships offer only empirical privacy guarantees. We present PATE-TabTransGAN, a generative framework that integrates the Private Aggregation of Teacher Ensembles (PATE) mechanism with a Transformer-based student discriminator to jointly address both requirements, and employs a GNMax RDP accountant for numerically stable privacy accounting. An ensemble of Logistic Regression teachers trained on disjoint partitions supervise the student via noisy-aggregated labels, and a residual generator is optimized against this differentially private student, inheriting formal ({\epsilon}, {\delta})-DP guarantees by post-processing. PATE-TabTransGAN was compared with PATE-GAN, DP-GAN, and DP-CTGAN, considered state-of-the-art in differentially private tabular synthesis. Experiments conducted on four tabular benchmarks (Adult, Breast, Cardio, Cervical) confirmed the high quality of the proposed method: PATE-TabTransGAN attains the best or tied-best AUROC on all four datasets. On AUCPR it matches the strongest baseline on Cardio, leads on Cervical, and trails on Breast; on Adult, we demonstrate that AUCPR is highly sensitive to positive-class convention, and that the observed gap is consistent with a convention difference between evaluation pipelines rather than a synthesis deficit.
### Title:
          Natural Human Motion Recovery by Aligning High-Order Temporal Dynamics from Monocular Videos
 - **Authors:** Dingkun Wei, Zehong Shen, Yan Xia, Georgios Pavlakos, Yujun Shen, Xiaowei Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human motion recovered from monocular videos often appears overly smooth or dynamically inconsistent, even when joint positions are numerically accurate. We observe that this limitation stems from the absence of reliable high-order temporal cues -- velocity and acceleration -- which are essential for reconstructing motion that exhibits realistic momentum, timing, and high-frequency detail. We introduce HTD-Refine, a post-processing framework that augments existing Human Motion Recovery (HMR) pipelines using explicitly estimated high-order temporal dynamics. At the core of our system is PVA-Net, a temporal transformer that infers per-joint 2D positions, 3D velocities, and 3D accelerations directly from a monocular video. These predicted dynamics serve as soft yet informative constraints in a global optimization procedure that refines world-space trajectories, significantly reducing jitter, suppressing over-smoothing, and restoring physically plausible motion. Extensive experiments on challenging in-the-wild benchmarks show that HTD-Refine consistently improves state-of-the-art HMR methods, yielding more accurate global trajectories and substantially more natural motion dynamics. Our results highlight the critical role of high-order temporal modeling in advancing monocular human motion recovery.
### Title:
          I2PRef: Image-Driven Point Completion with Iterative Refinement
 - **Authors:** Azhar Hussian, Marina Ritthaler, André Kaup, Vasileios Belagiannis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an image-conditioned point cloud completion approach that treats images as the primary geometric source rather than a secondary guide. To this end, we introduce an Image-to-Point (I2P) module that can reconstruct complete point clouds directly from a single RGB image, with no need for 3D inputs. Additionally, we introduce a transformer-based Point-to-Point (P2P) refinement module that uses self- and cross-attention between point tokens and image features to iteratively refine the coarse I2P output. The I2P module enables the image encoder to learn rich geometric representations, while the P2P module progressively recovers fine-grained details. Unlike existing multimodal methods that rely on auxiliary losses or fusion modules, our explicit I2P task provides a strong, geometry-aware prior based on images alone. Extensive experiments on ShapeNet-ViPC demonstrate state-of-the-art completion performance with a 12.3% relative Chamfer Distance improvement over prior methods. Code is available at: this https URL
### Title:
          Prompt Injection Detection is Regime-Dependent: A Deployment-Aware Evaluation with Interpretable Structural Signals
 - **Authors:** Akindoyin Akinrele, Shreyank N Gowda
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prompt injection poses a critical threat to the safe deployment of large language models, yet existing detection approaches are typically evaluated under limited settings that do not reflect real-world operating constraints. In this work, we present a deployment-aware evaluation of prompt injection detection using a multi-model and multi-regime experimental framework. We compare lexical, semantic, structural, and transformer-based detectors across multiple out-of-distribution settings, repeated data splits, and both ranking and thresholded deployment metrics. We introduce interpretable structural signals that capture hierarchy overrides, system prompt spoofing, role redefinition, and evasion patterns, and assess their contribution both within sparse models and in combination with strong encoder baselines. Our results show that detection performance is highly regime-dependent and sensitive to threshold selection, with no single model dominating across all settings. Transformer-based models achieve the strongest overall performance, while structural signals provide modest but consistent gains in certain regimes and improve low false positive rate behaviour in harder scenarios. These findings highlight the gap between ranking performance and deployment effectiveness and underscore the importance of evaluating prompt injection defences under realistic operational constraints. Code will be released.
### Title:
          Timestep-Aware SVDQuant-GPTQ for W4A4 Quantization of Wan2.2-I2V
 - **Authors:** Junhao Wu, Dezhong Yao, Hai Jin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 W4A4 quantization of large video diffusion Transformers offers substantial memory savings but is hindered by two main challenges: sparse large-magnitude activation outliers, and strongly timestep-dependent activation distributions across the multi-step denoising trajectory. These difficulties are compounded by Wan2.2-I2V's two-expert Mixture-of-Experts DiT design, whose high-noise and low-noise experts exhibit distinct quantization sensitivities that a single global calibration policy cannot capture. We propose a post-training quantization framework combining SVDQuant-based low-rank outlier compensation, GPTQ-based reconstruction-aware residual weight quantization, and timestep-bin-wise per-layer activation clipping-ratio search conducted independently for each expert. On the OpenS2V-Eval benchmark, our method reduces peak GPU memory by 59.3\% relative to the BF16 baseline while incurring only a 0.9\% drop in VBench average score and a 2.3\% drop in Imaging Quality, demonstrating that expert- and timestep-aware calibration is essential for high-fidelity W4A4 inference on MoE video DiTs.
### Title:
          SQARL: A Size-Agnostic Reinforcement Learning approach for Circuit Allocation in Distributed Quantum Architectures
 - **Authors:** Víctor Carballo, Júlia López-Closa, Mario Martin
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scaling of quantum processors is currently limited by technical challenges such as decoherence and cross-talk. As the number of qubits grows, interference increases the computational noise. Distributed quantum computing addresses these limitations by interconnecting smaller, easier-to-handle quantum processors (cores), but it introduces the challenge of minimizing slow, error-prone inter-core communication. The task of distributing quantum circuits across cores while minimizing communication costs is known as the Qubit Allocation problem. This work focuses on developing a deep learning approach to this problem, emphasizing flexibility to quantum hardware topology and improving state-of-the-art performance. Heuristic and non-learning algorithms, such as the Hungarian Qubit Allocation (HQA), currently represent the state of the art. Reinforcement Learning (RL) approaches leverage learned allocation policies but often lack flexibility, requiring retraining when hardware configurations change, and they fall short of the solution quality achieved by non-learning methods. However, learning mechanisms could outperform human-crafted heuristics. To overcome these limitations, this work proposes a flexible, transformer-based architecture that can handle arbitrary numbers of qubits and cores without retraining. Results show that the trained policy consistently outperforms the previous RL state of the art and narrows the gap between RL and HQA for the most common circuits. It achieves a 33% reduction in allocation cost relative to the HQA for the Cuccaro Adder and 25% on average for random circuits. These findings show that learning-based approaches can effectively match the performance of hand-crafted heuristics, a crucial step towards their application in real-world scenarios.
### Title:
          Tracing Computation Density in LLMs
 - **Authors:** Corentin Kervadec, Iuliia Lysova, Iuri Macocco, Marco Baroni, Gemma Boleda
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models (LLMs) are comprised of billions of parameters arranged in deep and wide computational graphs, but it is not clear that they exploit their full capacity for all inputs. We introduce the s-Trace method to efficiently estimate the subgraph of size s that best approximates a full model output. With this method, we find the computation in a variety of LLMs to be organized in two distinct phases. A small subgraph mostly composed of early-layer nodes can reconstruct the head of the full model output distribution. Adding further nodes, mostly located in later layers and increasingly consisting of attention heads, leads to incremental refinements in approximating the full output distribution. We find moreover that the amount of necessary computation per input correlates with model uncertainty, and that sparser subgraphs encode shallow statistics, such as unigram frequency. Overall, our results suggest a consistent modular organization in effective LLM computation, with a sparse early-layer core providing a rough prediction that is further refined through denser computations in later layers.
### Title:
          BatteryMFormer: Multi-level Learning for Battery Degradation Trajectory Forecasting
 - **Authors:** Ruifeng Tan, Jintao Dong, Weixiang Hong, Jia Li, Jiaqiang Huang, Tong-Yi Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early battery degradation trajectory forecasting (BDTF), which predicts the full-life state-of-health trajectory from early operational data, is critical for battery optimization, manufacturing, and deployment. Battery degradation data exhibit two key characteristics. First, degradation data present a multi-level structure, including regularities shared within aging conditions and trajectory patterns shared across batteries. Second, degradation-related variations in voltage-current profiles are often localized to specific state-of-charge (SOC) intervals. Existing approaches often fail to explicitly model these characteristics. To bridge this gap, we propose BatteryMFormer, a multi-level Transformer for early BDTF. BatteryMFormer integrates (1) an aging-condition-aware decoder that injects aging-condition priors via aging-condition-informed queries and aging-condition-aware attention, (2) a meta degradation pattern memory that learns and retrieves trajectory prototypes to guide long-horizon forecasting, and (3) a dual-view encoder that jointly captures temporal dynamics and SOC-localized variations from voltage and current time series. Extensive experiments on four battery domains show that BatteryMFormer consistently outperforms state-of-the-art baselines, marking a significant step toward reliable BDTF. Our code is available at this https URL.
### Title:
          SoftCap: Soft-Budget Control for Diffusion Transformer Acceleration
 - **Authors:** Yuhang Zhang, Junxiang Qiu, Huixia Ben, Zhenhua Tang, Shuo Wang, Yanbin Hao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) achieve strong visual quality, but their iterative denoising process requires many costly Transformer evaluations. Training-free acceleration methods reduce this cost by caching, forecasting, or verifying intermediate features, yet the runtime decision of when to execute a Full step is often driven by fixed schedules or hand-tuned thresholds. We propose \textbf{SoftCap}, a training-free control layer for cache-based DiT inference. SoftCap couples a Trajectory Drift Observer, which estimates local cache risk from lightweight hidden-state statistics, with a Soft-Budget PI Controller, which adjusts the Full-triggering threshold from realized compute relative to a fixed reference profile. The budget is a soft ceiling: it shapes the threshold but does not require a run to spend a prescribed number of Full evaluations. On FLUX.1-dev, SoftCap improves over SpeCa at a comparable middle-compute operating point, raising ImageReward from 0.967 to 0.981 and reducing LPIPS-Full from 0.518 to 0.498 at nearly identical FLOPs, while target-sweep diagnostics show the intended soft-ceiling behavior as the budget is relaxed.
### Title:
          JLT: Clean-Latent Prediction in Latent Diffusion Transformers
 - **Authors:** Funing Fu, Tenghui Wang, Junyong Cen, Qichao Zhu, Guanyu Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow matching with clean-data prediction has shown that regressing the clean point can exploit low-dimensional structure more effectively than predicting an ambient noised quantity. We ask whether this principle remains useful after images are mapped into a learned latent space, where compression has already removed much of the raw pixel variability. We introduce JLT, a 130M latent diffusion Transformer over frozen FLUX.2 VAE codes, and compare clean-latent prediction with a matched velocity-prediction DiT under the same representation, backbone, and training settings. Although the three variables x, epsilon, and v are linearly convertible for a fixed corruption time, a local Gaussian analysis shows that velocity regression inherits an isotropic target-covariance floor and amplifies low-variance latent directions, while clean prediction damps them. On ImageNet 256 x 256, JLT-B/1 obtains FID-50K 2.50 with classifier-free guidance, with a large matched-target gap over velocity prediction. These results suggest that prediction targets in latent diffusion are representation-dependent geometric choices, rather than interchangeable algebraic parameterizations.
### Title:
          Is an Image Also Worth 16x16=256 Superpixels? A Framework for Attentional Image Classification
 - **Authors:** Pedro Henrique da Costa Avelar, Anderson R. Tavares, Luís C. Lamb
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Superpixel-based image classification has traditionally leveraged graph neural networks (GNNs) for processing irregular image representations. Recent advances in computer vision, driven by Vision Transformers (ViTs), have introduced new paradigms in self-attentional models, surpassing convolutional neural networks (CNNs) in various tasks. However, a synergistic connection between GNNs, superpixels, and transformers remains unexplored. In this work, we propose Superpixel Transformers (SPT), a novel framework that unifies superpixel-based image classification and ViTs. SPT generalizes the Superpixel Image Classification with Graph Attention Networks (SICGAT) model and ViT to support arbitrary superpixel-based chunking strategies, connectivity graphs, and positional encodings. We introduce refinements including a multidimensional sine-cosine positional encoding and an enriched patch data structure that fully incorporates superpixel shape and color information. By testing SPT across datasets such as CIFAR10, FashionMNIST, and Imagenette, with various superpixel generation and graph connectivity strategies, we demonstrate that SPT achieves superior performance compared to previous superpixel-based GNN methods and remains competitive with ViTs. Notably, our approach addresses the limitations of SICGAT, such as information loss during pixel aggregation, and shows how constrained graph connectivity can enhance ViT performance. SPT bridges the gap between superpixel-based and transformer models, opening avenues for cross-domain generalization and future innovations in hybrid attentional frameworks, and showing that an image can also be worth $16\times16$ superpixels.
### Title:
          Symbolic Regression via Latent Iterative Refinement
 - **Authors:** Xieting Chu, Sriram Vishwanath, Vijay Ganesh
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Symbolic regression (SR) seeks closed-form mathematical expressions that fit observed data. Neural SR methods amortize the search by training an encoder to map observations directly to expressions in a single pass, but this amortized inference leaves a residual amortization gap between its one-shot prediction and the true posterior. We propose Latent Equation Embedding (LEE), a framework that closes this gap through iterative amortized inference in a functionally grounded latent space. LEE learns a shared latent space Z equipped with three components: an encoder f_theta that jointly embeds symbolic tokens and numerical observations into a single latent vector z; an expression decoder g_expr that reconstructs formulas from z; and an evaluation decoder g_eval that predicts function values from z, explicitly grounding the latent space in functional behavior. At inference, LEE performs iterative refinement by re-encoding decoded expressions jointly with observations, progressively improving the latent estimate. LEE uses the encoder itself as a learned inference optimizer: each re-encoding step implicitly computes the mismatch between the candidate and the data. Because g_eval is differentiable in z, we additionally interleave continuous gradient descent with discrete re-encoding, yielding a hybrid iterative and gradient refinement procedure. On SRBench across three noise levels, against 19 baselines spanning genetic programming, symbolic-neural hybrids, and pre-trained Transformers, LEE produces expressions 2--10x simpler than the strongest accuracy-oriented baselines, including Operon, GP-GOMEA, TPSR, RAG-SR, and GenSR, with complexity 8--11 versus 20--90. These results advance the low-complexity region of the accuracy-complexity Pareto frontier and show graceful degradation as noise increases.
### Title:
          Kan Extension Transformers: A Categorical Unification of Attention, Diffusion, and Predict-Detach Self-Conditioning
 - **Authors:** Sridhar Mahadevan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Kan Extension Transformers (KETs) as a unifying categorical framework for a diverse group of Transformer implementations. The core claim is that a Transformer layer can be viewed as a weighted structured extension operator: standard attention is the singleton-neighborhood case, Geometric Transformer style incidence mixing is a sparse edge-restricted case, and KET is the higher-order simplicial case. This lens also clarifies a bridge to diffusion-style completion. When the extension operator acts on detached predictive carriers instead of teacher-forced hidden states, it becomes a valid self-conditioning mechanism that exposes noncausal structure without leaking gold future tokens. We include a comprehensive experimental validation of 12 different Transformer implementations varying across strict-causal and predict-detach regimes on Penn Treebank, WikiText-2, and WikiText-103. In the strict-causal setting, quadratic KET is the strongest model among the compared causal architectures on WikiText-2 and WikiText-103. Across all datasets, however, the largest gains come from the predict-detach regime rather than from changing the neighborhood family alone.
### Title:
          Normal Guidance is what Attention Needs
 - **Authors:** Ethan Harvey, Dennis Johan Loevlie, Michael C. Hughes
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We consider training classifiers for 3D medical images using only one binary label for the entire volume rather than a label for each 2D slice. In such weakly supervised settings, can we learn accurate classifiers for slice-level predictions? Attention-based multiple instance learning (MIL) can produce an attention score for every slice. Yet recent work demonstrates that a simple center-focused baseline that ignores image content can outperform attention-based and transformer-based MIL at slice-level classification of 3D brain scans. We show this baseline also outperforms existing MIL at slice-level classification of thoracic and abdominal CT scans. Motivated by this baseline, we propose Normal Guidance, a regularization technique that encourages the learned attention distribution to follow a bell-shaped curve. Across three medical imaging datasets totaling over 4 million 2D slices, we show our Normal Guidance enables attention-based and transformer-based MIL methods to deliver significantly better slice-level localization than the state-of-the-art while remaining competitive at whole-scan classification.
### Title:
          PARE: Pruning and Adaptive Routing for Efficient Video Generation
 - **Authors:** Yutong Wang, Yunke Wang, Tianfan Xue, Yu Qiao, Yaohui Wang, Xinyuan Chen, Chang Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Diffusion Transformers (DiTs) generate high-quality videos but demand substantial compute due to wide blocks, deep architectures, and iterative sampling. Recent methods reduce cost by compressing width, depth, or sampling steps, but typically commit to a fixed architecture that cannot adapt to individual inputs or denoising stages. We propose PARE (Pruning and Adaptive Routing for Efficient video generation), which jointly compresses width and depth with structure-aware pruning and input-adaptive routing. For width, we observe that attention heads specialize into spatial and temporal roles, and design importance scoring that accounts for this distinction to prevent motion-critical temporal heads from being pruned prematurely. For depth, we train a lightweight router conditioned on denoising timestep and visual content to dynamically select which blocks to execute at each step, enabling per-input compute adaptation rather than static block removal. A progressive pipeline first recovers width-pruned quality via distillation, then jointly optimizes the student and router to decouple the two learning objectives. Experiments on Wan2.1-14B for both image-to-video and text-to-video generation show that PARE substantially reduces per-step computation while preserving quality across VBench dimensions, and composes with step distillation for further acceleration.
### Title:
          G3T Up! Gravity Aligned Coordinate Frames Simplify Pointmap Processing
 - **Authors:** Bharath Raj Nagoor Kani, Noah Snavely
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern feed-forward 3D reconstruction methods like VGGT predict pixel-aligned pointmaps in camera-centric coordinate frames. However, this choice of coordinate frame is not always optimal. We propose instead to predict pointmaps in upright, gravity-aligned frames that exploit strong structural cues present in many real-world scenes. Unlike camera-centric frames, gravity-aligned frames share a common vertical axis across viewpoints, reducing the rotational degrees of freedom needed to relate pointmaps to one another. To this end, we introduce the Gravity Grounded Geometry Transformer (G3T), fine-tuned from existing models on gravity-aligned 3D data. G3T produces highly accurate gravity-aware predictions, including upright pointmaps and camera-to-gravity poses. We further introduce G3T-Long, a submap-based incremental 3D reconstruction pipeline that leverages the reduced rotational degrees of freedom afforded by upright frames to achieve significantly improved reconstruction accuracy.
## Keyword: autonomous driving
### Title:
          When Does Adaptive Guidance Help? Belief-Aware Privileged Distillation for Autonomous Driving Under Partial Observability
 - **Authors:** Mehmet Haklidir
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Guided Soft Actor-Critic (GSAC) distills knowledge from a privileged full-state teacher to a partial-observation student for autonomous driving, but uses a fixed distillation coefficient lambda regardless of the agent's uncertainty. We present Belief-Aware GSAC (BA-GSAC), which modulates lambda via ensemble disagreement, and use it as a testbed for a systematic empirical study asking: when does adaptive guidance actually help? Evaluating five strategies (fixed lambda in {0.01, 0.1}, adaptive, linear decay, and vanilla SAC) across three POMDP difficulty levels on Highway-Env, we find that preliminary single-seed runs suggest benefits under mild and moderate partial observability, but under severe occlusion (evaluated with 3 seeds for all methods) the adaptive coefficient collapses to lambda_min within about 3K steps. We trace this to an observability blindness phenomenon: because the ensemble predicts partial observations, it achieves low disagreement even under heavy occlusion, modeling what is visible but unable to detect what is missing. We diagnose the root cause and propose an architectural fix (training the ensemble on full-state predictions using the guiding actor's privileged access); while not validated here, we show that even with current limitations, the warmup phase provides measurable stabilization (CV=13.3% vs. 29.8% for constant lambda=0.01). In fact, a simple deterministic linear decay schedule achieves the best severe-POMDP performance across all metrics (mean 116.5, CV=8.9%), suggesting that the scheduling effect, not the ensemble, drives the stability benefit. These findings provide practical guidance for designing uncertainty-aware teacher-student frameworks and highlight ensemble prediction targets as an important design choice.
### Title:
          Variational Inference for Evidential Deep Learning
 - **Authors:** Jiawei Tang, Xinyan Du, Hui Liu, Junhui Hou, Yuheng Jia
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Deep Neural Networks (DNNs) achieve remarkable performance, their tendency to produce overconfident predictions. Evidential Deep Learning (EDL) mitigates this by formulating predictions as a Dirichlet distribution over class probabilities to explicitly quantify epistemic uncertainty. However, we found that the conventional EDL suffers from two fundamental limitations: a Kullback-Leibler (KL) penalty that only suppresses the evidence of negative classes, producing excessively high evidence therefore decreasing the model's ability to quantify uncertainty, and an absence in theoretical guarantee of setting Dirichlet parameter $\alpha=e+1$. In this paper, we propose a mathematically principled framework, Variational Inference Evidential Deep Learning (VI-EDL). By reformulating evidential learning through the lens of variational inference, we derive an Evidence Lower Bound (ELBO), which prevents the evidence from growing excessively. Theoretically, we rigorously establish a generalization bound and reveal how the predicted uncertainty, feature and network complexity affect this bound, and why setting $\boldsymbol{\alpha} = \mathbf{e} + \mathbf{1}$ can minimize it. Extensive experiments on standard visual and medical datasets demonstrate that VI-EDL achieves state-of-the-art performance, showing excellent performance in out-of-distribution detection, noise detection and autonomous driving scenario. The code is available in this https URL.
### Title:
          Unveiling the Fragility of Vision-Language Models: Multi-Modal Adversarial Synergy via Texture-Constrained Perturbations and Cross-Modal Optimization
 - **Authors:** Xiang Fang, Wanlong Fang, Changshuo Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Vision-Language Models (LVLMs) have transformed multi-modal understanding, excelling in tasks like image captioning and visual question answering by integrating visual and textual inputs. However, their robustness against adversarial attacks, particularly those exploiting both modalities, remains underexplored, posing risks to critical applications like autonomous driving and content moderation. Existing attacks focus on single modalities or require impractical white-box access, limiting their real-world relevance. In this paper, we introduce Multi-Modal Adversarial Synergy, a groundbreaking framework that crafts universal, black-box multi-modal attacks against LVLMs. MMAS simultaneously generates a texture scale-constrained universal adversarial perturbation for images and a learnable prompt perturbation for text, optimized jointly using only model queries. The image perturbation leverages wavelet-based texture constraints to ensure imperceptibility and robustness across diverse visual inputs. The text perturbation, constrained by an L-norm in the embedding space, maintains semantic coherence while steering outputs toward a target. A novel cross-modal regularization term aligns the perturbations' gradient directions, enhancing their synergistic impact and transferability across tasks and models. Extensive experiments show the strong universal adversarial capabilities of our proposed attack with prevalent LVLMs.
### Title:
          Bridging Control with Neural Network Verifier alpha-beta-CROWN: A Tutorial
 - **Authors:** Haoyu Li, Xiangru Zhong, Hao Cheng, Bin Hu, Huan Zhang
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based methods for synthesizing controllers have gained popularity due to their high expressiveness and strong empirical performance. However, in safety-critical scenarios such as autonomous driving, robotics, and power systems, empirical performance alone is insufficient, and formal verification of controller properties such as stability and safety is highly desirable. Unfortunately, many prior verification approaches are either tied to specific structural assumptions on the system or the certificate, making them difficult to transfer across settings, or suffer from poor scalability on higher-dimensional neural network systems. In this tutorial, we present a unified framework that aims to mitigate this gap via bridging control with the state-of-the-art neural network verifier $\alpha,\!\beta$-CROWN (alpha-beta-CROWN). At its core, $\alpha,\!\beta$-CROWN is a general-purpose bounding engine for nonlinear functions represented as computation graphs: given an input domain, it can produce certified bounds and explicit linear relaxation of the nonlinear function. These certified bounds are useful on their own for tasks such as reachability analysis, and they also provide the foundation for more complex routines that perform satisfiability checking and optimization. More specifically, many control problems reduce to verifying real-valued inequalities over a state domain (e.g., Lyapunov theory). Consequently, $\alpha,\!\beta$-CROWN enables scalable verification of such conditions by computing tight bounds and recursively partitioning and pruning subdomains based on the bounds. Thanks to GPU parallelization, this pipeline demonstrates superior scalability on verification and optimization problems that are challenging for traditional approaches. In this tutorial, we discuss the basics of $\alpha,\!\beta$-CROWN and introduce its application to various control-related tasks.
### Title:
          TPS-Drive: Task-Guided Representation Purification for VLM-based Autonomous Driving
 - **Authors:** Jiaxiang Li, Yumao Liu, Ke Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) provide a promising foundation for autonomous driving planning, yet bridging semantic reasoning and precise 3D spatial forecasting remains a critical challenge. Existing representation strategies generally follow two paths: text-aligned methods flatten continuous spatial states into symbols, which compromises geometric structure and induces "spatial hallucinations"; dense visual methods preserve spatial topology but overwhelm standard tokenizers with redundant background textures, leading to "representation interference". To address these limitations, we introduce TPS-Drive, a novel framework centered on Task-Guided Representation Purification that empowers VLMs to Think in Purified Space. At its core, an Agent-Centric Tokenizer utilizes a task-guided vector quantization mechanism supervised by a frozen 3D detection head, which explicitly reallocates limited codebook capacity from pervasive static backgrounds to critical dynamic agents and effectively isolates spatial redundancy. Leveraging this purified spatial vocabulary, TPS-Drive employs a decoupled reasoning pipeline that sequentially performs scene understanding, future forecasting, and action generation. The framework is optimized via a progressive three-stage training paradigm, culminating in reward-driven refinement that surpasses pure imitation learning. Extensive experiments validate our approach: TPS-Drive achieves accurate agent spatial state forecasting and reduces collision rates in open-loop nuScenes evaluations, while establishing new safety records on the rigorous closed-loop NAVSIMv1 and NAVSIMv2 benchmarks.
