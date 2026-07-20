---
title: "Nous Hermes 2 Mixtral 8x7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Mixtral 8x7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-mixtral-8x7b"
vendor: "other"
version: "nous-hermes-2-mixtral-8x7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Mixtral 8x7B

## Tổng quan mô hình

NousResearch Hermes 2 Mixtral 8x7B 微调模型, 32K 上下文, 基于 Mixtral 8x7B, 改进指令遵循能力。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-mixtral-8x7b | 2024-02-19 | 32K | text | text | Apache 2.0 |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.4 | % | 5-shot |
| HumanEval | 78.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 42.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.4 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.4 | % | 0-shot |
| WinoGrande | 82.1 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 81.4, strong knowledge reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Nous Hermes 2 Mixtral 8x7B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2024-02-19
- Nhà cung cấp: Other
