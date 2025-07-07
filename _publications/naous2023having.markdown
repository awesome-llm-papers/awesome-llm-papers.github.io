---
layout: publication
title: Having Beer After Prayer? Measuring Cultural Bias In Large Language Models
authors: Tarek Naous, Michael J. Ryan, Alan Ritter, Wei Xu
conference: Arxiv
year: 2023
citations: 19
bibkey: naous2023having
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14456'}, {name: Code,
    url: 'https://github.com/tareknaous/camel'}]
tags: [Ethics and Bias, Training Techniques, Pre-Training, Has Code, Fairness, Bias
    Mitigation, Prompting]
---
As the reach of large language models (LMs) expands globally, their ability
to cater to diverse cultural contexts becomes crucial. Despite advancements in
multilingual capabilities, models are not designed with appropriate cultural
nuances. In this paper, we show that multilingual and Arabic monolingual LMs
exhibit bias towards entities associated with Western culture. We introduce
CAMeL, a novel resource of 628 naturally-occurring prompts and 20,368 entities
spanning eight types that contrast Arab and Western cultures. CAMeL provides a
foundation for measuring cultural biases in LMs through both extrinsic and
intrinsic evaluations. Using CAMeL, we examine the cross-cultural performance
in Arabic of 16 different LMs on tasks such as story generation, NER, and
sentiment analysis, where we find concerning cases of stereotyping and cultural
unfairness. We further test their text-infilling performance, revealing the
incapability of appropriate adaptation to Arab cultural contexts. Finally, we
analyze 6 Arabic pre-training corpora and find that commonly used sources such
as Wikipedia may not be best suited to build culturally aware LMs, if used as
they are without adjustment. We will make CAMeL publicly available at:
https://github.com/tareknaous/camel