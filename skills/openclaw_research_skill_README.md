# OpenClaw Research Skills

Spatial AGI 研究自动化技能集合。

## Skills

### spatial-agi-research

完整的Spatial AGI研究流程 - 从arXiv搜索到深度分析，每天精读5篇论文，使用research-assistant技能和NotebookLM（3个核心问题），生成论文文档和每日思考。

**功能**:
- 自动搜索arXiv最新论文
- 智能筛选最相关论文
- 并行深度分析（NotebookLM）
- 生成每日思考文档
- 自动Git提交

**使用**:
```bash
openclaw cron add "spatial-agi-research" "cron 0 7 * * *" --skill spatial-agi-research
```

## 相关仓库

- 研究产出: https://github.com/ahangchen/spatial_agi
