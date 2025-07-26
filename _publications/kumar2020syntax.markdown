---
layout: publication
title: Syntax-guided Controlled Generation Of Paraphrases
authors: Ashutosh Kumar, Kabir Ahuja, Raghuram Vadapalli, Partha Talukdar
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: kumar2020syntax
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.08417'}]
tags: ["TACL"]
short_authors: Kumar et al.
---
Given a sentence (e.g., "I like mangoes") and a constraint (e.g., sentiment
flip), the goal of controlled text generation is to produce a sentence that
adapts the input sentence to meet the requirements of the constraint (e.g., "I
hate mangoes"). Going beyond such simple constraints, recent works have started
exploring the incorporation of complex syntactic-guidance as constraints in the
task of controlled paraphrase generation. In these methods, syntactic-guidance
is sourced from a separate exemplar sentence. However, these prior works have
only utilized limited syntactic information available in the parse tree of the
exemplar sentence. We address this limitation in the paper and propose Syntax
Guided Controlled Paraphraser (SGCP), an end-to-end framework for syntactic
paraphrase generation. We find that SGCP can generate syntax conforming
sentences while not compromising on relevance. We perform extensive automated
and human evaluations over multiple real-world English language datasets to
demonstrate the efficacy of SGCP over state-of-the-art baselines. To drive
future research, we have made SGCP's source code available