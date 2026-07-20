---
title: "代码审查 场景推荐：Codestral Mamba"
description: "为什么 Codestral Mamba 适合 代码审查 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "code-review"
model_id: "codestral-mamba"
recommendation_score: 51
rank: 4
tags: ["use-case-model", "code-review", "codestral-mamba"]
---

# 代码审查 → Codestral Mamba

## 场景概述

Codestral Mamba 由 Mistral 发布，是 代码审查 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #4 | Mistral | 256K | 51/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 59.3 |
| HUMANEVAL | 86.2 |
| GSM8K | 67.8 |
| MATH | 28.1 |
| BBH | 66.0 |
| GPQA | 36.3 |

## 优势

- HumanEval 86.2，代码生成能力出色。
- 上下文窗口 256K，支持长文本。

## 需求

- 需要 mistral 的 API 密钥
- 输入长度须在 256K 上下文窗口内
