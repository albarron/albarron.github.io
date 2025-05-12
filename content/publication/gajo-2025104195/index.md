---
title: Natural vs programming language in LLM knowledge graph construction
authors:
- Paolo Gajo
- Alberto Barrón-Cedeño
date: '2025-01-01'
publishDate: '2025-05-12T16:06:04.468084Z'
publication_types:
- article-journal
publication: '*Information Processing & Management*'
doi: https://doi.org/10.1016/j.ipm.2025.104195
abstract: 'Research on knowledge graph construction (KGC) has recently shown great
  promise also thanks to the adoption of large language models (LLM) for the automatic
  extraction of structured information from raw text. However, most works rely on
  commercial, closed-source LLMs, hindering reproducibility and accessibility. We
  explore KGC with smaller, open-weight LLMs and investigate whether they can be used
  to improve upon the results obtained by systems leveraging bigger, closed-source
  models. Specifically, we focus on CodeKGC, a prompting framework based on GPT-3.5.
  We choose a variety of models either pre-trained primarily on natural language or
  on code and fine-tune them on three datasets used for information extraction. We
  fine-tune with prompts formatted either in natural language or as Python-like scripts.
  In addition, we optionally train the models with prompts including chain-of-thought
  sections. After fine-tuning, the choice of coding vs natural language prompts has
  a limited impact on performance, while chain-of-thought training mostly leads to
  a performance decrease. Moreover, we show that a LLM can be outperformed by much
  smaller versions on this task, after undergoing the same amount of training. We
  find that in general the selected lightweight LLMs outperform the much larger CodeKGC
  by as much as 15–20 absolute F1 points after fine-tuning. The results show that
  state-of-the-art KGC systems can be developed using smaller and open-weight models,
  enhancing research transparency, lowering compute requirements, and decreasing third-party
  API reliance. Code:'
tags:
- Knowledge graph construction
- large language models
- Code language models
- Information extraction
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0306457325001360
---
