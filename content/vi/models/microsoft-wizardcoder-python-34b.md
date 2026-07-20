---
title: "Microsoft WizardCoder Python 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardCoder Python 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-17
lastmod: 2023-08-17
draft: false
weight: 10
model_id: "microsoft-wizardcoder-python-34b"
vendor: "other"
version: "wizardcoder-python-34b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Microsoft WizardCoder Python 34B

## Tổng quan mô hình

Microsoft WizardCoder Python 34B 代码模型, 16K 上下文, 基于 Code Llama 34B, Python 代码生成突出。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardcoder-python-34b | 2023-08-17 | 16K | text | text | Llama 2 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.0 | % | 5-shot |
| HumanEval | 79.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.7 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 67.2 | % | 3-shot CoT |
| GPQA | 36.6 | % | 0-shot |
| IFEval | 53.8 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 53.1 | % | 0-shot |
| WinoGrande | 70.4 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Trường hợp sử dụng

- 代码生成与调试

## Tham chiếu

- [Microsoft WizardCoder Python 34B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2023-08-17
- Nhà cung cấp: Other
