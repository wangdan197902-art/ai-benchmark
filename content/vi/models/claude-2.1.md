---
title: "Claude 2.1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 2.1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-21
lastmod: 2023-11-21
draft: false
weight: 10
model_id: "claude-2.1"
vendor: "anthropic"
version: "2.1"
tags: ["legacy", "long-context"]
---

# Claude 2.1

## Tổng quan mô hình

Anthropic Claude 2.1, 200K 上下文, 相比 2.0 减少 2 倍幻觉率, 改进长文档召回能力。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 2.1 | 2023-11-21 | 200K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.9 | % | 5-shot |
| HumanEval | 28.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 45.7 | % | 0-shot CoT |
| MATH | 15.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.8 | % | 3-shot CoT |
| GPQA | 26.4 | % | 0-shot |
| IFEval | 55.0 | % | prompt_strict |
| ARC | 84.8 | % | challenge |
| MUSR | 37.7 | % | 0-shot |
| WinoGrande | 67.4 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 上下文窗口 200K，支持长文本。

## Điểm yếu

- HumanEval 28.1，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 长文档摘要

## Tham chiếu

- [Claude 2.1 Tài liệu](https://docs.anthropic.com/claude/docs)
- Ngày phát hành: 2023-11-21
- Nhà cung cấp: Anthropic
