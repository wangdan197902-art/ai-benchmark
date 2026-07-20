---
title: "GLM-4 Plus vs DeepSeek V3: Benchmark Comparison"
description: "Detailed comparison of GLM-4 Plus and DeepSeek V3 covering benchmarks, pricing, context window, and compliance."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
comparison_id: "glm-4-plus-vs-deepseek-v3"
models: ["glm-4-plus", "deepseek-v3"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "deepseek"]
---

# GLM-4 Plus 対 DeepSeek V3

## モデル概要

GLM-4 Plus and DeepSeek V3 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 主要仕様

| ベンダー | リリース日 | コンテキストウィンドウ | ライセンス |
|---------|-------------|----------------|---------|
| Other / Deepseek | 2024-08-12 / 2024-12-26 | 131K / 64K | Proprietary / DeepSeek License |

## ベンチマークパフォーマンス

| ベンチマーク | GLM-4 Plus | DeepSeek V3 | 勝者 |
|------|------|------|--------|
| ARC | 94.5 | — | A |
| BBH (BIG-Bench Hard) | 83.6 | 84.9 | B |
| GPQA | 35.4 | — | A |
| GSM8K (Grade School Math 8K) | 81.8 | 89.3 | B |
| HumanEval | 72.7 | 82.6 | B |
| IFEval | 79.2 | — | A |
| MATH | 53.3 | 61.6 | B |
| MMLU (Massive Multitask Language Understanding) | 84.3 | 88.5 | B |
| MUSR | 51.3 | — | A |
| WinoGrande | 85.8 | — | A |

## 料金比較

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*100万トークンあたり — A / B*

## 強み & 弱み

### GLM-4 Plus

- ✅ MMLU score 84.3, strong knowledge reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### DeepSeek V3

- ✅ MMLU score 88.5, strong knowledge reasoning.
- ✅ HumanEval 82.6, excellent code generation.
- ✅ GSM8K 89.3, robust math reasoning.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

## 編集者コメント

GLM-4 Plus and DeepSeek V3 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 参考文献

- [GLM-4 Plus ドキュメント](https://huggingface.co/models)
- [DeepSeek V3 ドキュメント](https://api-docs.deepseek.com/)
