---
title: "Mixtral 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mixtral 8x22B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-10
lastmod: 2024-04-10
draft: false
weight: 10
model_id: "mixtral-8x22b"
vendor: "mistral"
version: "8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Mixtral 8x22B

## Tổng quan mô hình

Mistral Mixtral 8x22B 是稀疏混合专家（MoE）开源模型，总参数 141B、活跃参数 39B，64K 上下文窗口，在多语言与代码任务上表现稳健，Apache 2.0 许可证可商用。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 8x22b | 2024-04-10 | 64K | text | text | Apache 2.0 |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.8 | % | 5-shot |
| HumanEval | 45.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.6 | % | 0-shot CoT |
| MATH | 46.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.5 | % | 3-shot CoT |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 采用 MoE 混合专家架构。

## Điểm yếu

- HumanEval 45.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Mixtral 8x22B Tài liệu](https://docs.mistral.ai/)
- Ngày phát hành: 2024-04-10
- Nhà cung cấp: Mistral
