---
title: "GPT-4 Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-06
lastmod: 2023-11-06
draft: false
weight: 10
model_id: "gpt-4-turbo"
vendor: "openai"
version: "turbo"
tags: ["flagship", "multimodal", "long-context"]
---

# GPT-4 Turbo

## Tổng quan mô hình

OpenAI GPT-4 Turbo 模型, 128K 上下文窗口, 支持视觉输入, 相比 GPT-4 价格降低 3 倍, 性能提升。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | turbo | 2023-11-06 | 128K | text, image | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.4 | % | 5-shot |
| HumanEval | 80.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.2 | % | 0-shot CoT |
| MATH | 50.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.5 | % | 3-shot CoT |
| GPQA | 49.2 | % | 0-shot |
| IFEval | 77.9 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 61.1 | % | 0-shot |
| WinoGrande | 80.8 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 84.4, strong knowledge reasoning.
- HumanEval 80.5, excellent code generation.
- GSM8K 85.2, robust math reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 128K，支持长文本。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## Tham chiếu

- [GPT-4 Turbo Tài liệu](https://platform.openai.com/docs/models)
- Ngày phát hành: 2023-11-06
- Nhà cung cấp: Openai
