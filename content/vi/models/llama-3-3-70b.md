---
title: "Llama 3.3 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.3 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-06
lastmod: 2024-12-06
draft: false
weight: 10
model_id: "llama-3-3-70b"
vendor: "meta"
version: "3.3-70b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.3 70B

## Tổng quan mô hình

Meta Llama 3.3 70B 开源旗舰, 128K 上下文, 性能超越 Llama 3.1 405B, 接近 GPT-4o 水平。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.3-70b | 2024-12-06 | 128K | text | text | Llama 3.3 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.4 | % | 5-shot |
| HumanEval | 87.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.9 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.9 | % | 3-shot CoT |
| GPQA | 52.8 | % | 0-shot |
| IFEval | 79.3 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 62.3 | % | 0-shot |
| WinoGrande | 86.8 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 83.4, strong knowledge reasoning.
- HumanEval 87.0, excellent code generation.
- GSM8K 86.9, robust math reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Llama 3.3 70B Tài liệu](https://llama.meta.com/docs/)
- Ngày phát hành: 2024-12-06
- Nhà cung cấp: Meta
