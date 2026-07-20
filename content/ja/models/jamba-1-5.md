---
title: "Jamba 1.5: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jamba 1.5 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-07
lastmod: 2024-08-07
draft: false
weight: 10
model_id: "jamba-1-5"
vendor: "other"
version: "jamba-1-5"
tags: ["open-weights", "long-context"]
---

# Jamba 1.5

## モデル概要

AI21 Labs Jamba 1.5 基础模型系列, 256K 上下文, 混合 SSM-Transformer 架构, 高效长上下文处理。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-1-5 | 2024-08-07 | 256K | text | text | Jamba Open Model License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.5 | % | 5-shot |
| HumanEval | 75.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.8 | % | 0-shot CoT |
| MATH | 48.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.3 | % | 3-shot CoT |
| GPQA | 30.2 | % | 0-shot |
| IFEval | 70.8 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 57.1 | % | 0-shot |
| WinoGrande | 84.5 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 上下文窗口 256K，支持长文本。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 长文档摘要

## 参考文献

- [Jamba 1.5 ドキュメント](https://huggingface.co/models)
- リリース日: 2024-08-07
- ベンダー: Other
