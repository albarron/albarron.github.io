---
title: 📈 New paper published at IPM (if. 7.4)
summary: 
date: 2025-06-04
tags:
  - knowledge graph construction
  - large language models
  - Code language models
  - Information extraction
  - IPM
image:
  caption: 'A snapshot of the paper'
  
authors:
  - admin
---

## Overview

Research on knowledge graph construction (KGC) has recently shown great promise also thanks to the adoption of large language models (LLM) for the automatic extraction of structured information from raw text. However, most works rely on commercial, closed-source LLMs, hindering reproducibility and accessibility. We explore KGC with smaller, open-weight LLMs and investigate whether they can be used to improve upon the results obtained by systems leveraging bigger, closed-source models. Specifically, we focus on CodeKGC, a prompting framework based on GPT-3.5. We choose a variety of models either pre-trained primarily on natural language or on code and fine-tune them on three datasets used for information extraction. 
We fine-tune with prompts formatted either in natural language or as Python-like scripts. In addition, we optionally train the models with prompts including chain-of-thought sections. After fine-tuning, the choice of coding vs natural language prompts has a limited impact on performance, while chain-of-thought training mostly leads to a performance decrease. Moreover, 

## Go further

- 📚 [**Check the paper**](https://www.sciencedirect.com/science/article/pii/S0306457325001360?via%3Dihub)
