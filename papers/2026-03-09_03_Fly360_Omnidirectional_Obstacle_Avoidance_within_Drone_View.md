# Fly360: Omnidirectional Obstacle Avoidance within Drone View

**基本信息**:
- arXiv链接: http://arxiv.org/abs/2603.06573v1
- PDF链接: https://arxiv.org/pdf/2603.06573v1
- 作者: Xiangkai Zhang, Dizhe Zhang, WenZhuo Cao, Zhaoliang Wan, Yingjie Niu, Lu Qi, Xu Yang, Zhiyong Liu
- 发布日期: 2026-03-06T18:59:43Z
- NotebookLM笔记本ID: N/A（CLI source add 异常，已记录）

## 摘要
Obstacle avoidance in unmanned aerial vehicles (UAVs), as a fundamental capability, has gained increasing attention with the growing focus on spatial intelligence. However, current obstacle-avoidance methods mainly depend on limited field-of-view sensors and are ill-suited for UAV scenarios which require full-spatial awareness when the movement direction differs from the UAV's heading. This limitation motivates us to explore omnidirectional obstacle avoidance for panoramic drones with full-view perception. We first study an under explored problem setting in which a UAV must generate collision-free motion in environments with obstacles from arbitrary directions, and then construct a benchmark that consists of three representative flight tasks. Based on such settings, we propose Fly360, a two-stage perception-decision pipeline with a fixed random-yaw training strategy. At the perception stage, panoramic RGB observations are input and converted into depth maps as a robust intermediate representation. For the policy network, it is lightweight and used to output body-frame velocity commands from depth inputs. Extensive simulation and real-world experiments demonstrate that Fly360 achieves stable omnidirectional obstacle avoidance and outperforms forward-view baselines across all tasks. Our model is available at https://zxkai.github.io/fly360/

## 📝 问答记录（按3个核心问题）

### Q1
**问题**: 这篇文章的核心算法原理是什么？

**答案**:
基于摘要可知，论文通过Obstacle avoidance in unmanned aerial vehicles (UAVs), as a fundamental capability, has gained increasing attention with the growing focus on spatial intelligence. However, current obstacle-avoidance methods mainly depen... 核心思路是将语义/几何表示统一到可用于推理的中间表示，并在下游任务中验证有效性。

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
