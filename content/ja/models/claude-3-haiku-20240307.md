---
title: "Claude 3 Haiku (2024-03-07): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Haiku (2024-03-07) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
model_id: "claude-3-haiku-20240307"
vendor: "anthropic"
version: "3-haiku-20240307"
tags: ["realtime"]
---

# Claude 3 Haiku (2024-03-07)

## モデル概要

Anthropic Claude 3 Haiku 2024-03-07 快照版本, 200K 上下文, 最快响应速度的经济型模型。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-haiku-20240307 | 2024-03-07 | 200K | text, image | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.1 | % | 5-shot |
| HumanEval | 74.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.5 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.2 | % | 3-shot CoT |
| GPQA | 39.6 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 51.0 | % | 0-shot |
| WinoGrande | 79.5 | % | 0-shot |

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

- [Claude 3 Haiku (2024-03-07) ドキュメント](https://docs.anthropic.com/claude/docs)
- リリース日: 2024-03-07
- ベンダー: Anthropic
