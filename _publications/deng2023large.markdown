---
layout: publication
title: 'Large Language Models Are Edge-case Fuzzers: Testing Deep Learning Libraries
  Via Fuzzgpt'
authors: Yinlin Deng, Chunqiu Steven Xia, Chenyuan Yang, Shizhuo Dylan Zhang, Shujing
  Yang, Lingming Zhang
conference: Proceedings of the 32nd ACM SIGSOFT International Symposium on Software
  Testing and Analysis
year: 2023
bibkey: deng2023large
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.02014'}]
tags: ["Applications", "Evaluation", "Tools"]
short_authors: Deng et al.
---
Deep Learning (DL) library bugs affect downstream DL applications,
emphasizing the need for reliable systems. Generating valid input programs for
fuzzing DL libraries is challenging due to the need for satisfying both
language syntax/semantics and constraints for constructing valid computational
graphs. Recently, the TitanFuzz work demonstrates that modern Large Language
Models (LLMs) can be directly leveraged to implicitly learn all the constraints
to generate valid DL programs for fuzzing. However, LLMs tend to generate
ordinary programs following similar patterns seen in their massive training
corpora, while fuzzing favors unusual inputs that cover edge cases or are
unlikely to be manually produced.
  To fill this gap, this paper proposes FuzzGPT, the first technique to prime
LLMs to synthesize unusual programs for fuzzing. FuzzGPT is built on the
well-known hypothesis that historical bug-triggering programs may include
rare/valuable code ingredients important for bug finding. Traditional
techniques leveraging such historical information require intensive human
efforts to design dedicated generators and ensure the validity of generated
programs. FuzzGPT demonstrates that this process can be fully automated via the
intrinsic capabilities of LLMs (including fine-tuning and in-context learning),
while being generalizable and applicable to challenging domains. While FuzzGPT
can be applied with different LLMs, this paper focuses on the powerful
GPT-style models: Codex and CodeGen. Moreover, FuzzGPT also shows the potential
of directly leveraging the instruct-following capability of the recent ChatGPT
for effective fuzzing. Evaluation on two popular DL libraries (PyTorch and
TensorFlow) shows that FuzzGPT can substantially outperform TitanFuzz,
detecting 76 bugs, with 49 already confirmed as previously unknown bugs,
including 11 high-priority bugs or security vulnerabilities.