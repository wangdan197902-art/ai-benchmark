---
title: "Nous Hermes 2 Solar 10.7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Solar 10.7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-solar-10-7b"
vendor: "other"
version: "nous-hermes-2-solar-10-7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Solar 10.7B

## モデル概要

NousResearch Hermes 2 Solar 10.7B 微调模型, 4K 上下文, 基于 Solar 10.7B, 性能接近 Llama 2 70B。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-solar-10-7b | 2024-02-19 | 4K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.4 | % | 5-shot |
| HumanEval | 59.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 37.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 39.6 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [Nous Hermes 2 Solar 10.7B ドキュメント](https://huggingface.co/models)
- リリース日: 2024-02-19
- ベンダー: Other
