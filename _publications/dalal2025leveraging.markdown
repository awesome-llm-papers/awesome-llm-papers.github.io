---
layout: publication
title: Leveraging LLM Inconsistency To Boost Pass@k Performance
authors: Dalal et al.
conference: Computer
year: 2025
bibkey: dalal2025leveraging
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.12938'}]
tags: [RAG, ICCV, Agentic, CVPR, Security, Datasets]
---
Large language models (LLMs) achieve impressive abilities in numerous domains, but exhibit inconsistent performance in response to minor input changes. Rather than view this as a drawback, in this paper we introduce a novel method for leveraging models' inconsistency to boost Pass@k performance. Specifically, we present a "Variator" agent that generates k variants of a given task and submits one candidate solution for each one. Our variant generation approach is applicable to a wide range of domains as it is task agnostic and compatible with free-form inputs. We demonstrate the efficacy of our agent theoretically using a probabilistic model of the inconsistency effect, and show empirically that it outperforms the baseline on the APPS dataset. Furthermore, we establish that inconsistency persists even in frontier reasoning models across coding and cybersecurity domains, suggesting our method is likely to remain relevant for future model generations.