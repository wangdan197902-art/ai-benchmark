---
title: "GPT-4 1106 Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 1106 Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-06
lastmod: 2023-11-06
draft: false
weight: 10
model_id: "gpt-4-1106-preview"
vendor: "openai"
version: "4-1106-preview"
tags: ["flagship", "long-context", "tool-use"]
---

# GPT-4 1106 Preview

## Tổng quan mô hình

OpenAI GPT-4 1106 预览版, 128K 上下文, 改进函数调用与 JSON 模式, 适合结构化输出任务。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-1106-preview | 2023-11-06 | 128K | text | text | Proprietary |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.8 | % | 5-shot |
| HumanEval | 83.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.4 | % | 0-shot CoT |
| MATH | 52.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.0 | % | 3-shot CoT |
| GPQA | 36.2 | % | 0-shot |
| IFEval | 73.9 | % | prompt_strict |
| ARC | 94.3 | % | challenge |
| MUSR | 58.4 | % | 0-shot |
| WinoGrande | 82.0 | % | 0-shot |

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- MMLU score 81.8, strong knowledge reasoning.
- HumanEval 83.7, excellent code generation.
- GSM8K 85.4, robust math reasoning.
- 上下文窗口 128K，支持长文本。

## Điểm yếu

- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## Tham chiếu

- [GPT-4 1106 Preview Tài liệu](https://platform.openai.com/docs/models)
- Ngày phát hành: 2023-11-06
- Nhà cung cấp: Openai
