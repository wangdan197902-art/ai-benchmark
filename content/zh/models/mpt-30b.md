---
title: "MPT 30B：完整基准性能指南"
description: "深入分析 MPT 30B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-06-22
lastmod: 2023-06-22
draft: false
weight: 10
model_id: "mpt-30b"
vendor: "other"
version: "mpt-30b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# MPT 30B

## 模型概述

MosaicML MPT 30B 开源模型, 8K 上下文, 300 亿参数, 改进长上下文处理, Apache 2.0 可商用。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | mpt-30b | 2023-06-22 | 8K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.2 | % | 5-shot |
| HumanEval | 49.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 21.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 24.2 | % | 0-shot |
| IFEval | 51.2 | % | prompt_strict |
| ARC | 80.7 | % | challenge |
| MUSR | 28.9 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 55.2，知识推理偏弱。
- HumanEval 49.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [MPT 30B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-06-22
- 厂商: Other
