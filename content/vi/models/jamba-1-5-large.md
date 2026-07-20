---
title: "Jamba 1.5 Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jamba 1.5 Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-07
lastmod: 2024-08-07
draft: false
weight: 10
model_id: "jamba-1-5-large"
vendor: "other"
version: "jamba-1-5-large"
tags: ["open-weights", "moe", "long-context"]
---

# Jamba 1.5 Large

## Tổng quan mô hình

AI21 Labs Jamba 1.5 Large 混合 SSM-Transformer 模型, 256K 上下文, 总参 398B/活跃 94B, 长上下文突出。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-1-5-large | 2024-08-07 | 256K | text | text | Jamba Open Model License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 73.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.5 | % | 0-shot CoT |
| MATH | 60.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.8 | % | 3-shot CoT |
| GPQA | 50.8 | % | 0-shot |
| IFEval | 70.8 | % | prompt_strict |
| ARC | 93.8 | % | challenge |
| MUSR | 51.1 | % | 0-shot |
| WinoGrande | 84.3 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 84.3, strong knowledge reasoning.
- 上下文窗口 256K，支持长文本。
- 采用 MoE 混合专家架构。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试
- 长文档摘要

## Tham chiếu

- [Jamba 1.5 Large Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2024-08-07
- Nhà cung cấp: Other
