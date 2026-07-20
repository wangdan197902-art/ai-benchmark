---
title: "Hermes 3 Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-405b"
vendor: "other"
version: "hermes-3-llama-3-1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Hermes 3 Llama 3.1 405B

## Tổng quan mô hình

NousResearch Hermes 3 Llama 3.1 405B 微调模型, 131K 上下文, 改进中立性与推理, 性能超越基座模型。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-405b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 88.9 | % | 0-shot CoT |
| MATH | 65.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 78.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 86.5 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 83.9, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 88.9, robust math reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Hermes 3 Llama 3.1 405B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2024-08-12
- Nhà cung cấp: Other
