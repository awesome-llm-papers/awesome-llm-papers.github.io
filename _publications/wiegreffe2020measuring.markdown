---
layout: publication
title: Measuring Association Between Labels And Free-text Rationales
authors: "Sarah Wiegreffe, Ana Marasovi\u0107, Noah A. Smith"
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: wiegreffe2020measuring
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12762'}]
tags: ["EMNLP"]
short_authors: "Sarah Wiegreffe, Ana Marasovi\u0107, Noah A. Smith"
---
In interpretable NLP, we require faithful rationales that reflect the model's
decision-making process for an explained instance. While prior work focuses on
extractive rationales (a subset of the input words), we investigate their
less-studied counterpart: free-text natural language rationales. We demonstrate
that pipelines, existing models for faithful extractive rationalization on
information-extraction style tasks, do not extend as reliably to "reasoning"
tasks requiring free-text rationales. We turn to models that jointly predict
and rationalize, a class of widely used high-performance models for free-text
rationalization whose faithfulness is not yet established. We define
label-rationale association as a necessary property for faithfulness: the
internal mechanisms of the model producing the label and the rationale must be
meaningfully correlated. We propose two measurements to test this property:
robustness equivalence and feature importance agreement. We find that
state-of-the-art T5-based joint models exhibit both properties for
rationalizing commonsense question-answering and natural language inference,
indicating their potential for producing faithful free-text rationales.