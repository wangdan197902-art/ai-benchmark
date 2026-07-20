---
title: "Gemini 1.0 Ultra: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Ultra performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-ultra"
vendor: "google"
version: "1.0-ultra"
tags: ["flagship", "multimodal", "legacy"]
---

# Gemini 1.0 Ultra

## モデル概要

Google Gemini 1.0 Ultra 旗舰模型, 32K 上下文, 在多项基准上接近 GPT-4, 多模态推理能力突出。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-ultra | 2023-12-06 | 32K | text, image | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.3 | % | 5-shot |
| HumanEval | 81.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.9 | % | 0-shot CoT |
| MATH | 57.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.8 | % | 3-shot CoT |
| GPQA | 46.9 | % | 0-shot |
| IFEval | 81.6 | % | prompt_strict |
| ARC | 95.7 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 80.4 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 80.3, strong knowledge reasoning.
- HumanEval 81.7, excellent code generation.
- GSM8K 85.9, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 参考文献

- [Gemini 1.0 Ultra ドキュメント](https://ai.google.dev/gemini-api/docs)
- リリース日: 2023-12-06
- ベンダー: Google
