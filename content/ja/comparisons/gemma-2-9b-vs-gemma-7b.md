---
title: "Gemma 2 9B vs Gemma 7B: Benchmark Comparison"
description: "Detailed comparison of Gemma 2 9B and Gemma 7B covering benchmarks, pricing, context window, and compliance."
date: 2024-06-27
lastmod: 2024-06-27
draft: false
weight: 10
comparison_id: "gemma-2-9b-vs-gemma-7b"
models: ["gemma-2-9b", "gemma-7b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "google", "google"]
---

# Gemma 2 9B 対 Gemma 7B

## モデル概要

Gemma 2 9B and Gemma 7B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Google / Google | 2024-06-27 / 2024-02-21 | 8K / 8K | Gemma License / Gemma License |

## ベンチマークパフォーマンス

| ベンチマーク | Gemma 2 9B | Gemma 7B | 勝者 |
|------|------|------|--------|
| ARC | 90.3 | 88.4 | A |
| BBH (BIG-Bench Hard) | 66.7 | 65.7 | A |
| GPQA | 30.3 | 37.1 | B |
| GSM8K (Grade School Math 8K) | 64.3 | 63.6 | A |
| HumanEval | 60.9 | 61.0 | Tie |
| IFEval | 64.3 | 66.9 | B |
| MATH | 28.9 | 25.7 | A |
| MMLU (Massive Multitask Language Understanding) | 64.3 | 69.6 | B |
| MUSR | 44.1 | 36.2 | A |
| WinoGrande | 72.5 | 74.1 | B |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Gemma 2 9B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

### Gemma 7B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## 編集者コメント

Gemma 2 9B and Gemma 7B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Gemma 2 9B ドキュメント](https://ai.google.dev/gemma/docs)
- [Gemma 7B ドキュメント](https://ai.google.dev/gemma/docs)
