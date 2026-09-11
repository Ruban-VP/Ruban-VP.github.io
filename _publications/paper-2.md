---
title: "SASC: Soft-Averaged Self-Consistency to Improve Chain-of-Thought Reasoning in Instruct-LLMs"
collection: publications
category: workshops
permalink: /publication/paper-2
excerpt: ''
date: 2026-07-10
venue: 'ICML 2026 Workshop on Structured Probabilistic Inference & Generative Modeling'
slidesurl:
paperurl:
bibtexurl: 'https://Ruban-VP.github.io/files/paper_2_bibtex.bib'
citation:
---
**Abstract:**
Improving the reasoning performance of LLMs during inference by combining scores of multiple output reasoning traces has emerged as a prominent technique, particularly for Chain-of-Thought Instruct-LLM models. Methods such as Self-Consistency and Self-Certainty assign simple yet effective metrics to the generated outputs which are then used to determine the final answer. These methods fit into the framework of designing a score vector over the set of generated answers, using weighted averaging of one-hot hard-decision vectors. In this work, we propose Soft-Averaged Self-Consistency, a simple method in which the hard-decision vectors are replaced with the conditional probability vectors obtained from the LLM logits, forming our soft-decision vectors. We show that our theoretically motivated method provides improved accuracy when compared against other baselines, backed by extensive experiments on a variety of tasks and models.