---
title: "Falcon 40B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Falcon 40B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-25
lastmod: 2023-05-25
draft: false
weight: 10
model_id: "falcon-40b"
vendor: "other"
version: "falcon-40b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Falcon 40B

## Tổng quan mô hình

TII Falcon 40B 中型开源模型, 2K 上下文, 400 亿参数, 在 40B 规模上曾领先 Llama 2 70B。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | falcon-40b | 2023-05-25 | 2K | text | text | TII Falcon LLM License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.7 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 61.3 | % | 0-shot CoT |
| MATH | 21.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.6 | % | 3-shot CoT |
| GPQA | 21.1 | % | 0-shot |
| IFEval | 57.2 | % | prompt_strict |
| ARC | 82.9 | % | challenge |
| MUSR | 38.1 | % | 0-shot |
| WinoGrande | 65.6 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- MMLU 仅 56.7，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Falcon 40B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2023-05-25
- Nhà cung cấp: Other
