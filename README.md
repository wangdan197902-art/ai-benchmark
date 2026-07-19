# AI Benchmark Hub — AI 模型对比基准库

> 本地优先、JAMstack 静态架构的 AI 模型对比网站

## 技术栈
- Hugo 0.130+（静态站点生成）
- Python 3.11+（数据采集与 AI 文案生成）
- Cloudflare Pages（生产部署；本地阶段用 `hugo server` 替代）

## 本地启动
```bash
# 1. 安装 Hugo（macOS）
brew install hugo

# 2. 启动 Hugo 开发服务器
hugo server -D --bind 0.0.0.0 --port 1313

# 3. 浏览器访问
open http://localhost:1313/
```

## 项目结构
- `archetypes/` — Hugo 内容模板（default / comparison / model / benchmark）
- `content/{lang}/` — 多语种内容（en / zh 优先）
- `data/` — JSON 数据源（models / benchmarks / pricing / schema）
- `layouts/` — Hugo 自定义模板与 shortcodes（不依赖外部主题）
- `scripts/` — Python 数据采集与生成脚本
- `static/` — 静态资源（css / js / images）

## 多语种
支持 10 语种：en / zh / es / ja / de / fr / ko / pt / ru / it
本地阶段先做 en + zh，其余 8 语种在 config.toml 中占位（disabled = true）。

## 数据模型
- `data/models/*.json` — 模型数据（GPT-4o / Claude 3.5 Sonnet / Gemini 1.5 Pro）
- `data/benchmarks/*.json` — 基准数据（MMLU / HumanEval / GSM8K / MATH / BBH）
- `data/pricing/*.json` — 定价对照数据
- `data/schema/*.json` — JSON Schema 定义（model_schema / benchmark_schema）

> 所有 fixture 数据均标注 `"data_source": "fixture_for_local_testing"`，仅用于本地验证。

## 开发阶段
- **阶段 A（P0）**：纯静态 Fixture + Hugo 构建
- **阶段 B（P1）**：Mock Server + 真实 Python 脚本全链路
- **阶段 C（P2，可选）**：Adapter 架构重构
