---
layout: publication
title: 'DREAM: A Challenge Dataset And Models For Dialogue-based Reading Comprehension'
authors: Kai Sun, Dian Yu, Jianshu Chen, Dong Yu, Yejin Choi, Claire Cardie
conference: Arxiv
year: 2019
bibkey: sun2019dream
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.00164'}]
tags: ["Datasets"]
short_authors: Sun et al.
---
We present DREAM, the first dialogue-based multiple-choice reading
comprehension dataset. Collected from English-as-a-foreign-language
examinations designed by human experts to evaluate the comprehension level of
Chinese learners of English, our dataset contains 10,197 multiple-choice
questions for 6,444 dialogues. In contrast to existing reading comprehension
datasets, DREAM is the first to focus on in-depth multi-turn multi-party
dialogue understanding. DREAM is likely to present significant challenges for
existing reading comprehension systems: 84% of answers are non-extractive, 85%
of questions require reasoning beyond a single sentence, and 34% of questions
also involve commonsense knowledge.
  We apply several popular neural reading comprehension models that primarily
exploit surface information within the text and find them to, at best, just
barely outperform a rule-based approach. We next investigate the effects of
incorporating dialogue structure and different kinds of general world knowledge
into both rule-based and (neural and non-neural) machine learning-based reading
comprehension models. Experimental results on the DREAM dataset show the
effectiveness of dialogue structure and general world knowledge. DREAM will be
available at https://dataset.org/dream/.