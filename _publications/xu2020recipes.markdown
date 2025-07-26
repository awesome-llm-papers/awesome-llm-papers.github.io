---
layout: publication
title: Recipes For Safety In Open-domain Chatbots
authors: Jing Xu, da Ju, Margaret Li, Y-lan Boureau, Jason Weston, Emily Dinan
conference: Arxiv
year: 2020
bibkey: xu2020recipes
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.07079'}]
tags: ["Ethics & Fairness"]
short_authors: Xu et al.
---
Models trained on large unlabeled corpora of human interactions will learn
patterns and mimic behaviors therein, which include offensive or otherwise
toxic behavior and unwanted biases. We investigate a variety of methods to
mitigate these issues in the context of open-domain generative dialogue models.
We introduce a new human-and-model-in-the-loop framework for both training
safer models and for evaluating them, as well as a novel method to distill
safety considerations inside generative models without the use of an external
classifier at deployment time. We conduct experiments comparing these methods
and find our new techniques are (i) safer than existing models as measured by
automatic and human evaluations while (ii) maintaining usability metrics such
as engagingness relative to the state of the art. We then discuss the
limitations of this work by analyzing failure cases of our models.