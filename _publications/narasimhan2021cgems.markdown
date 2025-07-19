---
layout: publication
title: 'Cgems: A Metric Model For Automatic Code Generation Using GPT-3'
authors: Narasimhan Aishwarya, Rao Krishna Prasad Agara Venkatesha, B Veena M
conference: Proceedings of the 37th IEEE/ACM International Conference on Automated
  Software Engineering
year: 2021
bibkey: narasimhan2021cgems
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.10168'}]
tags: [Model Architecture, Interpretability And Explainability, Evaluation, LLM For
    Code, Responsible AI, GPT, LLM for Code, Reinforcement Learning, Language Modeling]
---
Today, AI technology is showing its strengths in almost every industry and
walks of life. From text generation, text summarization, chatbots, NLP is being
used widely. One such paradigm is automatic code generation. An AI could be
generating anything; hence the output space is unconstrained. A self-driving
car is driven for 100 million miles to validate its safety, but tests cannot be
written to monitor and cover an unconstrained space. One of the solutions to
validate AI-generated content is to constrain the problem and convert it from
abstract to realistic, and this can be accomplished by either validating the
unconstrained algorithm using theoretical proofs or by using Monte-Carlo
simulation methods. In this case, we use the latter approach to test/validate a
statistically significant number of samples. This hypothesis of validating the
AI-generated code is the main motive of this work and to know if AI-generated
code is reliable, a metric model CGEMs is proposed. This is an extremely
challenging task as programs can have different logic with different naming
conventions, but the metrics must capture the structure and logic of the
program. This is similar to the importance grammar carries in AI-based text
generation, Q&A, translations, etc. The various metrics that are garnered in
this work to support the evaluation of generated code are as follows:
Compilation, NL description to logic conversion, number of edits needed, some
of the commonly used static-code metrics and NLP metrics. These metrics are
applied to 80 codes generated using OpenAI's GPT-3. Post which a Neural network
is designed for binary classification (acceptable/not acceptable quality of the
generated code). The inputs to this network are the values of the features
obtained from the metrics. The model achieves a classification accuracy of
76.92% and an F1 score of 55.56%. XAI is augmented for model interpretability.