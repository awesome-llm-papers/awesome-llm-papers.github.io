---
layout: publication
title: 'Revisiting Text-to-image Evaluation With Gecko: On Metrics, Prompts, And Human
  Ratings'
authors: Wiles et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: wiles2024revisiting
citations: 286
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.16820'}]
tags: [CVPR, Prompting, Evaluation, Datasets]
---
While text-to-image (T2I) generative models have become ubiquitous, they do
not necessarily generate images that align with a given prompt. While previous
work has evaluated T2I alignment by proposing metrics, benchmarks, and
templates for collecting human judgements, the quality of these components is
not systematically measured. Human-rated prompt sets are generally small and
the reliability of the ratings -- and thereby the prompt set used to compare
models -- is not evaluated. We address this gap by performing an extensive
study evaluating auto-eval metrics and human templates. We provide three main
contributions: (1) We introduce a comprehensive skills-based benchmark that can
discriminate models across different human templates. This skills-based
benchmark categorises prompts into sub-skills, allowing a practitioner to
pinpoint not only which skills are challenging, but at what level of complexity
a skill becomes challenging. (2) We gather human ratings across four templates
and four T2I models for a total of >100K annotations. This allows us to
understand where differences arise due to inherent ambiguity in the prompt and
where they arise due to differences in metric and model quality. (3) Finally,
we introduce a new QA-based auto-eval metric that is better correlated with
human ratings than existing metrics for our new dataset, across different human
templates, and on TIFA160.