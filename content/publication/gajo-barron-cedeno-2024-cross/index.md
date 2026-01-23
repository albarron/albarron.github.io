---
title: On Cross-Language Entity Label Projection and Recognition
authors:
- Paolo Gajo
- Alberto Barrón-Cedeño
date: '2024-12-01'
publishDate: '2026-01-22T16:17:01.364061Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Tenth Italian Conference on Computational Linguistics
  (CLiC-it 2024)*'
abstract: 'Most work on named entity recognition (NER) focuses solely on English.
  Through the use of training data augmentation via machine translation (MT), multilingual
  NER can become a powerful tool for information extraction in multilingual contexts.
  In this paper, we augment NER data from culinary recipe ingredient lists, by means
  of MT and word alignment (WA), following two approaches: (i) translating each entity
  separately, while taking into account the full context of the list and (ii) translating
  the whole list of ingredients and then aligning entities using three types of WA
  models: Giza++, Fast Align, and BERT, fine-tuned using a novel entity-shuffling
  approach. We depart from English data and produce Italian versions via MT, span-annotated
  with the entities projected from English. Then, we use the data produced by the
  two approaches to train mono- and multilingual NER BERT models. We test the performance
  of the WA and NER models on an annotated dataset of ingredient lists, partially
  out-of-domain compared to the training data. The results show that shuffling entities
  leads to better BERT aligner models. The higher quality NER data created by these
  models enables NER models to achieve better results, with multilingual models reaching
  performances equal to or greater than their monolingual counterparts.'
links:
- name: URL
  url: https://aclanthology.org/2024.clicit-1.47/
---
