---
layout: publication
title: 'Speechprompt V2: Prompt Tuning For Speech Classification Tasks'
authors: Kai-wei Chang et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: chang2023speechprompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.00733'}]
tags: [Tools, Prompting, Efficiency and Optimization, RAG]
---
Prompt tuning is a technology that tunes a small set of parameters to steer a
pre-trained language model (LM) to directly generate the output for downstream
tasks. Recently, prompt tuning has demonstrated its storage and computation
efficiency in both natural language processing (NLP) and speech processing
fields. These advantages have also revealed prompt tuning as a candidate
approach to serving pre-trained LM for multiple tasks in a unified manner. For
speech processing, SpeechPrompt shows its high parameter efficiency and
competitive performance on a few speech classification tasks. However, whether
SpeechPrompt is capable of serving a large number of tasks is unanswered. In
this work, we propose SpeechPrompt v2, a prompt tuning framework capable of
performing a wide variety of speech classification tasks, covering multiple
languages and prosody-related tasks. The experiment result shows that
SpeechPrompt v2 achieves performance on par with prior works with less than
0.15M trainable parameters in a unified framework.