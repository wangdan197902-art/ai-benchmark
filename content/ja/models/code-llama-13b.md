---
title: "Code Llama 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-13b"
vendor: "meta"
version: "code-llama-13b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 13B

## モデル概要

Meta Code Llama 13B 代码专用开源模型, 16K 上下文, 13B 参数, 适合中等规模代码任务部署。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-13b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.9 | % | 5-shot |
| HumanEval | 69.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.9 | % | 0-shot CoT |
| MATH | 37.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.0 | % | 3-shot CoT |
| GPQA | 36.4 | % | 0-shot |
| IFEval | 50.1 | % | prompt_strict |
| ARC | 87.8 | % | challenge |
| MUSR | 47.3 | % | 0-shot |
| WinoGrande | 70.4 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## ユースケース

- 代码生成与调试

## 参考文献

- [Code Llama 13B ドキュメント](https://llama.meta.com/docs/)
- リリース日: 2023-08-24
- ベンダー: Meta
