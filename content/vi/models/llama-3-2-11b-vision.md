---
title: "Llama 3.2 11B Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.2 11B Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-11b-vision"
vendor: "meta"
version: "3.2-11b-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Llama 3.2 11B Vision

## Tổng quan mô hình

Meta Llama 3.2 11B Vision 经济型多模态开源模型, 128K 上下文, 11B 参数, 适合边缘视觉任务。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-11b-vision | 2024-09-25 | 128K | text, image | text | Llama 3.2 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.9 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.2 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.1 | % | 3-shot CoT |
| GPQA | 35.5 | % | 0-shot |
| IFEval | 58.4 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 41.7 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 支持文本、图像、音频多模态输入。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 视觉与图像理解

## Tham chiếu

- [Llama 3.2 11B Vision Tài liệu](https://llama.meta.com/docs/)
- Ngày phát hành: 2024-09-25
- Nhà cung cấp: Meta
