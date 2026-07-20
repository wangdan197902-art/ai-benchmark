---
title: "HumanEval: Benchmark Detailed Guide"
description: "Detailed guide to HumanEval: category, metrics, sources and applicable models."
date: 2022-01-01
lastmod: 2022-01-01
draft: false
weight: 10
benchmark_id: "humaneval"
category: "coding"
tags: ["benchmark", "coding"]
---

# HumanEval

## 説明

OpenAI 发布的 164 道 Python 编程任务，每题包含函数签名、文档字符串、函数体与单元测试，评估模型的代码生成能力（pass@1）。

## コア仕様

| カテゴリ | ライセンス | 最終更新 |
|----------|---------|--------------|
| coding | MIT | 2022-01-01 |

## ベンチマーク

| 単位 |
|------|
| pass@1 |

## ソース

- [Hugging Face](https://huggingface.co/datasets/openai_humaneval)
- [Papers with Code](https://paperswithcode.com/dataset/humaneval)

## 公式URL

- [https://github.com/openai/human-eval](https://github.com/openai/human-eval)
