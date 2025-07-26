---
layout: publication
title: 'Codeplan: Repository-level Coding Using Llms And Planning'
authors: Ramakrishna Bairi, Atharv Sonwane, Aditya Kanade, Vageesh D C, Arun Iyer,
  Suresh Parthasarathy, Sriram Rajamani, B. Ashok, Shashank Shet
conference: No Venue
year: 2023
bibkey: bairi2023codeplan
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6510e1e011f3210cf7da7680'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2309.12499'}]
tags: ["Has Code", "Llm For Code", "Tools"]
short_authors: Bairi et al.
---
Software engineering activities such as package migration, fixing errors reports from static analysis or testing, and adding type annotations or other specifications to a codebase, involve pervasively editing the entire repository of code. We formulate these activities as repository-level coding tasks. Recent tools like GitHub Copilot, which are powered by Large Language Models (LLMs), have succeeded in offering high-quality solutions to localized coding problems. Repository-level coding tasks are more involved and cannot be solved directly using LLMs, since code within a repository is inter-dependent and the entire repository may be too large to fit into the prompt. We frame repository-level coding as a planning problem and present a task-agnostic framework, called CodePlan to solve it. CodePlan synthesizes a multi-step chain of edits (plan), where each step results in a call to an LLM on a code location with context derived from the entire repository, previous code changes and task-specific instructions. CodePlan is based on a novel combination of an incremental dependency analysis, a change may-impact analysis and an adaptive planning algorithm. We evaluate the effectiveness of CodePlan on two repository-level tasks: package migration (C#) and temporal code edits (Python). Each task is evaluated on multiple code repositories, each of which requires inter-dependent changes to many files (between 2-97 files). Coding tasks of this level of complexity have not been automated using LLMs before. Our results show that CodePlan has better match with the ground truth compared to baselines. CodePlan is able to get 5/6 repositories to pass the validity checks (e.g., to build without errors and make correct code edits) whereas the baselines (without planning but with the same type of contextual information as CodePlan) cannot get any of the repositories to pass them.

https://huggingface.co/discussions/paper/6510e1e011f3210cf7da7680