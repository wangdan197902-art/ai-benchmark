---
title: "Code Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "code-bison"
vendor: "google"
version: "code-bison"
tags: ["coding", "legacy"]
---

# Code Bison

## Tổng quan mô hình

Google Vertex AI Code Bison 代码生成模型, 基于 PaLM 2, 8K 上下文, 支持多语言代码生成与补全。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | code-bison | 2023-05-10 | 8K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.0 | % | 5-shot |
| HumanEval | 76.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.0 | % | 0-shot CoT |
| MATH | 34.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.4 | % | 3-shot CoT |
| GPQA | 29.1 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 86.1 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Code Bison Tài liệu](https://ai.google.dev/gemini-api/docs)
- Ngày phát hành: 2023-05-10
- Nhà cung cấp: Google
