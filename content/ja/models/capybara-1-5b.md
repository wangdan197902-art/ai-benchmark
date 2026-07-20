---
title: "Capybara 1.5B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Capybara 1.5B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-15
lastmod: 2023-11-15
draft: false
weight: 10
model_id: "capybara-1-5b"
vendor: "other"
version: "capybara-1-5b"
tags: ["open-weights", "self-hostable"]
---

# Capybara 1.5B

## モデル概要

IntrinsicaAI Capybara 1.5B 轻量对话模型, 4K 上下文, 1.5B 参数, 适合边缘设备对话场景。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | capybara-1-5b | 2023-11-15 | 4K | text | text | Apache 2.0 |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.7 | % | 5-shot |
| HumanEval | 30.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 28.5 | % | 0-shot CoT |
| MATH | 25.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.3 | % | 3-shot CoT |
| GPQA | 18.1 | % | 0-shot |
| IFEval | 52.4 | % | prompt_strict |
| ARC | 80.1 | % | challenge |
| MUSR | 34.0 | % | 0-shot |
| WinoGrande | 68.9 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- 可靠的通用模型。

## 弱み

- MMLU 仅 51.7，知识推理偏弱。
- HumanEval 30.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## ユースケース

- 通用对话与问答

## 参考文献

- [Capybara 1.5B ドキュメント](https://huggingface.co/models)
- リリース日: 2023-11-15
- ベンダー: Other
