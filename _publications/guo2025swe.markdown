---
layout: publication
title: 'Swe-factory: Your Automated Factory For Issue Resolution Training Data And
  Evaluation Benchmarks'
authors: Lianghong Guo, Yanlin Wang, Caihua Li, Pengyu Yang, Jiachi Chen, Wei Tao,
  Yingtian Zou, Duyu Tang, Zibin Zheng
conference: No Venue
year: 2025
bibkey: guo2025swe
additional_links: [{name: Code, url: 'https://github.com/DeepSoftwareAnalytics/swe-factory'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/684b7ea83b733ba333686f93'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.10954'}]
tags: ["Datasets", "Has Code", "Llm For Code"]
short_authors: Guo et al.
---
Constructing large-scale datasets for the GitHub issue resolution task is crucial for both training and evaluating the software engineering capabilities of Large Language Models (LLMs). However, the traditional process for creating such benchmarks is notoriously challenging and labor-intensive, particularly in the stages of setting up evaluation environments, grading test outcomes, and validating task instances. In this paper, we propose SWE-Factory, an automated pipeline designed to address these challenges. To tackle these issues, our pipeline integrates three core automated components. First, we introduce SWE-Builder, a multi-agent system that automates evaluation environment construction, which employs four specialized agents that work in a collaborative, iterative loop and leverages an environment memory pool to enhance efficiency. Second, we introduce a standardized, exit-code-based grading method that eliminates the need for manually writing custom parsers. Finally, we automate the fail2pass validation process using these reliable exit code signals. Experiments on 671 issues across four programming languages show that our pipeline can effectively construct valid task instances; for example, with GPT-4.1-mini, our SWE-Builder constructs 269 valid instances at 0.045 per instance, while with Gemini-2.5-flash, it achieves comparable performance at the lowest cost of 0.024 per instance. We also demonstrate that our exit-code-based grading achieves 100% accuracy compared to manual inspection, and our automated fail2pass validation reaches a precision of 0.92 and a recall of 1.00. We hope our automated pipeline will accelerate the collection of large-scale, high-quality GitHub issue resolution datasets for both training and evaluation. Our code and datasets are released at https://github.com/DeepSoftwareAnalytics/swe-factory.

https://huggingface.co/discussions/paper/684b7ea83b733ba333686f93