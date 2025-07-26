---
layout: publication
title: Entity-relation Extraction As Multi-turn Question Answering
authors: Xiaoya Li, Fan Yin, Zijun Sun, Xiayu Li, Arianna Yuan, Duo Chai, Mingxin
  Zhou, Jiwei Li
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: li2019entity
citations: 327
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.05529'}]
tags: ["Datasets"]
short_authors: Li et al.
---
In this paper, we propose a new paradigm for the task of entity-relation
extraction. We cast the task as a multi-turn question answering problem, i.e.,
the extraction of entities and relations is transformed to the task of
identifying answer spans from the context. This multi-turn QA formalization
comes with several key advantages: firstly, the question query encodes
important information for the entity/relation class we want to identify;
secondly, QA provides a natural way of jointly modeling entity and relation;
and thirdly, it allows us to exploit the well developed machine reading
comprehension (MRC) models. Experiments on the ACE and the CoNLL04 corpora
demonstrate that the proposed paradigm significantly outperforms previous best
models. We are able to obtain the state-of-the-art results on all of the ACE04,
ACE05 and CoNLL04 datasets, increasing the SOTA results on the three datasets
to 49.4 (+1.0), 60.2 (+0.6) and 68.9 (+2.1), respectively. Additionally, we
construct a newly developed dataset RESUME in Chinese, which requires
multi-step reasoning to construct entity dependencies, as opposed to the
single-step dependency extraction in the triplet exaction in previous datasets.
The proposed multi-turn QA model also achieves the best performance on the
RESUME dataset.