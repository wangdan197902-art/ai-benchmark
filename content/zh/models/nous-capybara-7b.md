---
title: "Nous Capybara 7B：完整基准性能指南"
description: "深入分析 Nous Capybara 7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-09-26
lastmod: 2023-09-26
draft: false
weight: 10
model_id: "nous-capybara-7b"
vendor: "other"
version: "nous-capybara-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Nous Capybara 7B

## 模型概述

NousResearch Capybara 7B 对话模型, 4K 上下文, 基于 Llama 2 微调, 改进多轮对话能力。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-capybara-7b | 2023-09-26 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.4 | % | 5-shot |
| HumanEval | 38.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.0 | % | 0-shot CoT |
| MATH | 19.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.6 | % | 3-shot CoT |
| GPQA | 31.0 | % | 0-shot |
| IFEval | 44.2 | % | prompt_strict |
| ARC | 87.0 | % | challenge |
| MUSR | 42.5 | % | 0-shot |
| WinoGrande | 77.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- HumanEval 38.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Nous Capybara 7B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-09-26
- 厂商: Other
