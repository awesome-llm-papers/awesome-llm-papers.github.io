---
layout: publication
title: 'Needlebench: Can Llms Do Retrieval And Reasoning In 1 Million Context Window?'
authors: Mo Li, Songyang Zhang, Yunxin Liu, Kai Chen
conference: No Venue
year: 2024
bibkey: li2024needlebench
additional_links: [{name: Code, url: 'https://github.com/open-compass/opencompass'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66973c08eb2a785068bb60f7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.11963'}]
tags: ["Tools"]
short_authors: Li et al.
---
In evaluating the long-context capabilities of large language models (LLMs), identifying content relevant to a user's query from original long documents is a crucial prerequisite for any LLM to answer questions based on long text. We present NeedleBench, a framework consisting of a series of progressively more challenging tasks for assessing bilingual long-context capabilities, spanning multiple length intervals (4k, 8k, 32k, 128k, 200k, 1000k, and beyond) and different depth ranges, allowing the strategic insertion of critical data points in different text depth zones to rigorously test the retrieval and reasoning capabilities of models in diverse contexts. We use the NeedleBench framework to assess how well the leading open-source models can identify key information relevant to the question and apply that information to reasoning in bilingual long texts. Furthermore, we propose the Ancestral Trace Challenge (ATC) to mimic the complexity of logical reasoning challenges that are likely to be present in real-world long-context tasks, providing a simple method for evaluating LLMs in dealing with complex long-context situations. Our results suggest that current LLMs have significant room for improvement in practical long-context applications, as they struggle with the complexity of logical reasoning challenges that are likely to be present in real-world long-context tasks. All codes and resources are available at OpenCompass: https://github.com/open-compass/opencompass.

https://huggingface.co/discussions/paper/66973c08eb2a785068bb60f7