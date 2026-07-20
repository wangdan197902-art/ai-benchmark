---
title: "Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "llama-3-1-nemotron-70b"
vendor: "meta"
version: "3.1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 Nemotron 70B

## モデル概要

Meta/NVIDIA Llama 3.1 Nemotron 70B, 128K 上下文, NVIDIA 优化版本, 在 Arena 排行榜上接近 GPT-4o。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-nemotron-70b | 2024-10-17 | 128K | text | text | Llama 3.1 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.5 | % | 5-shot |
| HumanEval | 79.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.6 | % | 0-shot CoT |
| MATH | 40.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 42.6 | % | 0-shot |
| IFEval | 74.5 | % | prompt_strict |
| ARC | 93.7 | % | challenge |
| MUSR | 54.1 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 81.5, strong knowledge reasoning.

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试

## 参考文献

- [Llama 3.1 Nemotron 70B ドキュメント](https://llama.meta.com/docs/)
- リリース日: 2024-10-17
- ベンダー: Meta
