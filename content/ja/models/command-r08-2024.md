---
title: "Command R (08-2024): Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R (08-2024) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r08-2024"
vendor: "cohere"
version: "r08-2024"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R (08-2024)

## モデル概要

Cohere Command R 08-2024 版本, 128K 上下文, 改进 RAG 与工具调用能力, 支持结构化输出。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r08-2024 | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.8 | % | 5-shot |
| HumanEval | 73.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.7 | % | 0-shot CoT |
| MATH | 47.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.8 | % | 3-shot CoT |
| GPQA | 44.6 | % | 0-shot |
| IFEval | 70.3 | % | prompt_strict |
| ARC | 94.4 | % | challenge |
| MUSR | 49.1 | % | 0-shot |
| WinoGrande | 79.3 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 企业级合规认证。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 企业客户支持

## 参考文献

- [Command R (08-2024) ドキュメント](https://docs.cohere.com/docs)
- リリース日: 2024-08-13
- ベンダー: Cohere
