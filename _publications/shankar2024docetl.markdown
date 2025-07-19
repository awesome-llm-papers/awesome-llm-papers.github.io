---
layout: publication
title: 'Docetl: Agentic Query Rewriting And Evaluation For Complex Document Processing'
authors: Shankar et al.
conference: Proceedings of the Third ACM International Conference on Distributed Event-Based
  Systems
year: 2024
bibkey: shankar2024docetl
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.12189'}]
tags: [RAG, Prompting, Agentic, Tools, Evaluation, Efficiency And Optimization]
---
Analyzing unstructured data has been a persistent challenge in data
processing. Large Language Models (LLMs) have shown promise in this regard,
leading to recent proposals for declarative frameworks for LLM-powered
processing of unstructured data. However, these frameworks focus on reducing
cost when executing user-specified operations using LLMs, rather than improving
accuracy, executing most operations as-is (in a single LLM call). This is
problematic for complex tasks and data, where LLM outputs for user-defined
operations are often inaccurate, even with optimized prompts. For example, an
LLM may struggle to identify \{\em all\} instances of specific clauses, like
force majeure or indemnification, in lengthy legal documents, requiring
decomposition of the data, the task, or both.
  We present DocETL, a system that optimizes complex document processing
pipelines, while accounting for LLM shortcomings. DocETL offers a declarative
interface for users to define such pipelines and uses an agent-based approach
to automatically optimize them, leveraging novel agent-based rewrites (that we
call rewrite directives), as well as an optimization and evaluation framework.
We introduce (i) logical rewriting of pipelines, tailored for LLM-based tasks,
(ii) an agent-guided plan evaluation mechanism that synthesizes and
orchestrates task-specific validation prompts, and (iii) an optimization
algorithm that efficiently finds promising plans, considering the latencies of
agent-based plan generation and evaluation. Our evaluation on four different
unstructured document analysis tasks demonstrates that DocETL finds plans with
outputs that are 25 to 80% more accurate than well-engineered baselines,
addressing a critical gap in unstructured data analysis. DocETL is open-source
at docetl.org, and as of March 2025, has amassed over 1.7k GitHub Stars, with
users spanning a variety of domains.