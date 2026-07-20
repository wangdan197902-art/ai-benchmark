---
title: "High Throughput Inference Recommendation: Mixtral 8x7B"
description: "Why is Mixtral 8x7B recommended for High Throughput Inference? Comprehensive evaluation across benchmarks, pricing, and features."
draft: false
weight: 10
use_case_id: "high-throughput"
model_id: "mixtral-8x7b"
recommendation_score: 35
rank: 8
tags: ["use-case-model", "high-throughput", "mixtral-8x7b"]
---

# High Throughput Inference → Mixtral 8x7B

## Обзор сценария

Mixtral 8x7B by Mistral is a recommended option for the High Throughput Inference use case.

## Рекомендуемые модели

| Ранг | Поставщик | Окно контекста | Score |
|------|--------|----------------|-------|
| #8 | Mistral | 32K | 35/100 |

## Анализ производительности

### Производительность

| Бенчмарк | Очки |
|------|------|
| MMLU | 77.2 |
| HUMANEVAL | 79.0 |
| GSM8K | 79.7 |
| MATH | 38.0 |
| BBH | 78.4 |
| GPQA | 43.0 |

## Сильные стороны

- 采用 MoE 混合专家架构。

## Требования

- 需要 mistral 的 API 密钥
- 输入长度须在 32K 上下文窗口内
