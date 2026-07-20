---
title: "Microsoft WizardLM 2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardLM 2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-15
lastmod: 2024-04-15
draft: false
weight: 10
model_id: "microsoft-wizardlm-2-7b"
vendor: "other"
version: "wizardlm-2-7b"
tags: ["open-weights", "self-hostable"]
---

# Microsoft WizardLM 2 7B

## 모델 개요

Microsoft WizardLM 2 7B 经济型微调模型, 32K 上下文, 基于 Llama 3 7B, 改进指令遵循能力。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardlm-2-7b | 2024-04-15 | 32K | text | text | Llama 3 Community License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.7 | % | 5-shot |
| HumanEval | 68.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.5 | % | 0-shot CoT |
| MATH | 30.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.4 | % | 3-shot CoT |
| GPQA | 26.1 | % | 0-shot |
| IFEval | 56.9 | % | prompt_strict |
| ARC | 85.6 | % | challenge |
| MUSR | 49.3 | % | 0-shot |
| WinoGrande | 76.8 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Microsoft WizardLM 2 7B 문서](https://huggingface.co/models)
- 출시일: 2024-04-15
- 공급업체: Other
