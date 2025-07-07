---
layout: publication
title: Distilling Large Language Models For Matching Patients To Clinical Trials
authors: Mauro Nievas, Aditya Basu, Yanshan Wang, Hrituraj Singh
conference: Arxiv
year: 2023
citations: 33
bibkey: nievas2023distilling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.09958'}]
tags: [Training Techniques, GPT, Fine-Tuning, Reinforcement Learning, Tools, Applications,
  Model Architecture]
---
The recent success of large language models (LLMs) has paved the way for
their adoption in the high-stakes domain of healthcare. Specifically, the
application of LLMs in patient-trial matching, which involves assessing patient
eligibility against clinical trial's nuanced inclusion and exclusion criteria,
has shown promise. Recent research has shown that GPT-3.5, a widely recognized
LLM developed by OpenAI, can outperform existing methods with minimal 'variable
engineering' by simply comparing clinical trial information against patient
summaries. However, there are significant challenges associated with using
closed-source proprietary LLMs like GPT-3.5 in practical healthcare
applications, such as cost, privacy and reproducibility concerns. To address
these issues, this study presents the first systematic examination of the
efficacy of both proprietary (GPT-3.5, and GPT-4) and open-source LLMs (LLAMA
7B,13B, and 70B) for the task of patient-trial matching. Employing a
multifaceted evaluation framework, we conducted extensive automated and
human-centric assessments coupled with a detailed error analysis for each
model. To enhance the adaptability of open-source LLMs, we have created a
specialized synthetic dataset utilizing GPT-4, enabling effective fine-tuning
under constrained data conditions. Our findings reveal that open-source LLMs,
when fine-tuned on this limited and synthetic dataset, demonstrate performance
parity with their proprietary counterparts. This presents a massive opportunity
for their deployment in real-world healthcare applications. To foster further
research and applications in this field, we release both the annotated
evaluation dataset along with the fine-tuned LLM -- Trial-LLAMA -- for public
use.