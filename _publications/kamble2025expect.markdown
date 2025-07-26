---
layout: publication
title: 'Expect The Unexpected: Failsafe Long Context QA For Finance'
authors: Kiran Kamble, Melisa Russak, Dmytro Mozolevskyi, Muayad Ali, Mateusz Russak,
  Waseem Alshikh
conference: No Venue
year: 2025
bibkey: kamble2025expect
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.06329'}]
tags: ["Applications", "Memory & Context"]
short_authors: Kamble et al.
---
We propose a new long-context financial benchmark, FailSafeQA, designed to test the robustness and context-awareness of LLMs against six variations in human-interface interactions in LLM-based query-answer systems within finance. We concentrate on two case studies: Query Failure and Context Failure. In the Query Failure scenario, we perturb the original query to vary in domain expertise, completeness, and linguistic accuracy. In the Context Failure case, we simulate the uploads of degraded, irrelevant, and empty documents. We employ the LLM-as-a-Judge methodology with Qwen2.5-72B-Instruct and use fine-grained rating criteria to define and calculate Robustness, Context Grounding, and Compliance scores for 24 off-the-shelf models. The results suggest that although some models excel at mitigating input perturbations, they must balance robust answering with the ability to refrain from hallucinating. Notably, Palmyra-Fin-128k-Instruct, recognized as the most compliant model, maintained strong baseline performance but encountered challenges in sustaining robust predictions in 17% of test cases. On the other hand, the most robust model, OpenAI o3-mini, fabricated information in 41% of tested cases. The results demonstrate that even high-performing models have significant room for improvement and highlight the role of FailSafeQA as a tool for developing LLMs optimized for dependability in financial applications. The dataset is available at: https://huggingface.co/datasets/Writer/FailSafeQA

https://huggingface.co/discussions/paper/67ab4175757d2eb190af03ca