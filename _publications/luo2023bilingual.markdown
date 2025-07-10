---
layout: publication
title: 'Taiyi: A Bilingual Fine-tuned Large Language Model For Diverse Biomedical
  Tasks'
authors: Ling Luo et al.
conference: Journal of the American Medical Informatics Association
year: 2023
citations: 28
bibkey: luo2023bilingual
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.11608'}]
tags: [Training Techniques, Fine-Tuning, RAG, Evaluation]
---
Objective: Most existing fine-tuned biomedical large language models (LLMs)
focus on enhancing performance in monolingual biomedical question answering and
conversation tasks. To investigate the effectiveness of the fine-tuned LLMs on
diverse biomedical NLP tasks in different languages, We present Taiyi, a
bilingual fine-tuned LLM for diverse biomedical tasks. Materials and Methods:
We first curated a comprehensive collection of 140 existing biomedical text
mining datasets (102 English and 38 Chinese datasets) across over 10 task
types. Subsequently, a two-stage strategy is proposed for supervised
fine-tuning to optimize the model performance across varied tasks. Results:
Experimental results on 13 test sets covering named entity recognition,
relation extraction, text classification, question answering tasks demonstrate
that Taiyi achieves superior performance compared to general LLMs. The case
study involving additional biomedical NLP tasks further shows Taiyi's
considerable potential for bilingual biomedical multi-tasking. Conclusion:
Leveraging rich high-quality biomedical corpora and developing effective
fine-tuning strategies can significantly improve the performance of LLMs within
the biomedical domain. Taiyi shows the bilingual multi-tasking capability
through supervised fine-tuning. However, those tasks such as information
extraction that are not generation tasks in nature remain challenging for
LLM-based generative approaches, and they still underperform the conventional
discriminative approaches of smaller language models.