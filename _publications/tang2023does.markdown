---
layout: publication
title: Does Synthetic Data Generation Of Llms Help Clinical Text Mining?
authors: Ruixiang Tang, Xiaotian Han, Xiaoqian Jiang, Xia Hu
conference: Arxiv
year: 2023
bibkey: tang2023does
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.04360'}]
tags: ["Datasets", "Tools"]
short_authors: Tang et al.
---
Recent advancements in large language models (LLMs) have led to the
development of highly potent models like OpenAI's ChatGPT. These models have
exhibited exceptional performance in a variety of tasks, such as question
answering, essay composition, and code generation. However, their effectiveness
in the healthcare sector remains uncertain. In this study, we seek to
investigate the potential of ChatGPT to aid in clinical text mining by
examining its ability to extract structured information from unstructured
healthcare texts, with a focus on biological named entity recognition and
relation extraction. However, our preliminary results indicate that employing
ChatGPT directly for these tasks resulted in poor performance and raised
privacy concerns associated with uploading patients' information to the ChatGPT
API. To overcome these limitations, we propose a new training paradigm that
involves generating a vast quantity of high-quality synthetic data with labels
utilizing ChatGPT and fine-tuning a local model for the downstream task. Our
method has resulted in significant improvements in the performance of
downstream tasks, improving the F1-score from 23.37% to 63.99% for the named
entity recognition task and from 75.86% to 83.59% for the relation extraction
task. Furthermore, generating data using ChatGPT can significantly reduce the
time and effort required for data collection and labeling, as well as mitigate
data privacy concerns. In summary, the proposed framework presents a promising
solution to enhance the applicability of LLM models to clinical text mining.