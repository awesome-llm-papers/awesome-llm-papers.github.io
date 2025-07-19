---
layout: publication
title: 'X-ray Made Simple: Lay Radiology Report Generation And Robust Evaluation'
authors: Zhao et al.
conference: Patterns
year: 2024
bibkey: zhao2024x
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.17911'}]
tags: [RAG, Fairness, Training Techniques, Bias Mitigation, Tools, Evaluation, Ethics
    And Bias, Reinforcement Learning, Security, Multimodal Models, Datasets]
---
Radiology Report Generation (RRG) has advanced considerably with the development of multimodal generative models. Despite the progress, the field still faces significant challenges in evaluation, as existing metrics lack robustness and fairness. We reveal that, RRG with high performance on existing lexical-based metrics (e.g. BLEU) might be more of a mirage - a model can get a high BLEU only by learning the template of reports. This has become a pressing issue for RRG due to the highly patternized nature of these reports. In addition, standard radiology reports are often highly technical. Helping patients understand these reports is crucial from a patient's perspective, yet this has been largely overlooked in previous work. In this work, we un-intuitively approach these problems by proposing the Layman's RRG framework that can systematically improve RRG with day-to-day language. Specifically, our framework first contributes a translated Layman's terms dataset. Building upon the dataset, we then propose a semantics-based evaluation method, which is effective in mitigating the inflated numbers of BLEU and provides more robust evaluation. We show that training on the layman's terms dataset encourages models to focus on the semantics of the reports, as opposed to overfitting to learning the report templates. Last, we reveal a promising scaling law between the number of training examples and semantics gain provided by our dataset, compared to the inverse pattern brought by the original formats.