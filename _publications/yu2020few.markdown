---
layout: publication
title: Few-shot Generative Conversational Query Rewriting
authors: Shi Yu, Jiahua Liu, Jingqin Yang, Chenyan Xiong, Paul Bennett, Jianfeng Gao,
  Zhiyuan Liu
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2020
bibkey: yu2020few
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.05009'}]
tags: ["Few-Shot", "SIGIR"]
short_authors: Yu et al.
---
Conversational query rewriting aims to reformulate a concise conversational
query to a fully specified, context-independent query that can be effectively
handled by existing information retrieval systems. This paper presents a
few-shot generative approach to conversational query rewriting. We develop two
methods, based on rules and self-supervised learning, to generate weak
supervision data using large amounts of ad hoc search sessions, and to
fine-tune GPT-2 to rewrite conversational queries. On the TREC Conversational
Assistance Track, our weakly supervised GPT-2 rewriter improves the
state-of-the-art ranking accuracy by 12%, only using very limited amounts of
manual query rewrites. In the zero-shot learning setting, the rewriter still
gives a comparable result to previous state-of-the-art systems. Our analyses
reveal that GPT-2 effectively picks up the task syntax and learns to capture
context dependencies, even for hard cases that involve group references and
long-turn dependencies.