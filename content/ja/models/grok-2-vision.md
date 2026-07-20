---
title: "Grok-2 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok-2 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2-vision"
vendor: "xai"
version: "2-vision"
tags: ["multimodal"]
---

# Grok-2 Vision

## モデル概要

xAI Grok-2 Vision 多模态模型, 32K 上下文, 支持图像理解, 适合视觉问答与多模态推理。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2-vision | 2024-08-13 | 32K | text, image | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.4 | % | 5-shot |
| HumanEval | 84.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.4 | % | 0-shot CoT |
| MATH | 41.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 43.8 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 87.5 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 83.4, strong knowledge reasoning.
- HumanEval 84.2, excellent code generation.
- 支持文本、图像、音频多模态输入。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 视觉与图像理解

## 参考文献

- [Grok-2 Vision ドキュメント](https://docs.x.ai/)
- リリース日: 2024-08-13
- ベンダー: Xai
