---
title: "Llama 2 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-70b"
vendor: "meta"
version: "2-70b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 70B

## Tổng quan mô hình

Meta Llama 2 70B 开源模型, 4K 上下文, 在开源模型中领先, 商用许可, 适合企业自托管。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-70b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.0 | % | 5-shot |
| HumanEval | 50.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.8 | % | 0-shot CoT |
| MATH | 22.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.5 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 57.1 | % | prompt_strict |
| ARC | 80.3 | % | challenge |
| MUSR | 36.1 | % | 0-shot |
| WinoGrande | 73.4 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- MMLU 仅 53.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Llama 2 70B Tài liệu](https://llama.meta.com/docs/)
- Ngày phát hành: 2023-07-18
- Nhà cung cấp: Meta
