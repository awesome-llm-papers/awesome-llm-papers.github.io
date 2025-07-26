---
layout: publication
title: Is Chatgpt The Ultimate Programming Assistant -- How Far Is It?
authors: "Haoye Tian, Weiqi Lu, Tsz On Li, Xunzhu Tang, Shing-chi Cheung, Jacques\
  \ Klein, Tegawend\xE9 F. Bissyand\xE9"
conference: Arxiv
year: 2023
bibkey: tian2023is
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.11938'}]
tags: ["Applications", "Llm For Code"]
short_authors: Tian et al.
---
Recently, the ChatGPT LLM has received great attention: it can be used as a
bot for discussing source code, prompting it to suggest changes, provide
descriptions or even generate code. Typical demonstrations generally focus on
existing benchmarks, which may have been used in model training (i.e., data
leakage). To assess the feasibility of using an LLM as a useful assistant bot
for programmers, we must assess its realistic capabilities on unseen problems
as well as its capabilities on various tasks. In this paper, we present an
empirical study of ChatGPT's potential as a fully automated programming
assistant, focusing on the tasks of code generation, program repair, and code
summariziation. The study investigates ChatGPT's performance on common
programming problems and compares it with state-of-the-art approaches on two
benchmarks. Among several findings, our study shows that ChatGPT is effective
in dealing with common programming problems. However, our experiments also
reveal limitations in terms of its attention span: detailed descriptions will
constrain the focus of ChatGPT and prevent it from leveraging its vast
knowledge to solve the actual problem. Surprisingly, we have identified the
ability of ChatGPT to reason the original intention of the code. We expect
future work to build on this insight for dealing with the open question of the
oracle problem. Our findings contribute interesting insights to the development
of LLMs for programming assistance, notably by demonstrating the importance of
prompt engineering, and providing a better understanding of ChatGPT's practical
applications for software engineering.