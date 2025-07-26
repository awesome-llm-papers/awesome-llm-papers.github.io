---
layout: publication
title: 'NL4DV: A Toolkit For Generating Analytic Specifications For Data Visualization
  From Natural Language Queries'
authors: Arpit Narechania, Arjun Srinivasan, John Stasko
conference: IEEE Transactions on Visualization and Computer Graphics
year: 2020
bibkey: narechania2020nl4dv
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.10723'}]
tags: ["Datasets"]
short_authors: Arpit Narechania, Arjun Srinivasan, John Stasko
---
Natural language interfaces (NLIs) have shown great promise for visual data
analysis, allowing people to flexibly specify and interact with visualizations.
However, developing visualization NLIs remains a challenging task, requiring
low-level implementation of natural language processing (NLP) techniques as
well as knowledge of visual analytic tasks and visualization design. We present
NL4DV, a toolkit for natural language-driven data visualization. NL4DV is a
Python package that takes as input a tabular dataset and a natural language
query about that dataset. In response, the toolkit returns an analytic
specification modeled as a JSON object containing data attributes, analytic
tasks, and a list of Vega-Lite specifications relevant to the input query. In
doing so, NL4DV aids visualization developers who may not have a background in
NLP, enabling them to create new visualization NLIs or incorporate natural
language input within their existing systems. We demonstrate NL4DV's usage and
capabilities through four examples: 1) rendering visualizations using natural
language in a Jupyter notebook, 2) developing a NLI to specify and edit
Vega-Lite charts, 3) recreating data ambiguity widgets from the DataTone
system, and 4) incorporating speech input to create a multimodal visualization
system.