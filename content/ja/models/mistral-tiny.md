---
title: "Mistral Tiny: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Tiny performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-tiny"
vendor: "mistral"
version: "tiny"
tags: ["realtime", "legacy"]
---

# Mistral Tiny

## モデル概要

Mistral AI Tiny 经济型模型, 32K 上下文, 基于 Mistral 7B, 价格最低, 适合简单任务。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | tiny | 2024-02-26 | 32K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 54.2 | % | 5-shot |
| HumanEval | 45.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 57.2 | % | 0-shot CoT |
| MATH | 16.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.3 | % | 3-shot CoT |
| GPQA | 28.7 | % | 0-shot |
| IFEval | 51.7 | % | prompt_strict |
| ARC | 82.4 | % | challenge |
| MUSR | 41.4 | % | 0-shot |
| WinoGrande | 66.6 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- MMLU 仅 54.2，知识推理偏弱。
- HumanEval 45.8，代码能力较弱。
- 闭源专有模型，不支持自托管。

## ユースケース

- 通用对话与问答

## 参考文献

- [Mistral Tiny ドキュメント](https://docs.mistral.ai/)
- リリース日: 2024-02-26
- ベンダー: Mistral
