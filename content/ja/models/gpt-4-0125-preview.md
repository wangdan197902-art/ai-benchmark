---
title: "GPT-4 0125 Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 0125 Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "gpt-4-0125-preview"
vendor: "openai"
version: "4-0125-preview"
tags: ["flagship", "long-context", "tool-use"]
---

# GPT-4 0125 Preview

## モデル概要

OpenAI GPT-4 0125 预览版, 128K 上下文, 修复函数调用重复调用问题, 改进代码生成能力。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-0125-preview | 2024-01-25 | 128K | text | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.6 | % | 5-shot |
| HumanEval | 80.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.9 | % | 0-shot CoT |
| MATH | 42.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.2 | % | 3-shot CoT |
| GPQA | 46.8 | % | 0-shot |
| IFEval | 71.4 | % | prompt_strict |
| ARC | 95.5 | % | challenge |
| MUSR | 65.8 | % | 0-shot |
| WinoGrande | 86.6 | % | 0-shot |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 82.6, strong knowledge reasoning.
- HumanEval 80.3, excellent code generation.
- 上下文窗口 128K，支持长文本。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 0125 Preview ドキュメント](https://platform.openai.com/docs/models)
- リリース日: 2024-01-25
- ベンダー: Openai
