---
layout: publication
title: 'Structgpt: A General Framework For Large Language Model To Reason Over Structured
  Data'
authors: Jinhao Jiang, Kun Zhou, Zican Dong, Keming Ye, Wayne Xin Zhao, Ji-rong Wen
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: jiang2023structgpt
citations: 67
additional_links: [{name: Code, url: 'https://github.com/RUCAIBox/StructGPT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2305.09645'}]
tags: ["EMNLP"]
short_authors: Jiang et al.
---
In this paper, we study how to improve the zero-shot reasoning ability of
large language models~(LLMs) over structured data in a unified way. Inspired by
the study on tool augmentation for LLMs, we develop an *Iterative
Reading-then-Reasoning~(IRR)* approach for solving question answering tasks
based on structured data, called \textbf\{StructGPT\}. In our approach, we
construct the specialized function to collect relevant evidence from structured
data (\ie *reading*), and let LLMs concentrate the reasoning task based on
the collected information (\ie *reasoning*). Specially, we propose an
*invoking-linearization-generation* procedure to support LLMs in reasoning
on the structured data with the help of the external interfaces. By iterating
this procedures with provided interfaces, our approach can gradually approach
the target answer to a given query. Extensive experiments conducted on three
types of structured data demonstrate the effectiveness of our approach, which
can significantly boost the performance of ChatGPT and achieve comparable
performance against the full-data supervised-tuning baselines. Our codes and
data are publicly available at~https://github.com/RUCAIBox/StructGPT.