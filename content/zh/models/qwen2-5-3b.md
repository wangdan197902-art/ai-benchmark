---
title: "Qwen2.5 3B：完整基准性能指南"
description: "深入分析 Qwen2.5 3B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-3b"
vendor: "alibaba"
version: "2.5-3b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 3B

## 模型概述

阿里巴巴 Qwen2.5 3B 轻量开源模型, 32K 上下文, 3B 参数, 适合移动设备与边缘部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-3b | 2024-09-19 | 32K | text | text | Qwen License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.8 | % | 5-shot |
| HumanEval | 49.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.3 | % | 0-shot CoT |
| MATH | 17.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.8 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 56.0 | % | prompt_strict |
| ARC | 76.5 | % | challenge |
| MUSR | 23.3 | % | 0-shot |
| WinoGrande | 61.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 56.8，知识推理偏弱。
- HumanEval 49.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [Qwen2.5 3B 文档地址](https://qwenlm.github.io/)
- 发布日期: 2024-09-19
- 厂商: Alibaba
