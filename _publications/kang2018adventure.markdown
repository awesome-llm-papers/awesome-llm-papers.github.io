---
layout: publication
title: 'Adventure: Adversarial Training For Textual Entailment With Knowledge-guided
  Examples'
authors: Dongyeop Kang, Tushar Khot, Ashish Sabharwal, Eduard Hovy
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: kang2018adventure
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.04680'}]
tags: ["Training Techniques"]
short_authors: Kang et al.
---
We consider the problem of learning textual entailment models with limited
supervision (5K-10K training examples), and present two complementary
approaches for it. First, we propose knowledge-guided adversarial example
generators for incorporating large lexical resources in entailment models via
only a handful of rule templates. Second, to make the entailment model - a
discriminator - more robust, we propose the first GAN-style approach for
training it using a natural language example generator that iteratively adjusts
based on the discriminator's performance. We demonstrate effectiveness using
two entailment datasets, where the proposed methods increase accuracy by 4.7%
on SciTail and by 2.8% on a 1% training sub-sample of SNLI. Notably, even a
single hand-written rule, negate, improves the accuracy on the negation
examples in SNLI by 6.1%.