# Showing new listings for Friday, 10 July 2026
## Keyword: SLAM
### Title:
          STEMbot: A Compliant Robot for Under-Canopy Plant Navigation
 - **Authors:** Zachary Charlick, Nilay Roy Choudhury, Haoyu Ma, Xiaonan Huang, Dmitry Berenson
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scalability of organic agriculture is partially limited by the labor costs associated with monitoring for pests. While drones and rovers are well-suited for agricultural monitoring from above or next to plants, many pests live on the underside of leaves or on plant stems, making them detectable only after they have caused significant damage. To enable early pest detection we present STEMbot, a miniature climbing robot system designed for autonomous navigation under plant canopies. Unlike existing climbing platforms that lack on-board perception or are restricted to unbranched vertical trunks, STEMbot integrates a fully geometric PIN-SLAM pipeline with a semantic OcTree to achieve robust localization and mapping while climbing the plant. To plan STEMbot's motion we propose a manifold-constrained A* planner along with ray-tracing goal specification to enable branch-aware traversal and the inspection of occluded targets. We validate our system through hardware experiments, demonstrating reliable traversal of stems ranging from 7-33mm and autonomous navigation across four distinct plant specimens. Quantitative evaluations show that our system achieves high-fidelity geometric reconstructions with an average Chamfer distance of less than 1cm relative to an offline photogrammetry baseline, confirming that STEMbot maintains the globally consistent odometry needed for autonomous navigation.
### Title:
          RadLoc: Radar-based 3-DoF Global Localization via Fast, Robust, and Lightweight Spatial Descriptor Across Diverse Environmental Scenarios
 - **Authors:** Hogyun Kim, Jiwon Choi, Jungwoo Lee, Younggun Cho
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While global localization using spinning radar has gained attention for its robustness to adverse weather and challenging environments, many studies have focused on individual components such as place recognition or pose estimation. In this paper, we take a holistic view of radar sensor-based global localization and present RadLoc, a fast, robust, and lightweight end-to-end pipeline from place recognition to 3-DoF pose estimation. RadLoc accelerates pre-processing using 1D CA-CFAR filtering and leverages the near-range dominance in spinning radar images to design a compact descriptor and an efficient hierarchical coarse-to-fine retrieval strategy. Moreover, coupled with phase correlation-based 3-DoF pose estimation, it forms a versatile global localization module applicable to SLAM and multi-session SLAM systems. Extensive experiments on 15 sequences across 5 datasets demonstrate that RadLoc achieves robust performance while maintaining the smallest descriptor size and fastest retrieval time among state-of-the-art approaches. The supplementary materials are available at this https URL.
### Title:
          Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery
 - **Authors:** Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaussian splatting is the current state-of-the-art for dense, deformable 3D anatomy reconstruction in robot-assisted minimally invasive surgery (RAMIS); however, most pipelines are offline and depend on accurate camera trajectory priors (often from robotic kinematics), limiting applicability when priors are missing or noisy. To address these limitations, we propose Track2Map, an online 3D Gaussian Splatting pipeline that jointly optimizes camera trajectory and 3D deformable scene representation directly from surgical video. Track2Map is therefore capable of robust 3D reconstructions when camera trajectory priors are either absent or noisy, and due to its online nature it effectively works as a Simultaneous Localisation and Mapping (SLAM) method. To stabilize optimization in the presence of tissue motion and ambiguous visual cues, we introduce a track-anchored deformation initialization using dense 2D point tracks. Track statistics are further utilized to disentangle camera motion from scene deformation by detecting static camera periods and reducing drift during incremental mapping. Experiments on StereoMIS show improved reconstruction quality and camera trajectory against competing SLAM methods, as well as compared to non-SLAM methods that utilize camera trajectory priors. The code is available at this https URL.
## Keyword: odometry
### Title:
          SASGeo: Stability-Aware Semantic Map Localization for GNSS-Denied UAVs -- A Framework and Synthetic Proof of Concept
 - **Authors:** Natalia Trukhina, Vadim Vashkelis
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GNSS-denied unmanned aerial vehicles require occasional absolute position fixes to bound the drift of visual-inertial odometry. Cross-view image retrieval can provide such fixes, but raw appearance is sensitive to season, illumination, viewpoint, map age, and sensor modality. We propose \sas, a semantic map-localization framework that represents the environment through persistent structures such as roads, buildings, waterways, railways, intersections, and field boundaries. The method combines semantic raster alignment, relational graph evidence, feature stability and geographic distinctiveness, explicit positive/contradictory/unknown observations, and integrity-aware rejection of ambiguous fixes. Unlike a broad architecture-only proposal, this paper specifies concrete weighting and decision models and reports a reproducible synthetic proof of concept. In 220 randomized retrieval trials with rotation, scale changes, partial crops, occlusion, simulated map changes, and hard semantic decoys, a global semantic descriptor achieved 58.6\% Recall@1, while spatial semantic matching variants achieved 94.5-95.5%. Wilson 95\% intervals separate the global descriptor from the spatial variants but overlap among the spatial variants, so the experiment supports semantic geometry rather than a definitive benefit from each proposed module. The preliminary experiment does not validate real-flight navigation; rather, it demonstrates that structured semantic geometry can discriminate locations under controlled cross-view perturbations and identifies the harder aliasing, map-aging, and rejection tests required next.
### Title:
          STEMbot: A Compliant Robot for Under-Canopy Plant Navigation
 - **Authors:** Zachary Charlick, Nilay Roy Choudhury, Haoyu Ma, Xiaonan Huang, Dmitry Berenson
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scalability of organic agriculture is partially limited by the labor costs associated with monitoring for pests. While drones and rovers are well-suited for agricultural monitoring from above or next to plants, many pests live on the underside of leaves or on plant stems, making them detectable only after they have caused significant damage. To enable early pest detection we present STEMbot, a miniature climbing robot system designed for autonomous navigation under plant canopies. Unlike existing climbing platforms that lack on-board perception or are restricted to unbranched vertical trunks, STEMbot integrates a fully geometric PIN-SLAM pipeline with a semantic OcTree to achieve robust localization and mapping while climbing the plant. To plan STEMbot's motion we propose a manifold-constrained A* planner along with ray-tracing goal specification to enable branch-aware traversal and the inspection of occluded targets. We validate our system through hardware experiments, demonstrating reliable traversal of stems ranging from 7-33mm and autonomous navigation across four distinct plant specimens. Quantitative evaluations show that our system achieves high-fidelity geometric reconstructions with an average Chamfer distance of less than 1cm relative to an offline photogrammetry baseline, confirming that STEMbot maintains the globally consistent odometry needed for autonomous navigation.
### Title:
          D-CLIPSE: Distributed Consensus-based Localization with Passive Listening on Shared State Exchange
 - **Authors:** Kyle Biron-Gricken, James Richard Forbes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-robot localization that is accurate and consistent is imperative for downstream tasks such as planning and control. Centralized filtering approaches optimally fuse all available sensor measurements of the team. However, a centralized solution is rarely implementable due to hardware, communication, and computational constraints. Distributed approaches deploy a filter on each robot to estimate their own state and neighbours' states using inter-robot communication. This paper proposes a consistent, communication-efficient, and consensus-based distributed filtering framework that shares both preintegrated odometry and relevant shared states among communicating robots. The proposed method is validated in simulated and experimental scenarios, showing near centralized performance in accuracy, and especially in consistency, compared to the current state-of-the-art decentralized approach.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Time-to-Collision Based Dynamic Obstacle Avoidance Using Pretrained Vision Models for Robots in Unstructured Environments
 - **Authors:** Erik Jagnandan, Mulugeta Haile, Gregory Barber, Pratik Chaudhari
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic obstacle avoidance in unstructured outdoor environments remains a critical challenge for autonomous mobile robots, particularly when large-scale robot-specific training data and simulation-based policies are impractical. We present a data-efficient, interpretable method for vision-based dynamic obstacle avoidance that operates entirely on real-world data, avoiding the sim-to-real transfer problem inherent in simulation-trained policies. Our approach leverages UniDepth, a large pretrained monocular depth estimation model, to produce dense depth maps from RGB video without requiring stereo cameras or LiDAR at inference time. Dynamic obstacle avoidance is achieved by extending the SuperPoint and SuperGlue feature correspondence pipeline to track keypoints across long frame sequences, projecting their 2D pixel-space positions into 3D using camera intrinsics and predicted depth, running bundle adjustment initialized from these 3D keypoints, and computing per-keypoint time-to-collision (TTC). A 2D motion primitive in the ground plane is then selected to move the robot away from the closest point of approach of the minimum-TTC keypoint. Evaluated on real-world data from the M3ED dataset, our pipeline achieves a precision of 0.49 and a recall of 0.38 in identifying frames with a ground truth TTC below 1 second, and correctly generates the evasive motion direction in 84\% of true positive detections. Crucially, it detects at least one frame with TTC less than 1 second for 20 out of 22 unique physical obstacles present in our test sequences. Unlike end-to-end learned methods that demand thousands of hours of robot-specific training data, our approach eliminates model training entirely, requiring only 74 seconds of data for hyperparameter tuning. This demonstrates exceptional data efficiency while preserving interpretable and generalizable behavior across diverse obstacle types.
### Title:
          On Exploring Input Resolution Scaling For Anytime LiDAR Object Detection
 - **Authors:** Ahmet Soyyigit, Shuochao Yao, Heechul Yun
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Making tradeoffs between execution latency and result utility (i.e., anytime computing) for adapting to dynamic operational requirements has been shown to enhance the performance of cyber-physical systems. In this work, we focus on enabling anytime computing for deep neural networks (DNNs) that process LiDAR point clouds for 3D object detection. We propose a novel method that enables multi-resolution inference for models that process point clouds as pillars or voxels, allowing the input to be dynamically scaled and processed at the resolution needed to meet timing requirements. Importantly, our memory-efficient approach requires the deployment of only a single DNN model, avoiding the need to deploy multiple models, each trained for a different input resolution. We also introduce a deadline-aware scheduler that selects the highest possible resolution for any given input by accurately predicting the execution time for all possible resolutions at runtime, which is challenging due to the irregularity of LiDAR point clouds. Experimental results on the nuScenes autonomous driving dataset demonstrate that our method significantly outperforms existing anytime computing approaches for LiDAR object detection. Finally, we deploy our approach in a simulated autonomous driving system, where it consistently enables collision-free navigation while avoiding unnecessary stalls caused by environmental complexity.
### Title:
          LTM: Large-scale Terrain Model for Wildfire-prone Landscapes
 - **Authors:** Xiao Fu, Yue Hu, Meida Chen, Peter Anthony Beerel, Barath Raghavan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D terrain maps are essential for emergency response when assessing wildfire hazards. However, wildfire-prone regions often span vast areas where conventional reconstruction methods underperform. Airborne LiDAR systems provide high-resolution terrain data, but they are expensive and infrequently updated. Image-based methods offer a lower-cost alternative, but struggle due to sparse visual features and limited image overlap. We propose a multi-modal reconstruction framework leveraging outdated Digital Elevation Models (DEMs) as geometric priors for image-based 3D reconstruction. Our key innovation is physics-based pixel-pixel alignment between images and DEM data, dramatically reducing computational complexity by eliminating expensive feature matching procedures. To validate our approach, we developed a large-terrain simulator based on a real wildfire-prone area, generating realistic images enabling a comprehensive evaluation. Given posed images and legacy DEMs, our method produces high-fidelity depth maps while maintaining real-time performance. We find significant improvements in reconstruction accuracy and computational efficiency over existing techniques, offering a scalable solution for wildfire response.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          AI-Driven Thermal Mapping and Management in 3D Integrated Photonic Circuits
 - **Authors:** Liton Kumar Biswas, Katayoon Yahyaei, Shajib Ghosh, M Shafkat M Khan, Himanandhan Reddy Kottur, Rayhane Ghane-Motlagh, Mahdi Nikdast, Navid Asadizanjani
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Photonic Integrated Circuits (PICs) are advancing high-performance computing, data centers, and sensing, yet three-dimensional (3D) PICs introduce critical thermal management challenges due to high-density bonding and heterogeneous materials. Traditional methods like thermal microscopes and in-package sensors yield sparse data, limiting full thermal profile visibility. This paper presents a dual-method solution combining an AI-driven thermal modeling framework with a design-based heuristic approach. The AI method integrates sparse sensor data with design layer and density information to predict multilayer temperature variations, while the heuristic approach uses localized material properties, design layout, component geometries, and sensor coordinates to refine thermal estimations in specific regions. A 2D thermal map of a 3D PIC is generated by interpolating sensor data and adjusting for local thermal resistivity using comparative analysis between design regions. The heuristic method complements the AI model, improving estimation accuracy without extensive training data. Together, these methods offer a scalable, accurate solution for real-time thermal mapping and design-time simulation, enabling reliable thermal management in next-generation 3D photonic systems.
### Title:
          Towards the Explainability of Temporal Graph Networks via Memory Backtracking and Topological Attribution
 - **Authors:** Yazheng Liu, Xi Zhang, Sihong Xie, Hui Xiong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal graphs are ubiquitous in real-world applications and Temporal Graph Networks (TGNs) have achieved superior predictive accuracy. Understanding which historical events drive model predictions can enhance trustworthiness of TGNs. Existing explanation methods overlook the memory module, the core component that records and updates node histories, leaving the influence of past events unexplored. To address this, we attribute TGNs predictions through the topology attribution tree and memory backtracking tree. The topology attribution tree captures the influence of neighbors and their memory vectors, then the memory backtracking tree quantifies how historical events shape node memory vectors. We apply the LRP in TGNs, ensuring that the total contribution of events equals the logits of model. Finally, top-k selection may be unfaithful due to the nonlinear mapping from logits to probabilities, we design optimization objectives to identify the important events. Experiments on nine temporal graph datasets, spanning node property prediction, link prediction tasks and graph classification tasks, show that our method provides faithful explanations and outperforms state-of-the-art baselines. The code is available at this https URL
### Title:
          STEMbot: A Compliant Robot for Under-Canopy Plant Navigation
 - **Authors:** Zachary Charlick, Nilay Roy Choudhury, Haoyu Ma, Xiaonan Huang, Dmitry Berenson
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scalability of organic agriculture is partially limited by the labor costs associated with monitoring for pests. While drones and rovers are well-suited for agricultural monitoring from above or next to plants, many pests live on the underside of leaves or on plant stems, making them detectable only after they have caused significant damage. To enable early pest detection we present STEMbot, a miniature climbing robot system designed for autonomous navigation under plant canopies. Unlike existing climbing platforms that lack on-board perception or are restricted to unbranched vertical trunks, STEMbot integrates a fully geometric PIN-SLAM pipeline with a semantic OcTree to achieve robust localization and mapping while climbing the plant. To plan STEMbot's motion we propose a manifold-constrained A* planner along with ray-tracing goal specification to enable branch-aware traversal and the inspection of occluded targets. We validate our system through hardware experiments, demonstrating reliable traversal of stems ranging from 7-33mm and autonomous navigation across four distinct plant specimens. Quantitative evaluations show that our system achieves high-fidelity geometric reconstructions with an average Chamfer distance of less than 1cm relative to an offline photogrammetry baseline, confirming that STEMbot maintains the globally consistent odometry needed for autonomous navigation.
### Title:
          RadioDiff-v2: Generative Angular Radio Maps for Multi-Beam Selection and Localization
 - **Authors:** Xiucheng Wang, Junxi Huang, Nan Cheng
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Angular radio maps describe the received-power distribution over the angle of arrival and underpin beam selection and receiver localization in sixth-generation (6G) networks. Predicting the angular power spectrum (APS) from geometry is difficult, because the mapping is ill-posed in non-line-of-sight (NLOS) conditions and must generalize to unseen environments. Distortion-minimizing regressors return the conditional mean, which over-smooths the spectrum and erases the multipath structure that downstream tasks need. We cast the task as a perception-distortion problem and propose RadioDiff-v2, a dual-branch one-dimensional diffusion transformer trained with flow matching. It couples periodic angular encoding, adaptive layer-normalization conditioning, a Fourier angular mixer, and joint velocity and clean-signal heads. A per-metric estimator portfolio reads every deployment quantity from this single model, so that samples carry the distribution, the clean-signal head supplies a regression-grade point estimate, Bayes-optimal rules select beams, and the conditional likelihood localizes the receiver. We prove that a concentrated conditional yields a straight probability-flow trajectory that one step integrates exactly, identifying deterministic transport as the correct inductive bias. On a zero-shot test of 99 environments and one million links, RadioDiff-v2 leads every baseline on every metric, with a 0.39 dB Wasserstein-1 distance, per-bin error below the regression baseline, a 2.43 dB eight-beam NLOS sweep loss, and a 20.6-pixel localization error with four base stations. Code is available at this https URL.
### Title:
          Leveraging Color Naming for Image Enhancement
 - **Authors:** David Serrano-Lozano, Luis Herranz, Michael S. Brown, Javier Vazquez-Corral
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enhancing images to make them visually appealing is a persistent challenge in computer vision. Many deep-learning methods train models on paired datasets to replicate expert editing styles. However, these approaches struggle with two key issues: (1) interpretability and (2) a parametrization suitable for user adjustments. To address these challenges, we present NamedCurves+, an approach inspired by the concept of Color Naming, a universal set of familiar colors widely used in software tools for intuitive editing. Our method integrates color names into a learning-based framework, enabling global adjustments for each named color through tone curves. To address local image variations, we incorporate a transformer block that captures spatial dependencies, enabling context-aware edits across the image. NamedCurves+ enhances the retouching process's interpretability and supports user interaction, allowing flexible modifications of individual tone curves to refine the retouched image according to personal preferences. Extensive experiments on tasks such as image retouching, tone mapping, and exposure correction demonstrate that NamedCurves+ outperforms state-of-the-art methods. Notably, our approach is both explainable, as the tone curves explicitly represent how each color name contributes to the enhancement, and interactive, allowing users to customize the retouching process and achieve results tailored to their liking.
### Title:
          Unpaired Joint Distribution Modeling via Multi-Scale Image Representations
 - **Authors:** Yihang Zou, Hui Zhang, Zuowei Shen, Chenglong Bao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies the problem of learning a joint distribution from marginal observations, which is inherently ill-posed due to the ambiguity of feasible couplings. We propose LUD-MSR, a latent-variable probabilistic framework that models the joint distribution via auxiliary representations and optimizes evidence lower bounds using only marginal data. Under mild assumptions, we establish an upper bound on the distribution approximation error. This analysis reveals a trade-off in representation learning between domain consistency and information preservation. To address this trade-off, we introduce a Multi-Scale image Representation (MSR) mapping that exploits structural similarity at coarse scales while suppressing domain-specific variations. We show that MSR achieves a more favorable balance of this trade-off compared to existing approaches. Experiments on real-world denoising benchmarks, including cryo-electron microscopy (cryo-EM), demonstrate the effectiveness of the proposed framework.
### Title:
          Multimodal 3D LUT Generation via StatLUT with Statistical Features for Photorealistic Style Transfer
 - **Authors:** Yifan Wang, Zhixiang Hao, Yu Wang, Congchao Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Photorealistic Style Transfer (PST) aims to transfer the color and tonal style of a reference to a content image while strictly preserving its structural integrity. However, existing deep learning-based methods inherently suffer from semantic entanglement caused by pre-trained image encoders, leading to unnatural spatial distortions. Moreover, current pixel-level mapping paradigms often ignore color gamut topology, resulting in color banding, while also lacking the multimodal capability for intuitive text-driven control. To address these bottlenecks, we propose StatLUT, an innovative multimodal framework for 3D LUT generation. First, we bypass traditional encoders and introduce a Lab-Extractor to derive spatially-agnostic statistical features, fundamentally decoupling color distributions from structural semantics to ensure artifact-free rendering. Second, we formulate LUT generation as a Transformer-based Seq2Seq translation task, utilizing a Multi-dimensional Residual Mapper (MR-Mapper) to predict topologically smooth 3D LUTs. Finally, to break the single-modal barrier, we propose the H-Diffuser, a lightweight Diffusion Transformer that directly synthesizes statistical features from natural language prompts, enabling flexible text-driven color grading. Extensive experiments on standard benchmarks demonstrate that StatLUT significantly outperforms state-of-the-art methods in both visual quality and quantitative metrics, pioneering a highly robust and flexible paradigm for multimodal photorealistic style transfer.
### Title:
          Enhancing the KidSat Model: Integrating Geographical Encoding and Data Quality Assessment for Childhood Poverty Prediction
 - **Authors:** Hou Hin Ip, Ka Nam Lam, Joshua Man Yu Ng, Makkunda Sharma, Seth Flaxman, Codie Gerlach-Wood, H Juliette T Unwin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Applications (stat.AP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate poverty mapping using satellite imagery is often hindered by (i) noisy and sparse survey-derived supervision, (ii) image quality issues such as cloud cover and image corruption, and (iii) lack of explicit spatial structure in image-only models. Building on the KidSat framework, we develop an enhanced pipeline that improves predictive accuracy via refined data preprocessing, systematic image quality assessment, and mathematically defined geographic encoding. First, we refine the fine-tuning target matrix by resolving high-cardinality sparsity and reducing one-hot dimensionality from 103 to 51 via DHS re-aggregation. Second, we introduce a simple two-stage quality-screening procedure to filter heavily clouded or corrupted observations. Third, we fuse DINOv2 visual embeddings with Spherical Harmonics (SH) location features. Across extensive experiments, these changes reduce MAE from 0.2167 to 0.1759, corresponding to an 18.83% relative reduction on the cluster-level severe-deprivation proportion scale. When extended from 16 to 33 African countries, the best-performing configuration achieves an overall MAE of 0.1658. We find that SH features consistently improve performance over the image-only backbone, whereas higher-capacity coordinate Multi Layer Perception augmentation (SH+SIREN) can underperform without carefully designed objectives. Finally, gradient-boosted tree heads (XGBoost/LightGBM) most effectively exploit nonlinear interactions in the fused visual-geographic representation. These findings provide a scalable and principled recipe for improving satellite-based socioeconomic predictions using only publicly accessible data.
### Title:
          Diagnosing and Repairing Persona Collapse in LLM Advice
 - **Authors:** Harsh Kumar, Karina Vold, Louis Tay, Ashton Anderson
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLMs are increasingly used for personal advice on relationships, work, moral dilemmas, and crises. Post-training selects a stable, prosocial Assistant persona, but good advice requires more than a good default character: a skilled advisor comforts someone in crisis, challenges someone in denial, and stays procedural with a logistical question. We formalize advice-giving as situation-conditioned persona selection in a space defined by hedonic tone and agency support, and call failures of this mapping "persona collapse" (the compression of diverse situations into a single default persona). Across 1,281 advice posts spanning 14 contexts, top-rated human responses shift systematically across five personas, while three frontier models collapse over 90\% of responses into a single supportive persona regardless of context. Prompting the model to first pick a fitting persona only deepens the collapse. We then ask whether the collapse can be repaired. Our method, Inverse-Process Distillation, reconstructs the situational reading that could have produced each human response and trains on the result, aiming to distill the situation-to-persona policy rather than the answers. It cuts divergence from the human persona distribution by approximately 80\%. Yet in a blinded study, 199 experienced advice-givers rating responses across four situations in sequence prefer the collapsed default over every repaired model, most strongly when the situation calls for challenge, though this preference shifts with repeated exposures.
### Title:
          AnyDexRT: Calibration-Free Dexterous Hand Retargeting with Few-Shot Human Guidance
 - **Authors:** Chenxi Wang, Ying Feng, Hongjie Fang, Shangning Xia, Lixin Yang, Chuan Wen, Cewu Lu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teleoperation is a key interface for controlling dexterous robotic hands and collecting demonstrations for imitation learning. Its effectiveness largely depends on kinematic retargeting, which maps operator hand motions to feasible and intuitive robot hand motions. Existing methods often require hand-crafted objectives, precise calibration, or global shape matching between human and robot hand spaces, making them sensitive to hand-specific tuning and less reliable across different dexterous hands. We propose AnyDexRT, a calibration-free retargeting method for intuitive dexterous teleoperation across human-like dexterous hands. AnyDexRT combines self-supervised fingertip correspondence learning with few-shot human guidance to anchor the mapping in task-relevant regions, and further refines pinch-related poses using a contact classifier. Experiments on diverse dexterous hands and real-world teleoperation tasks show that AnyDexRT improves retargeting quality, reduces manual tuning, and provides more intuitive and efficient control than prior retargeting methods. Project website: this https URL
### Title:
          FSD-VLN: Fast-Slow Dual-System Modeling for Aerial Long-Horizon Vision-Language Navigation
 - **Authors:** Xueke Zhu, Qingyan Meng, Liutao Yu, Wei Zhang, Zhengyu Ma, Huihui Zhou, Yonghong Tian
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Navigation (VLN) enables UAV autonomous navigation in unknown environments by mapping language instructions to real-time visual inputs. Compared with GPS-dependent or pre-programmed navigation, VLN supports intuitive human-machine interaction and stronger environmental adaptability, requiring tight integration of high-level semantic reasoning and low-latency flight this http URL methods suffer from structural misalignment between global multimodal understanding and sequential action generation, causing jittery trajectories and severe decision latency for long-horizon aerial navigation. To solve this issue, we propose FSD-VLN, a fast-slow dual-system architecture disentangling semantic reasoning and low-latency flight command this http URL framework has two asynchronous branches: a slow stream extracting stable semantic priors from pre-trained vision-language models, and a Diffusion Transformer (DiT) fast stream modeling cross-temporal action distributions to produce consistent flight outputs. We further introduce a time-aware adaptive optimizer to stabilize long-sequence training and reduce gradient this http URL-scale low-altitude simulation experiments show FSD-VLN achieves up to 2X higher navigation success rates on unseen scenes than SOTA methods, while cutting single-action inference delay and total task runtime by over 50%. Our work validates the benefit of decoupled semantic-control modeling and provides a practical paradigm for long-horizon aerial VLN.
### Title:
          Track2Map: Online Deformable SLAM with Motion-Aware Pose Optimization in Robotic Surgery
 - **Authors:** Tianyi Song, Sierra Bonilla, Xinwei Ju, Evangelos Mazomenos, Danail Stoyanov, Adam Schmidt, Omid Mohareri, Sophia Bano, Francisco Vasconcelos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gaussian splatting is the current state-of-the-art for dense, deformable 3D anatomy reconstruction in robot-assisted minimally invasive surgery (RAMIS); however, most pipelines are offline and depend on accurate camera trajectory priors (often from robotic kinematics), limiting applicability when priors are missing or noisy. To address these limitations, we propose Track2Map, an online 3D Gaussian Splatting pipeline that jointly optimizes camera trajectory and 3D deformable scene representation directly from surgical video. Track2Map is therefore capable of robust 3D reconstructions when camera trajectory priors are either absent or noisy, and due to its online nature it effectively works as a Simultaneous Localisation and Mapping (SLAM) method. To stabilize optimization in the presence of tissue motion and ambiguous visual cues, we introduce a track-anchored deformation initialization using dense 2D point tracks. Track statistics are further utilized to disentangle camera motion from scene deformation by detecting static camera periods and reducing drift during incremental mapping. Experiments on StereoMIS show improved reconstruction quality and camera trajectory against competing SLAM methods, as well as compared to non-SLAM methods that utilize camera trajectory priors. The code is available at this https URL.
### Title:
          Contravariance Theory: Strong Alignment for Minimal Solutions to Hard Tasks
 - **Authors:** Dan Yamins, Aran Nayebi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A series of results from the NeuroAI over the past fifteen years have raised core questions both about how to compare Deep Neural Network (DNN) models to the brain, and about how much convergent evolution to expect between artificial networks and real brain networks. Here, we show that for any two minimal DNN solutions to a sufficiently hard task: (i) "weak" alignment of network representations based on affine mappings guarantees "strong" alignment of privileged axes, and (ii) alignment "zippers" up the network hierarchy, causing the emergence of privileged axes from end-to-end task optimization. These results formalize the notion of contravariance from Cao and Yamins [2024], and illustrate important consequences for the theory of NeuroAI: with sufficiently strong tasks, choice of metric for inter-network comparison is not all that sensitive, and that convergent evolution is probably inevitable.
### Title:
          UltraX: Refining Pre-Training Data at Scale with Adaptive Programmatic Editing
 - **Authors:** Xinlong Zhao, Dongsheng Liu, Hengyu Zhao, Zixuan Fu, Zheng Wang, Jie Cai, Jie Zhou, Qiang Ma, Xuanhe Zhou, Xu Han, Yudong Wang, Zhiyuan Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As available training data approaches its physical limit, gains from Scaling Laws have begun to diminish. Consequently, improving Large Language Models (LLMs) now depends less on data expansion and more on higher-quality data utilization. However, in the context of large-scale corpora, existing refinement methodologies face significant limitations in quality, efficiency, and reliability: Rule-based approaches are constrained by fixed heuristics and struggle with instance-level variations; LLM-based approaches improve quality but fail to meet the efficiency and reliability requirements of large-scale data processing. To address these challenges, we propose UltraX, a function-calling refinement framework for large-scale pre-training data that completes the editing function space by introducing insertion in addition to deletion and modification, enabling fine-grained instance-level editing. Specifically, UltraX builds a reliable program-supervision generation pipeline. In this pipeline, dataset-adaptive prompt optimization first guides an expert LLM to produce high-quality end-to-end refined texts, and Line Alignment Mapping and Dynamic Context Replacement then convert original-refined text pairs into structured program supervision. Meanwhile, UltraX improves supervision quality and stabilizes the training distribution with low-confidence example filtering and ratio-controlled sampling by operation combination. During inference and execution, it normalizes and validates model outputs through sliding-window prediction, global operation aggregation, and systematic post-processing, improving the stability and reliability of large-scale execution. Experiments show that UltraX achieves the highest average performance across all corpora and also matches or surpasses baselines with fewer training tokens, demonstrating stronger data efficiency and refinement reliability.
### Title:
          Deep Learning for Joint Narrowband Interference Cancellation and Soft Demodulation in OFDM Systems
 - **Authors:** Emmanouil Kavvousanos, Francky Catthoor, Vassilis Paliouras
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Narrowband interference (NBI) severely degrades orthogonal frequency-division multiplexing (OFDM) systems by corrupting subcarriers and rendering classical soft demodulation ineffective. Conventional compressed-sensing (CS) mitigation exhibits high sequential latency and leaves structured, non-Gaussian residuals that cause log-likelihood ratio (LLR) unreliability, decoder saturation, and severe error floors when employing classical Gaussian demappers. We resolve this pipeline mismatch using a unified deep learning framework for joint NBI cancellation and robust soft demodulation. First, NBI-CNet employs a physics-informed convolutional architecture to estimate NBI parameters and remove multi-tone interference in a single forward pass. Without requiring prior knowledge of the active interferer count, NBI-CNet reduces computational complexity by up to 60% ($N{=}2048, Q{=}64$) compared to the state-of-the-art EOMP-IDS algorithm. Second, LLR-CNet acts as a structural whitener by mapping non-Gaussian post-mitigation residuals onto well-calibrated soft metrics. Simulations demonstrate that this joint framework eliminates the error floors inherent to traditional baselines across dense grids. Under severe interference ($\text{SIR}{=}{-}10$ dB), the pipeline operates within a $0.2$ to $0.5$ dB SNR margin of the optimal iterative baseline at a target block error rate (BLER) of $10^{-4}$. Under mild interference ($\text{SIR}{=}10$ dB) with heavy spectral overlap ($Q{=}12$), where classical greedy algorithms erroneously subtract valid data components and corrupt the payload, NBI-CNet avoids signal-peak confusion to deliver a coding gain exceeding $3$ dB. Finally, the architecture circumvents the $2{\times}10^{-4}$ error floor triggered by interferer-estimation errors, while its scale-invariant design enables robust generalization across arbitrary FFT sizes without retraining.
## Keyword: localization
### Title:
          SASGeo: Stability-Aware Semantic Map Localization for GNSS-Denied UAVs -- A Framework and Synthetic Proof of Concept
 - **Authors:** Natalia Trukhina, Vadim Vashkelis
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GNSS-denied unmanned aerial vehicles require occasional absolute position fixes to bound the drift of visual-inertial odometry. Cross-view image retrieval can provide such fixes, but raw appearance is sensitive to season, illumination, viewpoint, map age, and sensor modality. We propose \sas, a semantic map-localization framework that represents the environment through persistent structures such as roads, buildings, waterways, railways, intersections, and field boundaries. The method combines semantic raster alignment, relational graph evidence, feature stability and geographic distinctiveness, explicit positive/contradictory/unknown observations, and integrity-aware rejection of ambiguous fixes. Unlike a broad architecture-only proposal, this paper specifies concrete weighting and decision models and reports a reproducible synthetic proof of concept. In 220 randomized retrieval trials with rotation, scale changes, partial crops, occlusion, simulated map changes, and hard semantic decoys, a global semantic descriptor achieved 58.6\% Recall@1, while spatial semantic matching variants achieved 94.5-95.5%. Wilson 95\% intervals separate the global descriptor from the spatial variants but overlap among the spatial variants, so the experiment supports semantic geometry rather than a definitive benefit from each proposed module. The preliminary experiment does not validate real-flight navigation; rather, it demonstrates that structured semantic geometry can discriminate locations under controlled cross-view perturbations and identifies the harder aliasing, map-aging, and rejection tests required next.
### Title:
          STEMbot: A Compliant Robot for Under-Canopy Plant Navigation
 - **Authors:** Zachary Charlick, Nilay Roy Choudhury, Haoyu Ma, Xiaonan Huang, Dmitry Berenson
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The scalability of organic agriculture is partially limited by the labor costs associated with monitoring for pests. While drones and rovers are well-suited for agricultural monitoring from above or next to plants, many pests live on the underside of leaves or on plant stems, making them detectable only after they have caused significant damage. To enable early pest detection we present STEMbot, a miniature climbing robot system designed for autonomous navigation under plant canopies. Unlike existing climbing platforms that lack on-board perception or are restricted to unbranched vertical trunks, STEMbot integrates a fully geometric PIN-SLAM pipeline with a semantic OcTree to achieve robust localization and mapping while climbing the plant. To plan STEMbot's motion we propose a manifold-constrained A* planner along with ray-tracing goal specification to enable branch-aware traversal and the inspection of occluded targets. We validate our system through hardware experiments, demonstrating reliable traversal of stems ranging from 7-33mm and autonomous navigation across four distinct plant specimens. Quantitative evaluations show that our system achieves high-fidelity geometric reconstructions with an average Chamfer distance of less than 1cm relative to an offline photogrammetry baseline, confirming that STEMbot maintains the globally consistent odometry needed for autonomous navigation.
### Title:
          Who Broke the System? Failure Localization in LLM-Based Multi-Agent Systems
 - **Authors:** Yufei Xia, Anjun Gao, Yueyang Quan, Zhuqing Liu, Minghong Fang
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model (LLM) based multi-agent systems enable complex problem solving through coordinated reasoning and action, but their distributed structure also introduces new challenges in diagnosing system-level failures. When an execution fails, identifying which agent is responsible and at what point the trajectory first becomes irreversibly misdirected is difficult due to long-horizon interactions and tightly coupled agent behaviors. In this paper, we study the problem of failure localization in LLM-based multi-agent systems and present AgentLocate, a framework that attributes failures to both a specific agent and the earliest decisive step. AgentLocate combines an LLM-based judging mechanism with multi-perspective verification by independent evaluators, whose assessments are aggregated using a confidence-aware strategy. The resulting feedback is further used to adapt the judge through lightweight fine-tuning, improving attribution quality. We evaluate AgentLocate on two complementary benchmarks covering diverse tasks, agent configurations, and trajectory lengths. Experimental results show that AgentLocate consistently outperforms existing failure localization methods in identifying both responsible agents and failure steps, while remaining efficient in terms of token usage and running time.
### Title:
          D-CLIPSE: Distributed Consensus-based Localization with Passive Listening on Shared State Exchange
 - **Authors:** Kyle Biron-Gricken, James Richard Forbes
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-robot localization that is accurate and consistent is imperative for downstream tasks such as planning and control. Centralized filtering approaches optimally fuse all available sensor measurements of the team. However, a centralized solution is rarely implementable due to hardware, communication, and computational constraints. Distributed approaches deploy a filter on each robot to estimate their own state and neighbours' states using inter-robot communication. This paper proposes a consistent, communication-efficient, and consensus-based distributed filtering framework that shares both preintegrated odometry and relevant shared states among communicating robots. The proposed method is validated in simulated and experimental scenarios, showing near centralized performance in accuracy, and especially in consistency, compared to the current state-of-the-art decentralized approach.
### Title:
          RadioDiff-v2: Generative Angular Radio Maps for Multi-Beam Selection and Localization
 - **Authors:** Xiucheng Wang, Junxi Huang, Nan Cheng
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Angular radio maps describe the received-power distribution over the angle of arrival and underpin beam selection and receiver localization in sixth-generation (6G) networks. Predicting the angular power spectrum (APS) from geometry is difficult, because the mapping is ill-posed in non-line-of-sight (NLOS) conditions and must generalize to unseen environments. Distortion-minimizing regressors return the conditional mean, which over-smooths the spectrum and erases the multipath structure that downstream tasks need. We cast the task as a perception-distortion problem and propose RadioDiff-v2, a dual-branch one-dimensional diffusion transformer trained with flow matching. It couples periodic angular encoding, adaptive layer-normalization conditioning, a Fourier angular mixer, and joint velocity and clean-signal heads. A per-metric estimator portfolio reads every deployment quantity from this single model, so that samples carry the distribution, the clean-signal head supplies a regression-grade point estimate, Bayes-optimal rules select beams, and the conditional likelihood localizes the receiver. We prove that a concentrated conditional yields a straight probability-flow trajectory that one step integrates exactly, identifying deterministic transport as the correct inductive bias. On a zero-shot test of 99 environments and one million links, RadioDiff-v2 leads every baseline on every metric, with a 0.39 dB Wasserstein-1 distance, per-bin error below the regression baseline, a 2.43 dB eight-beam NLOS sweep loss, and a 20.6-pixel localization error with four base stations. Code is available at this https URL.
### Title:
          UAV-OVVIS: Unmanned Aerial Vehicles Also Need Open-Vocabulary Video Instance Segmentation
 - **Authors:** Mingyu Dou, Shi Qiu, Ming Hu, Yifan Chen, Zhe Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unmanned Aerial Vehicle (UAV) videos are widely used in traffic monitoring, urban management, and emergency rescue. However, existing UAV video perception mainly relies on box-level localization and trajectory association under predefined categories, making it difficult to simultaneously support flexible queries and fine-grained instance-level dynamic understanding in open scenarios. To this end, we introduce a new task, UAV Open-Vocabulary Video Instance Segmentation (UAV-OVVIS), which discovers targets in UAV videos according to open-vocabulary queries and outputs instance-level segmentation trajectories with globally consistent identities. Considering the scarcity of instance-level annotations in UAV scenarios, we propose AeroTrack, a training-free unified framework. AeroTrack centers on periodic open-vocabulary detection, short-segment mask propagation, and cross-segment identity unification, reusing existing visual foundation models to enable UAV-OVVIS. Based on this framework, we instantiate five AeroTrack variants and construct AeroVIS, an evaluation benchmark for UAV-OVVIS containing 9 UAV object categories and 8,279 trajectories. Experiments show that AeroTrack substantially outperforms existing general video instance segmentation methods in UAV scenarios and demonstrates strong open-vocabulary robustness and generalization. To support future research, we release AeroTrack and AeroVIS as a unified framework and benchmark for UAV-OVVIS.
### Title:
          RadLoc: Radar-based 3-DoF Global Localization via Fast, Robust, and Lightweight Spatial Descriptor Across Diverse Environmental Scenarios
 - **Authors:** Hogyun Kim, Jiwon Choi, Jungwoo Lee, Younggun Cho
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While global localization using spinning radar has gained attention for its robustness to adverse weather and challenging environments, many studies have focused on individual components such as place recognition or pose estimation. In this paper, we take a holistic view of radar sensor-based global localization and present RadLoc, a fast, robust, and lightweight end-to-end pipeline from place recognition to 3-DoF pose estimation. RadLoc accelerates pre-processing using 1D CA-CFAR filtering and leverages the near-range dominance in spinning radar images to design a compact descriptor and an efficient hierarchical coarse-to-fine retrieval strategy. Moreover, coupled with phase correlation-based 3-DoF pose estimation, it forms a versatile global localization module applicable to SLAM and multi-session SLAM systems. Extensive experiments on 15 sequences across 5 datasets demonstrate that RadLoc achieves robust performance while maintaining the smallest descriptor size and fastest retrieval time among state-of-the-art approaches. The supplementary materials are available at this https URL.
### Title:
          VocaDet: Sample-Driven Open-Vocabulary Object Detection and Segmentation via Visual Tokenization and Vector Database Retrieval
 - **Authors:** ZhiXin Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary object detection and segmentation aim to recognize arbitrary objects beyond predefined categories. Although recent vision-language and reference-based approaches have significantly advanced this field, they often rely on text prompts, limited visual examples, or expensive feature matching procedures, making them difficult to scale to large and continuously expanding object repositories. In this work, we propose VocaDet, a sample-driven open-vocabulary object detection and segmentation framework that learns object concepts directly from user-provided positive and negative sample collections without model retraining. The key idea is to transform continuous visual representations into discrete visual vocabularies and perform efficient retrieval-based recognition through a scalable vector database. Specifically, we employ DINOv3 as the visual feature extractor and apply agglomerative clustering with adaptive clustering sensitivity to generate multi-granularity visual tokens. These visual tokens, together with position-debiased representations and spatial topology information, are stored as expandable object memories in a vector database. During inference, query images are converted into visual tokens and efficiently matched against the stored object memories for object localization and segmentation. Furthermore, a background filtering mechanism is introduced to remove frequently occurring background patterns and reduce redundant retrieval operations in practical fixed-camera scenarios. Experiments on the UA-DETRAC dataset demonstrate that VocaDet achieves effective open-vocabulary detection performance without conventional detector training, while supporting continuously expandable recognition capability as additional positive and negative samples are accumulated.
### Title:
          HumanForge: A Human-Centric Deepfake Video Benchmark with Multi-Agent Forgery Rationales
 - **Authors:** Wenbo Xu, Zhimin Chen, Xiaojie Liang, Hengrui Liu, Wei Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid advancements in video diffusion models and temporal editing tools have enabled the generation of highly realistic human-centric videos, posing unprecedented challenges to digital content forensics. Existing benchmarks primarily focus on either face-swapping or global text-to-video synthesis, overlooking the crucial dimensions of human-object or human-human interactions and multi-modal alignment. To address these limitations, we introduce HumanForge, a unified, large-scale, and multi-paradigm human-centric video forgery dataset. To construct and annotate this dataset without labor-intensive manual labeling or hallucinated monolithic prompts, we propose Gen2Anno, a modular active multi-agent pipeline built on LangGraph. Gen2Anno coordinates six specialized agents-ranging from source profiling to MoE-based reference analysis and closed-loop forensic verification-to generate over 18K high-fidelity video segments and produce structured, contrastive omni-annotations containing binary decisions, fine-grained artifact categories, and spatio-temporal localization. Extensive benchmarks using state-of-the-art traditional detectors and Large Multimodal Models (LMMs) demonstrate the significant challenges of zero-shot generalization and fine-grained reasoning on HumanForge. Code and dataset will be publicly released.
## Keyword: transformer
### Title:
          LLT: Local Linear Transformer for PDE Operator Learning
 - **Authors:** Oded Ovadia, Eli Turkel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators have become a common approach for learning PDE solution maps and accelerating numerical simulations. Transformer-based neural operators are of particular interest, since attention can learn long-range dependencies in the computational domain. However, standard attention has two major limitations when applied to PDEs: it scales quadratically with the number of computational nodes, and it lacks an explicit bias toward local interactions. To address these issues, we introduce Local Linear Transformer (LLT) for PDE operator learning. The architecture combines linear global attention with local spatial mixing, and incorporates coordinate and geometry information. We evaluate LLT on several PDE problems, including elasticity, plasticity, airfoil flow, pipe flow, and Darcy flow. The reference data for these problems span finite-element, finite-volume, and finite-difference discretizations on structured and unstructured meshes. Compared with other neural-operator and transformer baselines from prior studies, LLT achieves competitive or lower relative $L_2$ error across these problems. On matched structured discretizations, wall-clock time per training iteration is reduced by factors of 1.8 to 2.5 relative to Transolver. We also scale the approach and apply it to a three-dimensional car aerodynamics dataset with 32,186 unstructured mesh points per sample. Together, these results indicate that LLT provides an accurate and computationally efficient operator for PDE problems across discretizations, mesh types, and problem settings.
### Title:
          SHIFT: Survival Prediction from Incomplete and Heterogeneous Genomic Data
 - **Authors:** Muhammet Sami Yavuz, Ayhan Can Erdur, Sabri Mustafa Kahya, Benedikt Wiestler, Jana Lipkova
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Genomics (q-bio.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Genomic prediction models often fail to transfer across institutions because sequencing panels differ across sites, creating structural feature missingness at deployment. Existing approaches to this challenge typically restrict analysis to genes shared across cohorts, exclude patients with incomplete profiles, or rely on test-time imputation, all of which can reduce robustness and limit the use of multi-center data. We propose Survival prediction Handling Incomplete Features using Transformer (SHIFT), a missingness-aware survival model that directly predicts from incomplete genomic inputs without test-time imputation. SHIFT represents each genomic feature separately and uses masked self-attention, along with a feature-availability mask, so that predictions are based only on observed inputs. Further, we introduce variable-rate feature masking during training to improve robustness to heterogeneous missingness patterns. We evaluate the approach on glioblastoma and lung squamous cell carcinoma with external validation across multiple cohorts, including a challenging setting with severe cross-cohort panel mismatch. Across these settings, SHIFT shows strong generalization and compares favorably with standard survival baselines and imputation-based approaches, while using a single model across differing feature sets. We also find that incorporating patients from incomplete cohorts during development can improve performance on external data, suggesting that partially observed cohorts need not be excluded from model building. These results support missingness-aware modeling as a practical strategy for multi-center survival prediction in precision oncology.
### Title:
          Architecture Generalization with MetaNCA
 - **Authors:** Meet Barot, Daniel Berenberg, Sina Khajehabdollahi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-organization is an emergent property of life, driven by the collective behavior of individual components acting on local information. Biological neurons, through local interactions transmitted through synapses, are able to learn efficiently and can adapt their connections over an organism's lifespan. Motivated by these desirable properties of adaptability and local interaction, neural cellular automata (NCA) models have been successful at learning morphogenesis solely through local update rules, demonstrating stability over many updates and robustness to perturbations. In this work, we introduce Meta Neural Cellular Automata (MetaNCA), a framework that learns local rules which self-organize the weights of artificial neural networks. A learned rule network iteratively updates the weights of a task network using only local interactions on the computation graph. We propose a novel Weight Transformer architecture for the local rule network, which uses linear attention to aggregate signals from neighboring weights and hidden states. Once trained, the rule network generates task networks of diverse architectures without backpropagation. We show that MetaNCA generates weights for feedforward MLPs, CNNs, and ResNets on MNIST and CIFAR-100, scaling to networks of 2 million parameters. We further show that MetaNCA generalizes to architectures not seen during meta-training, and that architectural diversity in the training phase strengthens this generalization.
### Title:
          Graph-Regularized Deep Learning for EEG-Based Emotion Recognition with Psychologically-Grounded Label Structure
 - **Authors:** Dongyang Kuang, Zizheng Ma, Yushan Zhang, Xiaocong Zeng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 EEG-based emotion recognition is critical for mental health monitoring and affective brain-computer interfaces, yet existing deep learning approaches often treat emotion classes as isolated labels, ignoring their psychological interdependencies. We propose a graph-regularized learning framework that conceptualizes emotions as nodes in a graph where edges encode proximity based on dimensional emotion theories. We adapt three complementary regularization strategies--Graph Label Smoothing (intuitive soft labeling), Commuting distance on graph via Graph Laplacian (spectral graph theory), and Sliced Wasserstein Distance (optimal transport on graph)--ordered by increasing computational complexity. These strategies penalize model predictions that deviate from the established emotion topology. Our framework is evaluated across three representative backbone architectures: AudioTransformer (pure transformer), Conformer (CNN-transformer hybrid), and DCGNN (causal graph neural network), demonstrating architecture-agnostic benefits. Experiments on SEED-IV (4 classes) and SEED-V (5 classes) datasets show consistent improvements: best case up to +5.42% accuracy and 39% reduction in psychologically implausible misclassifications. Ultimately, our framework help raise the upper bound of performance achievable with standard approaches. Code will be released.
### Title:
          Adversarial Decoys: Misdirecting Attention-Based Defenses in ViT
 - **Authors:** Giulia Marchiori Pietrosanti, Giulio Rossolini, Giorgio Buttazzo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) remain vulnerable to localized adversarial attacks, e.g., adversarial patches, while recent test-time defenses mitigate them by suppressing image tokens with abnormally high attention scores. These defenses exploit a strong coupling between attention and adversarial effectiveness: adversarial tokens often need to attract substantial attention to influence the prediction. We introduce adversarial decoys, independently optimized image patches that redirect the attention, and therefore related defenses, toward selected target tokens. Rather than jointly optimizing misclassifications and defense evasion, our approach decouples the two objectives: the original adversarial region induces the incorrect prediction, while a separate decoy manipulates the attention ranking used by the defense. A layer-wise objective increases target-token attention and promotes these tokens above competing non-target ones. Since the decoy is optimized independently of the underlying attack, the method is attack-agnostic and can be easily integrated with any existing adversarial patch attack. Experiments on ImageNet across multiple ViT architectures and attacks show that decoys can redirect high attention scores away from the true adversarial region while preserving much of the attack effectiveness. These results reveal a fundamental limitation of using attention magnitude as an indicator of adversarial relevance.
### Title:
          Evaluating the Generalizability of Foundation Models for Extreme Environmental Events: Case Study of California Wildfire PM2.5
 - **Authors:** Yongcan Huang, Li Jiang, Ze Yu Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wildfire smoke events produce extreme PM$_{2.5}$ concentrations that pose severe public health risks, yet forecasting rare, hazardous-level spikes remains a fundamental challenge. Time series foundation models (TSFMs), pretrained models offering zero-shot inference and efficient adaptation, perform strongly on general benchmarks, but their behavior under extreme out-of-distribution conditions is poorly understood. We present the first systematic benchmark comparing six TSFM configurations (zero-shot TimesFM, Chronos-2, Moirai-2, and Time-MoE, plus LoRA fine-tuned Chronos-2 and Time-MoE) against fully-trained baselines (LSTM, BiLSTM, Transformer) and naive persistence on a 12-year (2013--2025) hourly PM$_{2.5}$ dataset covering 1,375 wildfire incidents across 79 California monitoring sites. A leave-one-incident-out (LOIO) protocol evaluates generalization to unseen fires, using MAE, RMSE, and exceedance F1 at EPA AQI thresholds across 6-, 12-, and 24-hour horizons. Results reveal a consistent hierarchy. The BiLSTM achieves the lowest MAE ($5.16\,\mu g/m^3$) and the highest exceedance F1 at every threshold, including the Hazardous band ($>225.5\,\mu g/m^3$), reaching 0.63 versus at most 0.54 for any foundation model. Zero-shot TSFMs improve on persistence only modestly, and zero-shot Chronos-2 exhibits severe RMSE tail instability ($23.4\,\mu g/m^3$, negative $R^2$) from sporadic large errors. LoRA fine-tuning substantially improves both adapted families and largely repairs this instability, yet no foundation model surpasses the trained recurrent baselines on any metric. These findings challenge the assumption that larger pretrained models universally dominate environmental forecasting and provide actionable deployment guidance for wildfire air quality prediction.
### Title:
          LOGOS: Language-guided Oriented Object Detection in Aerial Scenes
 - **Authors:** Trong-Thuan Nguyen, Minh-Triet Tran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object detection in geospatial scenes, such as satellite and aerial imagery, poses significant challenges due to the varying orientations and densities of objects, as well as the complex backgrounds inherent to remote sensing imagery. Traditional methods for oriented object detection have struggled to address issues such as angular discontinuity, fixed query sizes, and inefficiencies in handling sparse or cluttered scenes. In this paper, we propose LOGOS, a novel transformer-based approach that leverages textual prompts to guide the detection of oriented objects in aerial scenes. In particular, our proposed approach incorporates prompt-modulated content queries to dynamically adjust the model's focus based on the provided text, thereby improving object detection accuracy in complex environments. Empirically, extensive experiments on the DOTA dataset demonstrate that LOGOS outperforms existing state-of-the-art methods, particularly in densely packed and rotated object scenarios. Our approach offers a significant step forward in improving the robustness and scalability of oriented object detection in remote sensing applications.
### Title:
          RadioDiff-v2: Generative Angular Radio Maps for Multi-Beam Selection and Localization
 - **Authors:** Xiucheng Wang, Junxi Huang, Nan Cheng
 - **Subjects:** Subjects:
Information Theory (cs.IT); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Angular radio maps describe the received-power distribution over the angle of arrival and underpin beam selection and receiver localization in sixth-generation (6G) networks. Predicting the angular power spectrum (APS) from geometry is difficult, because the mapping is ill-posed in non-line-of-sight (NLOS) conditions and must generalize to unseen environments. Distortion-minimizing regressors return the conditional mean, which over-smooths the spectrum and erases the multipath structure that downstream tasks need. We cast the task as a perception-distortion problem and propose RadioDiff-v2, a dual-branch one-dimensional diffusion transformer trained with flow matching. It couples periodic angular encoding, adaptive layer-normalization conditioning, a Fourier angular mixer, and joint velocity and clean-signal heads. A per-metric estimator portfolio reads every deployment quantity from this single model, so that samples carry the distribution, the clean-signal head supplies a regression-grade point estimate, Bayes-optimal rules select beams, and the conditional likelihood localizes the receiver. We prove that a concentrated conditional yields a straight probability-flow trajectory that one step integrates exactly, identifying deterministic transport as the correct inductive bias. On a zero-shot test of 99 environments and one million links, RadioDiff-v2 leads every baseline on every metric, with a 0.39 dB Wasserstein-1 distance, per-bin error below the regression baseline, a 2.43 dB eight-beam NLOS sweep loss, and a 20.6-pixel localization error with four base stations. Code is available at this https URL.
### Title:
          Leveraging Color Naming for Image Enhancement
 - **Authors:** David Serrano-Lozano, Luis Herranz, Michael S. Brown, Javier Vazquez-Corral
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enhancing images to make them visually appealing is a persistent challenge in computer vision. Many deep-learning methods train models on paired datasets to replicate expert editing styles. However, these approaches struggle with two key issues: (1) interpretability and (2) a parametrization suitable for user adjustments. To address these challenges, we present NamedCurves+, an approach inspired by the concept of Color Naming, a universal set of familiar colors widely used in software tools for intuitive editing. Our method integrates color names into a learning-based framework, enabling global adjustments for each named color through tone curves. To address local image variations, we incorporate a transformer block that captures spatial dependencies, enabling context-aware edits across the image. NamedCurves+ enhances the retouching process's interpretability and supports user interaction, allowing flexible modifications of individual tone curves to refine the retouched image according to personal preferences. Extensive experiments on tasks such as image retouching, tone mapping, and exposure correction demonstrate that NamedCurves+ outperforms state-of-the-art methods. Notably, our approach is both explainable, as the tone curves explicitly represent how each color name contributes to the enhancement, and interactive, allowing users to customize the retouching process and achieve results tailored to their liking.
### Title:
          Hidden Decoding at Scale: Latent Computation Scaling for Large Language Models
 - **Authors:** Aiwei Liu, Cheng Shi, Chuhan Wu, Ci Lei, Di Lu, Donald He, Fan Zhang, Fanhao Kong, Feifei Zhang, Guan Wang, Haicheng Wang, Haoyu Liu, Houjin Yu, Jiachen Ding, Jiayi Feng, Jie Zhou, Jijun Chi, Jindi Shi, Jing Lei, Junjie Zhang, Laiyi Li, Le Tian, Linhao Zhang, Miao Fan, Sijun Zhang, Wei Jia, Weiwei Shi, Wenhan Li, Wentao Zhao, Wenteng Liang, Xiao Zhou, Xiaojin Zhou, Xihuai Wang, Xinyu Gao, Xuanliang Wang, Xuyang Ao, Yang Yu, Yangxiu You, Yinuo Zhao, Yufei Kuang, Yufei Wang, Yuan Liu, Yuan Liu, Yuwen Chen, Zhencong Tian, Zhongyin Zhao, Zilin Yu, Zitao Wang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling Large Language Models (LLMs) has been driven mainly by enlarging the Transformer backbone, but for an already-strong model this requires another round of costly pretraining. We study whether an existing backbone can keep improving by allocating more computation to each token while leaving the Transformer backbone fixed. Depth-recurrent (looped) Transformers pursue this goal but are hard to scale, because looped computation does not fit naturally with the pipeline parallelism used to train the largest models. We add computation along the sequence-length dimension, where the extra computation is simply a longer input and stays compatible with standard large-model training. We propose Hidden Decoding, a sequence-length scaling method applied during continued pretraining (CPT). It expands each token into n streams with independent embedding tables and keeps the intermediate streams' key-value cache as context, so each token performs more internal computation without adding or widening Transformer layers. To keep this affordable at scale, we introduce Stream-Factorized Attention, in which most layers attend only within each stream and only a few layers mix across streams, reducing the attention cost from quadratic to roughly linear in n. Experiments support two scaling results. At frontier scale, we train WeLM-HD4-80B and WeLM-HD4-617B at n=4 and improve their matched non-HD baselines, making Hidden Decoding the first demonstrated sequence-length scaling method at the 100B+ MoE scale. Across expansion factors, the gains grow as n increases, showing that sequence-length expansion is a practical fixed-backbone scaling path for frontier-scale LLMs.
### Title:
          Multimodal 3D LUT Generation via StatLUT with Statistical Features for Photorealistic Style Transfer
 - **Authors:** Yifan Wang, Zhixiang Hao, Yu Wang, Congchao Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Photorealistic Style Transfer (PST) aims to transfer the color and tonal style of a reference to a content image while strictly preserving its structural integrity. However, existing deep learning-based methods inherently suffer from semantic entanglement caused by pre-trained image encoders, leading to unnatural spatial distortions. Moreover, current pixel-level mapping paradigms often ignore color gamut topology, resulting in color banding, while also lacking the multimodal capability for intuitive text-driven control. To address these bottlenecks, we propose StatLUT, an innovative multimodal framework for 3D LUT generation. First, we bypass traditional encoders and introduce a Lab-Extractor to derive spatially-agnostic statistical features, fundamentally decoupling color distributions from structural semantics to ensure artifact-free rendering. Second, we formulate LUT generation as a Transformer-based Seq2Seq translation task, utilizing a Multi-dimensional Residual Mapper (MR-Mapper) to predict topologically smooth 3D LUTs. Finally, to break the single-modal barrier, we propose the H-Diffuser, a lightweight Diffusion Transformer that directly synthesizes statistical features from natural language prompts, enabling flexible text-driven color grading. Extensive experiments on standard benchmarks demonstrate that StatLUT significantly outperforms state-of-the-art methods in both visual quality and quantitative metrics, pioneering a highly robust and flexible paradigm for multimodal photorealistic style transfer.
### Title:
          RhyMix: A Lightweight Adaptive Multi-Rhythm Network for Long-Term Time Series Forecasting
 - **Authors:** Sumit Satishrao Shevtekar, Chandresh Kumar Maurya
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world time series exhibit complex dynamics characterized by multiple simultaneous temporal patterns: short-term fluctuations, periodic seasonal cycles, long-term trends, and irregular abrupt changes. However, many existing forecasting architectures rely on single-path temporal modeling--transformers capture long-range dependencies but smooth local variations, convolutions capture local patterns but have limited receptive fields, and linear models are efficient but cannot capture nonlinear dynamics. To address this, we introduce RhyMix (RHYthm MIXture), a hybrid neural architecture designed around a parallel dual-path modeling paradigm with adaptive gating mechanisms. RhyMix integrates two complementary encoding branches: (i) a Cyclic Path that incorporates explicit seasonal inductive bias through learnable cyclic embeddings, capturing predictable rhythmic patterns; and (ii) a lightweight Multi-Scale Temporal Convolutional Network with Channel Attention Path that employs multi-scale depthwise dilated convolutions to capture temporal dependencies across different receptive fields. A key innovation is the use of adaptive gating at multiple levels: a path gate dynamically combines four specialized forecasting heads (Direct, Trend-Seasonal Decomposition, Local Convolution, and Periodic Fusion) per sample and channel, while a hybrid gate adaptively balances the Cyclic and MSTCN-CA Paths based on input characteristics. This design ensures the model adapts to specific temporal patterns while maintaining linear complexity in sequence length, channels, and prediction horizon. Across extensive benchmarks on 12 real-world datasets for long-term forecasting, RhyMix achieves state-of-the-art performance on 10 of 12 datasets. The model remains lightweight (~40K params) with linear complexity and low-latency inference (<5ms),suitable for resource-constrained edge devices and real-time deployment.
### Title:
          Progression as Latent Drift: Generative Forecasting of Slow-Evolving Pathologies
 - **Authors:** Yuxiang Feng, Juncheng Wang, Chao Xu, Wenlong Hou, Huihan Wang, Yijie Qian, Yang Liu, Baigui Sun, Yong Liu, Shujun Wan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting the future anatomy of slow-evolving neurodegenerative diseases could enable earlier, more targeted intervention and improve clinical trial design, but it remains challenging because true progression signals are subtle in longitudinal MRI. In this low-signal regime, transferring modern generative sequence models directly is unreliable: training is dominated by stable baseline anatomy and confounded by dense, sample-specific nuisance variation. We first provide a theoretical analysis that explains these failures through two modes. Identity collapse occurs when optimization is driven toward reproducing the current anatomy, which prevents the model from learning faint temporal change. The continuous interpolation trap arises when standard smooth networks cannot separate localized biological drift from pervasive noise, which leads to spurious changes that diffuse across the volume. To address both issues, we propose Latent Drift, a progressive generative framework that learns change in a compressed semantic representation rather than synthesizing full-resolution anatomy. This design removes pixel-level identity from the prediction target and concentrates model capacity on progression-relevant dynamics. We further apply Finite Scalar Quantization to the learned change representation, which suppresses small, high-frequency nuisance fluctuations while preserving consistent structural drift. Experiments on longitudinal 3D brain MRI show that Latent Drift improves patient-specific neuro-forecasting over diffusion and autoregressive transformer baselines across generative fidelity and clinically relevant evaluation metrics. Project page: \href{this https URL}{this https URL}.
### Title:
          Texture Representations in Deep Vision Models: Comparing CNNs, Vision Transformers, and Human Perception
 - **Authors:** Ludovica de Paolis, Marco Baroni, Alessandro Laio, Eugenio Piasini
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In computational vision science, Convolutional Neural Networks (CNNs) have emerged as a popular model of biological vision because of the alignment they can exhibit with neural and behavioral data in humans and animals. However, it remains unclear to what extent this alignment persists for visual tasks that extend beyond the canonical object recognition paradigm based on well defined semantic content. In this study, we diverge from the common object-centric view by focusing on another aspect of vision: texture perception. We consider textures of different complexity generated with three different algorithms from the same source images. Using a rank-based statistic, we quantify the information encoded in the internal representations of a CNN and three Vision Transformers (ViTs), and we compare the similarity of these representations to those inferred from human psychophysics data. We find that the representation of textures is aligned in different ViTs, but not between the ViTs and the CNN; that ViTs form similar representations for textures of different complexity; that human performance in recognizing textures can be better predicted from ViTs representations rather than CNN representations. Taken together, these results suggest that ViTs may capture more faithfully than CNNs how texture patterns are visually processed by humans, and that the representations of texture stimuli in computational models may be driven by the network architecture.
### Title:
          FSD-VLN: Fast-Slow Dual-System Modeling for Aerial Long-Horizon Vision-Language Navigation
 - **Authors:** Xueke Zhu, Qingyan Meng, Liutao Yu, Wei Zhang, Zhengyu Ma, Huihui Zhou, Yonghong Tian
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Navigation (VLN) enables UAV autonomous navigation in unknown environments by mapping language instructions to real-time visual inputs. Compared with GPS-dependent or pre-programmed navigation, VLN supports intuitive human-machine interaction and stronger environmental adaptability, requiring tight integration of high-level semantic reasoning and low-latency flight this http URL methods suffer from structural misalignment between global multimodal understanding and sequential action generation, causing jittery trajectories and severe decision latency for long-horizon aerial navigation. To solve this issue, we propose FSD-VLN, a fast-slow dual-system architecture disentangling semantic reasoning and low-latency flight command this http URL framework has two asynchronous branches: a slow stream extracting stable semantic priors from pre-trained vision-language models, and a Diffusion Transformer (DiT) fast stream modeling cross-temporal action distributions to produce consistent flight outputs. We further introduce a time-aware adaptive optimizer to stabilize long-sequence training and reduce gradient this http URL-scale low-altitude simulation experiments show FSD-VLN achieves up to 2X higher navigation success rates on unseen scenes than SOTA methods, while cutting single-action inference delay and total task runtime by over 50%. Our work validates the benefit of decoupled semantic-control modeling and provides a practical paradigm for long-horizon aerial VLN.
### Title:
          WCog-VLA: A Dual-Level World-Cognitive Vision-Language-Action Model for End-to-End Autonomous Driving
 - **Authors:** Xuerun Yan, Zhexi Lian, Nuoheng Zhang, Shiyu Fang, Haoran Wang, Chen Lv, Jia Hu, Binyang Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have advanced end-to-end autonomous driving. However, existing methods either lack comprehensive world cognition or suffer from fragmented world foresight, inherently confining these models to reactive driving. To address this limitation, we propose WCog-VLA, a novel dual-level World-Cognitive VLA framework that successfully bridges semantic world forecasting with generative world evolution to achieve proactive autonomous driving. At the semantic level, WCog-VLA unifies world cognition and reasoning by incorporating 3D spatial perception and injecting agent tokens to capture the world dynamics, while concurrently enabling Game-theoretic Chain-of-Thought (Game-CoT) reasoning. At the generative level, we introduce the Aligned Decoupled Diffusion Transformer (ADDT) as a powerful generative world model that synthesizes physically-plausible joint multi-agent trajectories. Through scene representation alignment, ADDT reduces the number of denoising steps required and thus significantly accelerates inference. To facilitate strategic reasoning, we further construct a large-scale dataset featuring 85k Game-CoT annotations. Extensive experiments on the NAVSIM benchmark demonstrate that WCog-VLA achieves a State-Of-The-Art (SOTA) PDMS score of 92.9.
### Title:
          Beyond Backpropagation: Monte Carlo Method Can Train Deep Neural Networks
 - **Authors:** Hong Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backpropagation (BP) dominates deep learning training, but its reliance on gradients brings inherent troubles -- vanishing and exploding gradients. The pursuit of gradient-free methods has long been a goal in the field of artificial intelligence. This paper shows that indeed the simplest Monte Carlo algorithm implemented on a single GPU -- randomly mutate a parameter, keep it if the loss decreases, otherwise retry -- can practically train deep networks. This gradient-free method does not even need common techniques such as batch normalization or residual connections to directly train sufficiently deep networks. More remarkably, its flexibility extends to several nontrivial scenarios: it enables pure pruning training, supports discrete weights, accommodates unconventional transfer functions such as Gaussian, and reveals the substantial redundancy of deep networks. We have demonstrated its feasibility on deep networks with more than 20 layers, single-hidden-layer wide networks with up to 16,384 hidden neurons, and even a simple Transformer architecture trained on both image classification (MNIST) and character-level language modeling (Tiny Shakespeare). This simple gradient-free method may offer a complementary perspective for understanding the self-organization and learning mechanisms of neural networks, and also provides an alternative route for building physically inspired deep learning systems.
### Title:
          Applying JEPA-Style Predictive Learning to JA4-Derived Network Fingerprints
 - **Authors:** Javier Izquierdo, Aygul Zagidullina
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 I-JEPA and V-JEPA learn by matching latent predictions to target encoder outputs rather than regenerating the original input, and this has worked well for images and video. We explore whether the same objective works for compact network fingerprints. We built JA4-JEPA, a Transformer-based model trained on JA4, JA4H, JA4S, and JA4X subfields drawn from JA4DB and CIC-IDS- 2017. The training data combines roughly 397K samples from both sources, though no single sample contains all four view families. We evaluated the learned representations with a frozen kNN probe on protocol-family classification across TLS, DNS, and SSH. On 39,416 heldout samples the model achieved a cosine similarity of 0.9899 and a kNN accuracy of 0.9220. These results indicate that JEPA-style predictive learning can produce useful embeddings from JA4-derived fingerprints, even with incomplete view overlap across sources. Keywords: JA4, network fingerprinting, JEPA, predictive representation learning, self-supervised learning
### Title:
          Systematic Evaluation of Learning Rate Scheduling Strategies Across Heterogeneous Architectures
 - **Authors:** Hafsa Mateen, Radu Timofte, Dmitry Ignatov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Choosing a learning rate scheduling strategy is critical to neural network training, but manual selection is costly and rarely exhaustive. While classical AutoML approaches often treat the scheduler as a secondary hyperparameter, we systematically investigate its impact on classification accuracy across a diverse pool of architectures. We evaluated 30 representative architectures from convolutional and transformer families within the LEMUR neural network dataset. Through automated source-code injection, we applied 25 scheduler configurations across nine PyTorch families, evaluating a total of 3,938 model variants on CIFAR-10. Our best configuration achieved a top-1 accuracy of 86.45%, with 237 variants exceeding 80%. The results show that the choice of scheduler depends heavily on the architecture: CosineAnnealingWarmRestarts and CyclicLR consistently outperform basic decay strategies. The resulting accuracy landscape, contributed to the LEMUR nn-dataset, provides a practical reference for principled scheduler selection.
### Title:
          Whareformer: Learning to Track What is Where in Long Egocentric Videos
 - **Authors:** Jacob Chalk, Saptarshi Sinha, Dima Damen, Yannis Kalantidis, Diane Larlus
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The recently established 'Out of Sight, Not out of Mind' (OSNOM) task for egocentric videos focuses on tracking objects that are moved by the camera wearer, online, maintaining knowledge of instance locations throughout the video even when they leave the field of view or become heavily occluded. In this paper, we propose the first learning-based solution to the OSNOM task: Whareformer, a transformer-based model with two components: an updatable memory of established tracks and a track assignment module that associates observations with existing tracks in a feed-forward manner. Whareformer jointly reasons over evolving object appearance (what) and updated 3D location (where), and employs a dedicated New Track token to reason about novel objects. Thanks to its design choices of using relative distances and evolving track representations, Whareformer is trained on a small set of 56 videos but achieves SOTA performance on 260 long test videos from three datasets: EPIC-KITCHENS-100 (unseen videos), IT3DEgo, and HD-EPIC, with significant absolute improvements over prior work.
### Title:
          SHAP-Weighted Cross-Modal Expert Fusion for Emotion and Sentiment Recognition: Evidence and Limits
 - **Authors:** Adis Alihodzic, Selma Skopljakovic Hubljar
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal emotion and sentiment recognition is commonly addressed by early fusion, which concatenates modalities before classification, or late fusion, which combines independently trained unimodal predictors. Early fusion can be accurate but monolithic, while late fusion is modular but may lose cross-modal interactions. This paper revisits XAI-guided adaptive fusion (\xgaf), a tree-based mixture of unimodal and cross-modal experts whose sample-level weights are derived from TreeSHAP attribution magnitudes. We focus on the effect of SHAP attribution reduction when experts have unequal feature dimensionalities. In this setting, mean-abs and median-abs reductions can suppress high-dimensional cross-modal experts, whereas sum-abs reduction preserves total attribution mass. On MELD 7-class emotion recognition, sum-abs \xgaf{} nearly matches early fusion across three face-sequence aggregators; the Transformer variant reaches 0.5983 \wf{}, compared with 0.6018 for early fusion and 0.4598 for probability-average late fusion. McNemar testing shows no significant difference between sum-abs \xgaf{} and early fusion on MELD ($p=1.000$), while \xgaf{} remains significantly better than late fusion ($p<0.0001$). On CMU-MOSEI 3-class sentiment recognition, sum-abs \xgaf{} reaches 0.6519 \wf{}, slightly exceeding early fusion (0.6485) and late fusion (0.5696). Ablation studies show that the main gain comes from adding cross-modal experts, especially the trimodal expert, rather than from complex per-sample routing. Diagnostics further show that mean-abs and median-abs weights are nearly uniform, while sum-abs weights concentrate on the trimodal expert. Thus, the main contribution is a transparent empirical analysis of how SHAP reduction, expert dimensionality, and cross-modal expert design affect modular multimodal fusion.
### Title:
          It Takes a MAESTRO To Prune Bad Experts
 - **Authors:** Palaash Goel, Ayush Maheshwari, Tanmoy Chakraborty
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparsely-activated Mixture-of-Experts (MoE) language models achieve remarkable inference efficiency by activating only a small fraction of parameters per token, yet their full expert banks reside in memory at all times, creating a prohibitive deployment bottleneck. Existing structured pruning methods, largely designed for dense transformers, assess expert importance using locally derived heuristics that are blind to the interdependent nature of MoE routing. We introduce MAESTRO (Markov-chain Approximated Expert Sparsification via Transition-based ROuting), a structured pruning framework designed for MoE architectures that models autoregressive expert activation trajectories as Ergodic Markov chains whose stationary distributions encode cross-layer dependencies, yielding a globally aware importance heuristic. Evaluated across five diverse domains including Safety, Bias, and Ethics, MAESTRO outperforms state-of-the-art baselines by up to 10.61% in average performance retention under a strict 50% compression regime, while exhibiting substantially lower cross-task variance, indicating that global, routing-congruent pruning produces models that generalize more consistently across heterogeneous tasks.
### Title:
          When Structured Sparse Autoencoders Learn Consistent Concepts Across Modalities
 - **Authors:** Weiduo Liao, Yunqiao Yang, Ying Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders (SAEs) have emerged as a promising technique for mechanistic interpretability by learning a set of sparse latent features in large models, each of which encodes a distinct concept. However, in vision-language models (VLMs), vanilla SAEs struggle to learn modality-consistent concepts, with concepts often exhibiting fragmented coverage (i.e., disjoint regions) in the visual modality. To address this challenge, we propose a Structured Sparse AutoEncoder ($S^2AE$) that enforces concept consistency from both semantic and spatial perspectives in the visual modality. Specifically, we group image patches based on Transformer attention similarity and spatial proximity, and introduce a structured sparsity regularization when training the vanilla SAE. The regularization consists of exclusive sparsity for inter-group concept disentanglement and group sparsity for intra-group concept consistency, which drives the latent neurons by SAEs to specialize in distinct, semantically grounded concepts. Evaluated on the \texttt{Qwen2.5-VL-7B-Instruct} model, the method achieves 6.06% average improvement in semantic alignment (mIoU) and 60.81 in representational efficiency (lower l0 norm) while maintaining near-perfect reconstruction fidelity with an Explained Variance above 99%. Cross-modal analysis further demonstrates that $S^2AE$ enhances neuronal monosemanticity by this visual structural prior, achieving a 3.08% average gain in semantic consistency and a 2.37% average gain in monosemanticity scores for both modalities of multimodal features, thereby fostering more coherent and disentangled representations.
### Title:
          BiSCo-LLM: Lookup-Free Binary Spherical Coding for Extreme Low-Bit Large Language Model Compression
 - **Authors:** Yuantian Shao, Peisong Wang, Zhilei Liu, Chuangyi Li, Yuanteng Chen, Pengcheng Xie, Yiwu Yao, Zhihui Wei, Jian Cheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly constrained by memory capacity, weight bandwidth, and checkpoint storage during deployment. Existing low-bit compression methods mainly follow two directions. Scalar or group-wise quantization is simple and compatible with efficient low-precision kernels, but its representation capacity becomes limited when the target budget approaches 2 bits per weight. Vector-quantized weight compression provides a richer block-level representation, but usually introduces explicit codebooks, index lookup, and additional storage accounting. This paper presents BiSCo-LLM, a codebook-free binary spherical coding framework for extreme low-bit LLM weight compression. The core pipeline is built on three components. First, local weight chunks are mapped onto a unit hypersphere and binarized into compact spherical codes, so that the main payload is a bit-packed sign stream rather than explicit VQ centroids. Second, a residual BSQ stage encodes the reconstruction error left by the base spherical codec, providing an explicit rate-distortion path without stored codebooks. Third, category-wise recovery distillation is performed after replacing each Transformer module category, reducing the mismatch between local weight reconstruction and assembled model behavior. A small 8-bit protected-channel path is used as an auxiliary stabilization mechanism for sensitive channels and is counted separately from the BSQ payload. The reported storage budget includes binary codes, neural decoders, protected-channel payloads, LoRA adapters, and metadata.
### Title:
          Multi-Resolution Feature Stem for Diabetic Retinopathy lesion segmentation
 - **Authors:** Indranil Dutta, Taehee Jeong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diabetic Retinopathy (DR) is a leading cause of preventable blindness worldwide, requiring automated lesion segmentation using deep learning models for early detection and monitoring. However, DR lesions vary dramatically in size from tiny microaneurysms to large hemorrhages and exudates. This variability creates conflicting demands on the model architecture and input resolution, posing a challenge for effective design. This work investigates the impact of input resolution on different lesion types. Through systematic experimentation with multiple architectures (U-Net, UNet++, Vision Transformers, DeepLabV3+) at $512 \times 512$ and $1024 \times 1024$ resolutions, we identify a critical, counter-intuitive phenomenon where increasing input resolution has opposing effects on different lesion types. We demonstrate that while higher resolution is essential for resolving fine-grained microaneurysms, it can unexpectedly degrade performance on larger hemorrhages. This finding challenges the common assumption that higher resolution is uniformly beneficial. To address this, we propose a novel Multi-Resolution Feature Stem, an input-level pyramid integrated with a UNet++ backbone. This architecture processes multiple scales in parallel, capturing fine-grained details without sacrificing contextual information. This work contributes crucial empirical evidence of this complex, resolution-dependent behavior and a practical, parameter-efficient architecture that successfully resolves this trade-off.
### Title:
          Pose-to-Biomechanics: Bridging 3D Human Pose Estimation and Biomechanical Attribute Prediction
 - **Authors:** Ayda Eghbalian, Kevin Desai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in 3D human pose estimation has made markerless recovery of skeletal motion increasingly accurate and scalable. However, most pose estimators remain optimized for geometric keypoint accuracy, while many real-world applications in rehabilitation, sports science, ergonomics, and clinical movement analysis require biomechanical quantities that describe how the body moves, loads, and activates. In this work, we propose BioModule, a lightweight plug-in temporal transformer that attaches downstream of any 3D pose estimator and predicts biomechanical attributes from standard 17-joint 3D skeletons. BioModule is estimator-agnostic and requires no modification of the upstream pose model, enabling existing pose estimators to be extended toward physically interpretable motion analysis. To train and evaluate BioModule, we construct a large-scale aligned dataset pairing Human3.6M video and 3D keypoints with the biomechanical label space of Human3.6Mplus. We establish and verify anatomical correspondence between coordinate systems of the two datasets, enabling frame-accurate cross-modal supervision. Using this aligned supervision, BioModule predicts biomechanical quantities. We further benchmark BioModule across seven state-of-the-art 3D pose estimators, providing the first systematic analysis of how upstream pose estimation quality propagates to downstream biomechanical prediction fidelity. The results position BioModule as a compact, modular bridge between vision-based pose estimation and biomechanically meaningful human motion analysis.
### Title:
          ARDY: Autoregressive Diffusion with Hybrid Representation for Interactive Human Motion Generation
 - **Authors:** Kaifeng Zhao, Mathis Petrovich, Haotian Zhang, Tingwu Wang, Siyu Tang, Davis Rempe
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating realistic 3D human motions in real-time within interactive applications is key for animation, simulation, and humanoid robotics. While recent offline motion generation approaches offer precise control via text and kinematic constraints, they lack the inference speed required for interactive settings. Conversely, existing online methods enable real-time synthesis but often sacrifice controllability or struggle with complex text semantics and long-horizon goals due to limited context windows. In this work, we introduce ARDY, a streaming generation framework that bridges this gap by enabling high-fidelity motion generation controllable via online text prompts and flexible kinematic constraints. ARDY employs a hybrid representation that combines explicit root features with a latent body embedding, balancing precise trajectory control with efficient generative learning. We propose a two-stage autoregressive transformer denoiser that features variable history context and supports conditioning on flexible, long-horizon kinematic constraints. By training on a large-scale motion capture dataset and being directly conditioned on text labels and kinematic constraints sampled from ground truth poses, ARDY natively learns controllable generation that supports online prompting and flexible long-horizon goals. Extensive evaluations on the HumanML3D benchmark and the large-scale, high-fidelity Bones Rigplay dataset demonstrate ARDY's high motion quality and constraint adherence, validating the efficacy of our key architectural decisions. Finally, we demonstrate the method's practical versatility through an interactive demo featuring dynamic text control, diverse keyframe pose constraints, path following, and interactive locomotion control via mouse and keyboard. Supplementary video results, code, and model releases can be found at this https URL.
## Keyword: autonomous driving
### Title:
          Post-Training in End-to-End Autonomous Driving
 - **Authors:** Ruining Yang, Muxing Wang, Yixiao Chen, Tongfei Guo, Yi Xu, Can Cui, Zichong Yang, Yitian Zhang, Ziran Wang, Yun Fu, Lili Su
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end models that map multimodal inputs directly to future trajectories/maneuvers have emerged as an increasingly prominent research paradigm in autonomous driving. This class of models includes both Vision-Language-Action models and trajectory-generative planners. Unlike classic machine learning applications, autonomous vehicles operate in safety-critical and interaction-intensive environments where traditional open-loop imitation of expert demonstrations is not sufficient to ensure reliability. In particular, small execution errors can accumulate over time, while recovery behaviors are scarce in training data. In addition, long-horizon objectives such as safety and driving comfort are not captured by pointwise labels either. These limitations have motivated a shift toward post-training techniques, which further refine driving policies beyond pure imitation. This survey presents a unified view of post-training for autonomous driving by defining its scope and organizing the existing literature into four major families based on the form of supervision they use. For each family, we discuss its capabilities, limitations, and open challenges. We aim to facilitate a systematic understanding of this emerging area and stimulate future research on reliable and efficient post-training for autonomous driving.
### Title:
          Securing Autonomous Vehicle Systems via Twin-Aware Federated Reinforcement Learning
 - **Authors:** Zifan Zhang, Minghong Fang, Dianwei Chen, Zhuqing Liu, Prashant Khanduri, Xianfeng Yang, Anupam Das, Yuchen Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated reinforcement learning (FRL) is crucial for enabling collaborative learning across multiple agents without sharing raw data, thereby enhancing privacy and scalability in the decision-making process within dynamic vehicular environments. However, poisoning attacks pose a significant threat to the security and reliability of FRL-based systems, particularly in safety-critical autonomous driving, where this vulnerability remains largely unexplored. These attacks can compromise the global control model by subtly injecting malicious system parameters, leading to potential hazards. To counter these challenges, we present \alg (\underline{Sec}ure \underline{A}ggregation with \underline{p}oisoning-\underline{p}revention and historical reinforcement) as a defensive framework aimed at enhancing the robustness of FRL systems designed for safety-critical driving scenarios. \alg strategically integrates digital twins for rehearsal-based learning and leverages historical aggregated model parameters along with a selected central gradient to ensure that only benign data is aggregated, effectively mitigating the influence of malicious agents. Theoretical guarantees are provided for the convergence performance of \alg in the presence of poisoning attacks. We also validate the effectiveness of \alg using developed digital twins that model realistic highway environments to evaluate the control of autonomous vehicles under adversarial conditions.
### Title:
          WCog-VLA: A Dual-Level World-Cognitive Vision-Language-Action Model for End-to-End Autonomous Driving
 - **Authors:** Xuerun Yan, Zhexi Lian, Nuoheng Zhang, Shiyu Fang, Haoran Wang, Chen Lv, Jia Hu, Binyang Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have advanced end-to-end autonomous driving. However, existing methods either lack comprehensive world cognition or suffer from fragmented world foresight, inherently confining these models to reactive driving. To address this limitation, we propose WCog-VLA, a novel dual-level World-Cognitive VLA framework that successfully bridges semantic world forecasting with generative world evolution to achieve proactive autonomous driving. At the semantic level, WCog-VLA unifies world cognition and reasoning by incorporating 3D spatial perception and injecting agent tokens to capture the world dynamics, while concurrently enabling Game-theoretic Chain-of-Thought (Game-CoT) reasoning. At the generative level, we introduce the Aligned Decoupled Diffusion Transformer (ADDT) as a powerful generative world model that synthesizes physically-plausible joint multi-agent trajectories. Through scene representation alignment, ADDT reduces the number of denoising steps required and thus significantly accelerates inference. To facilitate strategic reasoning, we further construct a large-scale dataset featuring 85k Game-CoT annotations. Extensive experiments on the NAVSIM benchmark demonstrate that WCog-VLA achieves a State-Of-The-Art (SOTA) PDMS score of 92.9.
### Title:
          On Exploring Input Resolution Scaling For Anytime LiDAR Object Detection
 - **Authors:** Ahmet Soyyigit, Shuochao Yao, Heechul Yun
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Making tradeoffs between execution latency and result utility (i.e., anytime computing) for adapting to dynamic operational requirements has been shown to enhance the performance of cyber-physical systems. In this work, we focus on enabling anytime computing for deep neural networks (DNNs) that process LiDAR point clouds for 3D object detection. We propose a novel method that enables multi-resolution inference for models that process point clouds as pillars or voxels, allowing the input to be dynamically scaled and processed at the resolution needed to meet timing requirements. Importantly, our memory-efficient approach requires the deployment of only a single DNN model, avoiding the need to deploy multiple models, each trained for a different input resolution. We also introduce a deadline-aware scheduler that selects the highest possible resolution for any given input by accurately predicting the execution time for all possible resolutions at runtime, which is challenging due to the irregularity of LiDAR point clouds. Experimental results on the nuScenes autonomous driving dataset demonstrate that our method significantly outperforms existing anytime computing approaches for LiDAR object detection. Finally, we deploy our approach in a simulated autonomous driving system, where it consistently enables collision-free navigation while avoiding unnecessary stalls caused by environmental complexity.
### Title:
          AUTOPILOT VQA: Benchmarking Vision-Language Models for Incident-Centric Dashcam Understanding
 - **Authors:** Siddharth Damodharan, Radhika Gupta, Ali Alshami, Ryan Rabinowitz, Jugal Kalita
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Vision-Language Models, Large Language Models, and Multimodal Large Language Models have improved autonomous driving tasks such as scene understanding, decision making, trajectory prediction, and visual question answering. However, evaluating whether these models can reliably reason about safety-critical incidents remains challenging. To address this gap, we present AUTOPILOT-VQA, an incident-centric visual question answering benchmark for dashcam video understanding. The dataset evaluates different systems through structured questions designed around real-world driving incidents and near-incidents. The benchmark covers diverse safety-relevant categories, including weather and lighting conditions, traffic environment, road layout, road surface state, signage, involved entities, accident occurrence, impact location, and avoidability-related reasoning. By requiring models to answer grounded questions about both contextual scene properties and event-level incident details, AUTOPILOT-VQA moves beyond object recognition toward temporally grounded, safety-aware reasoning. The dataset is released as part of the AUTOPILOT CVPR 2026 competition and provides a standardized benchmark for assessing the reliability of autonomous driving systems in different scenarios. Our benchmark support developments for more interpretable, robust, and safety-conscious vision-language systems for real-world autonomous driving.
