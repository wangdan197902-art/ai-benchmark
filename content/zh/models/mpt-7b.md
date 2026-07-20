---
title: "MPT 7B：完整基准性能指南"
description: "深入分析 MPT 7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-05-04
lastmod: 2023-05-04
draft: false
weight: 10
model_id: "mpt-7b"
vendor: "other"
version: "mpt-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# MPT 7B

## 模型概述

MosaicML MPT 7B 经济型开源模型, 2K 上下文, 7B 参数, Apache 2.0 可商用, 适合本地部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | mpt-7b | 2023-05-04 | 2K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.7 | % | 5-shot |
| HumanEval | 38.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 44.6 | % | 0-shot CoT |
| MATH | 18.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.9 | % | 3-shot CoT |
| GPQA | 34.2 | % | 0-shot |
| IFEval | 59.9 | % | prompt_strict |
| ARC | 87.5 | % | challenge |
| MUSR | 42.4 | % | 0-shot |
| WinoGrande | 65.5 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 51.7，知识推理偏弱。
- HumanEval 38.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [MPT 7B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-05-04
- 厂商: Other
