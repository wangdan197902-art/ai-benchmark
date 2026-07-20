---
title: "Falcon 40B：完整基准性能指南"
description: "深入分析 Falcon 40B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-05-25
lastmod: 2023-05-25
draft: false
weight: 10
model_id: "falcon-40b"
vendor: "other"
version: "falcon-40b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Falcon 40B

## 模型概述

TII Falcon 40B 中型开源模型, 2K 上下文, 400 亿参数, 在 40B 规模上曾领先 Llama 2 70B。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | falcon-40b | 2023-05-25 | 2K | text | text | TII Falcon LLM License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.7 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 61.3 | % | 0-shot CoT |
| MATH | 21.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.6 | % | 3-shot CoT |
| GPQA | 21.1 | % | 0-shot |
| IFEval | 57.2 | % | prompt_strict |
| ARC | 82.9 | % | challenge |
| MUSR | 38.1 | % | 0-shot |
| WinoGrande | 65.6 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 56.7，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Falcon 40B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-05-25
- 厂商: Other
