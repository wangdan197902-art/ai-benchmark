---
title: "Qwen1.5 72B：完整基准性能指南"
description: "深入分析 Qwen1.5 72B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
model_id: "qwen1-5-72b"
vendor: "alibaba"
version: "1.5-72b"
tags: ["open-weights", "chinese"]
---

# Qwen1.5 72B

## 模型概述

阿里巴巴 Qwen1.5 72B 开源模型, 32K 上下文, 中文理解与生成能力突出, 适合企业部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 1.5-72b | 2024-02-25 | 32K | text | text | Qwen License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.3 | % | 5-shot |
| HumanEval | 65.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 37.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.5 | % | 3-shot CoT |
| GPQA | 39.8 | % | 0-shot |
| IFEval | 76.4 | % | prompt_strict |
| ARC | 92.6 | % | challenge |
| MUSR | 50.8 | % | 0-shot |
| WinoGrande | 83.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 81.3，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [Qwen1.5 72B 文档地址](https://qwenlm.github.io/)
- 发布日期: 2024-02-25
- 厂商: Alibaba
