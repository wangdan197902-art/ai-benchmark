---
title: "Falcon 180B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Falcon 180B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-06
lastmod: 2023-09-06
draft: false
weight: 10
model_id: "falcon-180b"
vendor: "other"
version: "falcon-180b"
tags: ["open-weights", "self-hostable"]
---

# Falcon 180B

## Tổng quan mô hình

TII Falcon 180B 大型开源模型, 2K 上下文, 1800 亿参数, 在开源模型中曾排名第一, 排在 GPT-4 之后。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | falcon-180b | 2023-09-06 | 2K | text | text | TII Falcon LLM License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.7 | % | 5-shot |
| HumanEval | 68.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.5 | % | 0-shot CoT |
| MATH | 44.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.4 | % | 3-shot CoT |
| GPQA | 43.2 | % | 0-shot |
| IFEval | 70.5 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 59.1 | % | 0-shot |
| WinoGrande | 80.0 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Falcon 180B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2023-09-06
- Nhà cung cấp: Other
