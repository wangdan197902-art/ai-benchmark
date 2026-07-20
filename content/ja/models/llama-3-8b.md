---
title: "Llama 3 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-3-8b"
vendor: "meta"
version: "3-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3 8B

## モデル概要

Meta Llama 3 8B 经济型开源模型, 8K 上下文, 8B 参数, 性能超越 Llama 2 13B, 适合本地部署。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 67.8 | % | 5-shot |
| HumanEval | 65.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.6 | % | 0-shot CoT |
| MATH | 40.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.0 | % | 3-shot CoT |
| GPQA | 27.9 | % | 0-shot |
| IFEval | 68.2 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 46.1 | % | 0-shot |
| WinoGrande | 75.6 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [Llama 3 8B ドキュメント](https://llama.meta.com/docs/)
- リリース日: 2024-04-18
- ベンダー: Meta
