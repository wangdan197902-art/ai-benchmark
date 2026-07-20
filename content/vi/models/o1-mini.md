---
title: "o1 mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of o1 mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-12
lastmod: 2024-09-12
draft: false
weight: 10
model_id: "o1-mini"
vendor: "openai"
version: "o1-mini"
tags: ["reasoning", "coding"]
---

# o1 mini

## Tổng quan mô hình

OpenAI o1-mini 经济型推理模型, 针对编程与数学优化, 比 o1 便宜 80%, 适合 STEM 任务。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | o1-mini | 2024-09-12 | 128K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.2 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.6 | % | 0-shot CoT |
| MATH | 44.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.2 | % | 3-shot CoT |
| GPQA | 40.8 | % | 0-shot |
| IFEval | 73.1 | % | prompt_strict |
| ARC | 93.7 | % | challenge |
| MUSR | 54.0 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- GSM8K 86.6, robust math reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [o1 mini Tài liệu](https://platform.openai.com/docs/models)
- Ngày phát hành: 2024-09-12
- Nhà cung cấp: Openai
