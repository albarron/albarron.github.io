---
title: Fine-Tuning vs Prompting Techniques for Gender-Fair Rewriting of Machine Translations
authors:
- Paolo Mainardi
- Federico Garcea
- Alberto Barrón-Cedeño
date: '2025-08-01'
publishDate: '2025-08-13T19:23:48.235411Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 6th Workshop on Gender Bias in Natural Language
  Processing (GeBNLP)*'
doi: 10.18653/v1/2025.gebnlp-1.28
abstract: Increasing attention is being dedicated by the NLP community to gender-fair
  practices, including emerging forms of non-binary language. Given the shift to the
  prompting paradigm for multiple tasks, direct comparisons between prompted and fine-tuned
  models in this context are lacking. We aim to fill this gap by comparing prompt
  engineering and fine-tuning techniques for gender-fair rewriting in Italian. We
  do so by framing a rewriting task where Italian gender-marked translations from
  English gender-ambiguous sentences are adapted into a gender-neutral alternative
  using direct non-binary language. We augment existing datasets with gender-neutral
  translations and conduct experiments to determine the best architecture and approach
  to complete such task, by fine-tuning and prompting seq2seq encoder-decoder and
  autoregressive decoder-only models. We show that smaller seq2seq models can reach
  good performance when fine-tuned, even with relatively little data; when it comes
  to prompts, including task demonstrations is crucial, and we find that chat-tuned
  models reach the best results in a few-shot setting. We achieve promising results,
  especially in contexts of limited data and resources.
links:
- name: URL
  url: https://aclanthology.org/2025.gebnlp-1.28/
---
