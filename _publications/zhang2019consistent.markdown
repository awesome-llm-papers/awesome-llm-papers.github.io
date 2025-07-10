---
layout: publication
title: Consistent Dialogue Generation With Self-supervised Feature Learning
authors: Yizhe Zhang et al.
conference: Arxiv
year: 2019
citations: 32
bibkey: zhang2019consistent
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.05759'}]
tags: [Agentic, Training Techniques, Evaluation]
---
Generating responses that are consistent with the dialogue context is one of
the central challenges in building engaging conversational agents. We
demonstrate that neural conversation models can be geared towards generating
consistent responses by maintaining certain features related to topics and
personas throughout the conversation. Past work has required external
supervision that exploits features such as user identities that are often
unavailable. In our approach, topic and persona feature extractors are trained
using a contrastive training scheme that utilizes the natural structure of
dialogue data. We further adopt a feature disentangling loss which, paired with
controllable response generation techniques, allows us to promote or demote
certain learned topics and persona features. Evaluation results demonstrate the
model's ability to capture meaningful topics and persona features. The
incorporation of the learned features brings significant improvement in terms
of the quality of generated responses on two dialogue datasets.