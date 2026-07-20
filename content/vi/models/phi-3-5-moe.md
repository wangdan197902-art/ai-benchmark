---
title: "Phi-3.5 MoE: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3.5 MoE performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-moe"
vendor: "other"
version: "phi-3-5-moe"
tags: ["open-weights", "moe", "self-hostable"]
---

# Phi-3.5 MoE

## Tổng quan mô hình

Microsoft Phi-3.5 MoE 42B 混合专家模型, 128K 上下文, 总参 42B/活跃 6.6B, 性能接近 70B 稠密模型。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-moe | 2024-08-16 | 128K | text | text | MIT |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.7 | % | 5-shot |
| HumanEval | 69.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.5 | % | 0-shot CoT |
| MATH | 38.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.4 | % | 3-shot CoT |
| GPQA | 40.2 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 91.9 | % | challenge |
| MUSR | 50.3 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 采用 MoE 混合专家架构。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Phi-3.5 MoE Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2024-08-16
- Nhà cung cấp: Other
