---
title: "Baichuan2 7B Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of Baichuan2 7B Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-06
lastmod: 2023-09-06
draft: false
weight: 10
model_id: "baichuan2-7b-chat"
vendor: "other"
version: "baichuan2-7b-chat"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Baichuan2 7B Chat

## 모델 개요

百川智能 Baichuan2 7B Chat 经济型对话模型, 4K 上下文, 7B 参数, 适合本地中文场景部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | baichuan2-7b-chat | 2023-09-06 | 4K | text | text | Baichuan 2 License |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.9 | % | 5-shot |
| HumanEval | 49.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.0 | % | 0-shot CoT |
| MATH | 18.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 53.0 | % | 3-shot CoT |
| GPQA | 33.5 | % | 0-shot |
| IFEval | 50.1 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 33.1 | % | 0-shot |
| WinoGrande | 68.3 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 57.9，知识推理偏弱。
- HumanEval 49.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [Baichuan2 7B Chat 문서](https://huggingface.co/models)
- 출시일: 2023-09-06
- 공급업체: Other
