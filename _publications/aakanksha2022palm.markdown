---
layout: publication
title: 'Palm: Scaling Language Modeling With Pathways'
authors: [aakanksha Chowdhery, sharan Narang, jacob Devlin, maarten Bosma, gaurav
    Mishra, adam Roberts, paul Barham, hyung Won Chung, charles Sutton, sebastian
    Gehrmann, parker Schuh, kensen Shi, sasha Tsvyashchenko, joshua Maynez, abhishek
    Rao, parker Barnes, yi Tay, noam Shazeer, vinodkumar Prabhakaran, emily Reif,
  nan Du, ben Hutchinson, reiner Pope, james Bradbury, jacob Austin, michael Isard,
  guy Gur-ari, pengcheng Yin, toju Duke, anselm Levskaya, sanjay Ghemawat, sunipa
    Dev, henryk Michalewski, xavier Garcia, vedant Misra, kevin Robinson, liam Fedus,
  denny Zhou, daphne Ippolito, david Luan, hyeontaek Lim, barret Zoph, alexander Spiridonov,
  ryan Sepassi, david Dohan, shivani Agrawal, mark Omernick, andrew M. Dai, thanumalayan
    Sankaranarayana Pillai, marie Pellat, aitor Lewkowycz, erica Moreira, rewon Child,
  oleksandr Polozov, katherine Lee, zongwei Zhou, xuezhi Wang, brennan Saeta, mark
    Diaz, orhan Firat, michele Catasta, jason Wei, kathy Meier-hellstern, douglas
    Eck, jeff Dean, slav Petrov, noah Fiedel]
conference: Arxiv
year: 2022
bibkey: aakanksha2022palm
citations: 1913
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2204.02311v5'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Chowdhery et al.
---
Large language models have been shown to achieve remarkable performance
across a variety of natural language tasks using few-shot learning, which
drastically reduces the number of task-specific training examples needed to
adapt the model to a particular application. To further our understanding of
the impact of scale on few-shot learning, we trained a 540-billion parameter,
densely activated, Transformer language model, which we call Pathways Language
Model PaLM. We trained PaLM on 6144 TPU v4 chips using Pathways, a new ML
system which enables highly efficient training across multiple TPU Pods. We
demonstrate continued benefits of scaling by achieving state-of-the-art
few-shot learning results on hundreds of language understanding and generation
benchmarks. On a number of these tasks, PaLM 540B achieves breakthrough
performance, outperforming the finetuned state-of-the-art on a suite of
multi-step reasoning tasks, and outperforming average human performance on the
recently released BIG-bench benchmark. A significant number of BIG-bench tasks
showed discontinuous improvements from model scale, meaning that performance
steeply increased as we scaled to our largest model. PaLM also has strong
capabilities in multilingual tasks and source code generation, which we
demonstrate on a wide array of benchmarks. We additionally provide a
comprehensive analysis on bias and toxicity, and study the extent of training
data memorization with respect to model scale. Finally, we discuss the ethical
considerations related to large language models and discuss potential
mitigation strategies.