---
title: "Jurassic-2 Mid: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jurassic-2 Mid performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-01-12
lastmod: 2023-01-12
draft: false
weight: 10
model_id: "j2-mid"
vendor: "other"
version: "j2-mid"
tags: ["legacy"]
---

# Jurassic-2 Mid

## モデル概要

AI21 Labs Jurassic-2 Mid 中型模型, 8K 上下文, 多语言文本生成, 适合企业级内容创作。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | j2-mid | 2023-01-12 | 8K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.9 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 33.2 | % | 0-shot CoT |
| MATH | 20.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.8 | % | 3-shot CoT |
| GPQA | 25.7 | % | 0-shot |
| IFEval | 49.8 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 32.3 | % | 0-shot |
| WinoGrande | 67.1 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- MMLU 仅 55.9，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [Jurassic-2 Mid ドキュメント](https://huggingface.co/models)
- リリース日: 2023-01-12
- ベンダー: Other
