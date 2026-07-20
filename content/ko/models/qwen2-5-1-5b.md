---
title: "Qwen2.5 1.5B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 1.5B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-1-5b"
vendor: "alibaba"
version: "2.5-1-5b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 1.5B

## 모델 개요

阿里巴巴 Qwen2.5 1.5B 超轻量开源模型, 32K 上下文, 1.5B 参数, 适合资源受限设备部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-1-5b | 2024-09-19 | 32K | text | text | Qwen License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 54.5 | % | 5-shot |
| HumanEval | 35.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 33.2 | % | 0-shot CoT |
| MATH | 9.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.5 | % | 3-shot CoT |
| GPQA | 20.2 | % | 0-shot |
| IFEval | 41.9 | % | prompt_strict |
| ARC | 76.7 | % | challenge |
| MUSR | 37.8 | % | 0-shot |
| WinoGrande | 64.4 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 54.5，知识推理偏弱。
- HumanEval 35.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Qwen2.5 1.5B 문서](https://qwenlm.github.io/)
- 출시일: 2024-09-19
- 공급업체: Alibaba
