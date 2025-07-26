---
layout: publication
title: 'RULER: What''s The Real Context Size Of Your Long-context Language Models?'
authors: Cheng-ping Hsieh, Simeng Sun, Samuel Kriman, Shantanu Acharya, Dima Rekesh,
  Fei Jia, Boris Ginsburg
conference: No Venue
year: 2024
bibkey: hsieh2024ruler
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.06654'}]
tags: ["Evaluation", "Memory & Context"]
short_authors: Hsieh et al.
---
The needle-in-a-haystack (NIAH) test, which examines the ability to retrieve a piece of information (the "needle") from long distractor texts (the "haystack"), has been widely adopted to evaluate long-context language models (LMs). However, this simple retrieval-based test is indicative of only a superficial form of long-context understanding. To provide a more comprehensive evaluation of long-context LMs, we create a new synthetic benchmark RULER with flexible configurations for customized sequence length and task complexity. RULER expands upon the vanilla NIAH test to encompass variations with diverse types and quantities of needles. Moreover, RULER introduces new task categories multi-hop tracing and aggregation to test behaviors beyond searching from context. We evaluate ten long-context LMs with 13 representative tasks in RULER. Despite achieving nearly perfect accuracy in the vanilla NIAH test, all models exhibit large performance drops as the context length increases. While these models all claim context sizes of 32K tokens or greater, only four models (GPT-4, Command-R, Yi-34B, and Mixtral) can maintain satisfactory performance at the length of 32K. Our analysis of Yi-34B, which supports context length of 200K, reveals large room for improvement as we increase input length and task complexity. We open source RULER to spur comprehensive evaluation of long-context LMs.

https://huggingface.co/discussions/paper/66173e879c0e16d020e31f0d