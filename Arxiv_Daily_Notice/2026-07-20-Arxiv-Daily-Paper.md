# Showing new listings for Monday, 20 July 2026
## Keyword: SLAM
### Title:
          A New Implementation of NeoSLAM and a Comparative Evaluation with RatSLAM
 - **Authors:** Joao Victor T. Borges, Fabio Coelho, Paulo Padrao, Jose Fuentes, Ramon R. Costa, Liu Hsu, Leonardo Bobadilla
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a new implementation of the NeoSLAM algorithm. The proposed version is a complete rewrite of NeoSLAM into a modular architecture using modern frameworks that, together, enable real-time execution with minimal discarding of input data. This work also provides a comparative evaluation between NeoSLAM and RatSLAM across three datasets under varying environmental conditions. The experimental results highlight differences in mapping consistency and trajectory reconstruction, demonstrating the effectiveness and practical applicability of the proposed ROS2-based implementation. The results indicate that the new NeoSLAM outperforms the original in terms of processing throughput for real-time applications and achieves comparable performance to RatSLAM in terms of map reconstruction across the evaluated datasets.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Hardware-triggered Time Synchronization of Roadside Multi-lidar, Multi-camera Measurement System for Accurate Data Alignment
 - **Authors:** Shiva Agrawal, Savankumar Bhanderi, Zhiran Yan, Gordon Elger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate temporal alignment of heterogeneous sensors is necessary for reliable environment perception in roadside multi-lidar, multi-camera systems, particularly in dense urban traffic. For this purpose, an open-source, simple, modular, and configurable hardware-triggered time-synchronization circuit is presented in this work to perform temporal alignment or accurate time synchronization between a lidar and multiple cameras. In the designed circuit, a lidar synchronization pulse is used as a reference input, and independently programmable, time-delayed trigger pulses are generated for each camera, allowing flexible adaptation to varying sensor setups and mounting geometries. A series of experiments is conducted on a roadside-mounted perception system comprised of lidar and three cameras, in which the trigger delay is systematically varied, and its impact on spatial-temporal alignment is evaluated. For different classes of road users, the overlap between lidar point cloud measurements and camera measurements is quantified to identify delay configurations that maximize cross-sensor consistency. The proposed circuit is shown to achieve robust and repeatable synchronization while remaining straightforward to deploy, reconfigure, and extend due to its simple and open-source design. Following validation on a three-camera roadside system, the circuit is extended to a vehicle platform with seven cameras and a lidar, providing a low-cost, extensible solution for multi-sensor synchronization across infrastructure and vehicle setups. All hardware circuit design files and source codes are available at this https URL.
### Title:
          CLIFE: Camera-LiDAR Fusion Framework for Edge-Deployable Roadside VRU Perception
 - **Authors:** Tam Bang, Hoang H. Nguyen, Lei Cheng, Lihao Guo, Siyang Cao, Hussam Abubakr, Tianya Zhang, Austin Harris, Mina Sartipi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable roadside perception of vulnerable road users (VRUs) remains challenging under occlusions, variable lighting, and diverse weather conditions, particularly under strict edge-computing and latency constraints. Existing multi-sensor fusion systems rely on cloud or server-grade infrastructure, creating a deployment gap at real-world intersections. We present CLIFE, an edge-native camera-LiDAR fusion framework that integrates targetless online calibration and lightweight late-fusion tracking entirely on a single embedded device, without cloud offloading. CLIFE adaptively refines camera-LiDAR alignment on demand and performs multi-sensor fusion and track association with O(N log N) per-frame cost. We deploy CLIFE across 12 signalized intersections in Chattanooga and conduct an in-depth evaluation at a representative intersection using synchronized camera-LiDAR data that spans diverse daytime, nighttime, and weather conditions. Our experiments demonstrate that the fusion architecture substantially enhances the perceptual range and robustness of the individual sensors under varied environmental and traffic conditions. The late-fusion core operates at 53.2 FPS on the Jetson AGX Thor, ensuring high throughput for real-time intersection-scale applications. By centering perception at the edge, CLIFE provides a deployable foundation for downstream safety applications, while reducing bandwidth and calibration overhead for agencies operating multi-intersection corridors.
### Title:
          PRISA: Proactive Infrastructure LiDAR Framework for Intersection Safety Assessment
 - **Authors:** Tam Bang, Hussam Abubakr, Emiliano de la Garza Villarreal, Truc Phuong Nguyen, Austin Harris, Toru Hirano, Mina Sartipi, Yunfei Xu, Hoang H. Nguyen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban intersections are among the most hazardous locations in road networks, posing significant risks to vehicles and vulnerable road users (VRUs) such as pedestrians and cyclists. The complexity of multi-agent interactions demands continuous, real-time monitoring systems capable of anticipating conflicts before they escalate into crashes. We present PRISA, a modular infrastructure LiDAR framework leveraging privacy-preserving, low-light-robust roadside sensors for long-term traffic observation and real-time risk detection at the edge. The framework comprises two core components: a sensing and perception layer and a plug-and-play risk assessment module. The latter automatically curates site-specific training data from accumulated perception outputs to train a trajectory prediction model without manual annotation. It then deploys the trained model for continuous motion forecasting and dual surrogate safety evaluation, using Time-to-Collision (TTC) for longitudinal conflicts and Predicted Post-Encroachment Time (PPET) for crossing and VRU-involved interactions. PRISA is evaluated on the public R-LiViT dataset and deployed on an NVIDIA Jetson AGX Thor at a live signalized intersection in Chattanooga, Tennessee. PPET-based assessment operates at 194~ms end-to-end latency over a 2.4-second predictive horizon, with TTC-based detection and perception remaining within real-time constraints, demonstrating practical feasibility for proactive multi-agent intersection safety monitoring.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          ImprovedVBGS: Real-time Continual Variational Bayes Gaussian Splatting
 - **Authors:** Damani Mguni-Coker
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-the-fly reconstruction is a key requirement for many applications in robotics and autonomous navigation. Variational Bayes Gaussian Splatting (VBGS) enables continual learning without replay buffers using Coordinate Ascent Variational Inference (CAVI), but its per-frame iterations over all observed points make it too slow for real-time use with strict memory and latency requirements. We present ImprovedVBGS, an accelerated framework for on-the-fly continual reconstruction. This is achieved primarily through (i) spatially truncated variational inference, and (ii) improved reassignment that uses forwarding, truncation and eliminates wasteful dynamic recompilation. On the NeRF synthetic dataset, we reduce mean per-frame latency from ~84.0 s to ~0.050 s on an RTX 3070 Ti, a 1680x speed-up while maintaining reconstruction quality.
## Keyword: mapping
### Title:
          Dataset-Origin Signatures and Shortcut Learning in Screening Mammography AI: A Cross-Dataset Case Study
 - **Authors:** Parham Hajishafiezahramini, Matthew Hamilton, Oscar Meruvia-Pastor, Edward Kendall
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable AI for screening mammography requires training data representative of the low cancer prevalence and subtle abnormalities found in screening populations. We examined whether supplementing such data with biopsy-confirmed cases from abnormal-enriched external datasets improves performance. Using the Newfoundland and Labrador Breast Screening Dataset (NLBSD) alongside CBIS-DDSM and CMMD, we evaluated an EfficientNet-B5 encoder initialized with Mammo-CLIP weights as a frozen linear probe under consistent preprocessing and patient-level splits. The NLBSD-only model achieved an AUC-ROC of 0.737 (95% CI [0.686, 0.785]). Adding external positive cases reduced performance in every configuration (AUC-ROC = 0.620--0.644; DeLong test, Holm-corrected $p < 0.05$), with degradation increasing as additional sources were introduced. Domain-matched evaluation produced modest gains only when the training and test domains coincided, and no configuration surpassed the NLBSD-only model. As a diagnostic, we reframed the task as predicting each examination's dataset of origin. The datasets were separated almost perfectly despite identical preprocessing, indicating that dataset-specific characteristics strongly influence the learned representation. These findings show that naïvely pooling abnormal-enriched mammography datasets can introduce domain shift that outweighs the benefit of additional positive cases. Differences in acquisition, intensity mapping, and dataset construction persist after normalization, motivating domain-aware strategies for combining heterogeneous mammography datasets.
### Title:
          FLINT: Fingerprinting Federated Learning Architectures from 5G PHY-Layer Side Channels
 - **Authors:** Md Nahid Hasan Shuvo, Mahmudul Hassan Ashik, Moinul Hossain
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated Learning (FL) over 5G cellular networks protects raw data but remains vulnerable to side-channel leakage. Prior fingerprinting attacks assume packet-level network visibility, an assumption that does not hold at the 5G Physical (PHY) layer, where user payloads are encrypted and Radio Network Temporary Identifiers (RNTIs) may change over time. However, we demonstrate that PHY-layer scheduling metadata broadcast over the Physical Downlink Control Channel (PDCCH) preserves architecture-associated temporal patterns. We introduce FLINT, a novel black-box fingerprinting framework that infers FL model architecture families, including CNNs, RNNs, and Transformers, using only coarse PHY-layer observations. FLINT overcomes the lack of network-layer visibility by decoding PDCCH scheduling information, mapping changing RNTIs to physical user devices, and applying multi-view temporal modeling to distinguish architecture-specific training behavior. This leakage is security-critical because knowledge of a client's model architecture can transform passive reconnaissance into targeted downstream exploitation. Extensive experiments on an over-the-air srsRAN-based 5G testbed demonstrate that FLINT achieves a macro F1-score of 0.930 for architecture-family classification. To our knowledge, FLINT is the first work to fingerprint AI/ML model architectures using lower-layer 5G side-channel information obtainable by any protocol-aware adversary.
### Title:
          A Critical Analysis of Trustworthy AI Tools, Mark Frameworks, and the Implementation Chasms
 - **Authors:** Michael Papademas, Xenia Ziouvelou, Kostas Karpouzis, Vangelis Karkaletsis
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As artificial intelligence (AI) systems increasingly impact society, ensuring their ethical and trustworthy deployment has become a global priority. While a myriad of high-level ethical guidelines have emerged, criticism persists that these frameworks remain abstract and lack concrete mechanisms for implementation. This paper conducts a critical analysis of tools and trust mark frameworks intended to operationalize trustworthy AI (TAI), drawing on a comprehensive dataset from the OECD. Through empirical mapping and descriptive comparative analysis, we identify significant asymmetries in ethical focus, lifecycle coverage, stakeholder targeting, and tool typology. Our findings show a strong emphasis on fairness, transparency, and robustness, with comparatively little attention paid to explainability, digital security, and environmental sustainability. Moreover, most tools and certifications concentrate on post-development stages, with limited guidance for early design or data collection phases. Educational initiatives and policy engagement are notably underdeveloped, suggesting that current TAI efforts are dominated by technical and procedural measures within industry contexts. We argue that bridging the persistent chasm between AI principles and practice requires expanding ethical objectives, embedding ethics across the AI lifecycle, and fostering broader multi-stakeholder participation. This study provides both a diagnosis of existing implementation gaps and actionable recommendations for advancing more holistic, inclusive, and enforceable AI governance
### Title:
          DiTango: Cost-Effective Parallel Diffusion Generation with Selective Attention State Reuse
 - **Authors:** Yuyang Chen, Runxin Zhong, Zan Zong, Hengjie Li, Yuyang Jin, Jidong Zhai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in AI-generated content have driven widespread adoption of Diffusion Transformers (DiTs) for high-resolution, long-duration content generation. While parallelization techniques accelerate diffusion inference, they face significant scalability challenges due to excessive communication overhead in multi-node environments. We observe that sequence partitions in Context Parallelism (CP) exhibit distinct heterogeneity: spatially proximate partitions contribute more significantly to attention computation results. By mapping this heterogeneous pattern to hierarchical communication topology, we can access high-contribution partitions with reduced communication cost. This insight motivates our novel selective attention state mechanism that strategically balances partial attention computation and historical result reuse across denoising steps. We present DiTango, an efficient parallel framework for DiT generation. DiTango features an anchor-guided state selection planner that optimizes computation-reuse decisions for each partition, complemented by a runtime that orchestrates efficient state-centric operations. This design achieves superior system efficiency while preserving generation quality. Experimental evaluation on popular diffusion models demonstrates that DiTango achieves up to 1.9x end-to-end and 3.2x attention speedup with near-linear scaling in multi-node settings, while maintaining generation quality comparable to state-of-the-art approaches.
### Title:
          Beyond Frontiers: Scene-Anomaly Guided Autonomous Exploration
 - **Authors:** Akash Kumbar, Abhinav Raundhal, Madhava Krishna
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration of unknown 3D environments is traditionally driven by coverage-maximizing geometric heuristics. However, these methods typically determine exploration targets without considering the underlying structural context. This leads to inefficient trajectories often limiting the fidelity of the final 3D reconstruction. To bridge the gap between spatial coverage and reconstruction quality, we introduce a novel paradigm: reframing exploration as a geometric anomaly minimization problem. We present SCAGE: SCene Anomaly Guided Exploration, a novel autonomous exploration framework that operates directly on unstructured 3D point clouds. Instead of blindly chasing volumetric boundaries, we equip the robot with a foundational understanding of standard indoor architecture. As the robot navigates, it continuously evaluates its live 3D observations against these learned expectations. When the incoming geometry contradicts the learned priors of a typical indoor environment, such as a fragmented wall or a partial table, the system flags these regions as scene anomalies. These geometric inconsistencies act as a guiding signal, naturally drawing the robot to investigate and resolve these structural anomalies from optimal vantage points. By actively targeting poorly reconstructed regions rather than just empty space, our approach seamlessly couples spatial discovery with high-fidelity mapping. Extensive evaluations demonstrate that SCAGE achieves superior volumetric coverage (~90% in all scenes) and higher 3D reconstruction quality compared to state-of-the-art baselines.
### Title:
          Trans-Domain Digital Twin: Conceptual Foundations, Architecture, and Research Outlook
 - **Authors:** Mansoorali Amiri
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Complex systems comprise heterogeneous domains whose states, uncertainties, risks, and control consequences can cross domain boundaries. Existing cross-domain digital twin approaches broadly focus on comparison, reuse, semantic mapping, standardization, and interoperability, but do not inherently require operational connections among domain states, errors, objectives, constraints, decisions, and controls. This article proposes the trans-domain digital twin as an operational formulation along the continuum of Composite/Federated Digital Twin Systems. This approach connects heterogeneous domain twins through an aligned shared state, explicit coupling of data, models, states, errors, objectives, and controls, heterogeneous temporal coordination, joint decision-making, and feedback-based adaptation. The proposed framework presents a seven-layer conceptual architecture, a trans-domain orchestration core, minimum compliance conditions, a general operational formalism, progressive fast-meso-slow loops, and a single-episode offline training mechanism linked to bounded online adaptation. It also describes conceptual validation and evaluation criteria, a maturity model, a reference deployment architecture, and requirements for runtime safety, provenance, versioning, and model lifecycle management. The framework is conceptually mappable to standards for digital twins, model exchange, distributed simulation, and smart transducers; however, its formal compliance and operational effectiveness must be examined through independent benchmarks, uncertainty quantification, ablation testing, and field validation.
### Title:
          Lightweight return-mapping surrogates for multiscale plasticity: a practical guide
 - **Authors:** Alireza Daneshyar, Leon Herrmann, Stefan Kollmannsberger
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a practical guide to building lightweight neural-network surrogates for the plastic return-mapping process in concurrent multiscale (FE2) simulations. Rather than proposing a new architecture, we show how a deliberately simple feed-forward network, structured to mirror the classical return-mapping update, can replace the prohibitively expensive nested fine-scale solves that dominate the cost of conventional FE2 schemes based on FFT homogenization at the meso-scale. We walk through the full workflow: generating training data from incremental homogenization analyses, constructing a compact yet sufficient dataset, embedding material symmetries directly into the mapping, and deploying the trained network as a user-defined material subroutine (UMAT) in a standard finite-element solver -- enabling widespread use. A sensitivity study examines the model's robustness to data density, increment size, and mesh refinement, and we characterize the regimes in which the surrogate holds and where it breaks down. For the macroscopically isotropic, two-dimensional plane-stress setting considered here, the surrogate reproduces the reference response while reducing the per-analysis cost from hours to seconds with speed-ups up to 30,000 over standard FE2. The approach extends naturally to three dimensions and to weaker symmetry assumptions, given an appropriate sampling strategy and dataset.
### Title:
          CanonicalPhys: Pose-Robust Remote Photoplethysmography via Canonical-Space Priors
 - **Authors:** Hui Wei, Seyedata Jodeiri Seyedian, Xiaobai Li, Guoying Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep remote photoplethysmography (rPPG) attains sub-bpm heart-rate error on frontal, stationary faces yet degrades sharply under head pose: on MMPD, the state-of-the-art FactorizePhys backbone's MAE grows $1.60\times$ from frontal ($|\text{yaw}|{<}15^\circ$) to large-yaw ($|\text{yaw}|{\geq}45^\circ$) frames. We argue that pose is a \emph{coordinate-structural} nuisance rather than a data-augmentation problem: in image coordinates the same pixel maps to different anatomy at different poses, blocking three priors otherwise natural for rPPG, namely the dichromatic reflection model, pulse-phase invariance across skin regions, and the POS/CHROM chromaticity projection, each of which presumes a stable anatomy-to-pixel mapping. We introduce \textbf{CanonicalPhys}, which prepends a differentiable four-point homography that fixes four facial anchors at canonical positions; in this canonical frame the three priors become expressible as a per-pixel Lambertian weight, a cross-ROI temporal consistency loss, and knowledge distillation from windowed POS, none of which adds trainable parameters over the backbone. At an identical parameter count, CanonicalPhys reduces MMPD's frontal-to-large-yaw MAE degradation from $1.60\times$ to $1.33\times$ and flattens the mild-yaw bin from $1.32\times$ to $1.07\times$ (across CanonicalPhys variants), with matched cross-dataset MAE reductions of up to $32\%$ on pose-rich targets. Code: this https URL
### Title:
          Beyond Unfolding: 60x Faster One-Stage Unmixing for Closely-Spaced Infrared Small Targets
 - **Authors:** Ximeng Zhai, Zheng Wang, Yaohong Chen, Hao Wang, Ming-Ming Cheng, Yimian Dai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Due to the optical diffraction limit and long imaging distances, Closely-Spaced Infrared Small Targets (CSIST) typically exhibit energy overlap, manifesting as indistinguishable blobs in infrared images. This ambiguity invalidates the one-to-one mapping assumption of traditional detection, thereby necessitating a paradigm shift towards CSIST Unmixing, which decomposes these blobs into discrete sub-targets. However, the dominant paradigm deep unfolding networks are shackled by the high latency and structural inflexibility intrinsic to their repetitively iterative architecture. To this end, we propose the Fast One-stage CSIST Unmixing Scheme (FOCUS), a one-stage lightweight paradigm which demonstrates that deep unfolding is not necessary. Motivated by the key observation that image super-resolution (SR) and CSIST Unmixing share an isomorphic degradation model, our insight is that it is possible to achieve a paradigm shift from image SR to CSIST Unmixing via completely transforming the label space, loss functions, and evaluation criteria. Specifically, to avoid entangling geometric recovery with artifact suppression, FOCUS adopts a single pass mapping with an internal coarse-to-fine flow that progressively refines target localization from coarse spatial distributions to finer sub-pixel precision. While sparsity regularization suppresses background clutter, it also attenuates target intensities. To compensate for this attenuation of valid signals, flux conservation is introduced as a competing constraint that restores signal energy back to target centers. To the best of our knowledge, this work is the first attempt to address this task via a lightweight one-stage framework without the DUN paradigm. Experiments demonstrate that our method matches or surpasses the state-of-the-art unfolding approaches in both localization and unmixing accuracy, while boosting the inference speed by 60x.
### Title:
          Network-Induced Strategic Communication in Opinion Dynamics
 - **Authors:** Hassan Munif, Anthony Couthures, Vineeth S. Varma, Samson Lasaulce, Tamer Başar
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classical opinion dynamics typically assume a fixed mapping from private opinions to public signals, such as linear exchange, saturated signaling, or discrete public actions. In this paper, we show that these communication mappings can be derived from a strategic communication game played on a weighted influence network. Each agent acts as a receiver estimating its neighbors' states and as a sender broadcasting a public signal to influence its audience. We prove that the network's effect on a sender is summarized by a scalar, network-induced exaggeration factor, and the network game decouples into independent scalar cheap talk problems. The communication rules then emerge as behavioral regimes of one model: aligned incentives recover linear averaging; persuasive senders facing naive receivers produce saturated signaling; and persuasive senders facing Bayesian receivers cannot credibly reveal their opinions, so equilibrium communication becomes an interval quantizer, providing a game-theoretic foundation for continuous-opinion discrete-action (CODA) dynamics. Embedded in repeated opinion updates, the resulting strategic-CODA dynamics preserve opinion clustering and exclude extremism. The model predicts that a speaker exaggerates more when their audience is less influenced by them, and that under strong exaggeration, credible public expression collapses to a binary stance even while private opinions remain continuous.
### Title:
          Controlling Implicit Shortcut Reliance in L2 Spoken English Auto-markers
 - **Authors:** Shilin Gao, Mark J. F. Gales, Kate M. Knill
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Increasingly, speech and language processing tasks take either audio or text directly rather than extracting features from these as the input to the classifier or regressor. Often these systems make use of complex, for example transformer-based, processes that have the ability to derive highly non-linear mappings between the input and the output. Unfortunately these systems can also learn ''shortcuts'' where the classifier is overly reliant on particular aspects of the input to yield the output. For the task of language proficiency assessment, this over-reliance can enable learners to increase their score by exploiting the shortcut rather than improving their ability. This paper introduces a novel training criterion that is able to reduce the classifier's reliance on shortcuts, thus for example limiting this option for malpractice in language assessment. This process is illustrated on two forms of assessment system, one based on the audio the other on the speech recognition text. The results show that, for both systems, there is higher correlations with features that could be exploited for malpractice than expected from the human reference, indicating an over-reliance on these features. By introducing the modified training criterion, this correlation can be reduced to be closer to the reference correlation.
### Title:
          Neural spectroscopy of AlphaFold2 reveals encoded protein conformational landscapes
 - **Authors:** Kaustav Mehta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Biomolecules (q-bio.BM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AlphaFold2's 93 million parameters, shaped by the evolutionary record of protein structure encoded in the Protein Data Bank and in sequence alignments, are conventionally treated only as machinery for converting sequence to structure. We propose they are also a scientific object that can be analyzed directly: a learned encoding of protein conformational organization that can be probed and characterized. By smoothing the Evoformer's weight tensors with a Gaussian convolution and scaling the result, we show that the trained model produces physically structured conformational landscapes. Under perturbation, ubiquitin's native contacts break in the order established by decades of folding experiments. For KaiB, five independently trained models agree that the alternative fold is not recovered under perturbation. For alpha-synuclein, five models produce five different but coherent landscapes, mapping where the training signal has determined the representation and where it has not. Matched-power noise controls confirm that random corruption of equal magnitude produces debris, not conformations. The model learned to predict static structures; the conformational organization visible under perturbation was not an explicit training target, suggesting it emerged as a byproduct of that objective. AlphaFold2's weights appear to encode structural constraints, shaped by evolutionary and structural training data, that extend beyond what unperturbed inference reveals. We call the approach of reading them neural spectroscopy, and Scaled Gaussian Convolution one such protocol.
### Title:
          A New Implementation of NeoSLAM and a Comparative Evaluation with RatSLAM
 - **Authors:** Joao Victor T. Borges, Fabio Coelho, Paulo Padrao, Jose Fuentes, Ramon R. Costa, Liu Hsu, Leonardo Bobadilla
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a new implementation of the NeoSLAM algorithm. The proposed version is a complete rewrite of NeoSLAM into a modular architecture using modern frameworks that, together, enable real-time execution with minimal discarding of input data. This work also provides a comparative evaluation between NeoSLAM and RatSLAM across three datasets under varying environmental conditions. The experimental results highlight differences in mapping consistency and trajectory reconstruction, demonstrating the effectiveness and practical applicability of the proposed ROS2-based implementation. The results indicate that the new NeoSLAM outperforms the original in terms of processing throughput for real-time applications and achieves comparable performance to RatSLAM in terms of map reconstruction across the evaluated datasets.
### Title:
          Adaptive Fault Injection Planning for Multi-Layer Self-Healing AI Infrastructure
 - **Authors:** Saurabh Kulkarni, Yuxin Yang, Rohan Kulkarni, Gautam Nayak
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern GPU-accelerator platforms rely on multi-layer self-healing pipelines that span hardware, firmware, management software, and orchestration. When faults propagate across layer boundaries, they can bypass detection, corrupt diagnosis, or trigger conflicting remediations--yet conventional fault-injection campaigns test each layer in isolation. We present ADA-ST, an adaptive fault-injection methodology that uses a weighted fault-propagation graph to guide cross-layer scenario selection. We construct four-layer graphs for three successive platforms at a hyperscale operator: Alpha, Beta, and Gamma. Platform Alpha, a production system that accumulated 72,550 repair tickets over four years, provides the empirical foundation; 49% of those tickets involve cross-layer fault propagation. We show that existing static test campaigns cover only 20-25% of the modeled fault-propagation edges, leaving approximately three-quarters of the cross-layer attack surface unexercised. ADA-ST closes this gap through iterative, activity-guided scenario selection that maximizes marginal coverage gain per iteration, reaching full edge coverage within 10 iterations on Alpha, 12 on Beta, and 9 on Gamma. The Fault-Layer Abstraction Mapping (FLAM) transfers propagation knowledge across hardware generations with 100% fidelity from Alpha to Beta and 96% from Beta to Gamma. Physical spot-validation on the newest platform confirms all four tested propagation edges, revealing cross-layer vulnerabilities spanning telemetry blind spots, absence-based detection gaps, multi-signal correlation failures, and trust-without-verification propagation at the L2-to-L3 boundary.
### Title:
          Evaluating Open-Weight LLMs for Generating Structured Threat Information for Autonomous Vehicle Vulnerabilities
 - **Authors:** Md Erfan, Ahmed Ryan, Md Kamal Hossain Chowdhury, Md Rayhanur Rahman
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Connected and Autonomous Vehicles (CAVs) rely on interconnected software and hardware components, including sensors, Electronic Control Units, in-vehicle infotainment systems, and telematics units, where vulnerabilities can compromise assets, users, and vehicle operations. These vulnerabilities are commonly documented as plain text in the Common Vulnerabilities and Exposures (CVE) database; however, security practitioners require structured information about affected assets, types of weaknesses, and attack behaviors to effectively mitigate the risks from these vulnerabilities. To this end, we evaluate open-weight Large Language Models (LLMs) for generating Structured Threat Information Expression (STIX), a well-known structured format for representing threat information, for CAV-related CVEs. We construct a dataset called CAV-STIXGen that maps CAV vulnerability descriptions to STIX domain objects (SDO), STIX relationship objects (SRO), Common Weakness Enumeration (CWE), and MITRE ATT&CK techniques mappings. Using this dataset, we evaluated 11 open-weight LLMs (4B to 120B parameters) across various prompting strategies and temperatures. Single-model configurations achieve F1 scores of 0.94 for SDO, 0.63 for SRO, and 0.99 for CWE mapping, while complete MITRE ATT&CK mapping remains challenging. In a multi-agent setup, Gemma-4-31B and Codestral-22B achieve F1 scores of 0.91 for SDOs and 0.43 for SROs, respectively. Lastly, we analyze CWE and MITRE ATT&CK co-occurrences to identify recurring threat patterns in the CAV domain, demonstrating how AI-assisted vulnerability-to-STIX translation can automate threat intelligence and prioritize defense in transportation security.
## Keyword: localization
### Title:
          Unsupervised Keypoints for Real-Time Fall Detection: Comparative Analysis Under Real-world Conditions with Predictive Bandwidth Reduction
 - **Authors:** Tasmiah Haque, Jacob Kosinski, Sumit Mohan, Srinjoy Das, Mohammad Abdullah Al-Mamun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Falls among older adults are a major safety challenge, but continuous monitoring is difficult to sustain. Video captures fall-related posture and motion, yet deployment is limited by privacy, computation, and bandwidth. Supervised pose estimation is anatomically interpretable but vulnerable to occlusion and partial body visibility. We propose a privacy-preserving framework that replaces RGB transmission with compact motion representations based on unsupervised keypoints and predictive temporal modeling. Local processing performs segmentation and keypoint extraction; variational recurrent prediction and sequence classification then detect falls from observed and forecasted motion. We evaluate the framework on the UR Fall Detection and Human Fall datasets using random, subject-disjoint, and occlusion-based splits. Under random splits, neither representation consistently dominates, suggesting that standard protocols may hide meaningful differences. Under subject-disjoint evaluation, supervised keypoints show a statistically significant advantage, but performance varies by subject: they perform better when anatomical landmarks are visible, whereas unsupervised keypoints are more robust to occlusion and partial visibility, though they produce more false positives for complex activities. Under occlusion-based evaluation, supervised keypoints miss nearly half of all falls, while unsupervised keypoints retain strong sensitivity and substantially outperform them. Their anatomical independence allows spatial anchors to adapt to visible body structure rather than fail on absent landmarks. The gap widens under bandwidth constraints, where supervised localization errors compound through the temporal model. These findings show that representation choice should reflect expected visual conditions and that unsupervised keypoints offer an advantage when body visibility is compromised.
### Title:
          STAR: Astrocyte-Inspired State-Augmented Repair for Supervised Memristive AI Hardware Systems
 - **Authors:** Yusuf Ahmed Khan, Zhuangyu Han, Abhronil Sengupta
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Memristive crossbar arrays have emerged as a promising platform for efficient on-chip learning, enabling local learning rules such as Equilibrium Propagation (EP) to be realized without the memory overhead of conventional backpropagation. However, as these devices age, permanent stuck-at (SA) faults accumulate at individual synaptic elements, irreversibly corrupting the stored weights and degrading model performance in ways that in-situ retraining alone cannot address. Existing mitigation strategies either rely on hardware redundancy at significant area and power cost, or require explicit fault localization that is impractical to perform continuously on-chip. This paper adopts a brain-inspired fault recovery route motivated by self-repair functionalities enabled by astrocytes -- a type of glial cell. We couple a computational neuroscience study of astrocytic neuromodulation under permanent synaptic faults with an algorithmic recovery mechanism for faulted crossbar-mapped networks. Our computational neuroscience study characterizes how astrocytes modulate surviving synapses in a bidirectional EP-specific network setting under both SA-0 and high-conductance stuck-at fault conditions, revealing that recovery operates at the neural population level. Motivated by this observation, we propose a retraining-based repair mechanism that augments EP with an additional repair nudge anchored to pre-fault activation targets of the healthy network, encouraging surviving weights to collectively reconstruct pre-fault internal representations without any information of which weights are faulty. To our knowledge, STAR is the first astrocyte-inspired repair mechanism to operate under a supervised local learning rule and to scale to convolutional networks.
### Title:
          VTAP Gripper: Synergizing Fingertip Sensing and a Visuo-Tactile Active Palm for Dexterous In-Hand Manipulation
 - **Authors:** Yuhao Zhou, Sheeraz Athar, Zhixian Hu, Binghao Huang, Yunzhu Li, Juan Wachs, Yu She
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a tactile-reactive gripper that integrates a Visuo-Tactile Active Palm (VTAP) and compliant, reconfigurable fingers equipped with tactile array sensors. The design exploits structured finger-palm synergy and multi-modal perception to achieve both robust grasping and fine manipulation. The actuated bi-modal palm seamlessly combines long-range visual localization with contact-rich tactile feedback, substantially extending the system's manipulation capability. To bridge the embodiment gap between human hand motion and the heterogeneous three-finger structure, we further propose a staged, gesture-conditioned retargeting framework for dexterous teleoperation. Extensive experiments validate the system across a range of challenging tasks: reactive grasping of YCB and fragile objects, in-hand syringe reorientation and plunger actuation, singulation of clustered objects down to 3 mm in diameter, and vision-tactile peg-in-hole insertion. Results demonstrate that high manipulation performance can be achieved through coordinated finger-palm interaction and multi-modal sensing, without resorting to high degrees of freedom anthropomorphic designs. The VTAP gripper and its retargeting framework offer a practical reference architecture for dexterous gripper design, manipulation, and contact-rich data collection in support of learning-based approaches. Project webpage: this https URL.
### Title:
          Trajectory-aware Cross-view Geo-localization with Sequential Observations
 - **Authors:** Tianyi Gao, Jiayu Lin, Danielle Beaulieu, Nathan Jacobs
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization matches ground-level observations against geo-tagged satellite imagery. Recent methods show that sequential queries such as video clips yield richer spatiotemporal cues than single images, yet they overlook a complementary sequential modality: route descriptions -- which capture the same trajectory at a higher level of abstraction and are often the only input available (e.g., a user directing an autonomous vehicle to a pickup point). To bridge this gap, we introduce SeqGeo-VL, a dataset of $\sim$39K video-text-satellite triplets, and TrajLoc, a unified framework capable of processing both video clips and route descriptions. By leveraging both dense visual and abstract linguistic semantics, TrajLoc enables these modalities to mutually reinforce cross-view matching. We further propose TrajMod, a lightweight module that conditions query embeddings on trajectory geometry, yielding spatially-aware representations. Experiments show that TrajLoc achieves substantial gains over state-of-the-art methods on both video and text geo-localization. The project page is available at this https URL.
### Title:
          Region-Grounded Vision-Language Learning for Detection-Guided Mammographic Lesion Classification
 - **Authors:** Zhengbo Zhou, Jiren Li, Dooman Arefan, Margarita Zuley, Shandong Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models trained with contrastive objectives have shown promise in medical image analysis. However, conventional global image-text alignment is ill-suited for mammography, where diagnostically relevant lesions are spatially localized and occupy only a small fraction of the image. Subtle morphological cues critical for malignancy assessment can be diluted when representations are learned at the whole-image level. In this work, we propose a novel region-grounded vision-language learning method for detection-guided mammographic lesion classification. The method mirrors radiologists' diagnostic paradigm. First, a region-text contrastive pretraining stage aligns lesion-specific features with structured clinical descriptors derived from radiology metadata. To mitigate semantic collapse and background bias in low-vocabulary settings, we introduce a multi-component objective incorporating positive alignment, fine-grained semantic hard negatives, and background suppression. Second, an auxiliary lesion detection head is jointly optimized with contrastive classification to preserve spatial sensitivity and enable localization-aware malignancy classification. Extensive experiments on two independent datasets, CBIS-DDSM and VinDr-Mammo, show superior performance of our method compared to related methods under in-domain, cross-dataset, and transfer learning settings.
### Title:
          Understanding Agent-Reactive Bugs at the Model-Harness Boundary: An Empirical Study of LLM Agent Issue Reports
 - **Authors:** Jingyi Chen, Songqiang Chen, Hengcheng Zhu, Jialun Cao, Jiasi Shen, Shing-Chi Cheung
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM agents span command-line interfaces (e.g., Codex) and agent frameworks (e.g., LangChain), integrating backend LLMs with harness code that parses model outputs, controls agent loops, and manages context. Both the harness and LLM-generated responses jointly shape an agent's execution. This architecture gives rise to bugs that cannot be readily understood by inspecting either component alone, because some bugs occur only when a particular LLM response elicits an abnormal reaction from the agent. Prior empirical studies of agent bugs have largely attributed failures either to limited model capabilities or to harness-side defects, such as outdated APIs and configuration misalignment, without characterizing these AR bugs. We conduct the first empirical study focused on agent-reactive (AR) bugs. Through manual analysis of 255 bug reports from Codex, Gemini-CLI, LangChain, and CrewAI, we construct a two-axis taxonomy covering observable symptoms and the LLM behaviors that trigger them. Our findings show that many AR bugs manifest as silent errors without well-defined test oracles, which makes detection difficult. The stochasticity of LLM responses further complicates bug reproduction. We additionally examine fixes proposed by users and implemented by developers. This analysis exposes a mismatch: users frequently advocate harness-side guardrails, whereas developers may attribute the issue to the LLM or respond slowly to user-proposed fixes. These findings point to the need for mechanisms that help users and developers understand the root causes and resolutions of AR bugs. Overall, the study highlights challenges specific to LLM agents and motivates the design of test oracles, reproduction support, and fault-localization techniques for AR bugs.
### Title:
          Implicit Virtual Leader: Decentralized Vision-Only Relative Pose Estimation for Multi-Robot Formations
 - **Authors:** Shiyuan Yang, Zelin Wang, Zhijia Tao, Yilin Wang, Zhengyu Hou, Xiaosong Kong, Borong Zhang, Yip Fun Yeung, Yuankai Luo, Sharon Lee, Qingbiao Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classical leader-follower formation control suffers from single points of failure and error propagation, and relies on absolute localization sensors that are ill-suited for GPS-denied environments. We address these limitations by introducing a fully decentralized, vision-only relative pose estimation framework based on Graph Neural Networks (GNNs). The key idea is the implicit virtual leader (IVL): a non-physical formation reference frame that is not tied to any individual robot but is implicitly learned within the GNN using only monocular images and inter-robot communication. We attach a heteroscedastic GNLL head for aleatoric uncertainty and MC~Dropout for epistemic uncertainty, and conduct a systematic comparison across simulation and real-world test sets. Our framework achieves competitive pose estimation accuracy and generalizes naturally to heterogeneous robot platforms and varying formation sizes.
### Title:
          Deployment-Ready UWB Localization for Industrial Ground Robots with Automatic Anchor Calibration and Terrain-Aware Fusion
 - **Authors:** Alexander Raab, Giulio Delama, Roland Jung, Stephan Weiss
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultra-Wideband (UWB) ranging has become a viable option for industrial Autonomous Mobile Robot (AMR) localization due to improved accuracy and low cost. However, real-world deployments remain limited by two recurring challenges: calibrating static anchors can be time-consuming and error-prone, and integrating UWB with existing onboard sensors requires careful design to ensure robust and consistent pose estimation. Addressing these challenges, this paper presents an end-to-end pipeline that combines automatic anchor calibration with a generic multi-sensor estimator tailored to surface-bound vehicle motion. It targets existing AMR stacks in scenarios where robot pose priors are available for initialization. The calibration stage estimates anchor positions and range biases, while the localization stage fuses UWB with proprioceptive sensing in a bias-aware Extended Kalman Filter to improve consistency without extensive parameter tuning. Experiments on a commercial logistics AMR in a warehouse setting demonstrate accurate positioning indoors and across outdoor transitions, with improved consistency compared to an earlier estimator formulation. Evaluation on an independent forklift dataset further indicates transferability to other platforms. The method remains effective in test cases with limited line-of-sight and sparse anchor coverage. These results show that UWB localization can be deployed with substantially reduced manual effort while preserving the accuracy required for industrial AMRs. The collected warehouse dataset is made publicly available.
### Title:
          More with Less: a Large Scale Remote Sensing VLM with a Simple Recipe
 - **Authors:** Stefan Maria Ailuro, Mario Markov, Mohammad Mahdi, Luc Van Gool, Danda Pani Paudel (INSAIT, Sofia University "St. Kliment Ohridski")
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing vision-language models are increasingly expected to support open-ended reasoning over Earth Observation data and a variety of tasks. Most recent progress in this area has been driven by remote-sensing-specific architectural designs, often introducing new encoders, alignment modules, or task-specific fusion mechanisms. In this work, we challenge the necessity of such architectural specialization. We show that a generally capable vision-language model can achieve competitive or state-of-the-art performance at challenging remote sensing benchmarks, provided that it is trained at sufficient scale across diverse data and tasks. Our model uses a single language policy that can either answer directly in text or invoke a localization tool for segmentation and grounding. To train this heterogeneous behaviour, we employ a multi-task reinforcement learning framework with adaptive task rewards covering multiple-choice VQA, free-form VQA, captioning, detection, and segmentation across a large variety of input types. Our approach achieves competitive results across a broad set of benchmarks, including high-resolution, multi-temporal, multi-modal and multi-view tasks. Further, as training data scales, our experiments show consistent improvements across most tasks both in and out of distribution, which correlate with per-task data diversity. These findings suggest that, for remote sensing VLMs, data scale is more important than architectural novelty.
### Title:
          Beyond Unfolding: 60x Faster One-Stage Unmixing for Closely-Spaced Infrared Small Targets
 - **Authors:** Ximeng Zhai, Zheng Wang, Yaohong Chen, Hao Wang, Ming-Ming Cheng, Yimian Dai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Due to the optical diffraction limit and long imaging distances, Closely-Spaced Infrared Small Targets (CSIST) typically exhibit energy overlap, manifesting as indistinguishable blobs in infrared images. This ambiguity invalidates the one-to-one mapping assumption of traditional detection, thereby necessitating a paradigm shift towards CSIST Unmixing, which decomposes these blobs into discrete sub-targets. However, the dominant paradigm deep unfolding networks are shackled by the high latency and structural inflexibility intrinsic to their repetitively iterative architecture. To this end, we propose the Fast One-stage CSIST Unmixing Scheme (FOCUS), a one-stage lightweight paradigm which demonstrates that deep unfolding is not necessary. Motivated by the key observation that image super-resolution (SR) and CSIST Unmixing share an isomorphic degradation model, our insight is that it is possible to achieve a paradigm shift from image SR to CSIST Unmixing via completely transforming the label space, loss functions, and evaluation criteria. Specifically, to avoid entangling geometric recovery with artifact suppression, FOCUS adopts a single pass mapping with an internal coarse-to-fine flow that progressively refines target localization from coarse spatial distributions to finer sub-pixel precision. While sparsity regularization suppresses background clutter, it also attenuates target intensities. To compensate for this attenuation of valid signals, flux conservation is introduced as a competing constraint that restores signal energy back to target centers. To the best of our knowledge, this work is the first attempt to address this task via a lightweight one-stage framework without the DUN paradigm. Experiments demonstrate that our method matches or surpasses the state-of-the-art unfolding approaches in both localization and unmixing accuracy, while boosting the inference speed by 60x.
### Title:
          VTLoc: Learning-based Tactile Contact Localization in Visual Point Clouds
 - **Authors:** Zhiyuan Wu, Zhuo Chen, Shan Luo
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision and touch are complementary modalities essential for robotic perception and manipulation. While vision provides global object context, touch offers precise local information at contact points. Integrating these modalities for contact localization, i.e., predicting the location of touch on an object's surface, poses significant challenges due to the need for accurate spatial alignment between tactile data and visual geometry. To address this challenge, we propose VTLoc, a novel visual-tactile framework that localizes contact points from tactile readings using a 3D point cloud as visual input. VTLoc introduces two key components: a geometric multi-modal alignment module, which reconstructs a pseudo-point cloud from fused visual-tactile features and aligns it with the visual point cloud to enforce spatial consistencies across modalities; and an iterative localizing updater, which iteratively refines the predicted contact location using fused visual-tactile features. Evaluated on a new benchmark of 100 real-world objects, VTLoc improves single-touch contact localization by reducing local-to-global correspondence ambiguity.
### Title:
          Knowing the Self, Understanding the World: A Dual-Cognition Benchmark for UAV Spatio-temporal Reasoning with MLLMs
 - **Authors:** Like Liu, Zhengzheng Xu, Haitao He, Hongzhe Li, Shuchang Zhang, Dian Shao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models have achieved strong performance across diverse vision-language tasks, yet their capabilities in UAV scenarios remain insufficiently explored. Recent UAV-oriented benchmarks have begun to evaluate MLLMs in aerial scenarios, but they typically focus on scene understanding, event recognition, or navigation completion, rather than jointly assessing the dual-cognition capability required for UAV agents: reasoning about both the UAV's own state and the external environment in multiview spatio-temporal contexts. To address this gap, we present UAV-DualCog, a benchmark for aerial multiview spatio-temporal reasoning built on this dual-cognition perspective. UAV-DualCog includes both image and video tasks to jointly evaluate self-state and environment-state reasoning, while requiring spatial or temporal grounding beyond discrete answer prediction. We also develop an automated pipeline that constructs data from scene-level semantic point clouds, yielding a scalable benchmark with diverse scenes, hundreds of landmarks, and thousands of QA samples. Extensive evaluations show that current MLLMs remain far from reliable in UAV dual cognition. Self-state reasoning, viewpoint transformation, precise spatial grounding, and temporal interval localization are persistent bottlenecks, and additional validation with thinking/frontier models and a human baseline confirms that the benchmark is understandable to humans but challenging for existing models. We further construct UAV-DualCog-Train from disjoint scenes and show through a lightweight optimization probe that it provides useful structured supervision, suggesting its value not only as an evaluation benchmark but also as a data resource for advancing MLLM-based UAV agents. Project website and supplementary materials: this https URL
## Keyword: transformer
### Title:
          AV-JEPA: Extending LeJEPA to Audio-Visual Self-Supervised Learning
 - **Authors:** Benjamin Robson, Santeri Mentu, Wenshuai Zhao, Arno Solin
 - **Subjects:** Subjects:
Multimedia (cs.MM); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present AV-JEPA, an elegant multimodal extension of LeJEPA to audio-visual self-supervised learning. Using an early-fusion Vision Transformer and modality dropout as masking, the model is trained to align the embeddings of global and per-modality local views, while the SIGReg objective encourages a theoretically optimal distribution. This achieves cross-modal alignment in the latent space, resulting in a remarkably clean architecture with no decoder, EMA teacher, complex multi-term losses, or contrastive negatives. The proposed AV-JEPA backbone delivers competitive classification performance on VGGSound (57.1% top-1) and AudioSet (32.7 mAP) and supports zero-shot audio-video retrieval out of the box.
### Title:
          LLM4EHR: Aligning Clinical Time Series with Medical Event Sequences via Large Language Models
 - **Authors:** Jingteng Li, Alexander Capstick, Louise Rigny, Iona Biggart, Neil J Sebire, Payam Barnaghi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent research in clinical machine learning, focusing on outcome predictions in intensive care unit (ICU), has shifted from bespoke supervised models to foundation models, utilising modern representation learning methods. Here, foundation models are pre-trained on mixtures of complex clinical data modalities, useful for various downstream tasks. Existing works often utilise Electronic Health Records (EHR) to provide rich and diverse patient observations to train clinical foundation models. However, existing methods do not sufficiently explore the shared temporal structures between clinical events and time series (TS) observations recorded in EHRs. This limitation potentially leads to less robust and adaptive clinical foundation models, resulting in reduced performance on downstream tasks. To fully exploit this temporal structure, we propose LLM4EHR, a new clinical foundation model trained on ICU EHR data. Combining domain adapted large language models with a transformer TS encoder, we pre-trained LLM4EHR by temporally aligning the EHR events and TS. For this, we propose a regularised contrastive objective to learn robust EHR TS representations conditioned on EHR event embeddings produced by the domain adapted LLM. Supported by an ablation study, we find that learnt EHR TS embeddings from LLM4EHR improve performance on various downstream clinical tasks with competitive performance. Further, we empirically demonstrate that LLM4EHR learns transferable clinical TS embeddings that can be deployed to new cohorts via k-shot adaptation. These findings provide a step towards building more generalisable and performant clinical foundation models.
### Title:
          Relevant and Irrelevant: A Renormalization Group Analysis of Transformer Attention
 - **Authors:** Parviz Haggi-Mani, Irina Rish
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Using the language of Wilsonian renormalization group theory (RG), we treat the Transformer's attention mechanism as a perturbation of the trained MLP residual-stack fixed point and ask whether it constitutes a relevant, marginal, or irrelevant operator. We derive a fixed-point shift formula and obtain four testable predictions for the fixed-point geometry, effective rank profile, layer specificity, and perturbation decay spectrum. Testing these on synthetic Markov chain sequences with controlled correlation length, we find: (1) For large chains(long correlation), attention is strongly relevant: it closes a residual loss gap the MLP cannot bridge and drives a phase transition in representation space, with effective rank jumping above input dimensionality at layer 1 and stabilizing at a high-dimensional plateau. (2) For short chains(short correlation), attention is irrelevant: the Transformer converges to the same loss and fixed-point geometry as the MLP, though it contracts perturbations faster. (3) The transition is dominated by the first-layer head (L0H0), which accounts for more than 4 times the representational shift of any subsequent head, consistent with the prediction that the relevant operator acts before the MLP begins integrating out positional variation. (4) Perturbation decay experiments reveal a regime reversal: in the long correlation regime the Transformer selectively preserves slow Markov modes (5.4 times the dynamic range in decay length vs. 1.3 times for the MLP); in the short correlation regime it suppresses all modes faster than the MLP, with no spectral selectivity. Together, these results show that the relevance of attention is not a property of the architecture but of the spectral structure of the data-generating process, and that a first-order RG perturbation framework provides a predictive account of that difference.
### Title:
          Looped Latent Attention: Cross-Loop KV Compression for Looped Transformers
 - **Authors:** James O' Neill, Fergal Reid
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped, weight-tied Transformers reduce parameters by reusing a block, but decoding still stores a separate K/V cache for every recurrence step. We show that this loop-indexed cache is highly structured. For a fixed token, layer and head, K/V vectors trace a short low-rank trajectory across loops, while the head and layer axes remain much flatter. We introduce Looped Latent Attention (LLA), a post-training cache codec that stores compact K and V latents and reconstructs loop-specific K/V vectors only when attention reads them. The default per-head codec compresses recurrence, while LLA-2D also folds heads into one latent for the extreme-compression regime. The codec is initialized from SVD of teacher activations and refined with KL and attention-output distillation. At matched cache budget, per-head LLA outperforms head-axis MLA, cross-layer sharing, KV quantization and final-loop reuse, showing that the recurrent cache is low-rank but not safely collapsible to a single state. The same axis advantage holds on Ouro-2.6B-Thinking and transfers to Huginn-3.5B, where an SVD codec remains near-lossless to 32x in decoder-independent evaluation. The cache reduction is exact. On one H200, the latent-store path increases measured Ouro-1.4B batch capacity at 4k context from 32 to 768 sequences at 21.3x compression. For long math rollouts, on-policy refinement on student-generated prefixes raises MATH-500 at 4x from 0.43 to 0.66 and reduces no-answer generations.
### Title:
          FLINT: Fingerprinting Federated Learning Architectures from 5G PHY-Layer Side Channels
 - **Authors:** Md Nahid Hasan Shuvo, Mahmudul Hassan Ashik, Moinul Hossain
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated Learning (FL) over 5G cellular networks protects raw data but remains vulnerable to side-channel leakage. Prior fingerprinting attacks assume packet-level network visibility, an assumption that does not hold at the 5G Physical (PHY) layer, where user payloads are encrypted and Radio Network Temporary Identifiers (RNTIs) may change over time. However, we demonstrate that PHY-layer scheduling metadata broadcast over the Physical Downlink Control Channel (PDCCH) preserves architecture-associated temporal patterns. We introduce FLINT, a novel black-box fingerprinting framework that infers FL model architecture families, including CNNs, RNNs, and Transformers, using only coarse PHY-layer observations. FLINT overcomes the lack of network-layer visibility by decoding PDCCH scheduling information, mapping changing RNTIs to physical user devices, and applying multi-view temporal modeling to distinguish architecture-specific training behavior. This leakage is security-critical because knowledge of a client's model architecture can transform passive reconnaissance into targeted downstream exploitation. Extensive experiments on an over-the-air srsRAN-based 5G testbed demonstrate that FLINT achieves a macro F1-score of 0.930 for architecture-family classification. To our knowledge, FLINT is the first work to fingerprint AI/ML model architectures using lower-layer 5G side-channel information obtainable by any protocol-aware adversary.
### Title:
          Deep Learning Approaches for Sleep Apnea Classification from Polysomnographic EEG Signals
 - **Authors:** Shashank Manjunath, Mukesh Cheemakurthi, Aarti Sathyanarayana
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sleep apnea diagnosis via polysomnography remains resource intensive and relies on time consuming manual data analysis and scoring. Recent work has demonstrated that central nervous system effects of sleep apnea events can be detected through electroencephalogram (EEG) signals. However, most work uses a single feature type on various datasets combined with different classification algorithms. In this work, we present a comprehensive comparison of deep learning architectures and feature representations for automated sleep apnea detection from multichannel EEG on a single dataset of pediatric subjects. We evaluate Vision Transformers and Graph Attention Networks across distinct signal representations: raw temporal signals, short-time Fourier transform spectrograms, coherence based graphs, and two topological data analysis (TDA) derived features. Using age and sex matching of our train and test sets, we train on 2410 pediatric subjects and test on 575 pediatric subjects. We achieve a best test AUC of 0.750 using a vision transformer based model trained on TDA features. Stratified analysis across patient demographics (age, sex, AHI severity) and sleep stages (N1, N2, N3, REM) reveals significant performance variation. Our results demonstrate the feasibility of EEG based automated OSA screening while highlighting essential challenges for clinical deployment.
### Title:
          Kolmogorov--Arnold Networks for Small Language Models
 - **Authors:** Felippe Alves, Renato Vicente
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Kolmogorov--Arnold Networks (KANs) replace fixed node activations with learned one-dimensional edge functions, offering an explicit interface for interpretation and a possible alternative to transformer feed-forward networks. We test these claims separately. In a six-layer, 10M-parameter B-spline KAN, we reconstruct all 884,736 feed-forward edges: 87.8\% exceed (NLS>0.1) and 0.4\% are inactive. Pruning the lowest-activity 20--25\% causes negligible loss increase, although structured MLP neuron pruning tolerates comparable sparsity. The audit replicates on BabyLM, but grid-size sweeps show that near-total fPCA compression and high closed-form-fit coverage are properties of the low-capacity grid-2 basis, not universal KAN behavior. For replacement, we evaluate MLP, SwiGLU, grouped Chebyshev, and rational GR-KAN networks on BabyLM. The KAN-family and gated variants improve validation loss over the GELU MLP, but this ordering does not transfer to standardized benchmarks: across ten seeds and 59,875 BLiMP pairs, accuracies span 62.4--63.1\%, EWoK remains at chance, and a (+0.7)-point GR-KAN effect on BLiMP reverses on the supplement. Larger tests are also cautionary: parameter-matched MLPEdge underperforms the MLP on Wikitext-103, and 286M-parameter GR-KAN remains below a SwiGLU ClimbMix baseline after stabilization. Thus, small-basis KANs provide a practical, corpus-transferable interface for auditing learned scalar transformations, but the tested replacements show no consistent benchmark, quality, or latency advantage over strong MLP baselines.
### Title:
          LLMs Encode Relevance as a Layer-Wise Cross-Lingual Signal
 - **Authors:** Pietro Bernardelle, Samaneh Mohtadi, Stefano Civelli, Joel Mackenzie, Gianluca Demartini
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used in information retrieval (IR) pipelines as relevance judges and re-rankers. Yet most analyses remain output-centric, evaluating generated labels or scores while offering limited insight into how relevance is represented inside the model. In this work, we study whether query-document (q-d) relevance is linearly decodable from residual-stream activations in instruction-tuned LLMs, how this signal compares with generated relevance judgments, and whether it transfers across languages. Using the TREC DL20 and MIRACL evaluation collections, we guide medium-scale LLMs (4-9B parameters) with UMBRELA-style relevance judgment prompts, extract last-token activations from every transformer layer, and train linear probes to predict relevance labels. We compare probe predictions with generated judgments and use TREC DL20 to test whether probe-derived pseudo-labels preserve system rankings against human judgments. Our results suggest that q-d relevance is encoded as a depth-dependent signal: probe performance is weak in early layers and strongest in middle-to-late layers, indicating that relevance becomes more linearly accessible after contextual integration. Most importantly, in several models, validation-selected probes match or outperform generated judgments and better preserve system rankings, revealing a separation between internal relevance representation and external expression. Multilingual experiments suggest partial cross-language portability, although transfer remains weaker than within-language decoding. Overall, this work provides a representation-level perspective on LLM-based relevance assessment. Layer-wise probing can help diagnose where relevance emerges, when generated judgments fail to reflect internally available evidence, and how relevance representations vary across languages, datasets, and model families.
### Title:
          Are All Tokens Necessary for Visual Place Recognition? An Empirical Study of Token Reduction for Efficient Inference
 - **Authors:** Tong Jin, Yunpeng Liu, Shuyu Hu, Qinghua Zhang, Ruize Han, Song Wang, Feng Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent visual place recognition (VPR) methods based on vision transformers, particularly foundation models, have achieved remarkable recognition performance. However, these models process all visual tokens throughout the entire network, resulting in substantial computational overhead, which hinders their deployment in real-time and resource-constrained scenarios. A natural question thus arises: are all visual tokens necessary for VPR? To answer this question, we present the first systematic benchmark of token reduction for efficient visual place recognition. Our benchmark comprehensively evaluates representative token pruning, token merging, and hybrid pruning-merging methods across multiple state-of-the-art VPR models and diverse benchmark datasets covering urban, suburban, and natural environments. We further investigate token reduction from multiple perspectives, including recognition performance under different reduction configurations, computational complexity, inference speed, qualitative visualization, and deployment efficiency on edge devices. Through extensive experiments and in-depth analysis, our benchmark reveals multiple important characteristics of token reduction in VPR and provides several practical insights into the trade-offs between accuracy and inference efficiency. For example, token reduction can reduce computational cost by up to 29\% and improve throughput by up to 44\%, while incurring less than 1\% degradation in recognition accuracy. Overall, this work establishes a comprehensive foundation for future research on token-efficient VPR and efficient visual retrieval systems. Our codes and models will be available at this https URL
### Title:
          MGDT: MLLM-Guided Diffusion Transformer with Relation-Adaptive Mixture-of-Experts for Multimodal Knowledge Graph Completion
 - **Authors:** Xu Hou, Meiyu Liang, Wei Huang, Yawen Li, Zhe Xue, Wu Liu, Guanhua Ye, Lei Shi, Kangkang Lu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Knowledge Graph Completion (MKGC) requires inferring missing entities from structural, textual, and visual cues. Existing diffusion-based MKGC methods usually denoise directly on raw multimodal features. Such a design forces the denoiser to simultaneously perform relation-dependent cue selection, cross-modal semantic alignment, and structure-aware entity generation, which introduces noisy and semantically inconsistent conditions for diffusion and consequently leads to suboptimal completion performance. To address this limitation, we propose MGDT: MLLM-Guided Diffusion Transformer with Relation-Adaptive Mixture-of-Experts (MGDT), a novel MKGC framework built on an align-then-diffuse paradigm. MGDT first employs a Relation-Adaptive Semantic Routing Mixture-of-Experts (RASR-MoE) module to select relation-relevant multimodal semantic transformation paths and suppress irrelevant modality interference. MGDT then uses a frozen Multimodal Large Language Model (MLLM) as a semantic anchor to align the routed multimodal representations into a unified latent space and reduce cross-modal semantic heterogeneity. Finally, a Knowledge Graph Diffusion Transformer (KGDT) performs graph-conditioned denoising generation in the aligned space to produce the missing entity representation. Experiments on three benchmark datasets show that MGDT consistently outperforms strong baselines.
### Title:
          WREN: Low Light Image Enhancement Using Retinex theory-based Double U-Net-like Structures
 - **Authors:** Reina Kaneko, Junya Hara, Hiroshi Higashi, Yuichi Tanaka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a neural network for low light image enhancement (LLIE) based on retinex theory to make LLIE robust for various dynamic range scenes. The retinex theory is an image formulation model inspired by a human color perception hypothesis, where a low light image is decomposed into intrinsic color context (i.e., reflectance map) and scene-dependent illumination (i.e., illumination map). Due to non-uniqueness of its decomposition, existing retinex-based LLIE methods often fail to achieve stable decomposition, which lead to over-enhancement. Typically, they are sensitive to the dynamic ranges that vary in different lighting conditions. To tackle this issue, we propose WREN: An LLIE neural network with double U-Net-like structures. WREN consists of two U-Net-like sub-networks. The first network has one encoder and two decoders that decompose an input image into the reflectance and illumination maps. The second network with a customized Transformer block between an encoder and a decoder only enhances the illumination map obtained from the first network: This completely follows the assumption of the retinex theory. Finally, the enhanced illumination map is recombined with the reflectance map. The network is trained end-to-end with a scale-invariant loss function, which gives robustness against the illumination scaling. Numerical results show that our method achieves the state-of-the-art performance across multiple datasets. Our code is available online.
### Title:
          StemFX: Learning Mixing Style Representations via Autoregressive FX Chain Prediction on Source-Separated Stems
 - **Authors:** Yuan-Chiao Cheng, Jui-Te Wu, Brian Chen, Yen-Tung Yeh, Yu-Hua Chen, Yi-Hsuan Yang
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio mixing style encompasses the artistic and technical decisions a mix engineer makes, including level balancing, spatialization, and the choice, ordering, and parameterization of audio effects (FX) on each stem. FX chains are a key determinant of this style, yet existing approaches to modeling them remain limited. Some operate on stereo mixtures without explicit per-stem FX chain modeling, others fix the number or type of effects per track, and many require differentiable effect implementations or scarce multitrack datasets. We present StemFX, a framework that learns mixing style representations by autoregressively predicting variable-length FX chains on source-separated stems. A Transformer decoder predicts tokenized FX chains autoregressively, while a band-split multi-band CNN encoder with FiLM conditioning captures per-stem spectral structure. To enable large-scale paired training, we extract pseudo-stems from about 105K songs via source separation and augment them using MultiAFx, a toolkit unifying 85 audio effects from 7 Python libraries. Evaluated on mixing style retrieval, StemFX outperforms all baseline models across all tested chain lengths. On paired mixing style transfer, StemFX achieves the best spectral fidelity and the highest listener preference, over 4000 times faster than iterative optimization.
### Title:
          BCG-Former: Toward Pareto-Efficient Hyperspectral Image Classification via Band-Contextual Gating
 - **Authors:** Gaurav Sharma, Eungjoo Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyperspectral image (HSI) classification systems are increasingly deployed on platforms with strict computational budgets, such as UAVs and small spaceborne sensors. In these settings, accuracy alone is not enough; the model must also run within tight latency and memory constraints. Most recent HSI classifiers, however, focus on accuracy and pay relatively little attention to these constraints. We propose BCG-Former, a lightweight CNN-Transformer hybrid that targets this trade-off. The model introduces three innovations: (1) Band-Contextual Gating (BCG) for adaptive spectral recalibration using local inter-band context and learnable temperature sharpening, (2) a spectral summary token that bridges spectral and spatial features, and (3) single-pass Band-RoPE combined with linear attention for efficient joint representation learning. Evaluated on classical airborne (Pavia University, Salinas, Indian Pines, Houston 2013/2018) and UAV-borne benchmark datasets (WHU-Hi-LongKou, HongHu, and HanChuan), BCG-Former achieves over-all accuracy ranging from 91.51% on Houston 2018 to 99.49% on Houston 2013, while maintaining sub-millisecond inference latency (0.91-0.95ms) and using only 0.10-0.23M parameters. Across all eight benchmarks, BCG-Former consistently resides on or near the Pareto frontier of accuracy versus latency, outperforming or matching recent CNN-, Transformer-, and Mamba-based methods at a fraction of their computational cost. Ablation studies confirm that all three components are complementary, with BCG providing the largest individual contribution. These results establish BCG-Former as a strong accuracy-efficiency Pareto candidate for real-time and large-scale remote sensing applications.
### Title:
          DiTango: Cost-Effective Parallel Diffusion Generation with Selective Attention State Reuse
 - **Authors:** Yuyang Chen, Runxin Zhong, Zan Zong, Hengjie Li, Yuyang Jin, Jidong Zhai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in AI-generated content have driven widespread adoption of Diffusion Transformers (DiTs) for high-resolution, long-duration content generation. While parallelization techniques accelerate diffusion inference, they face significant scalability challenges due to excessive communication overhead in multi-node environments. We observe that sequence partitions in Context Parallelism (CP) exhibit distinct heterogeneity: spatially proximate partitions contribute more significantly to attention computation results. By mapping this heterogeneous pattern to hierarchical communication topology, we can access high-contribution partitions with reduced communication cost. This insight motivates our novel selective attention state mechanism that strategically balances partial attention computation and historical result reuse across denoising steps. We present DiTango, an efficient parallel framework for DiT generation. DiTango features an anchor-guided state selection planner that optimizes computation-reuse decisions for each partition, complemented by a runtime that orchestrates efficient state-centric operations. This design achieves superior system efficiency while preserving generation quality. Experimental evaluation on popular diffusion models demonstrates that DiTango achieves up to 1.9x end-to-end and 3.2x attention speedup with near-linear scaling in multi-node settings, while maintaining generation quality comparable to state-of-the-art approaches.
### Title:
          PE-Field 4D: Video Generation Models as Canvas
 - **Authors:** Yunpeng Bai, Haoxiang Li, Qixing Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers have recently achieved strong performance in video generation, yet controlling scene geometry under viewpoint changes and camera motion remains challenging. In this work, we revisit the role of positional encoding in video diffusion transformers and show that it provides a useful spatial bias for geometry-aware control. Specifically, if reference tokens are encoded according to their projected locations in the target view, the denoising model is encouraged to retrieve content from position aligned regions of the input video. Building on this observation, we introduce a geometry-aware cross-attention mechanism that enables target video latent tokens to attend to structured context tokens derived from reference images or frames. To establish correspondence between the reference content and the target camera trajectory, we equip the context tokens with a projected positional encoding scheme that combines target-view 2D reprojection with depth-aware disambiguation. At the same time, we preserve the original spatiotemporal positional encoding of the generated video latent, allowing geometric guidance to be injected while maintaining consistency with the video model's native latent structure. The resulting framework provides a simple and effective approach for controllable video generation. It improves spatial controllability in viewpoint-dependent editing tasks, including camera re-trajectory, novel-view video synthesis, and geometry-aware video editing, while preserving the generative prior of the underlying video diffusion model. The code is available at: this https URL.
### Title:
          A Benchmark for Electrical Load Forecasting Across Grid Levels: Time-Series Transformers Outperform Established Methods
 - **Authors:** Matthias Hertel, Sebastian Pütz, Jonathan Kolar, Benjamin Schäfer, Ralf Mikut, Veit Hagenmeyer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate load forecasting at multiple grid levels is essential for future smart grids, ranging from aggregated control area forecasts for balancing supply and demand to forecasts of individual end-consumer loads for demand-side management and energy management systems. We present a comprehensive benchmark for load forecasting across grid levels, comprising three datasets that represent a transmission system operator control area, low-voltage grid feeders, and individual end consumers. We evaluate ten methods for short-term load forecasting and find that Transformer-based approaches consistently outperform established methods, reducing forecast error by 6.6-10.7 %. To analyze the impact of architectural design, we introduce YAformer, a flexible Transformer architecture that integrates modifications from prior work and is optimized via hyperparameter optimization. However, the standard Transformer achieves superior performance, suggesting that these architectural modifications are not required for accurate load forecasting. We further evaluate the Transformer-based time-series foundation model Chronos-2, which demonstrates competitive zero-shot performance on two datasets but fails to accurately capture special events in the TSO data. Detailed analyses reveal model-specific strengths and weaknesses, and ablation studies highlight the importance of long input contexts, covariates and continuous retraining - aspects that are often overlooked in the time-series forecasting literature.
### Title:
          Scaling Time Series Classification via XAI-Driven Data Reduction
 - **Authors:** Davide Italo Serramazza, Thach Le Nguyen, Georgiana Ifrim
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Explainable AI (XAI) for time series has seen significant algorithmic growth, but its utility in providing measurable performance gains for downstream tasks remains under-explored. This paper bridges this gap by introducing drXAI, a novel methodology that repurposes XAI attribution methods for effective data reduction in Time Series Classification (TSC). The core challenge in modern TSC is scalability; state-of-the-art models, such as Transformers, exhibit quadratic complexity relative to sequence length and linear complexity relative to the number of channels. This renders them computationally prohibitive for massive datasets. drXAI addresses this by using a fast, GPU-accelerated classifier (Hydra) to generate local attributions. We aggregate these into global feature importance scores and employ an automated elbow-cut heuristic to select the most salient features without requiring manual thresholds. We evaluate our approach on both synthetic and real-world univariate and multivariate datasets. On synthetic benchmarks, drXAI successfully recovers ground-truth features where traditional baselines fail. On real-world data, drXAI achieves between 80% and 90% data reduction while maintaining classification accuracy comparable to models trained on the full dataset. Most importantly, we show that drXAI allows resource-intensive models like ConvTran to scale to datasets that were previously inaccessible due to memory constraints. Our results show the benefits of using XAI not just for interpretability, but as a robust tool for feature selection and scalability in time series analysis. All our code and data are openly available.
### Title:
          In-context learning of closed form solution to simple linear regression task using transformer with linear self-attention
 - **Authors:** Katsuyuki Hagiwara
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning is a remarkable property of transformers and has recently received a lot of interest. In many studies of in-context learning, it has been shown that transformers are capable of implementing solver for linear and non-linear regression problems, in which the most of them implement gradient descent algorithm. However, it is still unclear whether those implementations have actually been acquired through training. In this paper, we construct a transformer with linear self-attention, which in-context learns the least squares estimate in a simple regression task. The point here is that the closed form (analytical) solution is approximately obtained by using layer normalization rather than an approximate solution based on gradient descent algorithm. Then, we show an experimental example, in which our implementation is mainly used in the transformer trained with l1 regularization when the target output is the least squares estimate.
### Title:
          Cost-efficient generative AI summarization for scalable automated essay scoring in educational assessment
 - **Authors:** Haowei Hua
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated essay scoring (AES) enables scalable assessment and timely feedback but remains challenged by transformer input-length limitations, which can cause information loss when processing long essays. This study proposes a generative AI-assisted summarization framework to improve long-form essay representation while maintaining scoring reliability. Using the ASAP 2.0 dataset, we generate controlled-length summaries with three GPT-5 variants (GPT-5, GPT-5 mini, and GPT-5 nano) and use them as inputs for downstream AES models. To preserve original writing signals, handcrafted linguistic features extracted from full essays are integrated with summary representations to form a hybrid framework. The approach is evaluated in terms of scoring performance, summarization quality, and computational cost. Scoring reliability is measured using quadratic weighted kappa (QWK), while summary quality is assessed through lexical overlap, semantic similarity, information retention, and redundancy metrics. Results show that GPT-5 mini achieves the highest agreement with human ratings, whereas GPT-5 produces the strongest summarization quality. Summary quality decreases for higher-scoring essays, indicating that more complex writing is more difficult to compress without information loss. These findings reveal trade-offs among model capacity, summary fidelity, cost efficiency, and preservation of educational constructs. This study provides an initial controlled evaluation of GPT-based summarization for AES and identifies important baselines and ablation studies required for future generalization. Overall, generative AI summarization offers a promising approach for scalable writing assessment while requiring careful validation of information preservation and fairness.
### Title:
          DSTAR: Accelerating Diffusion Transformers via Spatial and Temporal Redundancy Reduction
 - **Authors:** Chi Zhang, Jieru Zhao, Yu Feng, Chen Zhang, Quan Chen, Minyi Guo
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have been widely used in many tasks, including image synthesis, video generation, and content editing. However, their multi-iteration inference process leads to performance inefficiency and high energy consumption. Existing acceleration methods primarily focus on reducing temporal redundancy between adjacent timesteps, but often overlook the specific features of DiTs. As a result, these approaches either suffer from great accuracy degradation or fail to achieve high efficiency. We present DSTAR, a software-hardware co-design framework that accelerates DiT inference by reducing spatial and temporal redundancy. At the algorithmic level, DSTAR introduces a fine-grained mixed-precision quantization method for differential activations in linear operations, significantly increasing the proportion of low-bit computations. Additionally, DSTAR incorporates a sparse attention reuse mechanism to minimize redundant computation in attention layers. For architectural support, we design a specialized hardware accelerator which achieves high efficiency in both latency and energy consumption. Evaluation on seven typical DiTs demonstrates that DSTAR achieves up to 7.33x latency speedup and 41.89x energy savings compared to an NVIDIA A100 GPU, and achieves up to 2.54x latency speedup and 3.68x energy savings compared to SOTA accelerators, without accuracy degradation.
### Title:
          Conditional Reliability of Toxicity Signals for Multilingual and Code-Mixed Abuse Detection
 - **Authors:** Indraveni Chebolu, Rohan Singh, Arnab Mallick, Harmesh Rana
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Moderation systems increasingly rely on external toxicity tools, but those tools are unreliable under code-mixing, transliteration, slang, and language mismatch. We study the \emph{conditional reliability} of toxicity priors in Indian multilingual and code-mixed short text: English toxicity, Indic abuse, and rule-based severity cues can be useful evidence, but only in some linguistic and abuse-severity contexts. We propose ToxGate, a trust-fusion head that conditions each auxiliary signal on the encoder representation before adding it to the prediction state. Across three short-text abuse datasets, four transformer encoders, and five seeds per setting, ToxGate improves over matched plain encoders in 10 of 12 in-domain settings and 7 of 8 transfer settings. The largest and most interpretable gains occur in high-risk moderation slices, including explicit slurs, violent threats, and cross-dataset transfer. The broader lesson is that moderation systems should treat external toxicity tools and priors as conditional evidence rather than fixed features or ground truth, in focused ablations, source-specific gating gives the strongest results in transfer, severe-abuse slices, and high-risk triage.
### Title:
          An MLIR-Based Compilation Method for Large Language Models
 - **Authors:** Pengchao Hu, Zhibin Xin, Yifan Chen, Yangyang Zhou, Liang Wang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have become the dominant workload on modern AI accelerators, yet deploying them on specialized hardware still faces two core challenges: how to import a trained model into a compiler-friendly intermediate representation, and how to efficiently schedule the autoregressive inference loop under limited on-chip memory. This paper presents an MLIR (Multi-Level Intermediate Representation) based compilation method for large language models, illustrated using two dialects of operators, TopOp and TpuOp. TopOp serves as a high-level graph dialect that is independent of both the source framework and the target chip, and is responsible for expressing model semantics; TpuOp serves as the target hardware dialect, carrying chip-related decisions such as quantization, layer groups, and memory layout. A model is first represented as TopOp, then lowered layer by layer to TpuOp, and finally a deployable binary is generated. In addition, each Transformer layer is split into three stages for static compilation: prefill, prefill_kv (prefill with historical key-value cache), and decode, so as to accommodate the different computational characteristics of prompt-parallel processing and per-token generation. The method has been implemented in the TPU-MLIR compiler{this https URL} and the LLM-TPU deployment project\footnote{this https URL}, supporting a variety of generative models including the Qwen, Llama, InternVL, and MiniCPM-V series, as well as multiple quantization and deployment forms such as GPTQ, AWQ, and AutoRound.
### Title:
          Induction in Both Directions: A Mechanistic Analysis of In-Context Learning in Masked Diffusion Language Models
 - **Authors:** Andy Catruna, Emilian Radoi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While the internal mechanisms of autoregressive (AR) transformers have been studied extensively, much less is known about diffusion language models (DLMs), an emerging alternative that generates text by iterative denoising. In this work, we study how DLMs implement induction, a mechanism behind in-context learning in which the model finds a repeated context and copies the token that followed it. Our analysis compares attention-only AR models and absorbing-mask DLMs with matched architectures. We find that DLMs learn a bidirectional induction circuit, where previous-token and next-token heads write local context into the residual stream and later induction heads use it to find and copy the answer from the matching source position. The circuit is direction-symmetric, working whether the source appears in the past or in the future. When only left context is visible, matching what an AR model sees, the DLM does not outperform its AR counterpart in induction capabilities. However, we observe it has stronger induction when both sides of the masked token are visible, pointing to bidirectional context access rather than a stronger one-sided mechanism. Beyond induction, we provide causal evidence that DLMs compute the global fraction of masked tokens and use it as an implicit timestep, even though they are given no explicit timestep embedding.
### Title:
          DPNeXt: A Lightweight Multi-Scale Feature Fusion Framework for Efficient ViT-Based Multi-Task Dense Prediction
 - **Authors:** Jehun Kang, Jungha Wang, Youngjun Hwang, David Hyunchul Shim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Task Learning (MTL) in robotics perception systems supports comprehensive 3D spatial scene understanding by integrating semantic segmentation and depth estimation. While Vision Foundation Models (VFMs) are increasingly adopted as robust feature encoders, existing decoding strategies present a critical bottleneck. To address this, we propose DPNeXt, a streamlined multi-scale feature fusion decoder and efficient alternative to the standard Dense Prediction Transformer (DPT). DPNeXt uses dual depthwise separable inverted bottlenecks to improve frozen VFM utilization through fusion-centric decoding and independent task modularization. To further mitigate negative inductive transfer between tasks, we introduce the Multi-Task Boundary Guidance (MTBG) strategy. Unlike prior boundary-aware methods that add fusion modules or gating, MTBG applies symmetric boundary-focused supervision to encourage geometric consistency without extra annotation or inference cost. Experiments on Cityscapes show that DPNeXt-S outperforms prior state-of-the-art (SOTA) MTL models, while DPNeXt-B further improves the overall performance and achieves the best results among the compared methods. On NYUv2, DPNeXt-B also achieves the best semantic segmentation and depth estimation results among the compared methods while requiring substantially fewer trainable parameters than prior large-scale MTL models. Compared with the standard DPT, DPNeXt-S reduces trainable parameters by 78.6% and achieves the fastest inference speed among the compared models on resource-constrained laptop hardware. The source code, model checkpoints, and a demo video will be made available at this https URL.
### Title:
          Loop the Loopies!
 - **Authors:** Zitian Gao, Yilong Chen, Yihao Xiao, Xinyu Yang, Ran Tao, Joey Zhou, Bryan Dai
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Loopie, the most powerful looped Transformer to date. The Loopie series consists of two Mixture-of-Experts (MoE) models: a 20B-parameter model with 2B active parameters and a 6Bparameter model with 0.6B active parameters. Looped Transformers have long faced a challenge: given an N-fold increase in pre-training compute, increasing the parameter count by a factor of N usually outperforms looping a model N times. Loopie addresses this challenge. Extensive ablation studies, including comparisons with a vanilla 30B-A3B model, show that Loopie substantially outperforms vanilla Transformer baselines trained with the same compute budget. Our novel post-training pipeline equips Loopie with strong reasoning abilities. At the 2025 IMO and IPhO, Loopie achieves gold-medal performance without tools.
### Title:
          Frontier Language Models Struggle to Copy: Text Can Be Better Viewed in 2D
 - **Authors:** Haodong Wen, Yiran Zhang, Yingfa Chen, Kaifeng Lyu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While large language models (LLMs) can solve advanced reasoning problems in seconds, we show that even frontier models fail to perform a much simpler operation: exactly copying an input string that lies well within their context windows. We attribute this failure to positional encodings in Transformer architectures, whose inductive bias favors copying through a shortcut based on matching local contexts rather than carefully locating the corresponding input positions. To address this issue, we introduce 2D-RoPE, which organizes text into a 2D grid rather than a 1D sequence and assigns each token a row ID and a column ID. Under this view, copying becomes simply retrieving input tokens at a fixed column offset, which makes the task easy to learn. In synthetic copy experiments, shallow Transformers with 2D-RoPE achieve perfect copying at input lengths hundreds of times longer than those seen during training, whereas standard positional encodings fall far behind. We further show that the advantage of 2D-RoPE language models on copy tasks consistently holds in large-scale pretraining on DCLM with model sizes up to 1.4B parameters. Overall, our results suggest that viewing text in 2D can benefit language modeling, and we hope this encourages future work to further explore the potential of 2D positional encodings.
### Title:
          Controlling Implicit Shortcut Reliance in L2 Spoken English Auto-markers
 - **Authors:** Shilin Gao, Mark J. F. Gales, Kate M. Knill
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Increasingly, speech and language processing tasks take either audio or text directly rather than extracting features from these as the input to the classifier or regressor. Often these systems make use of complex, for example transformer-based, processes that have the ability to derive highly non-linear mappings between the input and the output. Unfortunately these systems can also learn ''shortcuts'' where the classifier is overly reliant on particular aspects of the input to yield the output. For the task of language proficiency assessment, this over-reliance can enable learners to increase their score by exploiting the shortcut rather than improving their ability. This paper introduces a novel training criterion that is able to reduce the classifier's reliance on shortcuts, thus for example limiting this option for malpractice in language assessment. This process is illustrated on two forms of assessment system, one based on the audio the other on the speech recognition text. The results show that, for both systems, there is higher correlations with features that could be exploited for malpractice than expected from the human reference, indicating an over-reliance on these features. By introducing the modified training criterion, this correlation can be reduced to be closer to the reference correlation.
### Title:
          How Do VLMs Fail? Vision-Operation Misalignment in Compositional VQA
 - **Authors:** Navya Gupta, Bingjie Xu, Avinash Anand, Timothy Liu, Zhengchen Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Compositional visual question answering requires Vision-Language Models (VLMs) to execute multiple reasoning operations like object selection, spatial relation resolution, and attribute verification. Despite strong aggregate performance, the mechanistic basis of VLM failures on this task remains underexplored. To address this gap, we analyze vision-operation misalignment in VLMs by examining how failures relate to specific reasoning operations and the internal computational pathways through which they arise and propagate. We introduce an Operation-centric mechanistic framework that decomposes VLM failures by both the reasoning operation where they originate and the internal computational pathway through which they propagate. Our analysis reveals four mechanistically distinct failure modes: grounding failure, reasoning failure, attribute extraction failure, and language prior dominance failure. Each characterized by a unique relationship between visual grounding strength and answer correctness. Through three complementary causal interventions applied across all transformer layers, we further demonstrate a pathway dissociation: grounding failures route exclusively through the feedforward network, reasoning failures route through late-layer attention, and attribute extraction failures localize to the answer-position feedforward computation. This dissociation demonstrates that different failure types require fundamentally different corrective strategies, providing a principled foundation for targeted improvements to VLM reliability in multimedia reasoning.
### Title:
          Attention-Guided Saliency Maps for Interpreting Visualization Literacy in VLMs
 - **Authors:** Maeve Hutchinson, Abderrahmane Wassim Mehdaoui, Pranava Madhyastha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how vision-language models (VLMs) interpret data visualizations remains an open problem, and is increasingly important as these models are used for analytical tasks where reliable reasoning is essential. We introduce a lightweight, diagnostic saliency map method tailored for text generation over images using transformer models, the current state-of-the-art models in visualization interpretation. Our approach aggregates the language model's attention over the visual tokens across all heads and layers, then maps this attention back onto the vision encoder's patch grid to localise it over the image, producing a direct correspondence between each generated answer token and the image regions it attended to. This yields fast, gradient-free saliency maps that expose how VLMs allocate focus across visual elements during answer generation, enabling inspection of whether model attention aligns with semantically relevant components. We evaluate our approach using a deletion metric which validates the causal faithfulness of our saliency maps to the model's behavior.
### Title:
          FVAttn: Adaptive Sparse Attention with Runtime Load Balancing for Video Generation
 - **Authors:** Hao Liu, Chenghuan Huang, Ye Huang, Zhiying Wen, Hao Liu, Mohan Zhang, Chen Li, Ziyang Ma, Jing Lyu, Jiangsu Du
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Diffusion Transformers process long spatio-temporal sequences, making self-attention the main bottleneck in high-resolution video generation. Training-free sparse attention reduces this cost, but adaptive Top-$p$ routing creates uneven per-head workloads under multi-GPU sequence parallelism. The resulting workload heterogeneity turns sparse attention into a rank-level straggler problem. We present \method{}, a training-free sparse-attention system that improves the distributed execution efficiency of adaptive sparse attention under multi-GPU sequence parallelism. \method{} uses Top-$p$ routing, a Top-$k$ safety floor, and video-aware block organization as the sparse-routing frontend, then repairs the materialized mask at runtime. Runtime Load Balancing migrates a small number of heavy heads via P2P communication to shorten the current critical path. Slack-Aware Sparse Augmentation fills residual non-critical-rank slack with additional high-value blocks, while overlap hides scheduling and migration overhead behind existing computation. On step-distilled Wan2.2 I2V, \method{} reduces average load imbalance from 1.34 to 1.08 and delivers a $4.41\times$ attention speedup over FlashAttention, while achieving a $2.02$--$2.11\times$ DiT inference speedup with competitive video quality.
## Keyword: autonomous driving
### Title:
          SpeechGuard: Online Defense against Backdoor Attacks on Speech Recognition Models
 - **Authors:** Jinwen Xin, Xixiang Lv
 - **Subjects:** Subjects:
Sound (cs.SD); Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backdoor attacks pose a critical threat to neural network models, allowing attackers to implant a backdoor during the training phase by manipulating a small portion of the training data. In security-sensitive applications such as voice interaction for autonomous driving, the presence of backdoor attacks introduces substantial security risks. This study focuses on implementing backdoor defense measures for speech recognition models in run-time, taking into account the characteristics of audio signals. We propose SpeechGuard, the first online backdoor defense pipeline designed to identify and purify poisoned audio samples. Specifically, we improve STRIP method to perform adaptive perturbation injection to detect and filter poisoned samples, named as S-STRIP. More importantly, we further consider the purification of poisoned samples. We utilize time-frequency (T-F) masking to suppress the expression of trigger signals and autonomously generate masks based on an autoencoder. The two-stage processing prevents the backdoor in the model from being triggered, and even input speech carrying triggers can be accurately predicted. Extensive experimental demonstrate that SpeechGuard can accurately filter out poisoned samples. Through purification, it can significantly mitigate the backdoor threat while maintaining a certain prediction accuracy.
### Title:
          In the Driver's Seat: A Multi-Company Study on the Reality of Autonomous Driving System Testing
 - **Authors:** Qunying Song, Yuan Gao, Johannes Betz, Dietmar Pfahl, Mohammad Reza Mousavi, Federica Sarro
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems (ADS) are rapidly advancing and increasingly deployed in real-world applications. This creates growing demands for effective testing to ensure system functionality and safety. However, ADS testing remains complex and lacks well-established standards for scenario selection, performance evaluation, and acceptance criteria. To better understand current ADS testing practices and challenges, we conducted an interview study with experts working on ADS development and testing in nine companies from six different countries. Through thematic analysis, we synthesized industrial testing practices, challenges, potential solutions, future trends, and proposed an evidence-centered closed-loop testing framework for ADS testing. Our findings show that current practices primarily focus on scenario-based and X-in-the-loop testing approaches, supported by diverse tools, metrics, benchmarks, and testing strategies. The participants highlighted major challenges related to scenario realism, scenario coverage, simulation fidelity, and acceptance criteria, while also discussing potential solutions such as the use of AI, world models, and end-to-end approaches. Furthermore, participants envisioned future ADS testing to become more automated, data-driven, and transparent across the industry. Overall, this study provides a comprehensive industry-grounded overview of ADS testing, proposes an evidence-centered closed-loop testing framework to provide actionable guidance for ADS testing, and outlines important directions for future research and practice.
### Title:
          Red Light, Grey Zone: A Multi-Perspective Interactive Narrative for Autonomous Driving Ethics
 - **Authors:** Mengyi Wei, Nianhua Liu, Chenyu Zuo, Liqiu Meng
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving ethics is not only an expert concern, but also a public issue involving risk, responsibility, and governance. However, non-experts often struggle to interpret these issues in concrete incidents, especially when responsibility is distributed across multiple stakeholders. This paper investigates interactive narrative as a public-facing method for eliciting situated ethical reflection on autonomous driving. We present Red Light, Grey Zone, a web-based, multi-perspective interactive narrative prototype inspired by a real-world autonomous-driving incident. The prototype invites participants to compare stakeholder perspectives, examine scene materials, and make responsibility judgments in the face of ethical ambiguity. We report an exploratory user study (N=12) examining how differently non-experts responded to the prototype. Our analysis focuses on three dimensions of reflection: ethical cognition, responsibility-focused critical thinking, and multi-perspective reasoning. Exploratory pre-post results showed the strongest self-reported shift in responsibility-focused critical thinking among participants who completed the intended stakeholder-comparison process, while ethical cognition and multi-perspective reasoning showed positive directional trends. Qualitative findings further show how participants reflected on safety and market trade-offs, responsibility ambiguity, transparency and privacy, and governance gaps. Participants also used stakeholder comparison to corroborate evidence and, in many cases, broaden responsibility judgments from single-actor blame toward more distributed interpretations of accountability. Overall, the study suggests that multi-perspective interactive narratives may support non-expert reflection on accountability, evidence, and governance in AI-enabled systems.
### Title:
          Vision-Language Assistant for Emotional Reactions to Risky Driving
 - **Authors:** Harine Choi, Eun Hak Lee, Zhengzhong Tu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study introduces a vision-language pipeline that detects risky driving behaviors and generates emotionally expressive responses to support driver awareness and comfort. Although vision-language models have advanced perception and reasoning in autonomous driving, existing systems rarely consider the emotional dimension or real-world user experience. Keep Yelling Assistant (KYA) detects high-risk driving maneuvers in real time, such as sudden cut-ins. It then produces emotional responses through a large language model tailored to driver preferences. The framework comprises two core modules. The vision module uses YOLOv8 variants to detect nearby vehicles and identify risky behaviors such as sudden cut-ins. Key driving metrics, including relative distance, speed, and projected reach time, are extracted and normalized to produce a structured behavior log. The language module processes this log with user-defined emotional tone settings, such as neutral, humorous, and analytical, and generates verbal reactions using state-of-the-art large language models, including ChatGPT-4o, Claude 3, Gemini 2.5, and Copilot. We evaluated the proposed system using dashcam videos containing risky driving behaviors and a user study involving 108 participants. Participants selected preferred response styles, and the large language models were evaluated based on emotional alignment. All models received favorable ratings, although preferences varied across personas. Notably, the combination of YOLOv8s and ChatGPT-4o achieved the highest score of 4.29 out of 5.00. By integrating real-world perception with emotionally adaptive dialogue, KYA introduces a new paradigm for emotionally intelligent in-vehicle artificial intelligence. It offers promising directions for improving safety, trust, and emotional well-being in both conventional and autonomous vehicles.
