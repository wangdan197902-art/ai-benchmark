---
title: "Claude 3 Opus: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Opus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
model_id: "claude-3-opus"
vendor: "anthropic"
version: "3-opus"
tags: ["flagship", "multimodal", "long-context"]
---

# Claude 3 Opus

## 모델 개요

Anthropic Claude 3 Opus 旗舰模型, 200K 上下文, 超越 GPT-4 的推理与创意能力, 适合复杂分析任务。

## 핵심 사양

| 공급업체 | 버전 | 출시일 | 컨텍스트 창 | 입력 모달리티 | 출력 모달리티 | 라이선스 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-opus | 2024-03-04 | 200K | text, image | text | Proprietary |

## 벤치마크 성능

| 벤치마크 | 점수 | 단위 | 비고 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.2 | % | 5-shot |
| HumanEval | 83.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.8 | % | 0-shot CoT |
| MATH | 42.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 46.0 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 53.3 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## 가격

| 입력 | 출력 | 캐시 읽기 | 캐시 쓰기 |
|------|--------|-----------|-----------|
| — | — | — | — |

*백만 토큰당*

## 강점

- MMLU score 81.2, strong knowledge reasoning.
- HumanEval 83.3, excellent code generation.
- GSM8K 91.8, robust math reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## 약점

- 闭源专有模型，不支持自托管。

## 사용 사례

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## 참고문헌

- [Claude 3 Opus 문서](https://docs.anthropic.com/claude/docs)
- 출시일: 2024-03-04
- 공급업체: Anthropic
