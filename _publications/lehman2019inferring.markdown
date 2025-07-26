---
layout: publication
title: Inferring Which Medical Treatments Work From Reports Of Clinical Trials
authors: Eric Lehman, Jay Deyoung, Regina Barzilay, Byron C. Wallace
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: lehman2019inferring
citations: 105
additional_links: [{name: Code, url: 'http://evidence-inference.ebm-nlp.com/'}, {
    name: Paper, url: 'https://arxiv.org/abs/1904.01606'}]
tags: ["Datasets", "Evaluation"]
short_authors: Lehman et al.
---
How do we know if a particular medical treatment actually works? Ideally one
would consult all available evidence from relevant clinical trials.
Unfortunately, such results are primarily disseminated in natural language
scientific articles, imposing substantial burden on those trying to make sense
of them. In this paper, we present a new task and corpus for making this
unstructured evidence actionable. The task entails inferring reported findings
from a full-text article describing a randomized controlled trial (RCT) with
respect to a given intervention, comparator, and outcome of interest, e.g.,
inferring if an article provides evidence supporting the use of aspirin to
reduce risk of stroke, as compared to placebo.
  We present a new corpus for this task comprising 10,000+ prompts coupled with
full-text articles describing RCTs. Results using a suite of models --- ranging
from heuristic (rule-based) approaches to attentive neural architectures ---
demonstrate the difficulty of the task, which we believe largely owes to the
lengthy, technical input texts. To facilitate further work on this important,
challenging problem we make the corpus, documentation, a website and
leaderboard, and code for baselines and evaluation available at
http://evidence-inference.ebm-nlp.com/.