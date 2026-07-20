---
title: "Claude 3 Opus: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Opus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
model_id: "claude-3-opus"
vendor: "anthropic"
version: "3-opus"
tags: ["flagship", "multimodal", "long-context"]
---

# Claude 3 Opus

## Ikhtisar Model

Anthropic Claude 3 Opus 旗舰模型, 200K 上下文, 超越 GPT-4 的推理与创意能力, 适合复杂分析任务。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-opus | 2024-03-04 | 200K | text, image | text | Proprietary |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.2 | % | 5-shot |
| HumanEval | 83.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.8 | % | 0-shot CoT |
| MATH | 42.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 46.0 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 53.3 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- MMLU score 81.2, strong knowledge reasoning.
- HumanEval 83.3, excellent code generation.
- GSM8K 91.8, robust math reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## Kekurangan

- 闭源专有模型，不支持自托管。

## Kasus Penggunaan

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## Referensi

- [Claude 3 Opus Dokumentasi](https://docs.anthropic.com/claude/docs)
- Tanggal Rilis: 2024-03-04
- Vendor: Anthropic
