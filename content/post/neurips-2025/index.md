---
title: 📈 New paper published at NeurIPS 2025 Main Conference Track
summary: 
date: 2025-12-02
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

Dependency parsing is the task of inferring natural language structure, often 
approached by modeling word interactions via attention through biaffine scoring. 
This mechanism works like self-attention in Transformers, where scores are 
calculated for every pair of words in a sentence. However, unlike Transformer 
attention, biaffine scoring does not use normalization prior to taking the 
softmax of the scores. In this paper, we provide theoretical evidence and 
empirical results revealing that a lack of normalization necessarily results in 
overparameterized parser models, where the extra parameters compensate for the 
sharp softmax outputs produced by high variance inputs to the biaffine scoring 
function. We argue that biaffine scoring can be made substantially more 
efficient by performing score normalization. We conduct experiments on semantic 
and syntactic dependency parsing in multiple languages, along with latent graph 
inference on non-linguistic data, using various settings of a k-hop parser. We 
train N-layer stacked BiLSTMs and evaluate the parser's performance with and 
without normalizing biaffine scores. Normalizing allows us to achieve 
state-of-the-art performance with fewer samples and trainable parameters. 

## Go further

- 📚 [**Check the paper**](https://proceedings.neurips.cc/paper_files/paper/2025/hash/d2eb69b5b07dd88e8dd86f1cb4e059db-Abstract-Conference.html)
- 🧑‍💻 [**Code**](https://github.com/paolo-gajo/EfficientSDP)
