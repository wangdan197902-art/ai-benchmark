---
title: "Qwen2 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2 72B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
model_id: "qwen2-72b"
vendor: "alibaba"
version: "2-72b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2 72B

## モデル概要

阿里巴巴 Qwen2 72B 开源旗舰, 131K 上下文, 多语言/数学/编程能力突出, 性能接近 GPT-4。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2-72b | 2024-06-07 | 131K | text | text | Qwen License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.2 | % | 5-shot |
| HumanEval | 76.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 87.0 | % | 0-shot CoT |
| MATH | 71.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 53.6 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 94.4 | % | challenge |
| MUSR | 68.9 | % | 0-shot |
| WinoGrande | 82.5 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 80.2, strong knowledge reasoning.
- GSM8K 87.0, robust math reasoning.

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试

## 参考文献

- [Qwen2 72B ドキュメント](https://qwenlm.github.io/)
- リリース日: 2024-06-07
- ベンダー: Alibaba
