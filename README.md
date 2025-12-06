IPC-Benchmark v0.1
A benchmark for structural intelligence, rule discovery, and cross-domain reasoning.
📌 What is IPC-Benchmark?

IPC-Benchmark 是一个专为 结构智能（structural intelligence） 设计的评测框架，用来测量一个模型是否具备：

结构理解

跨域同构识别

最小规则重建

推理链透明性与自洽性

这些能力决定一个模型是否能够：

超越模板化 NLP

执行开放式系统建模

创造可检验的新理论

进行跨学科抽象

IPC-Benchmark 是完全开放的，任何模型（或人类）都可以参与。


Four Tracks
T1 — Structural Compression

测试模型能否从复杂文本中抽取“最小结构”、构建结构树、识别变形参数并具可逆性。

T2 — Isomorphism Detection

判断两个不同系统是否共享相同结构，并给出变量映射与不变量。

T3 — Rule Reconstruction

从观测数据反推出“最小规则集”，并预测隐藏样本。

T4 — Reasoning Transparency

评估开放问题中的推理链条、假设管理与可检验性。

📝 How to Run the Benchmark

对每个 JSON 任务，将 input 和 instructions 作为模型提示词。

固定采样参数：

temperature = 0.1–0.3

top_p = 1

将回答保存为 Markdown：
responses/T1_001/model_name.md

使用 scoring/rubric.md 给每个维度打分（0–5）。

将分数填入 score_sheet.csv 或 Markdown 模板。

计算每个 Track 的平均分和总分。

📈 Output Formats

建议保存：

模型完整回答

评分表

雷达图（四维能力）

📜 License

MIT License（建议）
