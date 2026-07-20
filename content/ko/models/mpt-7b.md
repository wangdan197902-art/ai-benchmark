---
title: "MPT 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of MPT 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-04
lastmod: 2023-05-04
draft: false
weight: 10
model_id: "mpt-7b"
vendor: "other"
version: "mpt-7b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# MPT 7B

## 모델 개요

MosaicML MPT 7B 经济型开源模型, 2K 上下文, 7B 参数, Apache 2.0 可商用, 适合本地部署。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | mpt-7b | 2023-05-04 | 2K | text | text | Apache 2.0 |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.7 | % | 5-shot |
| HumanEval | 38.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 44.6 | % | 0-shot CoT |
| MATH | 18.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.9 | % | 3-shot CoT |
| GPQA | 34.2 | % | 0-shot |
| IFEval | 59.9 | % | prompt_strict |
| ARC | 87.5 | % | challenge |
| MUSR | 42.4 | % | 0-shot |
| WinoGrande | 65.5 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 可靠的通用模型。

## 약점

- MMLU 仅 51.7，知识推理偏弱。
- HumanEval 38.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 사용 사례

- 通用对话与问答

## 참고문헌

- [MPT 7B 문서](https://huggingface.co/models)
- 출시일: 2023-05-04
- 공급업체: Other
