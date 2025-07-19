---
layout: publication
title: Code Hallucination
authors: Rahman Mirza Masfiqur, Kundu Ashish
conference: Journal of Neuroscience
year: 2024
bibkey: rahman2024code
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.04831'}]
tags: [Model Architecture, RAG, Prompting]
---
Generative models such as large language models are extensively used as code
copilots and for whole program generation. However, the programs they generate
often have questionable correctness, authenticity and reliability in terms of
integration as they might not follow the user requirements, provide incorrect
and/or nonsensical outputs, or even contain semantic/syntactic errors - overall
known as LLM hallucination. In this work, we present several types of code
hallucination. We have generated such hallucinated code manually using large
language models. We also present a technique - HallTrigger, in order to
demonstrate efficient ways of generating arbitrary code hallucination. Our
method leverages 3 different dynamic attributes of LLMs to craft prompts that
can successfully trigger hallucinations from models without the need to access
model architecture or parameters. Results from popular blackbox models suggest
that HallTrigger is indeed effective and the pervasive LLM hallucination have
sheer impact on software development.