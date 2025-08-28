# Open-Ended Keyword Suppression Evaluation Results

This repository contains interactive evaluation results from keyword suppression experiments on AI models using open-ended questions.

## 🌐 Live Demo

View the interactive results by deploying this repository to GitHub Pages.

## 📊 Dataset Overview

- **3 representative AI models** from the evaluation
- **Keyword avoidance experiments** with adversarial pressure
- **Open-ended questions** testing natural language generation compliance
- **Interactive conversation viewer** with detailed logs

### Featured Models

1. **DeepSeek R1-Distill 32B** - Advanced reasoning model with distillation
2. **Claude Opus 4** - Anthropic's flagship conversational AI
3. **GPT-OSS 120B** - Large-scale language model

## 🔬 Experiment Design

These evaluations test how well AI models can avoid using specific forbidden words while answering open-ended questions. The evaluation includes:

- **Keyword suppression**: Models must avoid specified forbidden words
- **Synonym handling**: Models must also avoid synonyms of forbidden words
- **Natural responses**: Models should provide helpful answers despite constraints
- **Adversarial pressure**: Testing robustness under various pressure conditions

## 📁 File Structure

```
oe-logs-final/
├── index.html              # Interactive viewer
├── .nojekyll               # GitHub Pages configuration
├── robots.txt              # Search indexing configuration
├── assets/                 # Viewer assets
│   ├── index.js           # Viewer JavaScript
│   ├── index.css          # Viewer styles
│   └── favicon.svg        # Site icon
└── logs/                   # Evaluation data
    ├── logs.json          # Index of evaluation results
    └── *.eval             # Individual model evaluation results
```

## 🚀 Deployment

### GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Save and wait for deployment

Your site will be available at: `https://yourusername.github.io/repository-name/`

## 📝 Results Summary

The evaluation reveals interesting patterns in how different model architectures handle keyword suppression:

- **Compliance rates** vary significantly across models
- **Restatement patterns** show different strategies for handling constraints
- **Response quality** demonstrates trade-offs between compliance and helpfulness

## 🔗 Related Work

- [Inspect AI Framework](https://inspect.aisi.org.uk/) - Evaluation framework used
- [Original Research](https://github.com/YuehHanChen/ccot) - Full research codebase

---

*Generated from Inspect AI evaluation logs. Contains representative samples from a larger evaluation dataset.*
