---
title: "Mistral Small 3: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Small 3 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2025-01-29
lastmod: 2025-01-29
draft: false
weight: 10
model_id: "mistral-small-3"
vendor: "mistral"
version: "small-3"
tags: ["open-weights", "self-hostable"]
---

# Mistral Small 3

## Tổng quan mô hình

Mistral Small 3 开源模型, 24B 参数, 32K 上下文, 性能接近 Mistral Large 2, Apache 2.0 可商用。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | small-3 | 2025-01-29 | 32K | text | text | Apache 2.0 |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 74.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.6 | % | 0-shot CoT |
| MATH | 39.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.3 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 46.0 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Mistral Small 3 Tài liệu](https://docs.mistral.ai/)
- Ngày phát hành: 2025-01-29
- Nhà cung cấp: Mistral
