---
title: "Claude 3 Sonnet (2024-02-29): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Sonnet (2024-02-29) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-29
lastmod: 2024-02-29
draft: false
weight: 10
model_id: "claude-3-sonnet-20240229"
vendor: "anthropic"
version: "3-sonnet-20240229"
tags: ["multimodal", "long-context"]
---

# Claude 3 Sonnet (2024-02-29)

## Tổng quan mô hình

Anthropic Claude 3 Sonnet 2024-02-29 快照版本, 200K 上下文, 速度与智能平衡型。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-sonnet-20240229 | 2024-02-29 | 200K | text, image | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.0 | % | 5-shot |
| HumanEval | 80.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.6 | % | 0-shot CoT |
| MATH | 46.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.2 | % | 3-shot CoT |
| GPQA | 41.7 | % | 0-shot |
| IFEval | 75.5 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 63.5 | % | 0-shot |
| WinoGrande | 80.3 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 84.0, strong knowledge reasoning.
- HumanEval 80.1, excellent code generation.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解

## Tham chiếu

- [Claude 3 Sonnet (2024-02-29) Tài liệu](https://docs.anthropic.com/claude/docs)
- Ngày phát hành: 2024-02-29
- Nhà cung cấp: Anthropic
