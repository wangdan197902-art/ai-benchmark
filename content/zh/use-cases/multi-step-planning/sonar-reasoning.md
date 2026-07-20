---
title: "多步规划 场景推荐：Sonar Reasoning"
description: "为什么 Sonar Reasoning 适合 多步规划 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "multi-step-planning"
model_id: "sonar-reasoning"
recommendation_score: 37
rank: 8
tags: ["use-case-model", "multi-step-planning", "sonar-reasoning"]
---

# 多步规划 → Sonar Reasoning

## 场景概述

Sonar Reasoning 由 Other 发布，是 多步规划 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #8 | Other | 127K | 37/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 87.7 |
| HUMANEVAL | 81.1 |
| GSM8K | 89.8 |
| MATH | 50.7 |
| BBH | 83.4 |
| GPQA | 50.1 |

## 优势

- MMLU 得分 87.7，知识推理能力强。
- HumanEval 81.1，代码生成能力出色。
- GSM8K 89.8，数学推理稳健。

## 需求

- 需要 other 的 API 密钥
- 输入长度须在 127K 上下文窗口内
