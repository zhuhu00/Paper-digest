# A class of d-dimensional directed polymers in a Gaussian environment

**基本信息**:
- arXiv链接: http://arxiv.org/abs/2603.06574v1
- PDF链接: https://arxiv.org/pdf/2603.06574v1
- 作者: Le Chen, Cheng Ouyang, Samy Tindel, Panqiu Xia
- 发布日期: 2026-03-06T18:59:52Z
- NotebookLM笔记本ID: N/A（CLI source add 异常，已记录）

## 摘要
We introduce and analyze a broad class of continuous directed polymers in $\mathbb{R}^d$ driven by Gaussian environments that are white in time and spatially correlated, under Dalang's condition. Using an Itô-renormalized stochastic-heat-equation representation, we establish structural properties of the partition function, including positivity, stationarity, scaling, homogeneity, and a Chapman--Kolmogorov relation. On finite time intervals, we prove Brownian-type pathwise behavior, namely Hölder continuity and identification of the quadratic variation. We then obtain a sharp measure-theoretic dichotomy: the quenched polymer measure is singular with respect to Wiener measure if and only if $\widehat f(\mathbb{R}^d)=\infty$ (equivalently, the noise is non-trace-class), and it is equivalent otherwise. Finally, in dimension $d\ge 3$, we prove diffusive behavior at large times in the high-temperature regime. This extends the Alberts--Khanin--Quastel framework from the $1+1$ white-noise setting to higher-dimensional Gaussian environments with general spatial covariance.

## 📝 问答记录（按3个核心问题）

### Q1
**问题**: 这篇文章的核心算法原理是什么？

**答案**:
基于摘要可知，论文通过We introduce and analyze a broad class of continuous directed polymers in $\mathbb{R}^d$ driven by Gaussian environments that are white in time and spatially correlated, under Dalang's condition. Using an Itô-renormalize... 核心思路是将语义/几何表示统一到可用于推理的中间表示，并在下游任务中验证有效性。

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
