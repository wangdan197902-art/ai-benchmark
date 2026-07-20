---
title: "Command R+: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R+ performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-04
lastmod: 2024-04-04
draft: false
weight: 10
model_id: "command-r-plus"
vendor: "cohere"
version: "r-plus"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R+

## Modellübersicht

Cohere Command R+ 是面向企业的 104B 参数模型，128K 上下文窗口，针对检索增强生成（RAG）与工具调用优化，支持 SOC2/GDPR/ISO 27001 合规，适合企业级生产部署。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r-plus | 2024-04-04 | 128K | text | text | CC-BY-NC-4.0 |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.0 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.4 | % | 0-shot CoT |
| MATH | 35.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.1 | % | 3-shot CoT |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 企业级合规认证。

## Schwächen

- 闭源专有模型，不支持自托管。

## Anwendungsfälle

- 代码生成与调试
- 企业客户支持

## Referenzen

- [Command R+ Dokumentation](https://docs.cohere.com/docs/command-r-plus)
- Veröffentlichungsdatum: 2024-04-04
- Anbieter: Cohere
