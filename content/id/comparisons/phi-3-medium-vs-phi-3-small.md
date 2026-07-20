---
title: "Phi-3 Medium vs Phi-3 Small: Benchmark Comparison"
description: "Detailed comparison of Phi-3 Medium and Phi-3 Small covering benchmarks, pricing, context window, and compliance."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
comparison_id: "phi-3-medium-vs-phi-3-small"
models: ["phi-3-medium", "phi-3-small"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Phi-3 Medium vs Phi-3 Small

## Ikhtisar Model

Phi-3 Medium and Phi-3 Small are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Spesifikasi Utama

| Vendor | Tanggal Rilis | Jendela Konteks | Lisensi |
|---------|-------------|----------------|---------|
| Other / Other | 2024-05-21 / 2024-05-21 | 4K / 8K | MIT / MIT |

## Kinerja Benchmark

| Benchmark | Phi-3 Medium | Phi-3 Small | Pemenang |
|------|------|------|--------|
| ARC | 90.1 | 89.6 | A |
| BBH (BIG-Bench Hard) | 71.4 | 71.8 | Tie |
| GPQA | 25.6 | 30.9 | B |
| GSM8K (Grade School Math 8K) | 59.0 | 62.7 | B |
| HumanEval | 53.9 | 68.3 | B |
| IFEval | 67.4 | 61.0 | A |
| MATH | 34.3 | 43.5 | B |
| MMLU (Massive Multitask Language Understanding) | 62.1 | 71.8 | B |
| MUSR | 43.9 | 36.5 | A |
| WinoGrande | 72.1 | 74.9 | B |

## Perbandingan Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per juta token — A / B*

## Kelebihan & Kekurangan

### Phi-3 Medium

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

### Phi-3 Small

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 8K 偏小。

## Pendapat Editor

Phi-3 Medium and Phi-3 Small each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referensi

- [Phi-3 Medium Dokumentasi](https://huggingface.co/models)
- [Phi-3 Small Dokumentasi](https://huggingface.co/models)
