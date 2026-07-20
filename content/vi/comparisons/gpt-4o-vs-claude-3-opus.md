---
title: "GPT-4o vs Claude 3 Opus: Benchmark Comparison"
description: "Detailed comparison of GPT-4o and Claude 3 Opus covering benchmarks, pricing, context window, and compliance."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "gpt-4o-vs-claude-3-opus"
models: ["gpt-4o", "claude-3-opus"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "anthropic"]
---

# GPT-4o đối Claude 3 Opus

## Tổng quan mô hình

GPT-4o and Claude 3 Opus are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Thông số kỹ thuật chính

| Nhà cung cấp | Ngày phát hành | Cửa sổ ngữ cảnh | Giấy phép |
|---------|-------------|----------------|---------|
| Openai / Anthropic | 2024-05-13 / 2024-03-04 | 128K / 200K | Proprietary / Proprietary |

## Hiệu suất benchmark

| Benchmark | GPT-4o | Claude 3 Opus | Người chiến thắng |
|------|------|------|--------|
| ARC | — | 94.5 | B |
| BBH (BIG-Bench Hard) | 83.1 | 81.6 | A |
| GPQA | — | 46.0 | B |
| GSM8K (Grade School Math 8K) | 95.8 | 91.8 | A |
| HumanEval | 90.2 | 83.3 | A |
| IFEval | — | 79.2 | B |
| MATH | 76.6 | 42.7 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 81.2 | A |
| MUSR | — | 53.3 | B |
| WinoGrande | — | 81.9 | B |

## So sánh giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*mỗi triệu token — A / B*

## Điểm mạnh & Điểm yếu

### GPT-4o

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 90.2, excellent code generation.
- ✅ GSM8K 95.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3 Opus

- ✅ MMLU score 81.2, strong knowledge reasoning.
- ✅ HumanEval 83.3, excellent code generation.
- ✅ GSM8K 91.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## Ý kiến biên tập

GPT-4o and Claude 3 Opus each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Câu hỏi thường gặp

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Tham chiếu

- [GPT-4o Tài liệu](https://platform.openai.com/docs/models/gpt-4o)
- [Claude 3 Opus Tài liệu](https://docs.anthropic.com/claude/docs)
