---
title: "Qwen2 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2 72B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
model_id: "qwen2-72b"
vendor: "alibaba"
version: "2-72b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2 72B

## Tổng quan mô hình

阿里巴巴 Qwen2 72B 开源旗舰, 131K 上下文, 多语言/数学/编程能力突出, 性能接近 GPT-4。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2-72b | 2024-06-07 | 131K | text | text | Qwen License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.2 | % | 5-shot |
| HumanEval | 76.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 87.0 | % | 0-shot CoT |
| MATH | 71.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 53.6 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 94.4 | % | challenge |
| MUSR | 68.9 | % | 0-shot |
| WinoGrande | 82.5 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 80.2, strong knowledge reasoning.
- GSM8K 87.0, robust math reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Qwen2 72B Tài liệu](https://qwenlm.github.io/)
- Ngày phát hành: 2024-06-07
- Nhà cung cấp: Alibaba
