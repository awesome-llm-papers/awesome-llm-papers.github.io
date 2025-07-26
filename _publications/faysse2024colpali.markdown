---
layout: publication
title: 'Colpali: Efficient Document Retrieval With Vision Language Models'
authors: "Manuel Faysse, Hugues Sibille, Tony Wu, Gautier Viaud, C\xE9line Hudelot,\
  \ Pierre Colombo"
conference: No Venue
year: 2024
bibkey: faysse2024colpali
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.01449'}]
tags: ["Applications", "Model Architecture", "Retrieval Systems"]
short_authors: Faysse et al.
---
Documents are visually rich structures that convey information through text, as well as tables, figures, page layouts, or fonts. While modern document retrieval systems exhibit strong performance on query-to-text matching, they struggle to exploit visual cues efficiently, hindering their performance on practical document retrieval applications such as Retrieval Augmented Generation. To benchmark current systems on visually rich document retrieval, we introduce the Visual Document Retrieval Benchmark ViDoRe, composed of various page-level retrieving tasks spanning multiple domains, languages, and settings. The inherent shortcomings of modern systems motivate the introduction of a new retrieval model architecture, ColPali, which leverages the document understanding capabilities of recent Vision Language Models to produce high-quality contextualized embeddings solely from images of document pages. Combined with a late interaction matching mechanism, ColPali largely outperforms modern document retrieval pipelines while being drastically faster and end-to-end trainable.

https://huggingface.co/discussions/paper/6683970a2235ae231ac5ef1c