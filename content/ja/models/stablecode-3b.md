---
title: "StableCode 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableCode 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablecode-3b"
vendor: "other"
version: "stablecode-3b"
tags: ["open-weights", "coding", "self-hostable", "long-context"]
---

# StableCode 3B

## モデル概要

Stability AI StableCode 3B 代码专用模型, 100K 上下文, 3B 参数, 支持多种编程语言代码补全。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablecode-3b | 2024-01-19 | 100K | text | text | Stability AI Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.4 | % | 5-shot |
| HumanEval | 77.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.5 | % | 0-shot CoT |
| MATH | 31.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.4 | % | 3-shot CoT |
| GPQA | 24.5 | % | 0-shot |
| IFEval | 51.8 | % | prompt_strict |
| ARC | 86.4 | % | challenge |
| MUSR | 51.8 | % | 0-shot |
| WinoGrande | 70.9 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 上下文窗口 100K，支持长文本。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 长文档摘要

## 参考文献

- [StableCode 3B ドキュメント](https://huggingface.co/models)
- リリース日: 2024-01-19
- ベンダー: Other
