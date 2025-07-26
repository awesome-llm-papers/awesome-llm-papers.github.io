---
layout: publication
title: 'Lila: A Unified Benchmark For Mathematical Reasoning'
authors: Swaroop Mishra, Matthew Finlayson, Pan Lu, Leonard Tang, Sean Welleck, Chitta
  Baral, Tanmay Rajpurohit, Oyvind Tafjord, Ashish Sabharwal, Peter Clark, Ashwin
  Kalyan
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: mishra2022lila
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.17517'}]
tags: ["Datasets", "EMNLP", "Evaluation"]
short_authors: Mishra et al.
---
Mathematical reasoning skills are essential for general-purpose intelligent
systems to perform tasks from grocery shopping to climate modeling. Towards
evaluating and improving AI systems in this domain, we propose LILA, a unified
mathematical reasoning benchmark consisting of 23 diverse tasks along four
dimensions: (i) mathematical abilities e.g., arithmetic, calculus (ii) language
format e.g., question-answering, fill-in-the-blanks (iii) language diversity
e.g., no language, simple language (iv) external knowledge e.g., commonsense,
physics. We construct our benchmark by extending 20 datasets benchmark by
collecting task instructions and solutions in the form of Python programs,
thereby obtaining explainable solutions in addition to the correct answer. We
additionally introduce two evaluation datasets to measure out-of-distribution
performance and robustness to language perturbation. Finally, we introduce
BHASKARA, a general-purpose mathematical reasoning model trained on LILA.
Importantly, we find that multi-tasking leads to significant improvements
(average relative improvement of 21.83% F1 score vs. single-task models), while
the best performing model only obtains 60.40%, indicating the room for
improvement in general mathematical reasoning and understanding.