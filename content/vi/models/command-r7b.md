---
title: "Command R7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r7b"
vendor: "cohere"
version: "r7b"
tags: ["open-weights", "rag", "self-hostable"]
---

# Command R7B

## Tổng quan mô hình

Cohere Command R7B 轻量开源模型, 128K 上下文, 7B 参数, 为 RAG 与工具调用优化, 适合边缘部署。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r7b | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.7 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.1 | % | 3-shot CoT |
| GPQA | 30.9 | % | 0-shot |
| IFEval | 67.2 | % | prompt_strict |
| ARC | 90.7 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

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

- [Command R7B Tài liệu](https://docs.cohere.com/docs)
- Ngày phát hành: 2024-08-13
- Nhà cung cấp: Cohere
