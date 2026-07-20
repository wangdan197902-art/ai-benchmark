---
title: "DeepSeek Math 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Math 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-06
lastmod: 2024-02-06
draft: false
weight: 10
model_id: "deepseek-math-7b"
vendor: "deepseek"
version: "math-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# DeepSeek Math 7B

## モデル概要

DeepSeek Math 7B 数学专用开源模型, 4K 上下文, 在 MATH 基准上达到 64.7%, 7B 规模数学模型领先。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | math-7b | 2024-02-06 | 4K | text | text | DeepSeek License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.3 | % | 5-shot |
| HumanEval | 54.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.1 | % | 0-shot CoT |
| MATH | 53.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.9 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 61.1 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

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

- [DeepSeek Math 7B ドキュメント](https://api-docs.deepseek.com/)
- リリース日: 2024-02-06
- ベンダー: Deepseek
