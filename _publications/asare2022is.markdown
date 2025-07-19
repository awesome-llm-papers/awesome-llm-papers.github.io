---
layout: publication
title: Is Github's Copilot As Bad As Humans At Introducing Vulnerabilities In Code?
authors: Asare Owura, Nagappan Meiyappan, Asokan N.
conference: Empirical Software Engineering
year: 2022
bibkey: asare2022is
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.04741'}]
tags: [Security, Prompting, Tools, LLM For Code, LLM for Code, Datasets]
---
Several advances in deep learning have been successfully applied to the
software development process. Of recent interest is the use of neural language
models to build tools, such as Copilot, that assist in writing code. In this
paper we perform a comparative empirical analysis of Copilot-generated code
from a security perspective. The aim of this study is to determine if Copilot
is as bad as human developers. We investigate whether Copilot is just as likely
to introduce the same software vulnerabilities as human developers. Using a
dataset of C/C++ vulnerabilities, we prompt Copilot to generate suggestions in
scenarios that led to the introduction of vulnerabilities by human developers.
The suggestions are inspected and categorized in a 2-stage process based on
whether the original vulnerability or fix is reintroduced. We find that Copilot
replicates the original vulnerable code about 33% of the time while replicating
the fixed code at a 25% rate. However this behaviour is not consistent: Copilot
is more likely to introduce some types of vulnerabilities than others and is
also more likely to generate vulnerable code in response to prompts that
correspond to older vulnerabilities. Overall, given that in a significant
number of cases it did not replicate the vulnerabilities previously introduced
by human developers, we conclude that Copilot, despite performing differently
across various vulnerability types, is not as bad as human developers at
introducing vulnerabilities in code.