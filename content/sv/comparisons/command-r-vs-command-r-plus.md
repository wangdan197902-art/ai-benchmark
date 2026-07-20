---
title: "Command R vs Command R+: Benchmark Comparison"
description: "Detailed comparison of Command R and Command R+ covering benchmarks, pricing, context window, and compliance."
date: 2024-03-11
lastmod: 2024-03-11
draft: false
weight: 10
comparison_id: "command-r-vs-command-r-plus"
models: ["command-r", "command-r-plus"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "cohere", "cohere"]
---

# Command R mot Command R+

## Modellöversikt

Command R and Command R+ are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Nyckelspecifikationer

| Leverantör | Releasedatum | Kontextfönster | Licens |
|---------|-------------|----------------|---------|
| Cohere / Cohere | 2024-03-11 / 2024-04-04 | 128K / 128K | CC-BY-NC-4.0 / CC-BY-NC-4.0 |

## Benchmarkprestanda

| Benchmark | Command R | Command R+ | Vinnare |
|------|------|------|--------|
| ARC | 93.9 | — | A |
| BBH (BIG-Bench Hard) | 78.4 | 66.1 | A |
| GPQA | 44.0 | — | A |
| GSM8K (Grade School Math 8K) | 86.9 | 68.4 | A |
| HumanEval | 75.8 | 70.7 | A |
| IFEval | 74.1 | — | A |
| MATH | 43.9 | 35.6 | A |
| MMLU (Massive Multitask Language Understanding) | 79.3 | 75.0 | A |
| MUSR | 57.0 | — | A |
| WinoGrande | 84.8 | — | A |

## Prisjämförelse

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*per miljon tokens — A / B*

## Styrkor & Svagheter

### Command R

- ✅ GSM8K 86.9, robust math reasoning.
- ✅ 企业级合规认证。
- ⚠️ 闭源专有模型，不支持自托管。

### Command R+

- ✅ 企业级合规认证。
- ⚠️ 闭源专有模型，不支持自托管。

## Redaktörens åsikt

Command R and Command R+ each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## Vanliga frågor

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Referenser

- [Command R Dokumentation](https://docs.cohere.com/docs)
- [Command R+ Dokumentation](https://docs.cohere.com/docs/command-r-plus)
