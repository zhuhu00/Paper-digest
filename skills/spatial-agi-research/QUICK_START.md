# Spatial AGI Research Skill - 快速开始指南

## 🎯 目标

使用research-assistant技能和NotebookLM深度分析Spatial AGI论文，为每篇论文创建详细的markdown文档。

## 📋 完整流程（必须按顺序执行）

### Step 1: 搜索论文
```bash
cd ~/.openclaw/workspace/scripts
python3 search_arxiv.py "all:spatial+all:intelligence" 20
```

### Step 2: 筛选论文
选择10篇最有价值的论文，记录：
- 论文标题
- arXiv链接
- PDF链接
- 代码仓库（如有）

### Step 3: 使用research-assistant技能（**必须**）

**对于每篇论文，执行以下命令**：

```bash
cd ~/.openclaw/workspace/scripts

# 完整的research-assistant流程
./research_analysis.sh \
  "<论文标题>" \
  "<arXiv页面URL>" \
  "<PDF URL>" \
  "[GitHub URL]"
```

**示例**：
```bash
./research_analysis.sh \
  "SPATIALALIGN: Aligning Dynamic Spatial Relationships in Video Generation" \
  "https://arxiv.org/abs/2602.22745v1" \
  "https://arxiv.org/pdf/2602.22745v1" \
  "https://github.com/xxx/spatialalign"
```

**这会自动执行**：
1. ✅ 创建NotebookLM笔记本
2. ✅ 添加来源（arXiv页面 + PDF + GitHub）
3. ✅ 生成演示文稿（可选）
4. ✅ 生成音频概览（可选）

### Step 4: 使用NotebookLM询问问题（**必须**）

**标准问题集（7个必问）**：

```bash
export PROXY_HOST=127.0.0.1
export PROXY_PORT=1080
export PROXY_TYPE=socks5

# Q1
./notebooklm-proxy.sh ask "这篇文章的核心算法流程是怎样的？"

# Q2
./notebooklm-proxy.sh ask "相比其他工作有什么改进和创新？"

# Q3
./notebooklm-proxy.sh ask "实验在什么环境部署，运行效率如何？"

# Q4
./notebooklm-proxy.sh ask "使用了什么方法论和框架？"

# Q5
./notebooklm-proxy.sh ask "主要的实验结果和性能指标是什么？"

# Q6
./notebooklm-proxy.sh ask "方法的局限性是什么？未来工作方向？"

# Q7
./notebooklm-proxy.sh ask "这篇文章对Spatial AGI有什么启发？"
```

**Spatial AGI定制问题（6个必问）**：

```bash
# Q8
./notebooklm-proxy.sh ask "如何理解和定义'空间'？使用什么空间表示方法？"

# Q9
./notebooklm-proxy.sh ask "如何处理空间关系？使用什么技术建模和推理？"

# Q10
./notebooklm-proxy.sh ask "与3D场景理解有什么关系？能否应用于3D环境？"

# Q11
./notebooklm-proxy.sh ask "展示了什么样的空间推理能力？如何评估？"

# Q12
./notebooklm-proxy.sh ask "对通用空间智能有什么启发？哪些思想可借鉴？"

# Q13
./notebooklm-proxy.sh ask "可以应用到哪些实际场景（机器人、AR/VR等）？"
```

**可选问题（根据兴趣）**：

```bash
# Q14
./notebooklm-proxy.sh ask "实验结果中最令你惊讶的是什么？"

# Q15
./notebooklm-proxy.sh ask "如何应用到实时系统？需要哪些改进？"

# 更多自由提问...
```

### Step 5: 创建Markdown文档（**必须**）

**使用模板**：
- 模板位置：`/home/cwh/coding/auto_blog/spatial_agi/papers/EXAMPLE_full_analysis_template.md`
- 参考这个1542行的完整示例

**必须包含的内容**：
1. ✅ 基本信息（标题、链接、作者、NotebookLM ID）
2. ✅ 核心问题（基于NotebookLM回答）
3. ✅ 主要方法（基于NotebookLM回答）
4. ✅ 关键创新（基于NotebookLM回答）
5. ✅ 实验结果（基于NotebookLM回答）
6. ✅ 与Spatial AGI的关系（基于NotebookLM回答）
7. ✅ 潜在应用（基于NotebookLM回答）
8. ✅ **完整的NotebookLM问答记录**（所有13+问题的完整回答）
9. ✅ 个人思考和见解

**保存位置**：
```bash
/home/cwh/coding/auto_blog/spatial_agi/papers/YYYY-MM-DD_XX_paper_title.md
```

### Step 6: 生成每日思考

综合所有论文的见解，生成深度思考文档。

## ✅ 质量检查清单

在完成每篇论文分析后，检查：

- [ ] 使用了research-assistant技能
- [ ] 创建了NotebookLM笔记本
- [ ] 添加了至少2个来源（arXiv页面 + PDF）
- [ ] 询问了所有7个标准问题
- [ ] 询问了所有6个Spatial AGI问题
- [ ] 询问了额外的感兴趣问题
- [ ] 创建了markdown文档
- [ ] 包含完整的NotebookLM问答记录
- [ ] 添加了个人思考和见解
- [ ] 文档至少500行
- [ ] 记录了NotebookLM笔记本ID

## 🔧 常用命令速查

### NotebookLM操作

```bash
# 查看所有笔记本
PROXY_HOST=127.0.0.1 PROXY_PORT=1080 PROXY_TYPE=socks5 \
  ./notebooklm-proxy.sh list

# 查看当前笔记本的来源
PROXY_HOST=127.0.0.1 PROXY_PORT=1080 PROXY_TYPE=socks5 \
  ./notebooklm-proxy.sh source list

# 查看artifacts状态
PROXY_HOST=127.0.0.1 PROXY_PORT=1080 PROXY_TYPE=socks5 \
  ./notebooklm-proxy.sh artifact list

# 下载演示文稿
PROXY_HOST=127.0.0.1 PROXY_PORT=1080 PROXY_TYPE=socks5 \
  ./notebooklm-proxy.sh download slide-deck

# 下载音频
PROXY_HOST=127.0.0.1 PROXY_PORT=1080 PROXY_TYPE=socks5 \
  ./notebooklm-proxy.sh download audio
```

### 网页界面

如果命令行工具遇到问题，可以直接访问：
- **NotebookLM**: https://notebooklm.google.com
- 在网页界面手动创建笔记本、添加来源、生成artifacts

## ⚠️ 注意事项

### 1. 代理配置
- 必须启动代理：`socks5://127.0.0.1:1080`
- 测试代理：`curl -x socks5://127.0.0.1:1080 https://google.com`

### 2. 时间管理
- 每篇论文：5-10分钟（NotebookLM） + 10-20分钟（文档编写）
- 10篇论文：总计约3-5小时
- 建议分批处理：每批3-5篇

### 3. PDF添加超时
- PDF文件较大，添加可能需要1-2分钟
- 如果超时，可以：
  - 在网页界面手动添加
  - 使用`--pdf-timeout 120`增加超时

### 4. Gateway问题
- 如果Gateway有token不匹配问题，定时任务可能无法执行
- 需要修复：`openclaw gateway restart`

## 📊 时间估算

| 步骤 | 时间/论文 | 10篇总计 |
|------|----------|---------|
| 搜索论文 | 5分钟 | 5分钟 |
| 筛选论文 | 10分钟 | 10分钟 |
| research-assistant | 5分钟 | 50分钟 |
| 询问问题 | 5分钟 | 50分钟 |
| 创建文档 | 15分钟 | 150分钟 |
| 生成思考 | 20分钟 | 20分钟 |
| **总计** | **~50分钟** | **~4.5小时** |

## 🎓 最佳实践

1. **优先级管理**
   - 最重要的3-5篇：完整流程 + 所有问题
   - 其他论文：快速分析 + 核心问题

2. **问题策略**
   - 先问标准问题，建立基础理解
   - 再问Spatial AGI问题，建立领域联系
   - 最后自由提问，深入感兴趣方向

3. **文档质量**
   - 包含完整的NotebookLM问答
   - 添加个人思考和见解
   - 建立论文之间的联系

4. **持续改进**
   - 根据使用经验调整问题集
   - 优化文档模板
   - 积累领域知识

## 📚 参考资源

- **Skill文档**: `~/.openclaw/workspace/skills/spatial-agi-research/SKILL.md`
- **示例文档**: `/home/cwh/coding/auto_blog/spatial_agi/papers/EXAMPLE_full_analysis_template.md`
- **research-assistant技能**: `~/.openclaw/workspace/skills/research-assistant/SKILL.md`
- **NotebookLM网页**: https://notebooklm.google.com

## 💡 提示

- ✅ **必须**使用research-assistant技能
- ✅ **必须**询问所有标准问题和Spatial AGI问题
- ✅ **必须**创建详细的markdown文档
- ✅ **应该**问更多你感兴趣的问题
- ✅ **应该**添加个人思考和见解
- ⭕ 演示文稿和音频是可选的

---

**记住**: 目标是深度理解论文与Spatial AGI的关系，而不是简单的摘要。使用NotebookLM获得深入见解，并用markdown文档记录完整的分析过程。
