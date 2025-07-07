---
layout: publication
title: Are Large Pre-trained Language Models Leaking Your Personal Information?
authors: Jie Huang, Hanyin Shao, Kevin Chen-chuan Chang
conference: Arxiv
year: 2022
citations: 37
bibkey: huang2022are
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12628'}]
tags: [Security, Prompting]
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