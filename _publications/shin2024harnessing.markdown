---
layout: publication
title: Harnessing Pubmed User Query Logs For Post Hoc Explanations Of Recommended
  Similar Articles
authors: Shin et al.
conference: ACM Transactions on Information Systems
year: 2024
bibkey: shin2024harnessing
citations: 243
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.03484'}]
tags: [Interpretability And Explainability, GPT, Evaluation, Transformer, Model Architecture,
  Reinforcement Learning, Datasets]
---
Searching for a related article based on a reference article is an integral
part of scientific research. PubMed, like many academic search engines, has a
"similar articles" feature that recommends articles relevant to the current
article viewed by a user. Explaining recommended items can be of great utility
to users, particularly in the literature search process. With more than a
million biomedical papers being published each year, explaining the recommended
similar articles would facilitate researchers and clinicians in searching for
related articles. Nonetheless, the majority of current literature
recommendation systems lack explanations for their suggestions. We employ a
post hoc approach to explaining recommendations by identifying relevant tokens
in the titles of similar articles. Our major contribution is building PubCLogs
by repurposing 5.6 million pairs of coclicked articles from PubMed's user query
logs. Using our PubCLogs dataset, we train the Highlight Similar Article Title
(HSAT), a transformer-based model designed to select the most relevant parts of
the title of a similar article, based on the title and abstract of a seed
article. HSAT demonstrates strong performance in our empirical evaluations,
achieving an F1 score of 91.72 percent on the PubCLogs test set, considerably
outperforming several baselines including BM25 (70.62), MPNet (67.11), MedCPT
(62.22), GPT-3.5 (46.00), and GPT-4 (64.89). Additional evaluations on a
separate, manually annotated test set further verifies HSAT's performance.
Moreover, participants of our user study indicate a preference for HSAT, due to
its superior balance between conciseness and comprehensiveness. Our study
suggests that repurposing user query logs of academic search engines can be a
promising way to train state-of-the-art models for explaining literature
recommendation.