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

## Tổng quan mô hình

Microsoft Phi-3 Vision 4.2B 多模态模型, 4K 上下文, 支持图像理解, 在 4B 规模上多模态能力领先。

## Thông số kỹ thuật cốt lõi

| Nhà cung cấp | Phiên bản | Ngày phát hành | Cửa sổ ngữ cảnh | Phương thức đầu vào | Phương thức đầu ra | Giấy phép |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-vision | 2024-05-21 | 4K | text, image | text | MIT |

## Hiệu suất benchmark

| Benchmark | Điểm | Đơn vị | Ghi chú |
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

## Giá

| Đầu vào | Đầu ra | Đọc bộ nhớ đệm | Ghi bộ nhớ đệm |
|------|--------|-----------|-----------|
| — | — | — | — |

*mỗi triệu token*

## Điểm mạnh

- 支持文本、图像、音频多模态输入。

## Điểm yếu

- MMLU 仅 56.4，知识推理偏弱。
- HumanEval 48.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Trường hợp sử dụng

- 视觉与图像理解

## Tham chiếu

- [Phi-3 Vision Tài liệu](https://huggingface.co/models)
- Ngày phát hành: 2024-05-21
- Nhà cung cấp: Other
