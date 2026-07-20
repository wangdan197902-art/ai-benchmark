---
title: "高吞吐推理 场景推荐：Jamba 1.5 Large"
description: "为什么 Jamba 1.5 Large 适合 高吞吐推理 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "high-throughput"
model_id: "jamba-1-5-large"
recommendation_score: 36
rank: 3
tags: ["use-case-model", "high-throughput", "jamba-1-5-large"]
---

# 高吞吐推理 → Jamba 1.5 Large

## 场景概述

Jamba 1.5 Large 由 Other 发布，是 高吞吐推理 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #3 | Other | 256K | 36/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 84.3 |
| HUMANEVAL | 73.7 |
| GSM8K | 83.5 |
| MATH | 60.0 |
| BBH | 82.8 |
| GPQA | 50.8 |

## 优势

- MMLU 得分 84.3，知识推理能力强。
- 上下文窗口 256K，支持长文本。
- 采用 MoE 混合专家架构。

## 需求

- 需要 other 的 API 密钥
- 输入长度须在 256K 上下文窗口内
