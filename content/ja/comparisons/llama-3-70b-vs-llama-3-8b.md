---
title: "Llama 3 70B vs Llama 3 8B: Benchmark Comparison"
description: "Detailed comparison of Llama 3 70B and Llama 3 8B covering benchmarks, pricing, context window, and compliance."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
comparison_id: "llama-3-70b-vs-llama-3-8b"
models: ["llama-3-70b", "llama-3-8b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "meta", "meta"]
---

# Llama 3 70B 対 Llama 3 8B

## モデル概要

Llama 3 70B and Llama 3 8B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Meta / Meta | 2024-04-18 / 2024-04-18 | 8K / 8K | Llama 3 Community License / Llama 3 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | Llama 3 70B | Llama 3 8B | 勝者 |
|------|------|------|--------|
| ARC | 93.4 | 91.2 | A |
| BBH (BIG-Bench Hard) | 77.6 | 65.0 | A |
| GPQA | 38.2 | 27.9 | A |
| GSM8K (Grade School Math 8K) | 76.2 | 56.6 | A |
| HumanEval | 73.0 | 65.0 | A |
| IFEval | 72.2 | 68.2 | A |
| MATH | 50.1 | 40.0 | A |
| MMLU (Massive Multitask Language Understanding) | 79.5 | 67.8 | A |
| MUSR | 51.2 | 46.1 | A |
| WinoGrande | 79.2 | 75.6 | A |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Llama 3 70B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

### Llama 3 8B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## 編集者コメント

Llama 3 70B and Llama 3 8B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Llama 3 70B ドキュメント](https://llama.meta.com/docs/)
- [Llama 3 8B ドキュメント](https://llama.meta.com/docs/)
