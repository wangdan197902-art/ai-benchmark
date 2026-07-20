---
title: "HumanEval：基准测试详解"
description: "详细介绍 HumanEval 基准：分类、评估指标、数据来源与适用模型。"
date: 2022-01-01
lastmod: 2022-01-01
draft: false
weight: 10
benchmark_id: "humaneval"
category: "coding"
tags: ["benchmark", "coding"]
---

# HumanEval

## 描述

OpenAI 发布的 164 道 Python 编程任务，每题包含函数签名、文档字符串、函数体与单元测试，评估模型的代码生成能力（pass@1）。

## 核心规格

| 分类 | 许可证 | 最后更新 |
|----------|---------|--------------|
| coding | MIT | 2022-01-01 |

## 基准

| 单位 |
|------|
| pass@1 |

## 数据来源

- [Hugging Face](https://huggingface.co/datasets/openai_humaneval)
- [Papers with Code](https://paperswithcode.com/dataset/humaneval)

## 官方地址

- [https://github.com/openai/human-eval](https://github.com/openai/human-eval)
