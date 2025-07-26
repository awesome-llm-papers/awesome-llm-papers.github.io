---
layout: publication
title: 'Compare-mt: A Tool For Holistic Comparison Of Language Generation Systems'
authors: Graham Neubig, Zi-yi Dou, Junjie Hu, Paul Michel, Danish Pruthi, Xinyi Wang,
  John Wieting
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: neubig2019compare
citations: 117
additional_links: [{name: Code, url: 'https://github.com/neulab/compare-mt'}, {name: Paper,
    url: 'https://arxiv.org/abs/1903.07926'}]
tags: ["Has Code", "Tools"]
short_authors: Neubig et al.
---
In this paper, we describe compare-mt, a tool for holistic analysis and
comparison of the results of systems for language generation tasks such as
machine translation. The main goal of the tool is to give the user a high-level
and coherent view of the salient differences between systems that can then be
used to guide further analysis or system improvement. It implements a number of
tools to do so, such as analysis of accuracy of generation of particular types
of words, bucketed histograms of sentence accuracies or counts based on salient
characteristics, and extraction of characteristic \\(n\\)-grams for each system. It
also has a number of advanced features such as use of linguistic labels, source
side data, or comparison of log likelihoods for probabilistic models, and also
aims to be easily extensible by users to new types of analysis. The code is
available at https://github.com/neulab/compare-mt