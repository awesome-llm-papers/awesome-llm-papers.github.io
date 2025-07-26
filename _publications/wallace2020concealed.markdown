---
layout: publication
title: Concealed Data Poisoning Attacks On NLP Models
authors: Eric Wallace, Tony Z. Zhao, Shi Feng, Sameer Singh
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: wallace2020concealed
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12563'}]
tags: ["NAACL", "Security"]
short_authors: Wallace et al.
---
Adversarial attacks alter NLP model predictions by perturbing test-time
inputs. However, it is much less understood whether, and how, predictions can
be manipulated with small, concealed changes to the training data. In this
work, we develop a new data poisoning attack that allows an adversary to
control model predictions whenever a desired trigger phrase is present in the
input. For instance, we insert 50 poison examples into a sentiment model's
training set that causes the model to frequently predict Positive whenever the
input contains "James Bond". Crucially, we craft these poison examples using a
gradient-based procedure so that they do not mention the trigger phrase. We
also apply our poison attack to language modeling ("Apple iPhone" triggers
negative generations) and machine translation ("iced coffee" mistranslated as
"hot coffee"). We conclude by proposing three defenses that can mitigate our
attack at some cost in prediction accuracy or extra human annotation.