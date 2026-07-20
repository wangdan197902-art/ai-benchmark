---
title: "Claude 3.5 Sonnet vs Claude 3 Opus: Benchmark Comparison"
description: "Detailed comparison of Claude 3.5 Sonnet and Claude 3 Opus covering benchmarks, pricing, context window, and compliance."
date: 2024-06-20
lastmod: 2024-06-20
draft: false
weight: 10
comparison_id: "claude-3-5-sonnet-vs-claude-3-opus"
models: ["claude-3-5-sonnet", "claude-3-opus"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "anthropic", "anthropic"]
---

# Claude 3.5 Sonnet 대 Claude 3 Opus

## 모델 개요

Claude 3.5 Sonnet and Claude 3 Opus are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## 핵심 사양

| 공급업체 | 출시일 | 컨텍스트 창 | 라이선스 |
|---------|-------------|----------------|---------|
| Anthropic / Anthropic | 2024-06-20 / 2024-03-04 | 200K / 200K | Proprietary / Proprietary |

## 벤치마크 성능

| 벤치마크 | Claude 3.5 Sonnet | Claude 3 Opus | 승자 |
|------|------|------|--------|
| ARC | — | 94.5 | B |
| BBH (BIG-Bench Hard) | 84.5 | 81.6 | A |
| GPQA | — | 46.0 | B |
| GSM8K (Grade School Math 8K) | 96.4 | 91.8 | A |
| HumanEval | 92.0 | 83.3 | A |
| IFEval | — | 79.2 | B |
| MATH | 71.1 | 42.7 | A |
| MMLU (Massive Multitask Language Understanding) | 88.7 | 81.2 | A |
| MUSR | — | 53.3 | B |
| WinoGrande | — | 81.9 | B |

## 가격 비교

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*백만 토큰당 — A / B*

## 강점 & 약점

### Claude 3.5 Sonnet

- ✅ MMLU score 88.7, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 96.4, robust math reasoning.
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Claude 3 Opus

- ✅ MMLU score 81.2, strong knowledge reasoning.
- ✅ HumanEval 83.3, excellent code generation.
- ✅ GSM8K 91.8, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 200K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## 편집자 의견

Claude 3.5 Sonnet and Claude 3 Opus each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## FAQ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## 참고문헌

- [Claude 3.5 Sonnet 문서](https://docs.anthropic.com/claude/docs)
- [Claude 3 Opus 문서](https://docs.anthropic.com/claude/docs)
