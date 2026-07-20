---
title: "WizardLM Team WizardLM 2 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of WizardLM Team WizardLM 2 8x22B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "wizardlmteam-wizardlm-2-8x22b"
vendor: "other"
version: "wizardlmteam-wizardlm-2-8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# WizardLM Team WizardLM 2 8x22B

## モデル概要

WizardLM Team WizardLM 2 8x22B 官方发布版, 64K 上下文, 基于 Mixtral 8x22B 微调, Arena 上接近 GPT-4。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlmteam-wizardlm-2-8x22b | 2024-04-15 | 65K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.2 | % | 5-shot |
| HumanEval | 70.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.9 | % | 0-shot CoT |
| MATH | 37.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.0 | % | 3-shot CoT |
| GPQA | 41.4 | % | 0-shot |
| IFEval | 70.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 56.8 | % | 0-shot |
| WinoGrande | 83.5 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 采用 MoE 混合专家架构。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试

## 参考文献

- [WizardLM Team WizardLM 2 8x22B ドキュメント](https://huggingface.co/models)
- リリース日: 2024-04-15
- ベンダー: Other
