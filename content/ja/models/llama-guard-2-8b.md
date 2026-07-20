---
title: "Llama Guard 2 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama Guard 2 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-guard-2-8b"
vendor: "meta"
version: "guard-2-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama Guard 2 8B

## モデル概要

Meta Llama Guard 2 8B 内容安全分类模型, 8K 上下文, 用于检测输入输出中的有害内容。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | guard-2-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 26.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.3 | % | 0-shot CoT |
| MATH | 26.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.6 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 34.9 | % | 0-shot |
| WinoGrande | 66.5 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 26.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [Llama Guard 2 8B ドキュメント](https://llama.meta.com/docs/)
- リリース日: 2024-04-18
- ベンダー: Meta
