---
layout: publication
title: 'Know What You Don''t Know: Unanswerable Questions For Squad'
authors: Pranav Rajpurkar, Robin Jia, Percy Liang
conference: Arxiv
year: 2018
bibkey: rajpurkar2018know
citations: 132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.03822'}]
tags: ["Datasets"]
short_authors: Pranav Rajpurkar, Robin Jia, Percy Liang
---
Extractive reading comprehension systems can often locate the correct answer
to a question in a context document, but they also tend to make unreliable
guesses on questions for which the correct answer is not stated in the context.
Existing datasets either focus exclusively on answerable questions, or use
automatically generated unanswerable questions that are easy to identify. To
address these weaknesses, we present SQuAD 2.0, the latest version of the
Stanford Question Answering Dataset (SQuAD). SQuAD 2.0 combines existing SQuAD
data with over 50,000 unanswerable questions written adversarially by
crowdworkers to look similar to answerable ones. To do well on SQuAD 2.0,
systems must not only answer questions when possible, but also determine when
no answer is supported by the paragraph and abstain from answering. SQuAD 2.0
is a challenging natural language understanding task for existing models: a
strong neural system that gets 86% F1 on SQuAD 1.1 achieves only 66% F1 on
SQuAD 2.0.