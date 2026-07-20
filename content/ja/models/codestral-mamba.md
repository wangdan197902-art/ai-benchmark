---
title: "Codestral Mamba: Complete Benchmark Performance Guide"
description: "In-depth analysis of Codestral Mamba performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-16
lastmod: 2024-07-16
draft: false
weight: 10
model_id: "codestral-mamba"
vendor: "mistral"
version: "codestral-mamba"
tags: ["coding", "open-weights", "long-context"]
---

# Codestral Mamba

## モデル概要

Mistral Codestral Mamba 7B 代码模型, 256K 上下文, 基于 Mamba 架构, 线性时间复杂度适合长序列。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral-mamba | 2024-07-16 | 256K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 59.3 | % | 5-shot |
| HumanEval | 86.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 67.8 | % | 0-shot CoT |
| MATH | 28.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 65.5 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- HumanEval 86.2, excellent code generation.
- 上下文窗口 256K，支持长文本。

## 弱み

- MMLU 仅 59.3，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 长文档摘要

## 参考文献

- [Codestral Mamba ドキュメント](https://docs.mistral.ai/)
- リリース日: 2024-07-16
- ベンダー: Mistral
