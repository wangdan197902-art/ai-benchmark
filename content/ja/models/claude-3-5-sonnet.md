---
title: "Claude 3.5 Sonnet: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Sonnet performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
model_id: "claude-3-5-sonnet"
vendor: "anthropic"
version: "3.5-sonnet"
tags: ["flagship", "coding", "long-context"]
---

# Claude 3.5 Sonnet

## モデル概要

Anthropic Claude 3.5 Sonnet 模型，200K 上下文窗口，在编码、视觉推理与长文本理解方面表现突出，平衡了智能与速度。

## コア仕様

| ベンダー | バージョン | リリース日 | コンテキストウィンドウ | 入力モダリティ | 出力モダリティ | ライセンス |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-sonnet | 2024-06-20 | 200K | text, image | text | Proprietary |

## ベンチマークパフォーマンス

| ベンチマーク | スコア | 単位 | 備考 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.7 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 96.4 | % | 0-shot CoT |
| MATH | 71.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.5 | % | 3-shot CoT |

## 料金

| 入力 | 出力 | キャッシュ読み取り | キャッシュ書き込み |
|------|--------|-----------|-----------|
| — | — | — | — |

*100万トークンあたり*

## 強み

- MMLU score 88.7, strong knowledge reasoning.
- HumanEval 92.0, excellent code generation.
- GSM8K 96.4, robust math reasoning.
- 上下文窗口 200K，支持长文本。

## 弱み

- 闭源专有模型，不支持自托管。

## ユースケース

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## 参考文献

- [Claude 3.5 Sonnet ドキュメント](https://docs.anthropic.com/claude/docs)
- リリース日: 2024-06-20
- ベンダー: Anthropic
