---
layout: publication
title: 'Commonsenseqa 2.0: Exposing The Limits Of AI Through Gamification'
authors: Alon Talmor et al.
conference: Arxiv
year: 2022
citations: 46
bibkey: talmor2022commonsenseqa
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.05320'}]
tags: [GPT, Few-Shot, Tools, Security, Model Architecture]
---
Constructing benchmarks that test the abilities of modern natural language
understanding models is difficult - pre-trained language models exploit
artifacts in benchmarks to achieve human parity, but still fail on adversarial
examples and make errors that demonstrate a lack of common sense. In this work,
we propose gamification as a framework for data construction. The goal of
players in the game is to compose questions that mislead a rival AI while using
specific phrases for extra points. The game environment leads to enhanced user
engagement and simultaneously gives the game designer control over the
collected data, allowing us to collect high-quality data at scale. Using our
method we create CommonsenseQA 2.0, which includes 14,343 yes/no questions, and
demonstrate its difficulty for models that are orders-of-magnitude larger than
the AI used in the game itself. Our best baseline, the T5-based Unicorn with
11B parameters achieves an accuracy of 70.2%, substantially higher than GPT-3
(52.9%) in a few-shot inference setup. Both score well below human performance
which is at 94.1%.