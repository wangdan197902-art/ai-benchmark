---
title: "Gemma 2B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 2B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-21
lastmod: 2024-02-21
draft: false
weight: 10
model_id: "gemma-2b"
vendor: "google"
version: "gemma-2b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 2B

## Tổng quan mô hình

Google Gemma 2B 轻量开源模型, 8K 上下文, 2B 参数, 适合资源受限环境与边缘部署。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-2b | 2024-02-21 | 8K | text | text | Gemma License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 48.0 | % | 5-shot |
| HumanEval | 43.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 27.8 | % | 0-shot CoT |
| MATH | 27.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 53.0 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 46.4 | % | prompt_strict |
| ARC | 77.7 | % | challenge |
| MUSR | 30.6 | % | 0-shot |
| WinoGrande | 72.0 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- MMLU 仅 48.0，知识推理偏弱。
- HumanEval 43.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Gemma 2B Tài liệu](https://ai.google.dev/gemma/docs)
- Ngày phát hành: 2024-02-21
- Nhà cung cấp: Google
