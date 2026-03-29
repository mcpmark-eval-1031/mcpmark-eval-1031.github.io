# Junteng Liu — Academic Website

Personal academic website of **Junteng Liu**, a PhD candidate at the [HKUST NLP Group](https://github.com/HKUNLP), [Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/), advised by [Prof. Junxian He](https://jxhe.github.io/).

🌐 **Live site:** [https://mcpmark-eval-1031.github.io](https://mcpmark-eval-1031.github.io)

## About

This repository hosts Junteng Liu's academic personal website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and served via GitHub Pages.

**Junteng Liu** is a first-year PhD candidate at HKUST (2024–Present), researching:
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLMs)
- LLM Truthfulness and Interpretability

📧 Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)  
🐙 GitHub: [Vicent0205](https://github.com/Vicent0205)  
🎓 Google Scholar: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)  
🐦 X / Twitter: [@junteng88716710](https://twitter.com/junteng88716710)

## Repository Structure

| Path | Purpose |
|------|--------|
| `_config.yml` | Site-wide configuration (author info, URL, social links) |
| `_pages/about.md` | Homepage / About page |
| `_pages/cv.md` | CV / Resume page |
| `_publications/` | Individual publication entries (6 papers) |
| `_data/navigation.yml` | Site navigation (About, Publications, CV) |

## Building Locally

```bash
# Install dependencies
bundle install

# Serve locally at http://localhost:4000
bundle exec jekyll serve -l -H localhost
```

Or use Docker:
```bash
docker compose up
```

## Template

Built on [Academic Pages](https://github.com/academicpages/academicpages.github.io) — a Jekyll theme for academic personal websites, forked from [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/).
