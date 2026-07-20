---
title: "MPT 30B: Complete Benchmark Performance Guide"
description: "In-depth analysis of MPT 30B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-06-22
lastmod: 2023-06-22
draft: false
weight: 10
model_id: "mpt-30b"
vendor: "other"
version: "mpt-30b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# MPT 30B

## モデル概要

MosaicML MPT 30B 开源模型, 8K 上下文, 300 亿参数, 改进长上下文处理, Apache 2.0 可商用。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | mpt-30b | 2023-06-22 | 8K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.2 | % | 5-shot |
| HumanEval | 49.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 21.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 24.2 | % | 0-shot |
| IFEval | 51.2 | % | prompt_strict |
| ARC | 80.7 | % | challenge |
| MUSR | 28.9 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- MMLU 仅 55.2，知识推理偏弱。
- HumanEval 49.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [MPT 30B ドキュメント](https://huggingface.co/models)
- リリース日: 2023-06-22
- ベンダー: Other
