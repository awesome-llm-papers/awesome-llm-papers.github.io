---
layout: publication
title: 'FLEX: Unifying Evaluation For Few-shot NLP'
authors: Jonathan Bragg, Arman Cohan, Kyle Lo, Iz Beltagy
conference: Arxiv
year: 2021
citations: 52
bibkey: bragg2021unifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.07170'}]
tags: [Few-Shot, Training Techniques, Prompting]
---
Few-shot NLP research is highly active, yet conducted in disjoint research
threads with evaluation suites that lack challenging-yet-realistic testing
setups and fail to employ careful experimental design. Consequently, the
community does not know which techniques perform best or even if they
outperform simple baselines. In response, we formulate the FLEX Principles, a
set of requirements and best practices for unified, rigorous, valid, and
cost-sensitive few-shot NLP evaluation. These principles include Sample Size
Design, a novel approach to benchmark design that optimizes statistical
accuracy and precision while keeping evaluation costs manageable. Following the
principles, we release the FLEX benchmark, which includes four few-shot
transfer settings, zero-shot evaluation, and a public leaderboard that covers
diverse NLP tasks. In addition, we present UniFew, a prompt-based model for
few-shot learning that unifies pretraining and finetuning prompt formats,
eschewing complex machinery of recent prompt-based approaches in adapting
downstream task formats to language model pretraining objectives. We
demonstrate that despite simplicity, UniFew achieves results competitive with
both popular meta-learning and prompt-based approaches.