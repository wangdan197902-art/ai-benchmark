---
title: "Microsoft WizardLM 2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardLM 2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "microsoft-wizardlm-2-7b"
vendor: "other"
version: "wizardlm-2-7b"
tags: ["open-weights", "self-hostable"]
---

# Microsoft WizardLM 2 7B

## Tổng quan mô hình

Microsoft WizardLM 2 7B 经济型微调模型, 32K 上下文, 基于 Llama 3 7B, 改进指令遵循能力。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-7b | 2024-04-15 | 32K | text | text | Llama 3 Community License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.7 | % | 5-shot |
| HumanEval | 68.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.5 | % | 0-shot CoT |
| MATH | 30.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.4 | % | 3-shot CoT |
| GPQA | 26.1 | % | 0-shot |
| IFEval | 56.9 | % | prompt_strict |
| ARC | 85.6 | % | challenge |
| MUSR | 49.3 | % | 0-shot |
| WinoGrande | 76.8 | % | 0-shot |

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

- [Microsoft WizardLM 2 7B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2024-04-15
- Nhà cung cấp: Other
