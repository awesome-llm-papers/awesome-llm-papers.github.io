---
layout: publication
title: 'Judging The Judges: Evaluating Alignment And Vulnerabilities In Llms-as-judges'
authors: Aman Singh Thakur, Kartik Choudhary, Venkat Srinik Ramayapally, Sankaran
  Vaidyanathan, Dieuwke Hupkes
conference: No Venue
year: 2024
bibkey: thakur2024judging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.12624'}]
tags: ["Ethics & Fairness", "Evaluation"]
short_authors: Thakur et al.
---
Offering a promising solution to the scalability challenges associated with human evaluation, the LLM-as-a-judge paradigm is rapidly gaining traction as an approach to evaluating large language models (LLMs). However, there are still many open questions about the strengths and weaknesses of this paradigm, and what potential biases it may hold. In this paper, we present a comprehensive study of the performance of various LLMs acting as judges. We leverage TriviaQA as a benchmark for assessing objective knowledge reasoning of LLMs and evaluate them alongside human annotations which we found to have a high inter-annotator agreement. Our study includes 9 judge models and 9 exam taker models -- both base and instruction-tuned. We assess the judge model's alignment across different model sizes, families, and judge prompts. Among other results, our research rediscovers the importance of using Cohen's kappa as a metric of alignment as opposed to simple percent agreement, showing that judges with high percent agreement can still assign vastly different scores. We find that both Llama-3 70B and GPT-4 Turbo have an excellent alignment with humans, but in terms of ranking exam taker models, they are outperformed by both JudgeLM-7B and the lexical judge Contains, which have up to 34 points lower human alignment. Through error analysis and various other studies, including the effects of instruction length and leniency bias, we hope to provide valuable lessons for using LLMs as judges in the future.

https://huggingface.co/discussions/paper/667801f00d65792ffd18c484