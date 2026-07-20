---
title: "GPT-4o vs Claude 3.5 Sonnet: Benchmark Comparison"
description: "Detailed comparison of GPT-4o and Claude 3.5 Sonnet covering benchmarks, pricing, context window, and compliance."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "gpt-4o-vs-claude-3-5-sonnet"
models: ["gpt-4o", "claude-3-5-sonnet"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "openai", "anthropic"]
---

# GPT-4o 대 Claude 3.5 Sonnet

## 모델 개요

GPT-4o and Claude 3.5 Sonnet are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Openai / Anthropic | 2024-05-13 / 2024-06-20 | 128K / 200K | Proprietary / Proprietary |

## 벤치마크 성능

| 벤치마크 | GPT-4o | Claude 3.5 Sonnet | 승자 |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 83.1 | 84.5 | B |
| GSM8K (Grade School Math 8K) | 95.8 | 96.4 | B |
| HumanEval | 90.2 | 92.0 | B |
| MATH | 76.6 | 71.1 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 88.7 | Tie |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### GPT-4o

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 90.2, excellent code generation.
- ✅ GSM8K 95.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3.5 Sonnet

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 96.4, robust math reasoning.
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

GPT-4o and Claude 3.5 Sonnet each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [GPT-4o 문서](https://platform.openai.com/docs/models/gpt-4o)
- [Claude 3.5 Sonnet 문서](https://docs.anthropic.com/claude/docs)
