---
title: "DeepSeek V2: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek V2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-07
lastmod: 2024-05-07
draft: false
weight: 10
model_id: "deepseek-v2"
vendor: "deepseek"
version: "v2"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V2

## モデル概要

DeepSeek V2 开源 MoE 模型, 总参 236B/活跃 21B, 32K 上下文, 首创 MLA 注意力机制, 性价比突出。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v2 | 2024-05-07 | 32K | text | text | DeepSeek License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.2 | % | 5-shot |
| HumanEval | 75.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 35.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.5 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 78.6 | % | prompt_strict |
| ARC | 92.1 | % | challenge |
| MUSR | 53.4 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

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

- [DeepSeek V2 ドキュメント](https://api-docs.deepseek.com/)
- リリース日: 2024-05-07
- ベンダー: Deepseek
