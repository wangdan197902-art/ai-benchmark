---
title: "Jurassic-2 Ultra: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jurassic-2 Ultra performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-01-12
lastmod: 2023-01-12
draft: false
weight: 10
model_id: "j2-ultra"
vendor: "other"
version: "j2-ultra"
tags: ["legacy", "flagship"]
---

# Jurassic-2 Ultra

## モデル概要

AI21 Labs Jurassic-2 Ultra 旗舰模型, 8K 上下文, 在 J2 系列中性能最强, 适合复杂推理任务。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | j2-ultra | 2023-01-12 | 8K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.5 | % | 5-shot |
| HumanEval | 50.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 30.3 | % | 0-shot CoT |
| MATH | 27.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.9 | % | 3-shot CoT |
| GPQA | 28.7 | % | 0-shot |
| IFEval | 47.9 | % | prompt_strict |
| ARC | 82.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

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

- Agent 工作流与工具调用

## 参考文献

- [Jurassic-2 Ultra ドキュメント](https://huggingface.co/models)
- リリース日: 2023-01-12
- ベンダー: Other
