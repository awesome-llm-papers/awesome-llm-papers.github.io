---
layout: publication
title: Evaluating GPT-4 And Chatgpt On Japanese Medical Licensing Examinations
authors: Jungo Kasai, Yuhei Kasai, Keisuke Sakaguchi, Yutaro Yamada, Dragomir Radev
conference: Arxiv
year: 2023
citations: 33
bibkey: kasai2023evaluating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.18027'}, {name: Code,
    url: 'https://github.com/jungokasai/IgakuQA'}]
tags: [Has Code, Model Architecture, Applications, Tools, GPT, Evaluation]
---
As large language models (LLMs) gain popularity among speakers of diverse
languages, we believe that it is crucial to benchmark them to better understand
model behaviors, failures, and limitations in languages beyond English. In this
work, we evaluate LLM APIs (ChatGPT, GPT-3, and GPT-4) on the Japanese national
medical licensing examinations from the past five years, including the current
year. Our team comprises native Japanese-speaking NLP researchers and a
practicing cardiologist based in Japan. Our experiments show that GPT-4
outperforms ChatGPT and GPT-3 and passes all six years of the exams,
highlighting LLMs' potential in a language that is typologically distant from
English. However, our evaluation also exposes critical limitations of the
current LLM APIs. First, LLMs sometimes select prohibited choices that should
be strictly avoided in medical practice in Japan, such as suggesting
euthanasia. Further, our analysis shows that the API costs are generally higher
and the maximum context size is smaller for Japanese because of the way
non-Latin scripts are currently tokenized in the pipeline. We release our
benchmark as Igaku QA as well as all model outputs and exam metadata. We hope
that our results and benchmark will spur progress on more diverse applications
of LLMs. Our benchmark is available at https://github.com/jungokasai/IgakuQA.