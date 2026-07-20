---
title: "Sonar Reasoning: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Reasoning performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-18
lastmod: 2024-12-18
draft: false
weight: 10
model_id: "sonar-reasoning"
vendor: "other"
version: "sonar-reasoning"
tags: ["rag", "reasoning"]
---

# Sonar Reasoning

## モデル概要

Perplexity Sonar Reasoning 推理型在线 RAG 模型, 127K 上下文, 基于 DeepSeek R1 微调, 链式思维推理。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-reasoning | 2024-12-18 | 127K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.7 | % | 5-shot |
| HumanEval | 81.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.8 | % | 0-shot CoT |
| MATH | 50.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 50.1 | % | 0-shot |
| IFEval | 83.1 | % | prompt_strict |
| ARC | 96.2 | % | challenge |
| MUSR | 69.4 | % | 0-shot |
| WinoGrande | 87.2 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 87.7, strong knowledge reasoning.
- HumanEval 81.1, excellent code generation.
- GSM8K 89.8, robust math reasoning.

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试

## 参考文献

- [Sonar Reasoning ドキュメント](https://huggingface.co/models)
- リリース日: 2024-12-18
- ベンダー: Other
