---
title: "GLM-4 Plus: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 Plus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-plus"
vendor: "other"
version: "glm-4-plus"
tags: ["flagship", "chinese", "multimodal"]
---

# GLM-4 Plus

## モデル概要

清华智谱 GLM-4 Plus 旗舰模型, 131K 上下文, 支持文本与图像输入, 中文能力突出。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-plus | 2024-08-12 | 131K | text, image | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 72.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.8 | % | 0-shot CoT |
| MATH | 53.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.6 | % | 3-shot CoT |
| GPQA | 35.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 51.3 | % | 0-shot |
| WinoGrande | 85.8 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 84.3, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 参考文献

- [GLM-4 Plus ドキュメント](https://huggingface.co/models)
- リリース日: 2024-08-12
- ベンダー: Other
