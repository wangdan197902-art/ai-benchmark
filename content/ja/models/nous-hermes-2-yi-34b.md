---
title: "Nous Hermes 2 Yi 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Yi 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-22
lastmod: 2024-01-22
draft: false
weight: 10
model_id: "nous-hermes-2-yi-34b"
vendor: "other"
version: "nous-hermes-2-yi-34b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Nous Hermes 2 Yi 34B

## モデル概要

NousResearch Hermes 2 Yi 34B 微调模型, 4K 上下文, 基于 Yi 34B, 改进多语言与指令遵循。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-yi-34b | 2024-01-22 | 4K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 73.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.7 | % | 0-shot CoT |
| MATH | 44.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.6 | % | 3-shot CoT |
| GPQA | 39.0 | % | 0-shot |
| IFEval | 68.3 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 48.8 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

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

- 代码生成与调试

## 参考文献

- [Nous Hermes 2 Yi 34B ドキュメント](https://huggingface.co/models)
- リリース日: 2024-01-22
- ベンダー: Other
