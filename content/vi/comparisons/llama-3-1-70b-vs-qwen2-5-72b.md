---
title: "Llama 3.1 70B vs Qwen2.5 72B: Benchmark Comparison"
description: "Detailed comparison of Llama 3.1 70B and Qwen2.5 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
comparison_id: "llama-3-1-70b-vs-qwen2-5-72b"
models: ["llama-3-1-70b", "qwen2-5-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "meta", "alibaba"]
---

# Llama 3.1 70B đối Qwen2.5 72B

## Tổng quan mô hình

Llama 3.1 70B and Qwen2.5 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Thông số kỹ thuật chính

| Nhà cung cấp | Ngày phát hành | Cửa sổ ngữ cảnh | Giấy phép |
|---------|-------------|----------------|---------|
| Meta / Alibaba | 2024-07-23 / 2024-09-19 | 128K / 131K | Llama 3 Community License / Qwen License |

## Hiệu suất benchmark

| Benchmark | Llama 3.1 70B | Qwen2.5 72B | Người chiến thắng |
|------|------|------|--------|
| ARC | 92.3 | — | A |
| BBH (BIG-Bench Hard) | 70.2 | 82.4 | B |
| GPQA | 40.0 | — | A |
| GSM8K (Grade School Math 8K) | 78.8 | 88.4 | B |
| HumanEval | 79.7 | 86.6 | B |
| IFEval | 73.7 | — | A |
| MATH | 38.5 | 83.1 | B |
| MMLU (Massive Multitask Language Understanding) | 75.6 | 86.1 | B |
| MUSR | 48.1 | — | A |
| WinoGrande | 81.0 | — | A |

## So sánh giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*mỗi triệu token — A / B*

## Điểm mạnh & Điểm yếu

### Llama 3.1 70B

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Ý kiến biên tập

Llama 3.1 70B and Qwen2.5 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Câu hỏi thường gặp

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Tham chiếu

- [Llama 3.1 70B Tài liệu](https://llama.meta.com/docs/)
- [Qwen2.5 72B Tài liệu](https://qwenlm.github.io/)
