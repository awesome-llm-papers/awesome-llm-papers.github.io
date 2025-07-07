---
layout: publication
title: 'Leancontext: Cost-efficient Domain-specific Question Answering Using Llms'
authors: Md Adnan Arefeen, Biplob Debnath, Srimat Chakradhar
conference: Arxiv
year: 2023
citations: 18
bibkey: arefeen2023cost
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.00841'}]
tags: [Tools, Agentic, Reinforcement Learning, Arxiv]
---
Question-answering (QA) is a significant application of Large Language Models
(LLMs), shaping chatbot capabilities across healthcare, education, and customer
service. However, widespread LLM integration presents a challenge for small
businesses due to the high expenses of LLM API usage. Costs rise rapidly when
domain-specific data (context) is used alongside queries for accurate
domain-specific LLM responses. One option is to summarize the context by using
LLMs and reduce the context. However, this can also filter out useful
information that is necessary to answer some domain-specific queries. In this
paper, we shift from human-oriented summarizers to AI model-friendly summaries.
Our approach, LeanContext, efficiently extracts \\(k\\) key sentences from the
context that are closely aligned with the query. The choice of \\(k\\) is neither
static nor random; we introduce a reinforcement learning technique that
dynamically determines \\(k\\) based on the query and context. The rest of the less
important sentences are reduced using a free open source text reduction method.
We evaluate LeanContext against several recent query-aware and query-unaware
context reduction approaches on prominent datasets (arxiv papers and BBC news
articles). Despite cost reductions of \\(37.29%\\) to \\(67.81%\\), LeanContext's
ROUGE-1 score decreases only by \\(1.41%\\) to \\(2.65%\\) compared to a baseline
that retains the entire context (no summarization). Additionally, if free
pretrained LLM-based summarizers are used to reduce context (into human
consumable summaries), LeanContext can further modify the reduced context to
enhance the accuracy (ROUGE-1 score) by \\(13.22%\\) to \\(24.61%\\).