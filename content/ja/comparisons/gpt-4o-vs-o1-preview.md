---
title: "GPT-4o vs o1 Preview: Benchmark Comparison"
description: "Detailed comparison of GPT-4o and o1 Preview covering benchmarks, pricing, context window, and compliance."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "gpt-4o-vs-o1-preview"
models: ["gpt-4o", "o1-preview"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "openai"]
---

# GPT-4o 対 o1 Preview

## モデル概要

GPT-4o and o1 Preview are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Openai / Openai | 2024-05-13 / 2024-09-12 | 128K / 128K | Proprietary / Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | GPT-4o | o1 Preview | 勝者 |
|------|------|------|--------|
| ARC | — | 96.0 | B |
| BBH (BIG-Bench Hard) | 83.1 | 84.5 | B |
| GPQA | — | 57.7 | B |
| GSM8K (Grade School Math 8K) | 95.8 | 92.5 | A |
| HumanEval | 90.2 | 90.1 | Tie |
| IFEval | — | 84.4 | B |
| MATH | 76.6 | 71.5 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 85.3 | A |
| MUSR | — | 64.1 | B |
| WinoGrande | — | 85.2 | B |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### GPT-4o

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 90.2, excellent code generation.
- ✅ GSM8K 95.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### o1 Preview

- ✅ MMLU score 85.3, strong knowledge reasoning.
- ✅ HumanEval 90.1, excellent code generation.
- ✅ GSM8K 92.5, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

GPT-4o and o1 Preview each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [GPT-4o ドキュメント](https://platform.openai.com/docs/models/gpt-4o)
- [o1 Preview ドキュメント](https://platform.openai.com/docs/models)
