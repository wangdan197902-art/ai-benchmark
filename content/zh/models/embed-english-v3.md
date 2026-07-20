---
title: "Embed English v3：完整基准性能指南"
description: "深入分析 Embed English v3 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-01
lastmod: 2023-11-01
draft: false
weight: 10
model_id: "embed-english-v3"
vendor: "cohere"
version: "embed-english-v3"
tags: ["embed", "english"]
---

# Embed English v3

## 模型概述

Cohere Embed English v3 英文嵌入模型, 512 token 输入, 为检索/分类/聚类优化, 英文语义搜索领先。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | embed-english-v3 | 2023-11-01 | 512 | text | — | CC-BY-NC-4.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 0.0 | % | embed model - not applicable |
| HumanEval | 0.0 | pass@1 | embed model - not applicable |
| GSM8K (Grade School Math 8K) | 0.0 | % | embed model - not applicable |
| MATH | 0.0 | % | embed model - not applicable |
| BBH (BIG-Bench Hard) | 0.0 | % | embed model - not applicable |
| GPQA | 0.0 | % | embed model - not applicable |
| IFEval | 0.0 | % | embed model - not applicable |
| ARC | 0.0 | % | embed model - not applicable |
| MUSR | 0.0 | % | embed model - not applicable |
| WinoGrande | 0.0 | % | embed model - not applicable |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 0.0，知识推理偏弱。
- HumanEval 0.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 0K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Embed English v3 文档地址](https://docs.cohere.com/docs)
- 发布日期: 2023-11-01
- 厂商: Cohere
