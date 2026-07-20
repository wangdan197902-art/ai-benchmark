---
title: "Llama 3.1 405B vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Llama 3.1 405B and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
comparison_id: "llama-3-1-405b-vs-qwen2-5-72b"
models: ["llama-3-1-405b", "qwen2-5-72b"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "meta", "alibaba"]
---

# Llama 3.1 405B 対 Qwen2.5 72B

## モデル概要

Llama 3.1 405B and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Meta / Alibaba | 2024-07-23 / 2024-09-19 | 128K / 131K | Llama 3 Community License / Qwen License |

## ベンチマークパフォーマンス

| ベンチマーク | Llama 3.1 405B | Qwen2.5 72B | 勝者 |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 82.9 | 82.4 | A |
| GSM8K (Grade School Math 8K) | 89.2 | 88.4 | A |
| HumanEval | 89.0 | 86.6 | A |
| MATH | 73.8 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 88.6 | 86.1 | A |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Llama 3.1 405B

- ✅ MMLU score 88.6, strong knowledge reasoning.
- ✅ HumanEval 89.0, excellent code generation.
- ✅ GSM8K 89.2, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

Llama 3.1 405B and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Llama 3.1 405B ドキュメント](https://llama.meta.com/docs/)
- [Qwen2.5 72B ドキュメント](https://qwenlm.github.io/)
