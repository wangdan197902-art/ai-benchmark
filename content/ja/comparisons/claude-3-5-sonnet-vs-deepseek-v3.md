---
title: "Claude 3.5 Sonnet vs DeepSeek V3: Benchmark Comparison"
description: "Detailed comparison of Claude 3.5 Sonnet and DeepSeek V3 covering benchmarks, pricing, context window, and compliance."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
comparison_id: "claude-3-5-sonnet-vs-deepseek-v3"
models: ["claude-3-5-sonnet", "deepseek-v3"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "deepseek"]
---

# Claude 3.5 Sonnet 対 DeepSeek V3

## モデル概要

Claude 3.5 Sonnet and DeepSeek V3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Anthropic / Deepseek | 2024-06-20 / 2024-12-26 | 200K / 64K | Proprietary / DeepSeek License |

## ベンチマークパフォーマンス

| ベンチマーク | Claude 3.5 Sonnet | DeepSeek V3 | 勝者 |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 84.5 | 84.9 | Tie |
| GSM8K (Grade School Math 8K) | 96.4 | 89.3 | A |
| HumanEval | 92.0 | 82.6 | A |
| MATH | 71.1 | 61.6 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 88.5 | Tie |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Claude 3.5 Sonnet

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 96.4, robust math reasoning.
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### DeepSeek V3

- ✅ MMLU score 88.5, strong knowledge reasoning.
- ✅ HumanEval 82.6, excellent code generation.
- ✅ GSM8K 89.3, robust math reasoning.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

Claude 3.5 Sonnet and DeepSeek V3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Claude 3.5 Sonnet ドキュメント](https://docs.anthropic.com/claude/docs)
- [DeepSeek V3 ドキュメント](https://api-docs.deepseek.com/)
