---
title: "Grok-2 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok-2 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2-mini"
vendor: "xai"
version: "2-mini"
tags: ["realtime"]
---

# Grok-2 Mini

## Tổng quan mô hình

xAI Grok-2 Mini 经济型模型, 131K 上下文, 速度快成本低, 适合实时对话与高吞吐场景。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2-mini | 2024-08-13 | 131K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.6 | % | 5-shot |
| HumanEval | 77.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.6 | % | 0-shot CoT |
| MATH | 45.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.6 | % | 3-shot CoT |
| GPQA | 31.7 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 92.2 | % | challenge |
| MUSR | 51.4 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 80.6, strong knowledge reasoning.

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Grok-2 Mini Tài liệu](https://docs.x.ai/)
- Ngày phát hành: 2024-08-13
- Nhà cung cấp: Xai
