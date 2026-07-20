---
title: "高吞吐推理 场景推荐：DBRX Instruct"
description: "为什么 DBRX Instruct 适合 高吞吐推理 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "high-throughput"
model_id: "dbrx-instruct"
recommendation_score: 36
rank: 2
tags: ["use-case-model", "high-throughput", "dbrx-instruct"]
---

# 高吞吐推理 → DBRX Instruct

## 场景概述

DBRX Instruct 由 Other 发布，是 高吞吐推理 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #2 | Other | 32K | 36/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 81.3 |
| HUMANEVAL | 72.8 |
| GSM8K | 78.7 |
| MATH | 50.1 |
| BBH | 71.7 |
| GPQA | 34.7 |

## 优势

- MMLU 得分 81.3，知识推理能力强。
- 采用 MoE 混合专家架构。

## 需求

- 需要 other 的 API 密钥
- 输入长度须在 32K 上下文窗口内
