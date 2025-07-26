---
layout: publication
title: To Believe Or Not To Believe Your LLM
authors: "Yasin Abbasi Yadkori, Ilja Kuzborskij, Andr\xE1s Gy\xF6rgy, Csaba Szepesv\xE1\
  ri"
conference: No Venue
year: 2024
bibkey: yadkori2024believe
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.02543'}]
tags: ["Prompting"]
short_authors: Yadkori et al.
---
We explore uncertainty quantification in large language models (LLMs), with the goal to identify when uncertainty in responses given a query is large. We simultaneously consider both epistemic and aleatoric uncertainties, where the former comes from the lack of knowledge about the ground truth (such as about facts or the language), and the latter comes from irreducible randomness (such as multiple possible answers). In particular, we derive an information-theoretic metric that allows to reliably detect when only epistemic uncertainty is large, in which case the output of the model is unreliable. This condition can be computed based solely on the output of the model obtained simply by some special iterative prompting based on the previous responses. Such quantification, for instance, allows to detect hallucinations (cases when epistemic uncertainty is high) in both single- and multi-answer responses. This is in contrast to many standard uncertainty quantification strategies (such as thresholding the log-likelihood of a response) where hallucinations in the multi-answer case cannot be detected. We conduct a series of experiments which demonstrate the advantage of our formulation. Further, our investigations shed some light on how the probabilities assigned to a given output by an LLM can be amplified by iterative prompting, which might be of independent interest.

https://huggingface.co/discussions/paper/665fe729ae03446a3da12204