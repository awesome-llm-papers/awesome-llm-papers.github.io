---
layout: publication
title: Retrieving Supporting Evidence For Generative Question Answering
authors: Siqing Huo, Negar Arabzadeh, Charles L. A. Clarke
conference: 'SIGIR-AP ''23: Annual International ACM SIGIR Conference on Research
  and Development in Information Retrieval in the Asia Pacific Region'
year: 2023
citations: 19
bibkey: huo2023retrieving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.11392'}]
tags: [Reinforcement Learning, Prompting]
---
Current large language models (LLMs) can exhibit near-human levels of
performance on many natural language-based tasks, including open-domain
question answering. Unfortunately, at this time, they also convincingly
hallucinate incorrect answers, so that responses to questions must be verified
against external sources before they can be accepted at face value. In this
paper, we report two simple experiments to automatically validate generated
answers against a corpus. We base our experiments on questions and passages
from the MS MARCO (V1) test collection, and a retrieval pipeline consisting of
sparse retrieval, dense retrieval and neural rerankers. In the first
experiment, we validate the generated answer in its entirety. After presenting
a question to an LLM and receiving a generated answer, we query the corpus with
the combination of the question + generated answer. We then present the LLM
with the combination of the question + generated answer + retrieved answer,
prompting it to indicate if the generated answer can be supported by the
retrieved answer. In the second experiment, we consider the generated answer at
a more granular level, prompting the LLM to extract a list of factual
statements from the answer and verifying each statement separately. We query
the corpus with each factual statement and then present the LLM with the
statement and the corresponding retrieved evidence. The LLM is prompted to
indicate if the statement can be supported and make necessary edits using the
retrieved material. With an accuracy of over 80%, we find that an LLM is
capable of verifying its generated answer when a corpus of supporting material
is provided. However, manual assessment of a random sample of questions reveals
that incorrect generated answers are missed by this verification process. While
this verification process can reduce hallucinations, it can not entirely
eliminate them.