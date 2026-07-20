---
title: "GPT-4o mini vs Gemini 1.5 Flash: Benchmark Comparison"
description: "Detailed comparison of GPT-4o mini and Gemini 1.5 Flash covering benchmarks, pricing, context window, and compliance."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
comparison_id: "gpt-4o-mini-vs-gemini-1-5-flash"
models: ["gpt-4o-mini", "gemini-1-5-flash"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "google"]
---

# GPT-4o mini đối Gemini 1.5 Flash

## Tổng quan mô hình

GPT-4o mini and Gemini 1.5 Flash are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Thông số kỹ thuật chính

| Nhà cung cấp | Ngày phát hành | Cửa sổ ngữ cảnh | Giấy phép |
|---------|-------------|----------------|---------|
| Openai / Google | 2024-07-18 / 2024-05-14 | 128K / 1000K | Proprietary / Proprietary |

## Hiệu suất benchmark

| Benchmark | GPT-4o mini | Gemini 1.5 Flash | Người chiến thắng |
|------|------|------|--------|
| ARC | 93.9 | 93.4 | A |
| BBH (BIG-Bench Hard) | 70.3 | 71.7 | B |
| GPQA | 42.6 | 38.5 | A |
| GSM8K (Grade School Math 8K) | 75.1 | 75.2 | Tie |
| HumanEval | 78.0 | 67.5 | A |
| IFEval | 67.9 | 68.0 | Tie |
| MATH | 51.8 | 53.2 | B |
| MMLU (Massive Multitask Language Understanding) | 79.7 | 76.0 | A |
| MUSR | 53.1 | 46.1 | A |
| WinoGrande | 79.6 | 78.9 | A |

## So sánh giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*mỗi triệu token — A / B*

## Điểm mạnh & Điểm yếu

### GPT-4o mini

- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Gemini 1.5 Flash

- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 1000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## Ý kiến biên tập

GPT-4o mini and Gemini 1.5 Flash each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Câu hỏi thường gặp

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Tham chiếu

- [GPT-4o mini Tài liệu](https://platform.openai.com/docs/models)
- [Gemini 1.5 Flash Tài liệu](https://ai.google.dev/gemini-api/docs)
