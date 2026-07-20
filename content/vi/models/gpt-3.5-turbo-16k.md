---
title: "GPT-3.5 Turbo 16K: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo 16K performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-06-13
lastmod: 2023-06-13
draft: false
weight: 10
model_id: "gpt-3.5-turbo-16k"
vendor: "openai"
version: "3.5-turbo-16k"
tags: ["legacy", "long-context"]
---

# GPT-3.5 Turbo 16K

## Tổng quan mô hình

OpenAI GPT-3.5 Turbo 16K 长上下文版本, 支持 16385 token, 适合中等长度文档处理。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo-16k | 2023-06-13 | 16K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.2 | % | 5-shot |
| HumanEval | 36.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.8 | % | 0-shot CoT |
| MATH | 30.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 21.6 | % | 0-shot |
| IFEval | 48.5 | % | prompt_strict |
| ARC | 83.1 | % | challenge |
| MUSR | 29.1 | % | 0-shot |
| WinoGrande | 74.0 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 上下文窗口 16K，支持长文本。

## Điểm yếu

- HumanEval 36.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Trường hợp sử dụng

- 长文档摘要

## Tham chiếu

- [GPT-3.5 Turbo 16K Tài liệu](https://platform.openai.com/docs/models)
- Ngày phát hành: 2023-06-13
- Nhà cung cấp: Openai
