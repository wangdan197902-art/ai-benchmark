---
title: "Claude 3 Haiku (2024-03-07): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Haiku (2024-03-07) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-07
lastmod: 2024-03-07
draft: false
weight: 10
model_id: "claude-3-haiku-20240307"
vendor: "anthropic"
version: "3-haiku-20240307"
tags: ["realtime"]
---

# Claude 3 Haiku (2024-03-07)

## Tổng quan mô hình

Anthropic Claude 3 Haiku 2024-03-07 快照版本, 200K 上下文, 最快响应速度的经济型模型。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-haiku-20240307 | 2024-03-07 | 200K | text, image | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.1 | % | 5-shot |
| HumanEval | 74.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.5 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.2 | % | 3-shot CoT |
| GPQA | 39.6 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 51.0 | % | 0-shot |
| WinoGrande | 79.5 | % | 0-shot |

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

- [Claude 3 Haiku (2024-03-07) Tài liệu](https://docs.anthropic.com/claude/docs)
- Ngày phát hành: 2024-03-07
- Nhà cung cấp: Anthropic
