---
layout: publication
title: 'Wildchat: 1M Chatgpt Interaction Logs In The Wild'
authors: Wenting Zhao, Xiang Ren, Jack Hessel, Claire Cardie, Yejin Choi, Yuntian
  Deng
conference: No Venue
year: 2024
bibkey: zhao2024wildchat
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2405.01470'}]
tags: ["Applications", "Datasets"]
short_authors: Zhao et al.
---
Chatbots such as GPT-4 and ChatGPT are now serving millions of users. Despite their widespread use, there remains a lack of public datasets showcasing how these tools are used by a population of users in practice. To bridge this gap, we offered free access to ChatGPT for online users in exchange for their affirmative, consensual opt-in to anonymously collect their chat transcripts and request headers. From this, we compiled WildChat, a corpus of 1 million user-ChatGPT conversations, which consists of over 2.5 million interaction turns. We compare WildChat with other popular user-chatbot interaction datasets, and find that our dataset offers the most diverse user prompts, contains the largest number of languages, and presents the richest variety of potentially toxic use-cases for researchers to study. In addition to timestamped chat transcripts, we enrich the dataset with demographic data, including state, country, and hashed IP addresses, alongside request headers. This augmentation allows for more detailed analysis of user behaviors across different geographical regions and temporal dimensions. Finally, because it captures a broad range of use cases, we demonstrate the dataset's potential utility in fine-tuning instruction-following models. WildChat is released at https://wildchat.allen.ai under AI2 ImpACT Licenses.

https://huggingface.co/discussions/paper/663448bfa41adb34338cfd5e