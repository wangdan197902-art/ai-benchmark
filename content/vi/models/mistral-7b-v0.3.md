---
title: "Mistral 7B v0.3: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.3 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-22
lastmod: 2024-05-22
draft: false
weight: 10
model_id: "mistral-7b-v0.3"
vendor: "mistral"
version: "7b-v0.3"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.3

## Tổng quan mô hình

Mistral 7B v0.3 开源模型, 32K 上下文, 改进 v0.2, 扩展词汇表至 32768, 适合本地部署。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.3 | 2024-05-22 | 32K | text | text | Apache 2.0 |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.6 | % | 5-shot |
| HumanEval | 68.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.4 | % | 0-shot CoT |
| MATH | 26.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.5 | % | 3-shot CoT |
| GPQA | 31.2 | % | 0-shot |
| IFEval | 60.9 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

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

- 通用对话与问答

## Tham chiếu

- [Mistral 7B v0.3 Tài liệu](https://docs.mistral.ai/)
- Ngày phát hành: 2024-05-22
- Nhà cung cấp: Mistral
