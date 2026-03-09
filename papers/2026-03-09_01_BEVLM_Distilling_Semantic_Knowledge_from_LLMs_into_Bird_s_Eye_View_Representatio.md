# BEVLM: Distilling Semantic Knowledge from LLMs into Bird's-Eye View Representations

**基本信息**:
- arXiv链接: http://arxiv.org/abs/2603.06576v1
- PDF链接: https://arxiv.org/pdf/2603.06576v1
- 作者: Thomas Monninger, Shaoyuan Xie, Qi Alfred Chen, Sihao Ding
- 发布日期: 2026-03-06T18:59:55Z
- NotebookLM笔记本ID: N/A（CLI source add 异常，已记录）

## 摘要
The integration of Large Language Models (LLMs) into autonomous driving has attracted growing interest for their strong reasoning and semantic understanding abilities, which are essential for handling complex decision-making and long-tail scenarios. However, existing methods typically feed LLMs with tokens from multi-view and multi-frame images independently, leading to redundant computation and limited spatial consistency. This separation in visual processing hinders accurate 3D spatial reasoning and fails to maintain geometric coherence across views. On the other hand, Bird's-Eye View (BEV) representations learned from geometrically annotated tasks (e.g., object detection) provide spatial structure but lack the semantic richness of foundation vision encoders. To bridge this gap, we propose BEVLM, a framework that connects a spatially consistent and semantically distilled BEV representation with LLMs. Through extensive experiments, we show that BEVLM enables LLMs to reason more effectively in cross-view driving scenes, improving accuracy by 46%, by leveraging BEV features as unified inputs. Furthermore, by distilling semantic knowledge from LLMs into BEV representations, BEVLM significantly improves closed-loop end-to-end driving performance by 29% in safety-critical scenarios.

## 📝 问答记录（按3个核心问题）

### Q1
**问题**: 这篇文章的核心算法原理是什么？

**答案**:
基于摘要可知，论文通过The integration of Large Language Models (LLMs) into autonomous driving has attracted growing interest for their strong reasoning and semantic understanding abilities, which are essential for handling complex decision-ma... 核心思路是将语义/几何表示统一到可用于推理的中间表示，并在下游任务中验证有效性。

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
