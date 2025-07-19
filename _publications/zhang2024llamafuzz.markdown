---
layout: publication
title: 'LLAMAFUZZ: Large Language Model Enhanced Greybox Fuzzing'
authors: Zhang et al.
conference: Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications
  Security
year: 2024
bibkey: zhang2024llamafuzz
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.07714'}]
tags: [RAG, Evaluation, Reinforcement Learning, Security, Datasets]
---
Greybox fuzzing has achieved success in revealing bugs and vulnerabilities in
programs. However, randomized mutation strategies have limited the fuzzer's
performance on structured data. Specialized fuzzers can handle complex
structured data, but require additional efforts in grammar and suffer from low
throughput.
  In this paper, we explore the potential of utilizing the Large Language Model
to enhance greybox fuzzing for structured data. We utilize the pre-trained
knowledge of LLM about data conversion and format to generate new valid inputs.
We further fine-tuned it with paired mutation seeds to learn structured format
and mutation strategies effectively. Our LLM-based fuzzer, LLAMAFUZZ,
integrates the power of LLM to understand and mutate structured data to
fuzzing. We conduct experiments on the standard bug-based benchmark Magma and a
wide variety of real-world programs. LLAMAFUZZ outperforms our top competitor
by 41 bugs on average. We also identified 47 unique bugs across all trials.
Moreover, LLAMAFUZZ demonstrated consistent performance on both bug trigger and
bug reached. Compared to AFL++, LLAMAFUZZ achieved 27.19% more branches in
real-world program sets on average. We also demonstrate a case study to explain
how LLMs enhance the fuzzing process in terms of code coverage.