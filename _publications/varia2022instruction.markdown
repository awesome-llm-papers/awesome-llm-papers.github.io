---
layout: publication
title: Instruction Tuning For Few-shot Aspect-based Sentiment Analysis
authors: Siddharth Varia et al.
conference: Arxiv
year: 2022
citations: 15
bibkey: varia2022instruction
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.06629'}]
tags: [Few-Shot, Tools, Prompting]
---
Aspect-based Sentiment Analysis (ABSA) is a fine-grained sentiment analysis
task which involves four elements from user-generated texts: aspect term,
aspect category, opinion term, and sentiment polarity. Most computational
approaches focus on some of the ABSA sub-tasks such as tuple (aspect term,
sentiment polarity) or triplet (aspect term, opinion term, sentiment polarity)
extraction using either pipeline or joint modeling approaches. Recently,
generative approaches have been proposed to extract all four elements as (one
or more) quadruplets from text as a single task. In this work, we take a step
further and propose a unified framework for solving ABSA, and the associated
sub-tasks to improve the performance in few-shot scenarios. To this end, we
fine-tune a T5 model with instructional prompts in a multi-task learning
fashion covering all the sub-tasks, as well as the entire quadruple prediction
task. In experiments with multiple benchmark datasets, we show that the
proposed multi-task prompting approach brings performance boost (by absolute
8.29 F1) in the few-shot learning setting.