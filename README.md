<p align="center">
  <img src="https://img.shields.io/badge/models-10-00D9FF?style=for-the-badge" alt="10 Models">
  <img src="https://img.shields.io/badge/presets-6-FF6D5A?style=for-the-badge" alt="6 Presets">
  <img src="https://img.shields.io/badge/platform-n8n-FF6D5A?style=for-the-badge" alt="n8n">
  <img src="https://img.shields.io/badge/no_backend-static_HTML-3fb950?style=for-the-badge" alt="Static HTML">
  <img src="https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge" alt="MIT">
  <img src="https://img.shields.io/github/stars/enzoemir1/n8n-cost-calculator?style=for-the-badge&color=FFD700" alt="Stars">
</p>

<h1 align="center">n8n AI Cost Calculator</h1>

<p align="center">
  <strong>Estimate your AI workflow costs before you build.</strong><br/>
  Compare 10 models, use quick presets, and find the cheapest way to run your n8n automations.
</p>

---

## Features

- **10 AI models** with real pricing (GPT-4o, GPT-4o-mini, Claude 3.5, Gemini, Llama, DeepSeek, and more)
- **Real-time calculation** — sliders update cost per run, daily, monthly, and yearly instantly
- **6 workflow presets** — Content Repurposing, Email Classifier, Support Bot, Web Scraping, Lead Scoring, RAG Chatbot
- **Model comparison table** — see all models side-by-side, sorted by cost, with savings percentages
- **7 cost optimization tips** — practical advice to reduce your AI spend
- **Zero dependencies** — single HTML file, no backend, no framework, no CDN
- **Mobile responsive** — works on any device
- **Dark theme** — easy on the eyes

---

## Quick Start

### Option 1: Open directly

```bash
git clone https://github.com/enzoemir1/n8n-cost-calculator.git
open n8n-cost-calculator/index.html
```

### Option 2: GitHub Pages

Visit the live version: `https://enzoemir1.github.io/n8n-cost-calculator/`

---

## Supported Models

| Model | Input (per 1M tokens) | Output (per 1M tokens) | Notes |
|-------|----------------------|------------------------|-------|
| GPT-4o | $2.50 | $10.00 | Best quality, highest cost |
| GPT-4o-mini | $0.15 | $0.60 | Best quality/cost ratio |
| GPT-3.5-turbo | $0.50 | $1.50 | Legacy, still decent |
| Claude 3.5 Sonnet | $3.00 | $15.00 | Premium quality |
| Claude 3 Haiku | $0.25 | $1.25 | Fast and cheap |
| Gemini 1.5 Flash | $0.075 | $0.30 | Cheapest paid option |
| Gemini 1.5 Pro | $1.25 | $5.00 | Google premium |
| DeepSeek V2 | $0.14 | $0.28 | Budget friendly |
| Llama 3.1 70B (Groq) | FREE | FREE | Free tier available |
| Mistral 7B (local) | FREE | FREE | Run on your own hardware |

*Prices as of 2026. Check provider websites for current pricing.*

---

## Workflow Presets

Click any preset to auto-fill realistic parameters:

| Preset | Input Tokens | Output Tokens | AI Nodes | Runs/Day | Default Model |
|--------|-------------|---------------|----------|----------|---------------|
| Content Repurposing | 2,000 | 800 | 2 | 20 | gpt-4o-mini |
| Email Classifier | 500 | 200 | 1 | 100 | gpt-3.5-turbo |
| Support Bot | 800 | 500 | 3 | 50 | gpt-4o-mini |
| Web Scraping + AI | 3,000 | 400 | 2 | 200 | gpt-4o-mini |
| Lead Scoring | 600 | 400 | 2 | 30 | gpt-4o-mini |
| RAG Chatbot | 1,500 | 600 | 2 | 500 | gpt-4o-mini |

---

## How Cost Is Calculated

```
Cost per Run = (input_tokens x input_price / 1,000,000
              + output_tokens x output_price / 1,000,000)
              x number_of_ai_nodes

Daily Cost   = Cost per Run x runs_per_day
Monthly Cost = Daily Cost x 30
Yearly Cost  = Daily Cost x 365
```

---

## Also by Automatia BCN

- **[autoflow-n8n-workflows](https://github.com/enzoemir1/autoflow-n8n-workflows)** — 8 free AI automation workflows for n8n
- **[n8n-prompt-library](https://github.com/enzoemir1/n8n-prompt-library)** — 20 production-ready AI prompts for n8n
- **[n8n-telegram-approval](https://github.com/enzoemir1/n8n-telegram-approval)** — Human-in-the-loop approval via Telegram
- **[free-ai-prompts](https://github.com/enzoemir1/free-ai-prompts)** — 90 free AI prompts for ChatGPT, Gemini & more

---

## License

MIT License — free for personal and commercial use.

---

<p align="center">
  <strong>If this saves you money, a star would mean a lot!</strong>
</p>
