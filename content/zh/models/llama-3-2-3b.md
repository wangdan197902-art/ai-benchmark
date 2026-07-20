---
title: "Llama 3.2 3B：完整基准性能指南"
description: "深入分析 Llama 3.2 3B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-3b"
vendor: "meta"
version: "3.2-3b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.2 3B

## 模型概述

Meta Llama 3.2 3B 轻量开源模型, 128K 上下文, 3B 参数, 适合移动设备与边缘部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-3b | 2024-09-25 | 128K | text | text | Llama 3.2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.5 | % | 5-shot |
| HumanEval | 42.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.4 | % | 0-shot CoT |
| MATH | 10.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 46.0 | % | 3-shot CoT |
| GPQA | 18.8 | % | 0-shot |
| IFEval | 48.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 29.3 | % | 0-shot |
| WinoGrande | 67.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 52.5，知识推理偏弱。
- HumanEval 42.5，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [Llama 3.2 3B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-09-25
- 厂商: Meta
