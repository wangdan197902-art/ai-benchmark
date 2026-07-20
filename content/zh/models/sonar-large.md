---
title: "Sonar Large：完整基准性能指南"
description: "深入分析 Sonar Large 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "sonar-large"
vendor: "other"
version: "sonar-large"
tags: ["rag", "enterprise"]
---

# Sonar Large

## 模型概述

Perplexity Sonar Large 在线 RAG 模型, 128K 上下文, 基于 Llama 3 70B 微调, 集成实时搜索。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-large | 2024-05-13 | 128K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.5 | % | 5-shot |
| HumanEval | 80.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 51.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 41.6 | % | 0-shot |
| IFEval | 74.9 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 65.6 | % | 0-shot |
| WinoGrande | 81.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 82.5，知识推理能力强。
- HumanEval 80.4，代码生成能力出色。
- 企业级合规认证。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 企业客户支持

## 参考文献

- [Sonar Large 文档地址](https://huggingface.co/models)
- 发布日期: 2024-05-13
- 厂商: Other
