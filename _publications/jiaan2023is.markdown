---
layout: publication
title: Is Chatgpt A Good NLG Evaluator? A Preliminary Study
authors: [jiaan Wang, yunlong Liang, fandong Meng, zengkui Sun, haoxiang Shi, zhixu
    Li, jinan Xu, jianfeng Qu, jie Zhou]
conference: Proceedings of the 4th New Frontiers in Summarization Workshop
year: 2023
bibkey: jiaan2023is
citations: 138
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2303.04048v3'}]
tags: ["Evaluation"]
short_authors: Wang et al.
---
Recently, the emergence of ChatGPT has attracted wide attention from the
computational linguistics community. Many prior studies have shown that ChatGPT
achieves remarkable performance on various NLP tasks in terms of automatic
evaluation metrics. However, the ability of ChatGPT to serve as an evaluation
metric is still underexplored. Considering assessing the quality of natural
language generation (NLG) models is an arduous task and NLG metrics notoriously
show their poor correlation with human judgments, we wonder whether ChatGPT is
a good NLG evaluation metric. In this report, we provide a preliminary
meta-evaluation on ChatGPT to show its reliability as an NLG metric. In detail,
we regard ChatGPT as a human evaluator and give task-specific (e.g.,
summarization) and aspect-specific (e.g., relevance) instruction to prompt
ChatGPT to evaluate the generated results of NLG models. We conduct experiments
on five NLG meta-evaluation datasets (including summarization, story generation
and data-to-text tasks). Experimental results show that compared with previous
automatic metrics, ChatGPT achieves state-of-the-art or competitive correlation
with human judgments in most cases. In addition, we find that the effectiveness
of the ChatGPT evaluator might be influenced by the creation method of the
meta-evaluation datasets. For the meta-evaluation datasets which are created
greatly depending on the reference and thus are biased, the ChatGPT evaluator
might lose its effectiveness. We hope our preliminary study could prompt the
emergence of a general-purposed reliable NLG metric.