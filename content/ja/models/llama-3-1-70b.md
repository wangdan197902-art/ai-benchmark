---
title: "Llama 3.1 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-70b"
vendor: "meta"
version: "3.1-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.1 70B

## モデル概要

Meta Llama 3.1 70B 中端开源模型, 128K 上下文, 性能接近 GPT-4, 推理与编码能力突出。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-70b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.6 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 38.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 40.0 | % | 0-shot |
| IFEval | 73.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 81.0 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试

## 参考文献

- [Llama 3.1 70B ドキュメント](https://llama.meta.com/docs/)
- リリース日: 2024-07-23
- ベンダー: Meta
