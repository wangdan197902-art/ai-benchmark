---
title: "Zephyr 7B Alpha：完整基准性能指南"
description: "深入分析 Zephyr 7B Alpha 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-10-04
lastmod: 2023-10-04
draft: false
weight: 10
model_id: "zephyr-7b-alpha"
vendor: "other"
version: "zephyr-7b-alpha"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Zephyr 7B Alpha

## 模型概述

HuggingFaceH4 Zephyr 7B Alpha 首版对话模型, 4K 上下文, 基于 Mistral 7B SFT 微调。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-7b-alpha | 2023-10-04 | 4K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.2 | % | 5-shot |
| HumanEval | 35.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.8 | % | 0-shot CoT |
| MATH | 23.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.7 | % | 3-shot CoT |
| GPQA | 34.3 | % | 0-shot |
| IFEval | 50.9 | % | prompt_strict |
| ARC | 84.7 | % | challenge |
| MUSR | 40.5 | % | 0-shot |
| WinoGrande | 75.0 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 52.2，知识推理偏弱。
- HumanEval 35.9，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Zephyr 7B Alpha 文档地址](https://huggingface.co/models)
- 发布日期: 2023-10-04
- 厂商: Other
