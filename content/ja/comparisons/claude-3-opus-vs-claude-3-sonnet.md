---
title: "Claude 3 Opus vs Claude 3 Sonnet: Benchmark Comparison"
description: "Detailed comparison of Claude 3 Opus and Claude 3 Sonnet covering benchmarks, pricing, context window, and compliance."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
comparison_id: "claude-3-opus-vs-claude-3-sonnet"
models: ["claude-3-opus", "claude-3-sonnet"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "anthropic"]
---

# Claude 3 Opus 対 Claude 3 Sonnet

## モデル概要

Claude 3 Opus and Claude 3 Sonnet are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Anthropic / Anthropic | 2024-03-04 / 2024-03-04 | 200K / 200K | Proprietary / Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | Claude 3 Opus | Claude 3 Sonnet | 勝者 |
|------|------|------|--------|
| ARC | 94.5 | 94.8 | Tie |
| BBH (BIG-Bench Hard) | 81.6 | 76.1 | A |
| GPQA | 46.0 | 35.9 | A |
| GSM8K (Grade School Math 8K) | 91.8 | 84.0 | A |
| HumanEval | 83.3 | 74.5 | A |
| IFEval | 79.2 | 74.3 | A |
| MATH | 42.7 | 42.4 | Tie |
| MMLU (Massive Multitask Language Understanding) | 81.2 | 81.5 | Tie |
| MUSR | 53.3 | 64.1 | B |
| WinoGrande | 81.9 | 83.8 | B |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### Claude 3 Opus

- ✅ MMLU score 81.2, strong knowledge reasoning.
- ✅ HumanEval 83.3, excellent code generation.
- ✅ GSM8K 91.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3 Sonnet

- ✅ MMLU score 81.5, strong knowledge reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

Claude 3 Opus and Claude 3 Sonnet each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [Claude 3 Opus ドキュメント](https://docs.anthropic.com/claude/docs)
- [Claude 3 Sonnet ドキュメント](https://docs.anthropic.com/claude/docs)
