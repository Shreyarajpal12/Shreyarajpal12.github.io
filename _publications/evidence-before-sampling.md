---
title: "Evidence Before Sampling: Interpretable Implicit Negative Candidate Discovery for Recommendation"
collection: publications
permalink: /publication/evidence-before-sampling
date: 2026-10-06
venue: "arXiv preprint"
featured: false
paperurl: "https://arxiv.org/pdf/2610.07708"
description: "Intuit research led by Shreya Rajpal on interpretable, evidence-backed discovery of implicit negative candidates for recommender systems."
authors:
  - "Shreya Rajpal"
  - "Sonia Sharma"
  - "Swapnil Parekh"
  - "Lisa Li"
  - "Jeyendran Balakrishnan"
  - "Nagaraj Janardhana"
  - "Andrew Mattarella-Micke"
---

**Shreya Rajpal**, Sonia Sharma, Swapnil Parekh, Lisa Li, Jeyendran Balakrishnan, Nagaraj Janardhana, and Andrew Mattarella-Micke.

Recommender systems often lack explicit negative feedback. Instead of sampling negatives at random, we discover unobserved user-item pairs that are supported by observed customer behavior, encode these patterns as symbolic rules scored on support, informativeness, and product relevance, and use an LLM to interpret them against business objectives. On an industrial B2B dataset and five public datasets, the approach yields higher candidate precision than baselines and a 12.5% gain in downstream test PR-AUC over random selection in the industrial task.
