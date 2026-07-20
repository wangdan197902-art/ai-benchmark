---
title: "高吞吐推理 场景推荐：DBRX Base"
description: "为什么 DBRX Base 适合 高吞吐推理 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "high-throughput"
model_id: "dbrx-base"
recommendation_score: 35
rank: 4
tags: ["use-case-model", "high-throughput", "dbrx-base"]
---

# 高吞吐推理 → DBRX Base

## 场景概述

DBRX Base 由 Other 发布，是 高吞吐推理 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #4 | Other | 32K | 35/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 79.9 |
| HUMANEVAL | 72.1 |
| GSM8K | 75.4 |
| MATH | 36.0 |
| BBH | 72.3 |
| GPQA | 39.3 |

## 优势

- 采用 MoE 混合专家架构。

## 需求

- 需要 other 的 API 密钥
- 输入长度须在 32K 上下文窗口内
