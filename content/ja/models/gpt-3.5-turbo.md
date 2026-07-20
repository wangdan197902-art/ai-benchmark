---
title: "GPT-3.5 Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-01
lastmod: 2023-03-01
draft: false
weight: 10
model_id: "gpt-3.5-turbo"
vendor: "openai"
version: "3.5-turbo"
tags: ["legacy", "realtime"]
---

# GPT-3.5 Turbo

## モデル概要

OpenAI GPT-3.5 Turbo 经济型模型, 16K 上下文, 速度快价格低, 适合对话与通用任务。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo | 2023-03-01 | 16K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.1 | % | 5-shot |
| HumanEval | 51.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.3 | % | 0-shot CoT |
| MATH | 17.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 22.4 | % | 0-shot |
| IFEval | 57.4 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 29.2 | % | 0-shot |
| WinoGrande | 76.7 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [GPT-3.5 Turbo ドキュメント](https://platform.openai.com/docs/models)
- リリース日: 2023-03-01
- ベンダー: Openai
