---
layout: publication
title: Towards Open-world Recommendation With Knowledge Augmentation From Large Language
  Models
authors: Yunjia Xi et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: xi2023towards
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.10933'}]
tags: [Training Techniques, RecSys, Tools, Reinforcement Learning, Prompting]
---
Recommender systems play a vital role in various online services. However,
the insulated nature of training and deploying separately within a specific
domain limits their access to open-world knowledge. Recently, the emergence of
large language models (LLMs) has shown promise in bridging this gap by encoding
extensive world knowledge and demonstrating reasoning capability. Nevertheless,
previous attempts to directly use LLMs as recommenders have not achieved
satisfactory results. In this work, we propose an Open-World Knowledge
Augmented Recommendation Framework with Large Language Models, dubbed KAR, to
acquire two types of external knowledge from LLMs -- the reasoning knowledge on
user preferences and the factual knowledge on items. We introduce factorization
prompting to elicit accurate reasoning on user preferences. The generated
reasoning and factual knowledge are effectively transformed and condensed into
augmented vectors by a hybrid-expert adaptor in order to be compatible with the
recommendation task. The obtained vectors can then be directly used to enhance
the performance of any recommendation model. We also ensure efficient inference
by preprocessing and prestoring the knowledge from the LLM. Extensive
experiments show that KAR significantly outperforms the state-of-the-art
baselines and is compatible with a wide range of recommendation algorithms. We
deploy KAR to Huawei's news and music recommendation platforms and gain a 7%
and 1.7% improvement in the online A/B test, respectively.