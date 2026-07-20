---
title: "高吞吐推理 场景推荐：DeepSeek V3"
description: "为什么 DeepSeek V3 适合 高吞吐推理 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "high-throughput"
model_id: "deepseek-v3"
recommendation_score: 37
rank: 1
tags: ["use-case-model", "high-throughput", "deepseek-v3"]
---

# 高吞吐推理 → DeepSeek V3

## 场景概述

DeepSeek V3 由 Deepseek 发布，是 高吞吐推理 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #1 | Deepseek | 64K | 37/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 88.5 |
| HUMANEVAL | 82.6 |
| GSM8K | 89.3 |
| MATH | 61.6 |
| BBH | 84.9 |

## 优势

- MMLU 得分 88.5，知识推理能力强。
- HumanEval 82.6，代码生成能力出色。
- GSM8K 89.3，数学推理稳健。
- 采用 MoE 混合专家架构。

## 需求

- 需要 deepseek 的 API 密钥
- 输入长度须在 64K 上下文窗口内
