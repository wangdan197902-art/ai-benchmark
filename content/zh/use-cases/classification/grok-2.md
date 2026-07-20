---
title: "文本分类 场景推荐：Grok-2"
description: "为什么 Grok-2 适合 文本分类 场景？从基准、定价与特性综合评估。"
draft: false
weight: 10
use_case_id: "classification"
model_id: "grok-2"
recommendation_score: 37
rank: 10
tags: ["use-case-model", "classification", "grok-2"]
---

# 文本分类 → Grok-2

## 场景概述

Grok-2 由 Xai 发布，是 文本分类 场景下的推荐选项之一。

## 推荐模型

| 排名 | 厂商 | 上下文窗口 | Score |
|------|--------|----------------|-------|
| #10 | Xai | 131K | 37/100 |

## 性能分析

### 基准测试表现

| 基准 | 得分 |
|------|------|
| MMLU | 87.5 |
| HUMANEVAL | 88.4 |
| GSM8K | 93.2 |
| MATH | 76.8 |
| BBH | 84.0 |

## 优势

- MMLU 得分 87.5，知识推理能力强。
- HumanEval 88.4，代码生成能力出色。
- GSM8K 93.2，数学推理稳健。
- 支持文本、图像、音频多模态输入。

## 需求

- 需要 xai 的 API 密钥
- 输入长度须在 131K 上下文窗口内
