# Spatial AGI Research - 执行检查清单

## 📋 执行前准备

### 1. 检查代理
```bash
# 测试代理是否可用
curl -x socks5://127.0.0.1:1080 -m 5 https://www.google.com

# 如果失败，启动代理
# (根据你的代理配置启动)
```

### 2. 检查脚本
```bash
cd /home/cwh/.openclaw/workspace/scripts

# 检查research_analysis.sh是否存在
ls -la research_analysis.sh

# 检查notebooklm-proxy.sh是否存在
ls -la notebooklm-proxy.sh

# 检查执行权限
chmod +x research_analysis.sh notebooklm-proxy.sh
```

### 3. 准备目录
```bash
# 创建必要的目录
mkdir -p /home/cwh/coding/auto_blog/spatial_agi/notebooks
mkdir -p /home/cwh/coding/auto_blog/spatial_agi/papers
mkdir -p /home/cwh/coding/auto_blog/spatial_agi/daily_thinking
```

## 🔍 论文选择

### 标准筛选
- [ ] 与spatial intelligence直接相关
- [ ] 最近1-2个月发表
- [ ] 来自知名机构或作者
- [ ] 有完整的项目页面和PDF
- [ ] （可选）有代码仓库

### 优先级
1. **最重要（3-5篇）**: 完整流程 + 所有问题
2. **次要（5-7篇）**: 核心问题 + 快速分析

## ✅ 执行检查清单

### Step 1: research-assistant技能

```bash
cd /home/cwh/.openclaw/workspace/scripts

# 执行research-assistant
./research_analysis.sh \
  "论文标题" \
  "arXiv页面URL" \
  "PDF URL" \
  "[GitHub URL]"
```

**检查点**:
- [ ] NotebookLM笔记本创建成功
- [ ] arXiv页面添加成功
- [ ] PDF添加成功（可能需要1-2分钟）
- [ ] （可选）演示文稿生成中
- [ ] （可选）音频概览生成中
- [ ] 记录笔记本ID

**如果失败**:
1. 检查代理连接
2. 尝试在网页界面手动创建
3. 查看错误日志

### Step 2: 询问标准问题（7个必问）

```bash
export PROXY_HOST=127.0.0.1
export PROXY_PORT=1080
export PROXY_TYPE=socks5

cd /home/cwh/.openclaw/workspace/scripts
```

**Q1**: 核心算法流程
```bash
./notebooklm-proxy.sh ask "这篇文章的核心算法流程是怎样的？请详细描述算法的输入、处理步骤和输出。"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q2**: 改进和创新
```bash
./notebooklm-proxy.sh ask "这篇文章相比其他工作或者它的baseline有什么改进和创新？具体的技术创新点是什么？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q3**: 实验部署
```bash
./notebooklm-proxy.sh ask "这个工作的实验在什么环境部署的？部署时运行效率如何？有哪些性能指标？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q4**: 方法论和框架
```bash
./notebooklm-proxy.sh ask "使用了什么方法论和框架？为什么选择这些方法？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q5**: 实验结果
```bash
./notebooklm-proxy.sh ask "主要的实验结果和性能指标是什么？在哪些数据集上进行了测试？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q6**: 局限性
```bash
./notebooklm-proxy.sh ask "方法的局限性是什么？作者提到了哪些未来工作方向？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q7**: Spatial AGI启发
```bash
./notebooklm-proxy.sh ask "这篇文章对通用空间智能（Spatial AGI）有什么启发？有哪些可以借鉴的思想？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

### Step 3: 询问Spatial AGI问题（6个必问）

**Q8**: 空间定义
```bash
./notebooklm-proxy.sh ask "这篇文章如何理解和定义'空间'？使用了什么样的空间表示方法？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q9**: 空间关系处理
```bash
./notebooklm-proxy.sh ask "这篇文章如何处理空间关系？使用了什么技术来建模和推理空间关系？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q10**: 3D场景理解
```bash
./notebooklm-proxy.sh ask "这个工作与3D场景理解有什么关系？能否应用于3D环境？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q11**: 空间推理能力
```bash
./notebooklm-proxy.sh ask "这篇文章展示了什么样的空间推理能力？如何评估这些能力？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q12**: 通用空间智能启发
```bash
./notebooklm-proxy.sh ask "这篇文章对通用空间智能（Spatial AGI）有什么启发？有哪些可以借鉴的思想？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

**Q13**: 实际应用
```bash
./notebooklm-proxy.sh ask "这个方法可以应用到哪些实际场景？特别是机器人、AR/VR等需要空间智能的领域？"
```
- [ ] 获得完整回答
- [ ] 记录到文档

### Step 4: 自由提问（至少2个）

**示例问题**:
```bash
# Q14
./notebooklm-proxy.sh ask "实验结果中最令你惊讶的是什么？为什么？"

# Q15
./notebooklm-proxy.sh ask "如何将这个方法应用到实时系统？需要做哪些改进？"

# Q16
./notebooklm-proxy.sh ask "这篇文章的代码实现中有哪些细节值得注意？"

# Q17
./notebooklm-proxy.sh ask "与其他领域的方法（如SLAM、3D重建）相比，这篇文章的方法有什么优势？"
```

- [ ] 至少问了2个自由问题
- [ ] 记录所有回答

### Step 5: 记录笔记本ID

```bash
# 查看笔记本列表
./notebooklm-proxy.sh list

# 记录笔记本ID
echo '{
  "paper": "论文标题",
  "date": "2026-03-02",
  "notebook_id": "笔记本ID",
  "arxiv": "https://arxiv.org/abs/xxx",
  "questions_asked": 15
}' >> /home/cwh/coding/auto_blog/spatial_agi/notebooks/notebook_ids.json
```

- [ ] 记录笔记本ID
- [ ] 更新索引文件

### Step 6: 创建Markdown文档

**使用模板**: `/home/cwh/coding/auto_blog/spatial_agi/papers/EXAMPLE_full_analysis_template.md`

**必须包含的内容**:
- [ ] 基本信息（标题、链接、作者、NotebookLM ID）
- [ ] 核心问题（基于Q1回答）
- [ ] 主要方法（基于Q1回答）
- [ ] 关键创新（基于Q2回答）
- [ ] 实验结果（基于Q3, Q5回答）
- [ ] 与Spatial AGI的关系（基于Q8-Q13回答）
- [ ] 潜在应用（基于Q13回答）
- [ ] 局限性（基于Q6回答）
- [ ] **完整的NotebookLM问答记录**（所有15+问题）
- [ ] 个人思考和见解

**质量检查**:
- [ ] 文档至少500行
- [ ] 包含完整的问答记录（不总结）
- [ ] 添加了个人思考
- [ ] 保存到正确位置

**保存位置**:
```bash
/home/cwh/coding/auto_blog/spatial_agi/papers/2026-03-02_XX_paper_title.md
```

## 📊 时间记录

| 步骤 | 开始时间 | 结束时间 | 实际用时 |
|------|---------|---------|---------|
| research-assistant | | | 分钟 |
| 标准问题（7个）| | | 分钟 |
| Spatial AGI问题（6个）| | | 分钟 |
| 自由问题（2+）| | | 分钟 |
| 创建文档 | | | 分钟 |
| **总计** | | | **分钟** |

## ⚠️ 常见问题

### 1. 代理连接失败
**解决**:
```bash
# 检查代理是否启动
ps aux | grep -i proxy

# 测试代理
curl -x socks5://127.0.0.1:1080 https://www.google.com

# 如果失败，启动代理
# (根据你的配置启动)
```

### 2. PDF添加超时
**解决**:
```bash
# 方法1: 增加超时
./research_analysis.sh ... --pdf-timeout 120

# 方法2: 在网页界面手动添加
# 访问 https://notebooklm.google.com
```

### 3. NotebookLM问答无响应
**解决**:
```bash
# 检查来源是否添加成功
./notebooklm-proxy.sh source list

# 如果来源为空，重新添加
./notebooklm-proxy.sh source add <URL>
```

### 4. Gateway token不匹配
**解决**:
```bash
# 重启Gateway
openclaw gateway restart

# 检查状态
openclaw gateway status
```

## ✅ 完成检查

### 论文分析完成标准
- [ ] 使用了research-assistant技能
- [ ] NotebookLM笔记本创建成功
- [ ] 添加了至少2个来源
- [ ] 询问了所有7个标准问题
- [ ] 询问了所有6个Spatial AGI问题
- [ ] 询问了至少2个自由问题
- [ ] 创建了详细的markdown文档
- [ ] 文档包含完整的问答记录
- [ ] 文档至少500行
- [ ] 记录了笔记本ID
- [ ] 文档保存到正确位置

### 质量标准
- [ ] 问答记录完整（不总结）
- [ ] 添加了个人思考和见解
- [ ] 建立了与Spatial AGI的联系
- [ ] 提出了有价值的研究问题

## 📝 每日总结

完成所有论文后：

### 1. 更新论文列表
```bash
# 更新 /home/cwh/coding/auto_blog/spatial_agi/papers_list.md
# 添加今日分析的论文
```

### 2. 生成每日思考
```bash
# 创建 /home/cwh/coding/auto_blog/spatial_agi/daily_thinking/2026-03-02.md
# 基于所有论文的见解生成深度思考
```

### 3. 更新知识库
```bash
# 将有价值的见解添加到knowledge目录
```

### 4. 提交到git
```bash
cd /home/cwh/coding/auto_blog/spatial_agi
git add .
git commit -m "docs: 添加Spatial AGI研究 - 2026-03-02"
git push
```

## 🎯 质量指标

### 每篇论文
- 问答数量: 15+ 个
- 文档行数: 500+ 行
- 个人见解: 3+ 点
- 与Spatial AGI联系: 明确

### 每日总结
- 论文数量: 10篇
- 总问答: 150+ 个
- 思考文档: 200+ 行
- 核心发现: 3-5个

---

**记住**: 
- 质量 > 数量
- 深度 > 广度
- 完整记录 > 简单总结
