---
title: "CCommon Objects Out of Context (COOCo): Investigating Multimodal Context and Semantic Scene Violations in Referential Communication"
collection: publications
category: manuscripts
permalink: '/publication/2025-06-27-paper-title-cooco'
excerpt: ''
date: 2026-06-01
venue: 'Transactions of the Association for Computational Linguistics (2026) 14: 1163–1185.'
#slidesurl: ''
paperurl: 'https://doi.org/10.1162/TACL.a.701'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: ''
---
Natural scenes provide us with rich contexts for object recognition and reference. In particular, knowing what type of scene one is looking at generates expectations about which objects will occur, and what their spatial configuration should be. Do VisionLanguage Models (VLMs) learn to rely on scene contexts in a similar way, when generating references to objects? To address this question, we introduce the Common Objects Out-of-Context (COOCO) dataset and test to what extent VLMs rely on scene context to refer to objects under different degrees of scene-object congruency, and different perturbations. Our findings show that models leverage scene context adaptively, depending on both the semantic relatedness between object and scene and the level of noise. In particular, models rely more on context under high target-scene congruence or when objects are degraded. Attention analysis reveals that successful object categorisation involves increased focus on the target in mid-level layers, especially under moderate noise, suggesting that VLMs dynamically balance local and contextual information for reference generation.

[Dataset](https://huggingface.co/datasets/fmerlo/COOCO)
