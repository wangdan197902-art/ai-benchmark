---
title: "Qwen2.5 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-3b"
vendor: "alibaba"
version: "2.5-3b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 3B

## 모델 개요

阿里巴巴 Qwen2.5 3B 轻量开源模型, 32K 上下文, 3B 参数, 适合移动设备与边缘部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-3b | 2024-09-19 | 32K | text | text | Qwen License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.8 | % | 5-shot |
| HumanEval | 49.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 31.3 | % | 0-shot CoT |
| MATH | 17.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.8 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 56.0 | % | prompt_strict |
| ARC | 76.5 | % | challenge |
| MUSR | 23.3 | % | 0-shot |
| WinoGrande | 61.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 56.8，知识推理偏弱。
- HumanEval 49.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Qwen2.5 3B 문서](https://qwenlm.github.io/)
- 출시일: 2024-09-19
- 공급업체: Alibaba
