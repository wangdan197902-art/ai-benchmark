---
title: "Code Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "code-bison"
vendor: "google"
version: "code-bison"
tags: ["coding", "legacy"]
---

# Code Bison

## モデル概要

Google Vertex AI Code Bison 代码生成模型, 基于 PaLM 2, 8K 上下文, 支持多语言代码生成与补全。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | code-bison | 2023-05-10 | 8K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.0 | % | 5-shot |
| HumanEval | 76.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.0 | % | 0-shot CoT |
| MATH | 34.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.4 | % | 3-shot CoT |
| GPQA | 29.1 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 86.1 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## ユースケース

- 代码生成与调试

## 参考文献

- [Code Bison ドキュメント](https://ai.google.dev/gemini-api/docs)
- リリース日: 2023-05-10
- ベンダー: Google
