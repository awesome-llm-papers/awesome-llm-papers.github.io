---
layout: publication
title: 'REL: An Entity Linker Standing On The Shoulders Of Giants'
authors: Johannes M. van Hulst, Faegheh Hasibi, Koen Dercksen, Krisztian Balog, Arjen
  P. de Vries
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2020
bibkey: vanhulst2020rel
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.01969'}]
tags: ["SIGIR", "Tools"]
short_authors: Hulst et al.
---
Entity linking is a standard component in modern retrieval system that is
often performed by third-party toolkits. Despite the plethora of open source
options, it is difficult to find a single system that has a modular
architecture where certain components may be replaced, does not depend on
external sources, can easily be updated to newer Wikipedia versions, and, most
important of all, has state-of-the-art performance. The REL system presented in
this paper aims to fill that gap. Building on state-of-the-art neural
components from natural language processing research, it is provided as a
Python package as well as a web API. We also report on an experimental
comparison against both well-established systems and the current
state-of-the-art on standard entity linking benchmarks.