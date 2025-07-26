---
layout: publication
title: A Human-inspired Reading Agent With Gist Memory Of Very Long Contexts
authors: Kuang-huei Lee, Xinyun Chen, Hiroki Furuta, John Canny, Ian Fischer
conference: No Venue
year: 2024
bibkey: lee2024human
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.09727'}]
tags: ["Agentic", "Memory & Context"]
short_authors: Lee et al.
---
Current Large Language Models (LLMs) are not only limited to some maximum context length, but also are not able to robustly consume long inputs. To address these limitations, we propose ReadAgent, an LLM agent system that increases effective context length up to 20x in our experiments. Inspired by how humans interactively read long documents, we implement ReadAgent as a simple prompting system that uses the advanced language capabilities of LLMs to (1) decide what content to store together in a memory episode, (2) compress those memory episodes into short episodic memories called gist memories, and (3) take actions to look up passages in the original text if ReadAgent needs to remind itself of relevant details to complete a task. We evaluate ReadAgent against baselines using retrieval methods, using the original long contexts, and using the gist memories. These evaluations are performed on three long-document reading comprehension tasks: QuALITY, NarrativeQA, and QMSum. ReadAgent outperforms the baselines on all three tasks while extending the effective context window by 3-20x.

https://huggingface.co/discussions/paper/65ced76da0f4d749b2e6f9e4