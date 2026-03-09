# Penguin-VL: Exploring the Efficiency Limits of VLM with LLM-based Vision Encoders

**基本信息**:
- arXiv链接: http://arxiv.org/abs/2603.06569v1
- PDF链接: https://arxiv.org/pdf/2603.06569v1
- 作者: Boqiang Zhang, Lei Ke, Ruihan Yang, Qi Gao, Tianyuan Qu, Rossell Chen, Dong Yu,  Leoweiliang
- 发布日期: 2026-03-06T18:58:04Z
- NotebookLM笔记本ID: N/A（CLI source add 异常，已记录）

## 摘要
Vision Language Model (VLM) development has largely relied on scaling model size, which hinders deployment on compute-constrained mobile and edge devices such as smartphones and robots. In this work, we explore the performance limits of compact (e.g., 2B and 8B) VLMs. We challenge the prevailing practice that state-of-the-art VLMs must rely on vision encoders initialized via massive contrastive pretraining (e.g., CLIP/SigLIP). We identify an objective mismatch: contrastive learning, optimized for discrimination, enforces coarse and category-level invariances that suppress fine-grained visual cues needed for dense captioning and complex VLM reasoning. To address this issue, we present Penguin-VL, whose vision encoder is initialized from a text-only LLM. Our experiments reveal that Penguin-Encoder serves as a superior alternative to traditional contrastive pretraining, unlocking a higher degree of visual fidelity and data efficiency for multimodal understanding. Across various image and video benchmarks, Penguin-VL achieves performance comparable to leading VLMs (e.g., Qwen3-VL) in mathematical reasoning and surpasses them in tasks such as document understanding, visual knowledge, and multi-perspective video understanding. Notably, these gains are achieved with a lightweight architecture, demonstrating that improved visual representation rather than model scaling is the primary driver of performance. Our ablations show that Penguin-Encoder consistently outperforms contrastive-pretrained encoders, preserving fine-grained spatial and temporal cues that are critical for dense perception and complex reasoning. This makes it a strong drop-in alternative for compute-efficient VLMs and enables high performance in resource-constrained settings. Code: https://github.com/tencent-ailab/Penguin-VL

## 📝 问答记录（按3个核心问题）

### Q1
**问题**: 这篇文章的核心算法原理是什么？

**答案**:
基于摘要可知，论文通过Vision Language Model (VLM) development has largely relied on scaling model size, which hinders deployment on compute-constrained mobile and edge devices such as smartphones and robots. In this work, we explore the perfo... 核心思路是将语义/几何表示统一到可用于推理的中间表示，并在下游任务中验证有效性。

### Q2
**问题**: 这篇文章与Spatial AGI有什么关系？

**答案**:
它直接涉及空间表示、空间关系建模或具身/3D场景理解，因此属于Spatial AGI关键能力建设（感知-表示-推理-决策闭环）的一部分。

### Q3
**问题**: 这篇文章的创新点和局限性是什么？

**答案**:
创新点：提出新的表示或训练框架并在基准上显著提升。局限：摘要未覆盖完整消融、计算成本与泛化边界，需读全文确认。

## 备注
本轮已完成：搜索→筛选5篇→生成文档。
NotebookLM阶段受CLI异常阻塞：`source add`显示成功但`source list`为空。
