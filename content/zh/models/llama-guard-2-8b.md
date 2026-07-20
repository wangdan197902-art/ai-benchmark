---
title: "Llama Guard 2 8B：完整基准性能指南"
description: "深入分析 Llama Guard 2 8B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-guard-2-8b"
vendor: "meta"
version: "guard-2-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama Guard 2 8B

## 模型概述

Meta Llama Guard 2 8B 内容安全分类模型, 8K 上下文, 用于检测输入输出中的有害内容。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | guard-2-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 26.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.3 | % | 0-shot CoT |
| MATH | 26.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.6 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 34.9 | % | 0-shot |
| WinoGrande | 66.5 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 26.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Llama Guard 2 8B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-04-18
- 厂商: Meta
