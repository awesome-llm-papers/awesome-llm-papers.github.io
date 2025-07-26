---
layout: publication
title: An Empirical Evaluation Of Using Large Language Models For Automated Unit Test
  Generation
authors: "Max Sch\xE4fer, Sarah Nadi, Aryaz Eghbali, Frank Tip"
conference: IEEE Transactions on Software Engineering
year: 2023
bibkey: "sch\xE4fer2023empirical"
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.06527'}]
tags: ["Evaluation", "Llm For Code"]
short_authors: "Sch\xE4fer et al."
---
Unit tests play a key role in ensuring the correctness of software. However,
manually creating unit tests is a laborious task, motivating the need for
automation. Large Language Models (LLMs) have recently been applied to this
problem, utilizing additional training or few-shot learning on examples of
existing tests. This paper presents a large-scale empirical evaluation on the
effectiveness of LLMs for automated unit test generation without additional
training or manual effort, providing the LLM with the signature and
implementation of the function under test, along with usage examples extracted
from documentation. We also attempt to repair failed generated tests by
re-prompting the model with the failing test and error message. We implement
our approach in TestPilot, a test generation tool for JavaScript that
automatically generates unit tests for all API functions in an npm package. We
evaluate TestPilot using OpenAI's gpt3.5-turbo LLM on 25 npm packages with a
total of 1,684 API functions. The generated tests achieve a median statement
coverage of 70.2% and branch coverage of 52.8%, significantly improving on
Nessie, a recent feedback-directed JavaScript test generation technique, which
achieves only 51.3% statement coverage and 25.6% branch coverage. We also find
that 92.8% of TestPilot's generated tests have no more than 50% similarity with
existing tests (as measured by normalized edit distance), with none of them
being exact copies. Finally, we run TestPilot with two additional LLMs,
OpenAI's older code-cushman-002 LLM and the open LLM StarCoder. Overall, we
observed similar results with the former (68.2% median statement coverage), and
somewhat worse results with the latter (54.0% median statement coverage),
suggesting that the effectiveness of the approach is influenced by the size and
training set of the LLM, but does not fundamentally depend on the specific
model.