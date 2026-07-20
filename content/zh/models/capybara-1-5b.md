---
title: "Capybara 1.5B：完整基准性能指南"
description: "深入分析 Capybara 1.5B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-15
lastmod: 2023-11-15
draft: false
weight: 10
model_id: "capybara-1-5b"
vendor: "other"
version: "capybara-1-5b"
tags: ["open-weights", "self-hostable"]
---

# Capybara 1.5B

## 模型概述

IntrinsicaAI Capybara 1.5B 轻量对话模型, 4K 上下文, 1.5B 参数, 适合边缘设备对话场景。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | capybara-1-5b | 2023-11-15 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.7 | % | 5-shot |
| HumanEval | 30.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 28.5 | % | 0-shot CoT |
| MATH | 25.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.3 | % | 3-shot CoT |
| GPQA | 18.1 | % | 0-shot |
| IFEval | 52.4 | % | prompt_strict |
| ARC | 80.1 | % | challenge |
| MUSR | 34.0 | % | 0-shot |
| WinoGrande | 68.9 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 51.7，知识推理偏弱。
- HumanEval 30.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Capybara 1.5B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-11-15
- 厂商: Other
