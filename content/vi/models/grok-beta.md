---
title: "Grok Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-04
lastmod: 2023-11-04
draft: false
weight: 10
model_id: "grok-beta"
vendor: "xai"
version: "beta"
tags: ["legacy", "realtime"]
---

# Grok Beta

## Tổng quan mô hình

xAI Grok Beta 早期预览版, 8K 上下文, 集成 X 平台实时数据, 幽默风格对话能力突出。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | beta | 2023-11-04 | 8K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 31.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.7 | % | 0-shot CoT |
| MATH | 19.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 20.6 | % | 0-shot |
| IFEval | 56.2 | % | prompt_strict |
| ARC | 81.7 | % | challenge |
| MUSR | 43.7 | % | 0-shot |
| WinoGrande | 69.2 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 31.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [Grok Beta Tài liệu](https://docs.x.ai/)
- Ngày phát hành: 2023-11-04
- Nhà cung cấp: Xai
