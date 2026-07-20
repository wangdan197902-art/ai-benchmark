---
title: "Chat Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Chat Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "chat-bison"
vendor: "google"
version: "chat-bison"
tags: ["legacy"]
---

# Chat Bison

## Tổng quan mô hình

Google Vertex AI Chat Bison 对话模型, 基于 PaLM 2, 8K 上下文, 适合企业级对话应用。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | chat-bison | 2023-05-10 | 8K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.1 | % | 5-shot |
| HumanEval | 36.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.4 | % | 0-shot CoT |
| MATH | 19.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 54.6 | % | 3-shot CoT |
| GPQA | 25.0 | % | 0-shot |
| IFEval | 48.2 | % | prompt_strict |
| ARC | 82.6 | % | challenge |
| MUSR | 32.8 | % | 0-shot |
| WinoGrande | 66.2 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- HumanEval 36.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Chat Bison Tài liệu](https://ai.google.dev/gemini-api/docs)
- Ngày phát hành: 2023-05-10
- Nhà cung cấp: Google
