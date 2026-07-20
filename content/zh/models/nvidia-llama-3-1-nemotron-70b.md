---
title: "NVIDIA Llama 3.1 Nemotron 70B：完整基准性能指南"
description: "深入分析 NVIDIA Llama 3.1 Nemotron 70B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "nvidia-llama-3-1-nemotron-70b"
vendor: "other"
version: "nvidia-llama-3-1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# NVIDIA Llama 3.1 Nemotron 70B

## 模型概述

NVIDIA Llama 3.1 Nemotron 70B, 131K 上下文, NVIDIA 优化 Llama 3.1, 在 Arena 上接近 GPT-4o。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nvidia-llama-3-1-nemotron-70b | 2024-10-17 | 131K | text | text | Llama 3.1 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.4 | % | 5-shot |
| HumanEval | 66.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.8 | % | 0-shot CoT |
| MATH | 40.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.6 | % | 3-shot CoT |
| GPQA | 37.6 | % | 0-shot |
| IFEval | 69.6 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 47.7 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 80.4，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [NVIDIA Llama 3.1 Nemotron 70B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-10-17
- 厂商: Other
