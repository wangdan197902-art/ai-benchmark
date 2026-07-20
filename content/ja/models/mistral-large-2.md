---
title: "Mistral Large 2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large 2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-24
lastmod: 2024-07-24
draft: false
weight: 10
model_id: "mistral-large-2"
vendor: "mistral"
version: "large-2"
tags: ["flagship", "coding", "eu-residency"]
---

# Mistral Large 2

## モデル概要

Mistral Large 2 是 Mistral AI 旗舰模型，123B 参数，128K 上下文窗口，在代码生成、数学推理与多语言任务上表现强劲，支持欧盟数据驻留与 GDPR/ISO 27001 合规。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large-2 | 2024-07-24 | 128K | text | text | Mistral Research License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.0 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 93.0 | % | 0-shot CoT |
| MATH | 71.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.0 | % | 3-shot CoT |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 84.0, strong knowledge reasoning.
- HumanEval 92.0, excellent code generation.
- GSM8K 93.0, robust math reasoning.

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- Agent 工作流与工具调用

## 参考文献

- [Mistral Large 2 ドキュメント](https://docs.mistral.ai/)
- リリース日: 2024-07-24
- ベンダー: Mistral
