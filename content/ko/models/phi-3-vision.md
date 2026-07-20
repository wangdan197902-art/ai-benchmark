---
title: "Phi-3 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-vision"
vendor: "other"
version: "phi-3-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Phi-3 Vision

## 모델 개요

Microsoft Phi-3 Vision 4.2B 多模态模型, 4K 上下文, 支持图像理解, 在 4B 规模上多模态能力领先。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-vision | 2024-05-21 | 4K | text, image | text | MIT |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.4 | % | 5-shot |
| HumanEval | 48.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 30.0 | % | 0-shot CoT |
| MATH | 24.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 40.1 | % | 3-shot CoT |
| GPQA | 17.4 | % | 0-shot |
| IFEval | 56.4 | % | prompt_strict |
| ARC | 77.4 | % | challenge |
| MUSR | 32.1 | % | 0-shot |
| WinoGrande | 74.7 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- 支持文本、图像、音频多模态输入。

## 약점

- MMLU 仅 56.4，知识推理偏弱。
- HumanEval 48.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 사용 사례

- 视觉与图像理解

## 참고문헌

- [Phi-3 Vision 문서](https://huggingface.co/models)
- 출시일: 2024-05-21
- 공급업체: Other
