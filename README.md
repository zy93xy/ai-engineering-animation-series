# ai-engineering-animation-series
AI 大模型工程化可视化动画合集｜Manim 源码，6 大章节：提示词工程、Agent 系列、大模型概念、RAG 知识库、Prompt 判断、微调


# AI大模型工程化可视化动画系列
> B站配套技术教学视频仓库 | Manim 科技动画源码
面向程序员、AI开发学习者，用动画可视化讲解大模型工程化知识。

## 📚 内容章节
合集一共6大模块，持续更新：
1. **提示词工程**：Prompt编写思路、框架、最佳实践
2. **Agent系列**：智能体架构、规划、工具调用、记忆机制
3. **大模型概念**：基础原理、Transformer、词向量等基础概念
4. **RAG-知识库**：向量检索、Milvus、稀疏/稠密检索、Rerank
5. **Prompt判断**：提示注入检测、输入校验、安全判断
6. **微调**：LoRA、全参数微调，适用场景与工程取舍

### 当前已完成
- Agent架构拆解｜从原理到工程落地

### 待更新清单
- Milvus向量数据库四层架构
- RAG混合检索（稀疏检索/稠密检索/Rerank精排）
- 提示词工程底层逻辑
- 大模型基础概念
- Prompt安全与提示注入判断
- 大模型微调原理：LoRA vs 全参数微调

## 📂 仓库目录结构

ai-engineering-animation-series/
├── manim/                # Manim 动画源脚本
│   ├── agent/
│   ├── rag/
│   ├── prompt-eng/
│   ├── prompt-check/
│   ├── llm-basic/
│   └── finetune/
├── script/               # 视频分镜 + 旁白文稿
├── docs/                 # 配套学习讲义、资料
└── assets/               # 动画素材、配色规范



## ⚙️ 环境依赖
Python >=3.11
Manim Community

```bash
# 安装依赖
pip install manim


manim -pqh manim/agent/agent_architecture.py AgentFullScene
## 🎬 视频观看地址

B 站合集页：【填入你的 B 站合集链接】
当前视频：图解 AI Agent 架构｜从原理到工程落地 【BV 号】


## 📜 License

MIT License，可自由学习使用；二次发布请注明来源。

## ⭐ 支持

如果项目对你有帮助，欢迎 Star。
有问题欢迎在 B 站评论区或仓库 Issue 讨论。
