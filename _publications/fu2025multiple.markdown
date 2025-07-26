---
layout: publication
title: 'Multiple Choice Questions: Reasoning Makes Large Language Models (llms) More
  Self-confident Even When They Are Wrong'
authors: "Tairan Fu, Javier Conde, Gonzalo Mart\xEDnez, Mar\xEDa Grandury, Pedro Reviriego"
conference: No Venue
year: 2025
bibkey: fu2025multiple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.09775'}]
tags: ["Evaluation"]
short_authors: Fu et al.
---
One of the most widely used methods to evaluate LLMs are Multiple Choice Question (MCQ) tests. MCQ benchmarks enable the testing of LLM knowledge on almost any topic at scale as the results can be processed automatically. To help the LLM answer, a few examples called few shots can be included in the prompt. Moreover, the LLM can be asked to answer the question directly with the selected option or to first provide the reasoning and then the selected answer, which is known as chain of thought. In addition to checking whether the selected answer is correct, the evaluation can look at the LLM-estimated probability of its response as an indication of the confidence of the LLM in the response. In this paper, we study how the LLM confidence in its answer depends on whether the model has been asked to answer directly or to provide the reasoning before answering. The results of the evaluation of questions on a wide range of topics in seven different models show that LLMs are more confident in their answers when they provide reasoning before the answer. This occurs regardless of whether the selected answer is correct. Our hypothesis is that this behavior is due to the reasoning that modifies the probability of the selected answer, as the LLM predicts the answer based on the input question and the reasoning that supports the selection made. Therefore, LLM estimated probabilities seem to have intrinsic limitations that should be understood in order to use them in evaluation procedures. Interestingly, the same behavior has been observed in humans, for whom explaining an answer increases confidence in its correctness.

https://huggingface.co/discussions/paper/678e1b161a99a49b98056e61