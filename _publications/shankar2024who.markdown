---
layout: publication
title: Who Validates The Validators? Aligning Llm-assisted Evaluation Of LLM Outputs
  With Human Preferences
authors: "Shreya Shankar, J. D. Zamfirescu-pereira, Bj\xF6rn Hartmann, Aditya G. Parameswaran,\
  \ Ian Arawjo"
conference: Arxiv
year: 2024
citations: 46
bibkey: shankar2024who
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.12272'}]
tags: [Reinforcement Learning, Prompting]
---
Due to the cumbersome nature of human evaluation and limitations of
code-based evaluation, Large Language Models (LLMs) are increasingly being used
to assist humans in evaluating LLM outputs. Yet LLM-generated evaluators simply
inherit all the problems of the LLMs they evaluate, requiring further human
validation. We present a mixed-initiative approach to ``validate the
validators'' -- aligning LLM-generated evaluation functions (be it prompts or
code) with human requirements. Our interface, EvalGen, provides automated
assistance to users in generating evaluation criteria and implementing
assertions. While generating candidate implementations (Python functions, LLM
grader prompts), EvalGen asks humans to grade a subset of LLM outputs; this
feedback is used to select implementations that better align with user grades.
A qualitative study finds overall support for EvalGen but underscores the
subjectivity and iterative process of alignment. In particular, we identify a
phenomenon we dub *criteria drift*: users need criteria to grade outputs,
but grading outputs helps users define criteria. What is more, some criteria
appears *dependent* on the specific LLM outputs observed (rather than
independent criteria that can be defined *a priori*), raising serious
questions for approaches that assume the independence of evaluation from
observation of model outputs. We present our interface and implementation
details, a comparison of our algorithm with a baseline approach, and
implications for the design of future LLM evaluation assistants.