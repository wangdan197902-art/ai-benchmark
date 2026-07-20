---
title: "Sonar Huge: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Huge performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "sonar-huge"
vendor: "other"
version: "sonar-huge"
tags: ["rag", "enterprise", "reasoning"]
---

# Sonar Huge

## モデル概要

Perplexity Sonar Huge 旗舰在线 RAG 模型, 127K 上下文, 基于 Llama 3.1 405B 微调, 推理能力最强。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-huge | 2024-08-13 | 127K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.0 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 90.4 | % | 0-shot CoT |
| MATH | 46.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.6 | % | 3-shot CoT |
| GPQA | 46.7 | % | 0-shot |
| IFEval | 78.7 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 55.4 | % | 0-shot |
| WinoGrande | 87.7 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 81.0, strong knowledge reasoning.
- GSM8K 90.4, robust math reasoning.
- 企业级合规认证。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 企业客户支持

## 参考文献

- [Sonar Huge ドキュメント](https://huggingface.co/models)
- リリース日: 2024-08-13
- ベンダー: Other
