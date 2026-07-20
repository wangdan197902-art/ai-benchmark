---
title: "Codestral: Complete Benchmark Performance Guide"
description: "In-depth analysis of Codestral performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-29
lastmod: 2024-05-29
draft: false
weight: 10
model_id: "codestral"
vendor: "mistral"
version: "codestral"
tags: ["coding", "open-weights"]
---

# Codestral

## Tổng quan mô hình

Mistral Codestral 22B 代码专用模型, 32K 上下文, 支持 80+ 编程语言, 代码生成与补全性能突出。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral | 2024-05-29 | 32K | text | text | MNPL |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.1 | % | 5-shot |
| HumanEval | 69.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.3 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.3 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 59.4 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.2 | % | 0-shot |
| WinoGrande | 75.8 | % | 0-shot |

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

- [Codestral Tài liệu](https://docs.mistral.ai/)
- Ngày phát hành: 2024-05-29
- Nhà cung cấp: Mistral
