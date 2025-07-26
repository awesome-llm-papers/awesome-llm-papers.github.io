---
layout: publication
title: 'MMM: Multi-stage Multi-task Learning For Multi-choice Reading Comprehension'
authors: di Jin, Shuyang Gao, Jiun-yu Kao, Tagyoung Chung, Dilek Hakkani-tur
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: jin2019mmm
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.00458'}]
tags: ["AAAI"]
short_authors: Jin et al.
---
Machine Reading Comprehension (MRC) for question answering (QA), which aims
to answer a question given the relevant context passages, is an important way
to test the ability of intelligence systems to understand human language.
Multiple-Choice QA (MCQA) is one of the most difficult tasks in MRC because it
often requires more advanced reading comprehension skills such as logical
reasoning, summarization, and arithmetic operations, compared to the extractive
counterpart where answers are usually spans of text within given passages.
Moreover, most existing MCQA datasets are small in size, making the learning
task even harder. We introduce MMM, a Multi-stage Multi-task learning framework
for Multi-choice reading comprehension. Our method involves two sequential
stages: coarse-tuning stage using out-of-domain datasets and multi-task
learning stage using a larger in-domain dataset to help model generalize better
with limited data. Furthermore, we propose a novel multi-step attention network
(MAN) as the top-level classifier for this task. We demonstrate MMM
significantly advances the state-of-the-art on four representative MCQA
datasets.