---
layout: publication
title: Are Large Pre-trained Language Models Leaking Your Personal Information?
authors: Huang Jie, Shao Hanyin, Chang Kevin Chen-chuan
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2022'
year: 2022
bibkey: huang2022are
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12628'}]
tags: [Security, EMNLP, Prompting, ACL]
---
Are Large Pre-Trained Language Models Leaking Your Personal Information? In
this paper, we analyze whether Pre-Trained Language Models (PLMs) are prone to
leaking personal information. Specifically, we query PLMs for email addresses
with contexts of the email address or prompts containing the owner's name. We
find that PLMs do leak personal information due to memorization. However, since
the models are weak at association, the risk of specific personal information
being extracted by attackers is low. We hope this work could help the community
to better understand the privacy risk of PLMs and bring new insights to make
PLMs safe.