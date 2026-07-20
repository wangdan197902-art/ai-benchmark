---
title: "Gemini 1.5 Pro vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Gemini 1.5 Pro and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-02-15
lastmod: 2024-02-15
draft: false
weight: 10
comparison_id: "gemini-1-5-pro-vs-qwen2-5-72b"
models: ["gemini-1-5-pro", "qwen2-5-72b"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "google", "alibaba"]
---

# Gemini 1.5 Pro 対 Qwen2.5 72B

## モデル概要

Gemini 1.5 Pro and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Google / Alibaba | 2024-02-15 / 2024-09-19 | 2000K / 131K | Proprietary / Qwen License |

## ベンチマークパフォーマンス

| ベンチマーク | Gemini 1.5 Pro | Qwen2.5 72B | 勝者 |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 84.0 | 82.4 | A |
| GSM8K (Grade School Math 8K) | 91.7 | 88.4 | A |
| HumanEval | 71.9 | 86.6 | B |
| MATH | 58.5 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 85.9 | 86.1 | Tie |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Gemini 1.5 Pro

- ✅ MMLU score 85.9, strong knowledge reasoning.
- ✅ GSM8K 91.7, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 2000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

Gemini 1.5 Pro and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Gemini 1.5 Pro ドキュメント](https://ai.google.dev/gemini-api/docs)
- [Qwen2.5 72B ドキュメント](https://qwenlm.github.io/)
