---
title: "Mixtral 8x7B vs Mixtral 8x22B: Benchmark Comparison"
description: "Detailed comparison of Mixtral 8x7B and Mixtral 8x22B covering benchmarks, pricing, context window, and compliance."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
comparison_id: "mixtral-8x7b-vs-mixtral-8x22b"
models: ["mixtral-8x7b", "mixtral-8x22b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "mistral", "mistral"]
---

# Mixtral 8x7B 対 Mixtral 8x22B

## モデル概要

Mixtral 8x7B and Mixtral 8x22B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Mistral / Mistral | 2023-12-11 / 2024-04-10 | 32K / 64K | Apache 2.0 / Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | Mixtral 8x7B | Mixtral 8x22B | 勝者 |
|------|------|------|--------|
| ARC | 91.6 | — | A |
| BBH (BIG-Bench Hard) | 78.4 | 74.5 | A |
| GPQA | 43.0 | — | A |
| GSM8K (Grade School Math 8K) | 79.7 | 78.6 | A |
| HumanEval | 79.0 | 45.2 | A |
| IFEval | 72.1 | — | A |
| MATH | 38.0 | 46.0 | B |
| MMLU (Massive Multitask Language Understanding) | 77.2 | 77.8 | B |
| MUSR | 53.5 | — | A |
| WinoGrande | 82.0 | — | A |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Mixtral 8x7B

- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

### Mixtral 8x22B

- ✅ 采用 MoE 混合专家架构。
- ⚠️ HumanEval 45.2，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

Mixtral 8x7B and Mixtral 8x22B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Mixtral 8x7B ドキュメント](https://docs.mistral.ai/)
- [Mixtral 8x22B ドキュメント](https://docs.mistral.ai/)
