---
title: "高吞吐推理 场景推荐：Mixtral 8x7B"
description: "为什么 Mixtral 8x7B 适合 高吞吐推理 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "high-throughput"
model_id: "mixtral-8x7b"
recommendation_score: 35
rank: 8
tags: ["use-case-model", "high-throughput", "mixtral-8x7b"]
---

# 高吞吐推理 → Mixtral 8x7B

## 场景概述

Mixtral 8x7B 由 Mistral 发布，是 高吞吐推理 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #8 | Mistral | 32K | 35/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 77.2 |
| HUMANEVAL | 79.0 |
| GSM8K | 79.7 |
| MATH | 38.0 |
| BBH | 78.4 |
| GPQA | 43.0 |

## 优势

- 采用 MoE 混合专家架构。

## 需求

- 需要 mistral 的 API 密钥
- 输入长度须在 32K 上下文窗口内
