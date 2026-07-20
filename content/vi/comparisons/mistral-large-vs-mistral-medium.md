---
title: "Mistral Large vs Mistral Medium: Benchmark Comparison"
description: "Detailed comparison of Mistral Large and Mistral Medium covering benchmarks, pricing, context window, and compliance."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
comparison_id: "mistral-large-vs-mistral-medium"
models: ["mistral-large", "mistral-medium"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "mistral", "mistral"]
---

# Mistral Large đối Mistral Medium

## Tổng quan mô hình

Mistral Large and Mistral Medium are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Thông số kỹ thuật chính

| Nhà cung cấp | Ngày phát hành | Cửa sổ ngữ cảnh | Giấy phép |
|---------|-------------|----------------|---------|
| Mistral / Mistral | 2024-02-26 / 2023-12-11 | 32K / 32K | Apache 2.0 / Apache 2.0 |

## Hiệu suất benchmark

| Benchmark | Mistral Large | Mistral Medium | Người chiến thắng |
|------|------|------|--------|
| ARC | 93.3 | 94.6 | B |
| BBH (BIG-Bench Hard) | 76.7 | 83.4 | B |
| GPQA | 38.1 | 48.7 | B |
| GSM8K (Grade School Math 8K) | 80.9 | 82.5 | B |
| HumanEval | 73.4 | 78.0 | B |
| IFEval | 75.8 | 77.4 | B |
| MATH | 49.3 | 54.9 | B |
| MMLU (Massive Multitask Language Understanding) | 82.0 | 82.9 | B |
| MUSR | 52.1 | 64.3 | B |
| WinoGrande | 83.3 | 82.4 | A |

## So sánh giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*mỗi triệu token — A / B*

## Điểm mạnh & Điểm yếu

### Mistral Large

- ✅ MMLU score 82.0, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Medium

- ✅ MMLU score 82.9, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Ý kiến biên tập

Mistral Large and Mistral Medium each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Câu hỏi thường gặp

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Tham chiếu

- [Mistral Large Tài liệu](https://docs.mistral.ai/)
- [Mistral Medium Tài liệu](https://docs.mistral.ai/)
