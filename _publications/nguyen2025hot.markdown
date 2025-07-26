---
layout: publication
title: 'Hot: Highlighted Chain Of Thought For Referencing Supporting Facts From Inputs'
authors: Tin Nguyen, Logan Bolton, Mohammad Reza Taesiri, Anh Totti Nguyen
conference: No Venue
year: 2025
bibkey: nguyen2025hot
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.02003'}]
tags: ["Few-Shot", "Prompting"]
short_authors: Nguyen et al.
---
An Achilles heel of Large Language Models (LLMs) is their tendency to hallucinate non-factual statements. A response mixed of factual and non-factual statements poses a challenge for humans to verify and accurately base their decisions on. To combat this problem, we propose Highlighted Chain-of-Thought Prompting (HoT), a technique for prompting LLMs to generate responses with XML tags that ground facts to those provided in the query. That is, given an input question, LLMs would first re-format the question to add XML tags highlighting key facts, and then, generate a response with highlights over the facts referenced from the input. Interestingly, in few-shot settings, HoT outperforms vanilla chain of thought prompting (CoT) on a wide range of 17 tasks from arithmetic, reading comprehension to logical reasoning. When asking humans to verify LLM responses, highlights help time-limited participants to more accurately and efficiently recognize when LLMs are correct. Yet, surprisingly, when LLMs are wrong, HoTs tend to make users believe that an answer is correct.

https://huggingface.co/discussions/paper/67c9dc7bb918b6494634f946