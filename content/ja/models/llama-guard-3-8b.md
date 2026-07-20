---
title: "Llama Guard 3 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama Guard 3 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-guard-3-8b"
vendor: "meta"
version: "guard-3-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama Guard 3 8B

## モデル概要

Meta Llama Guard 3 8B 内容安全分类模型, 128K 上下文, 支持 MLCommons 安全分类标准。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | guard-3-8b | 2024-07-23 | 128K | text | text | Llama 3.2 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 40.1 | % | 5-shot |
| HumanEval | 28.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 30.9 | % | 0-shot CoT |
| MATH | 8.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 44.1 | % | 3-shot CoT |
| GPQA | 27.9 | % | 0-shot |
| IFEval | 50.0 | % | prompt_strict |
| ARC | 76.0 | % | challenge |
| MUSR | 22.8 | % | 0-shot |
| WinoGrande | 68.0 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- MMLU 仅 40.1，知识推理偏弱。
- HumanEval 28.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## ユースケース

- 通用对话与问答

## 参考文献

- [Llama Guard 3 8B ドキュメント](https://llama.meta.com/docs/)
- リリース日: 2024-07-23
- ベンダー: Meta
