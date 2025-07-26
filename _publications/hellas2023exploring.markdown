---
layout: publication
title: Exploring The Responses Of Large Language Models To Beginner Programmers' Help
  Requests
authors: "Arto Hellas, Juho Leinonen, Sami Sarsa, Charles Koutcheme, Lilja Kujanp\xE4\
  \xE4, Juha Sorva"
conference: Proceedings of the 2023 ACM Conference on International Computing Education
  Research V.1
year: 2023
bibkey: hellas2023exploring
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.05715'}]
tags: ["Model Architecture"]
short_authors: Hellas et al.
---
Background and Context: Over the past year, large language models (LLMs) have
taken the world by storm. In computing education, like in other walks of life,
many opportunities and threats have emerged as a consequence.
  Objectives: In this article, we explore such opportunities and threats in a
specific area: responding to student programmers' help requests. More
specifically, we assess how good LLMs are at identifying issues in problematic
code that students request help on.
  Method: We collected a sample of help requests and code from an online
programming course. We then prompted two different LLMs (OpenAI Codex and
GPT-3.5) to identify and explain the issues in the students' code and assessed
the LLM-generated answers both quantitatively and qualitatively.
  Findings: GPT-3.5 outperforms Codex in most respects. Both LLMs frequently
find at least one actual issue in each student program (GPT-3.5 in 90% of the
cases). Neither LLM excels at finding all the issues (GPT-3.5 finding them 57%
of the time). False positives are common (40% chance for GPT-3.5). The advice
that the LLMs provide on the issues is often sensible. The LLMs perform better
on issues involving program logic rather than on output formatting. Model
solutions are frequently provided even when the LLM is prompted not to. LLM
responses to prompts in a non-English language are only slightly worse than
responses to English prompts.
  Implications: Our results continue to highlight the utility of LLMs in
programming education. At the same time, the results highlight the
unreliability of LLMs: LLMs make some of the same mistakes that students do,
perhaps especially when formatting output as required by automated assessment
systems. Our study informs teachers interested in using LLMs as well as future
efforts to customize LLMs for the needs of programming education.