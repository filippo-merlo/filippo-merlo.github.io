---
title: "Exploring the Impact of Tokenization Strategies on Machine Translation using Transformer Seq2Seq Architecture"
excerpt: "This project examines how different tokenization strategies—character-level, word-level, and subword-level (WordPiece)—affect the translation quality of Transformer-based Neural Machine Translation models, hypothesizing that subword-level tokenization offers the best trade-off between vocabulary efficiency and performance as measured by BLEU scores.<img src='/images/transformer.png' width='300' style='display: block; margin-left: auto; margin-right: auto;'>"
collection: portfolio
---

Transformers have significantly improved Neural Machine Translation (NMT) by removing the constraints of sequential processing, allowing for more efficient training and scalability to larger datasets. However, the performance of these models is highly sensitive to the tokenization strategy used, which breaks down text into tokens that the model can process. Tokenization directly impacts the model's input representation, influencing its ability to capture linguistic nuances and, consequently, its translation quality.

This project investigates three tokenization methods:

Character-level tokenization: Treats each character as a separate token, capturing detailed information but resulting in longer sequences that complicate training.

Word-level tokenization: Treats each word as an individual token, simplifying implementation but struggling with out-of-vocabulary (OOV) words and leading to a large vocabulary.

WordPiece tokenization: A subword-level approach that balances vocabulary size and OOV handling by breaking words into smaller subwords.

We hypothesize that different tokenization strategies significantly impact the translation quality of Transformer-based Seq2Seq models, measured using the Bilingual Evaluation Understudy (BLEU) score. WordPiece tokenization is expected to offer the best trade-off between vocabulary size and translation performance.

[Document 1](../../files/merlo_MLI_research_design.pdf)  [Document 2](../../files/merlo_MLI_experiment.pdf) [Code](https://github.com/filippo-merlo/transformer_translate_en_it.git)