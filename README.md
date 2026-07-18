# AI Benchmark Hub

> AI Model Benchmark Comparison

## Deployment

- **Production URL**: https://ai-benchmark-f3o.pages.dev/
- **GitHub Repo**: https://github.com/wangdan197902-art/ai-benchmark
- **Cloudflare Project**: ai-benchmark

## Local Development

```bash
# Install Hugo (macOS)
brew install hugo

# Run dev server
hugo server -D

# Build for production
hugo --minify --baseURL "https://ai-benchmark-f3o.pages.dev/"
```

## Auto Deploy

Push to `main` branch → GitHub Actions auto-deploys to Cloudflare Pages.

## Project Structure

```
├── content/           # Markdown content
├── layouts/           # Hugo templates
├── static/            # Static assets (images, CSS)
├── data/              # JSON data files
├── hugo.toml          # Hugo config
├── wrangler.toml      # Cloudflare Pages config
└── .github/workflows/ # CI/CD
```
