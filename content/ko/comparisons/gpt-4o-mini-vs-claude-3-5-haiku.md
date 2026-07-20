---
title: "GPT-4o mini vs Claude 3.5 Haiku: Benchmark Comparison"
description: "Detailed comparison of GPT-4o mini and Claude 3.5 Haiku covering benchmarks, pricing, context window, and compliance."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
comparison_id: "gpt-4o-mini-vs-claude-3-5-haiku"
models: ["gpt-4o-mini", "claude-3-5-haiku"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "anthropic"]
---

# GPT-4o mini 대 Claude 3.5 Haiku

## 모델 개요

GPT-4o mini and Claude 3.5 Haiku are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Openai / Anthropic | 2024-07-18 / 2024-11-04 | 128K / 200K | Proprietary / Proprietary |

## 벤치마크 성능

| 벤치마크 | GPT-4o mini | Claude 3.5 Haiku | 승자 |
|------|------|------|--------|
| ARC | 93.9 | 91.8 | A |
| BBH (BIG-Bench Hard) | 70.3 | 70.2 | Tie |
| GPQA | 42.6 | 31.1 | A |
| GSM8K (Grade School Math 8K) | 75.1 | 75.5 | Tie |
| HumanEval | 78.0 | 73.8 | A |
| IFEval | 67.9 | 73.6 | B |
| MATH | 51.8 | 53.0 | B |
| MMLU (Massive Multitask Language Understanding) | 79.7 | 77.6 | A |
| MUSR | 53.1 | 52.3 | A |
| WinoGrande | 79.6 | 83.8 | B |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### GPT-4o mini

- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3.5 Haiku

- ✅ 可靠的通用模型。
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

GPT-4o mini and Claude 3.5 Haiku each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [GPT-4o mini 문서](https://platform.openai.com/docs/models)
- [Claude 3.5 Haiku 문서](https://docs.anthropic.com/claude/docs)
