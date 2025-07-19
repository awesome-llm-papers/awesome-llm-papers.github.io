---
layout: publication
title: Automated Paper Screening For Clinical Reviews Using Large Language Models
authors: Guo et al.
conference: Journal of Medical Internet Research
year: 2023
bibkey: guo2023automated
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.00844'}]
tags: [GPT, Tools, Model Architecture, Efficiency And Optimization, Survey Paper,
  Reinforcement Learning, Datasets]
---
Objective: To assess the performance of the OpenAI GPT API in accurately and
efficiently identifying relevant titles and abstracts from real-world clinical
review datasets and compare its performance against ground truth labelling by
two independent human reviewers.
  Methods: We introduce a novel workflow using the OpenAI GPT API for screening
titles and abstracts in clinical reviews. A Python script was created to make
calls to the GPT API with the screening criteria in natural language and a
corpus of title and abstract datasets that have been filtered by a minimum of
two human reviewers. We compared the performance of our model against
human-reviewed papers across six review papers, screening over 24,000 titles
and abstracts.
  Results: Our results show an accuracy of 0.91, a sensitivity of excluded
papers of 0.91, and a sensitivity of included papers of 0.76. On a randomly
selected subset of papers, the GPT API demonstrated the ability to provide
reasoning for its decisions and corrected its initial decision upon being asked
to explain its reasoning for a subset of incorrect classifications.
  Conclusion: The GPT API has the potential to streamline the clinical review
process, save valuable time and effort for researchers, and contribute to the
overall quality of clinical reviews. By prioritizing the workflow and acting as
an aid rather than a replacement for researchers and reviewers, the GPT API can
enhance efficiency and lead to more accurate and reliable conclusions in
medical research.