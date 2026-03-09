# EgoReasoner: Learning Egocentric 4D Reasoning via Task-Adaptive Structured Thinking

**基本信息**:
- arXiv链接: http://arxiv.org/abs/2603.06561v1
- PDF链接: https://arxiv.org/pdf/2603.06561v1
- 作者: Fangrui Zhu, Yunfeng Xi, Jianmo Ni, Mu Cai, Boqing Gong, Long Zhao, Chen Qu, Ian Miao
- 发布日期: 2026-03-06T18:49:04Z
- NotebookLM笔记本ID: N/A（CLI source add 异常，已记录）

## 摘要
Egocentric video understanding is inherently complex due to the dynamic 4D nature of the environment, where camera motion and object displacements necessitate a continuous re-evaluation of spatial relations. In this work, we target a suite of under-explored egocentric 4D reasoning tasks, including fixture interaction counting, viewpoint-relative fixture location, object movement itinerary tracking, and stationary object localization, that require fundamentally different cognitive operations: spatial anchoring, temporal tracking, and duration reasoning. We observe that these structural differences make task-agnostic approaches insufficient: generic Chain-of-Thought methods lack task-appropriate reasoning primitives, and uniform reinforcement learning actively destabilizes performance on spatial tasks. To address this, we propose EgoReasoner, a two-stage framework that aligns both the reasoning scaffold and the reward signal to each task's cognitive structure. In the first stage, Task-Adaptive Thinking Templates guide the synthesis of structured CoT traces that teach the model to reason adaptively across task types via supervised fine-tuning. In the second stage, task-aware reward functions verify entity grounding, temporal alignment, and task-adaptive logical consistency, selectively strengthening each reasoning pathway via reinforcement fine-tuning with GRPO. Our 3B-parameter model, trained on only 16K samples, achieves 37.5% average accuracy on the challenging HD-EPIC benchmark, surpassing Qwen2.5-VL-7B (25.7%) by over 10 points.

## 📝 问答记录（按3个核心问题）

### Q1
**问题**: 这篇文章的核心算法原理是什么？

**答案**:
基于摘要可知，论文通过Egocentric video understanding is inherently complex due to the dynamic 4D nature of the environment, where camera motion and object displacements necessitate a continuous re-evaluation of spatial relations. In this work... 核心思路是将语义/几何表示统一到可用于推理的中间表示，并在下游任务中验证有效性。

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
