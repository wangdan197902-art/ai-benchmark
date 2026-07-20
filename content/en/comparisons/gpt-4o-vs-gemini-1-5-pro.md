---
title: "GPT-4o vs Gemini 1.5 Pro: Benchmark Comparison"
description: "Detailed comparison between GPT-4o and Gemini 1.5 Pro covering benchmarks, pricing, context window, and compliance."
date: 2026-07-18
lastmod: 2026-07-18
draft: false
weight: 20
comparison_id: "gpt-4o-vs-gemini-1-5-pro"
models: ["gpt-4o", "gemini-1-5-pro"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section for recommendation."
tags: ["comparison", "openai", "google"]
faqs:
  - question: "Placeholder question 1?"
    answer: "Replace with generated FAQ from body."
  - question: "Placeholder question 2?"
    answer: "Replace with generated FAQ from body."
---

# GPT-4o vs Gemini 1.5 Pro

## GPT-4o vs Claude 3.5 Sonnet — 对比分析

两个模型均为 2024 年中发布的旗舰 LLM。GPT-4o 在多模态与音频处理上更具优势，Claude 3.5 Sonnet 在编程任务上略胜一筹。

### 关键规格
| 规格 | GPT-4o | Claude 3.5 Sonnet |
|------|--------|--------------------|
| 厂商 | OpenAI | Anthropic |
| 发布日期 | 2024-05-13 | 2024-06-20 |
| 上下文窗口 | 128,000 tokens | 200,000 tokens |
| 输入模态 | 文本、图像、音频 | 文本、图像 |
| 输出模态 | 文本、音频 | 文本 |

### 性能对比
| 基准 | GPT-4o | Claude 3.5 Sonnet | 胜者 |
|------|--------|--------------------|------|
| MMLU (%) | 88.7 | 88.7 | 平局 |
| HumanEval (pass@1) | 90.2 | 92.0 | Claude |
| GSM8K (%) | 95.8 | 96.4 | Claude |
| MATH (%) | 76.6 | 71.1 | GPT-4o |
| BBH (%) | 83.1 | 84.5 | Claude |

### 价格对比
GPT-4o 输入 $2.50/Mtok，输出 $10/Mtok；Claude 输入 $3.00/Mtok，输出 $15/Mtok。GPT-4o 整体便宜约 30%，但 Claude 在缓存读取上有显著优势（$0.30 vs $1.25）。

### 优劣分析

**GPT-4o 优势：**
- 原生多模态支持包括音频输入输出（独有）
- 基础输入输出价格更低
- HIPAA 合规，适用于医疗场景
- 低延迟，适合实时语音应用

**GPT-4o 劣势：**
- 上下文窗口较小（128K vs 200K）
- 在 HumanEval 和 BBH 上落后于 Claude

**Claude 3.5 Sonnet 优势：**
- HumanEval 行业领先（92.0 pass@1）
- 200K 上下文窗口
- 缓存读取更便宜（$0.30 vs $1.25）
- 强大的工具调用与代理可靠性

**Claude 3.5 Sonnet 劣势：**
- 不支持音频模态
- 基础输入输出价格更高
- 不支持 HIPAA 合规

### 编辑点评
选择 Claude 用于代码生成与学术问答；选择 GPT-4o 用于多模态与日常对话。生产环境中，许多团队会并行使用两个模型，将编程任务路由到 Claude，多模态/语音任务路由到 GPT-4o。
