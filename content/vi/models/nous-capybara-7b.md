---
title: "Nous Capybara 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Capybara 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-26
lastmod: 2023-09-26
draft: false
weight: 10
model_id: "nous-capybara-7b"
vendor: "other"
version: "nous-capybara-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Nous Capybara 7B

## Tổng quan mô hình

NousResearch Capybara 7B 对话模型, 4K 上下文, 基于 Llama 2 微调, 改进多轮对话能力。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-capybara-7b | 2023-09-26 | 4K | text | text | Apache 2.0 |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.4 | % | 5-shot |
| HumanEval | 38.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.0 | % | 0-shot CoT |
| MATH | 19.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.6 | % | 3-shot CoT |
| GPQA | 31.0 | % | 0-shot |
| IFEval | 44.2 | % | prompt_strict |
| ARC | 87.0 | % | challenge |
| MUSR | 42.5 | % | 0-shot |
| WinoGrande | 77.1 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- HumanEval 38.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Nous Capybara 7B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2023-09-26
- Nhà cung cấp: Other
