---
layout: publication
title: Large Language Models As Batteries-included Zero-shot ESCO Skills Matchers
authors: "Clavi\xE9 Benjamin, Souli\xE9 Guillaume"
conference: Proceedings of the 32nd ACM International Conference on Information and
  Knowledge Management
year: 2023
bibkey: "clavi\xE92023large"
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.03539'}]
tags: [Training Techniques, GPT, Prompting, Tools, Model Architecture, CIKM, Reinforcement
    Learning]
---
Understanding labour market dynamics requires accurately identifying the
skills required for and possessed by the workforce. Automation techniques are
increasingly being developed to support this effort. However, automatically
extracting skills from job postings is challenging due to the vast number of
existing skills. The ESCO (European Skills, Competences, Qualifications and
Occupations) framework provides a useful reference, listing over 13,000
individual skills. However, skills extraction remains difficult and accurately
matching job posts to the ESCO taxonomy is an open problem. In this work, we
propose an end-to-end zero-shot system for skills extraction from job
descriptions based on large language models (LLMs). We generate synthetic
training data for the entirety of ESCO skills and train a classifier to extract
skill mentions from job posts. We also employ a similarity retriever to
generate skill candidates which are then re-ranked using a second LLM. Using
synthetic data achieves an RP@10 score 10 points higher than previous distant
supervision approaches. Adding GPT-4 re-ranking improves RP@10 by over 22
points over previous methods. We also show that Framing the task as mock
programming when prompting the LLM can lead to better performance than natural
language prompts, especially with weaker LLMs. We demonstrate the potential of
integrating large language models at both ends of skills matching pipelines.
Our approach requires no human annotations and achieve extremely promising
results on skills extraction against ESCO.