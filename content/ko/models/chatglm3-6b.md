---
title: "ChatGLM3 6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of ChatGLM3 6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-27
lastmod: 2023-10-27
draft: false
weight: 10
model_id: "chatglm3-6b"
vendor: "other"
version: "chatglm3-6b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# ChatGLM3 6B

## 모델 개요

清华智谱 ChatGLM3 6B 第三代开源模型, 32K 上下文, 6B 参数, 中英双语对话能力突出, 适合本地部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | chatglm3-6b | 2023-10-27 | 32K | text | text | GLM-3 License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.0 | % | 5-shot |
| HumanEval | 51.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 37.9 | % | 0-shot CoT |
| MATH | 31.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.7 | % | 3-shot CoT |
| GPQA | 20.1 | % | 0-shot |
| IFEval | 42.5 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 67.7 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 58.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [ChatGLM3 6B 문서](https://huggingface.co/models)
- 출시일: 2023-10-27
- 공급업체: Other
