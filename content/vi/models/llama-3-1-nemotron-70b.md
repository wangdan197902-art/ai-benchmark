---
title: "Llama 3.1 Nemotron 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 Nemotron 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-17
lastmod: 2024-10-17
draft: false
weight: 10
model_id: "llama-3-1-nemotron-70b"
vendor: "meta"
version: "3.1-nemotron-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 Nemotron 70B

## Tổng quan mô hình

Meta/NVIDIA Llama 3.1 Nemotron 70B, 128K 上下文, NVIDIA 优化版本, 在 Arena 排行榜上接近 GPT-4o。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-nemotron-70b | 2024-10-17 | 128K | text | text | Llama 3.1 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.5 | % | 5-shot |
| HumanEval | 79.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.6 | % | 0-shot CoT |
| MATH | 40.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 42.6 | % | 0-shot |
| IFEval | 74.5 | % | prompt_strict |
| ARC | 93.7 | % | challenge |
| MUSR | 54.1 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 81.5, strong knowledge reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Llama 3.1 Nemotron 70B Tài liệu](https://llama.meta.com/docs/)
- Ngày phát hành: 2024-10-17
- Nhà cung cấp: Meta
