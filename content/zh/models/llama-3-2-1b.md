---
title: "Llama 3.2 1B：完整基准性能指南"
description: "深入分析 Llama 3.2 1B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-1b"
vendor: "meta"
version: "3.2-1b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.2 1B

## 模型概述

Meta Llama 3.2 1B 超轻量开源模型, 128K 上下文, 1B 参数, 适合资源受限设备与离线部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-1b | 2024-09-25 | 128K | text | text | Llama 3.2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 48.6 | % | 5-shot |
| HumanEval | 29.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.9 | % | 0-shot CoT |
| MATH | 11.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 38.8 | % | 3-shot CoT |
| GPQA | 22.6 | % | 0-shot |
| IFEval | 44.1 | % | prompt_strict |
| ARC | 75.9 | % | challenge |
| MUSR | 26.6 | % | 0-shot |
| WinoGrande | 64.0 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 48.6，知识推理偏弱。
- HumanEval 29.9，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [Llama 3.2 1B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-09-25
- 厂商: Meta
