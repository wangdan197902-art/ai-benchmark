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

## Tổng quan mô hình

清华智谱 ChatGLM3 6B 第三代开源模型, 32K 上下文, 6B 参数, 中英双语对话能力突出, 适合本地部署。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | chatglm3-6b | 2023-10-27 | 32K | text | text | GLM-3 License |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
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

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 可靠的通用模型。

## Điểm yếu

- MMLU 仅 58.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。

## Trường hợp sử dụng

- 通用对话与问答

## Tham chiếu

- [ChatGLM3 6B Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2023-10-27
- Nhà cung cấp: Other
