---
title: "Claude 3.5 Sonnet: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Sonnet performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
model_id: "claude-3-5-sonnet"
vendor: "anthropic"
version: "3.5-sonnet"
tags: ["flagship", "coding", "long-context"]
---

# Claude 3.5 Sonnet

## Tổng quan mô hình

Anthropic Claude 3.5 Sonnet 模型，200K 上下文窗口，在编码、视觉推理与长文本理解方面表现突出，平衡了智能与速度。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-sonnet | 2024-06-20 | 200K | text, image | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.7 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 96.4 | % | 0-shot CoT |
| MATH | 71.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.5 | % | 3-shot CoT |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 88.7, strong knowledge reasoning.
- HumanEval 92.0, excellent code generation.
- GSM8K 96.4, robust math reasoning.
- 上下文窗口 200K，支持长文本。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## Tham chiếu

- [Claude 3.5 Sonnet Tài liệu](https://docs.anthropic.com/claude/docs)
- Ngày phát hành: 2024-06-20
- Nhà cung cấp: Anthropic
