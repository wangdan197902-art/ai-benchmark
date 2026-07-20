---
title: "Nous Hermes 2 Mixtral 8x7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Mixtral 8x7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-mixtral-8x7b"
vendor: "other"
version: "nous-hermes-2-mixtral-8x7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Mixtral 8x7B

## モデル概要

NousResearch Hermes 2 Mixtral 8x7B 微调模型, 32K 上下文, 基于 Mixtral 8x7B, 改进指令遵循能力。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-mixtral-8x7b | 2024-02-19 | 32K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.4 | % | 5-shot |
| HumanEval | 78.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 42.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.4 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.4 | % | 0-shot |
| WinoGrande | 82.1 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 81.4, strong knowledge reasoning.

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试

## 参考文献

- [Nous Hermes 2 Mixtral 8x7B ドキュメント](https://huggingface.co/models)
- リリース日: 2024-02-19
- ベンダー: Other
