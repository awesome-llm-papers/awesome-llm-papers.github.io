---
layout: publication
title: Mechanistic Understanding Of Language Models In Syntactic Code Completion
authors: Miller Samuel, Rai Daking, Yao Ziyu
conference: ACM SIGPLAN Notices
year: 2025
bibkey: miller2025mechanistic
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.18499'}]
tags: [Interpretability And Explainability, Attention Mechanism, Model Architecture,
  Reinforcement Learning, Datasets, LLM For Code]
---
Recently, language models (LMs) have shown impressive proficiency in code
generation tasks, especially when fine-tuned on code-specific datasets,
commonly known as Code LMs. However, our understanding of the internal
decision-making processes of Code LMs, such as how they use their (syntactic or
semantic) knowledge, remains limited, which could lead to unintended harm as
they are increasingly used in real life. This motivates us to conduct one of
the first Mechanistic Interpretability works to understand how Code LMs perform
a syntactic completion task, specifically the closing parenthesis task, on the
CodeLlama-7b model (Roziere et al. 2023). Our findings reveal that the model
requires middle-later layers until it can confidently predict the correct label
for the closing parenthesis task. Additionally, we identify that while both
multi-head attention (MHA) and feed-forward (FF) sub-layers play essential
roles, MHA is particularly crucial. Furthermore, we also discover attention
heads that keep track of the number of already closed parentheses precisely but
may or may not promote a correct number of closing parentheses that are still
missing, leading to a positive or negative impact on the model's performance.