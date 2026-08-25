# learningAI · AI 学堂

面向股宇宙团队的 AI 学习课程：从大模型原理到 AI 产品落地，五讲
中文交互课件，全部免费开放。

🔗 **在线访问：** <https://bayshier.github.io/learningAI/>

📚 **入口：** 已融入[股宇宙知识库](https://bayshier.github.io/GYZApp/knowledge.html)，
在知识库首页「AI 学堂」横幅一键进入。

## 课程结构

课程体系参考 [itshen/learn-ai](https://github.com/itshen/learn-ai)
（作者洛小山的《AI 产品从入门到精通》），课件内容围绕股宇宙
产品场景重新编写，案例取自团队真实项目。

| 讲次 | 课件 | 内容 |
|------|------|------|
| 第 1 讲 | [大模型基础](slides/ch1-llm.html) | Token、下一词预测、训练三阶段、温度、幻觉成因：为什么 AI 会编造股票数据 |
| 第 2 讲 | [Prompt 与上下文工程](slides/ch2-prompt.html) | 提示词结构、少样本示例、稳定输出 JSON 行情摘要、上下文窗口、提示词注入防御 |
| 第 3 讲 | [RAG 与向量检索](slides/ch3-rag.html) | Embedding、分块、检索增强生成链路：用股宇宙知识库做证券问答 |
| 第 4 讲 | [Agent 与工具调用](slides/ch4-agent.html) | ReAct 循环、工具定义、MCP 协议：kline-mcp 行情工具实战 |
| 第 5 讲 | [AI 产品落地](slides/ch5-product.html) | 评测集、成本优化、投资建议合规红线、上线检查清单 |

从 [课程目录](index.html) 开始，或按顺序从第 1 讲看起。课件均为
单文件 HTML，本地双击即可阅读，无需服务器。

## 学习建议

- **产品与运营**：按 1 → 2 → 5 顺序，重点理解能力边界与合规
- **开发同学**：按 1 → 2 → 3 → 4 顺序，第 4 讲对应团队 kline-mcp、
  android-mcp 两个真实项目
- **所有人**：第 1 讲的「幻觉」与第 5 讲的「投资建议红线」是股宇宙
  场景下的必修内容

## 技术形态

与股宇宙知识库系统（GYZApp）保持一致：纯静态、零构建、零依赖，
HTML + 原生 JS（ES5），浅色主题（`#1a2b4a` / `#d4a644`），移动端
自适应。键盘 ←/→ 翻页，点击左右区域也可翻页。

## 致谢与协议

课程体系与教学结构来自 [itshen/learn-ai](https://github.com/itshen/learn-ai)
（AGPL-3.0，作者洛小山），在此致谢；延伸阅读推荐直接学习
[原课程](https://xueai.app)（54 个主题、180+ 页交互幻灯片）。

本项目采用 **AGPL-3.0** 协议：可免费使用、学习、改进；衍生版本
必须同样开源并保留署名；禁止用于闭源商业产品。详见
[LICENSE](LICENSE) 与 [NOTICE](NOTICE)。

---

*Copyright 2026 Easin · 股宇宙知识库系统成员站点*
