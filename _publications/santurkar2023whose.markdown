---
layout: publication
title: Whose Opinions Do Language Models Reflect?
authors: Shibani Santurkar, Esin Durmus, Faisal Ladhak, Cinoo Lee, Percy Liang, Tatsunori
  Hashimoto
conference: Arxiv
year: 2023
bibkey: santurkar2023whose
citations: 73
additional_links: [{name: Code, url: 'https://github.com/tatsu-lab/opinions_qa'},
  {name: Paper, url: 'https://arxiv.org/abs/2303.17548'}]
tags: ["Datasets", "Has Code", "Tools"]
short_authors: Santurkar et al.
---
Language models (LMs) are increasingly being used in open-ended contexts,
where the opinions reflected by LMs in response to subjective queries can have
a profound impact, both on user satisfaction, as well as shaping the views of
society at large. In this work, we put forth a quantitative framework to
investigate the opinions reflected by LMs -- by leveraging high-quality public
opinion polls and their associated human responses. Using this framework, we
create OpinionsQA, a new dataset for evaluating the alignment of LM opinions
with those of 60 US demographic groups over topics ranging from abortion to
automation. Across topics, we find substantial misalignment between the views
reflected by current LMs and those of US demographic groups: on par with the
Democrat-Republican divide on climate change. Notably, this misalignment
persists even after explicitly steering the LMs towards particular demographic
groups. Our analysis not only confirms prior observations about the
left-leaning tendencies of some human feedback-tuned LMs, but also surfaces
groups whose opinions are poorly reflected by current LMs (e.g., 65+ and
widowed individuals). Our code and data are available at
https://github.com/tatsu-lab/opinions_qa.