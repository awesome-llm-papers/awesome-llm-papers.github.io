---
layout: publication
title: 'Swe-rebench: An Automated Pipeline For Task Collection And Decontaminated
  Evaluation Of Software Engineering Agents'
authors: Ibragim Badertdinov, Alexander Golubev, Maksim Nekrashevich, Anton Shevtsov,
  Simon Karasik, Andrei Andriushchenko, Maria Trofimova, Daria Litvintseva, Boris
  Yangel
conference: No Venue
year: 2025
bibkey: badertdinov2025swe
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/683735b0f42cc8a1d260e69f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.20411'}]
tags: ["Has Code"]
short_authors: Badertdinov et al.
---
LLM-based agents have shown promising capabilities in a growing range of software engineering (SWE) tasks. However, advancing this field faces two critical challenges. First, high-quality training data is scarce, especially data that reflects real-world SWE scenarios, where agents must interact with development environments, execute code and adapt behavior based on the outcomes of their actions. Existing datasets are either limited to one-shot code generation or comprise small, manually curated collections of interactive tasks, lacking both scale and diversity. Second, the lack of fresh interactive SWE tasks affects evaluation of rapidly improving models, as static benchmarks quickly become outdated due to contamination issues. To address these limitations, we introduce a novel, automated, and scalable pipeline to continuously extract real-world interactive SWE tasks from diverse GitHub repositories. Using this pipeline, we construct SWE-rebench, a public dataset comprising over 21,000 interactive Python-based SWE tasks, suitable for reinforcement learning of SWE agents at scale. Additionally, we use continuous supply of fresh tasks collected using SWE-rebench methodology to build a contamination-free benchmark for agentic software engineering. We compare results of various LLMs on this benchmark to results on SWE-bench Verified and show that performance of some language models might be inflated due to contamination issues.

https://huggingface.co/discussions/paper/683735b0f42cc8a1d260e69f