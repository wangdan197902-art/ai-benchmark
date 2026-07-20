---
title: "GPT-4 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "gpt-4-vision"
vendor: "openai"
version: "4-vision"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision

## Tổng quan mô hình

OpenAI GPT-4 Vision 正式版, 支持图像理解与多模态推理, 128K 上下文窗口。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision | 2024-01-25 | 128K | text, image | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.6 | % | 0-shot CoT |
| MATH | 48.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.9 | % | 3-shot CoT |
| GPQA | 41.8 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 86.9 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 83.9, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Tham chiếu

- [GPT-4 Vision Tài liệu](https://platform.openai.com/docs/models)
- Ngày phát hành: 2024-01-25
- Nhà cung cấp: Openai
