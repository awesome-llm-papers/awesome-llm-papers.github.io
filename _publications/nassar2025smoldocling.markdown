---
layout: publication
title: 'Smoldocling: An Ultra-compact Vision-language Model For End-to-end Multi-modal
  Document Conversion'
authors: "Ahmed Nassar, Andres Marafioti, Matteo Omenetti, Maksym Lysak, Nikolaos\
  \ Livathinos, Christoph Auer, Lucas Morin, Rafael Teixeira de Lima, Yusik Kim, A.\
  \ Said Gurbuz, Michele Dolfi, Miquel Farr\xE9, Peter W. J. Staar"
conference: No Venue
year: 2025
bibkey: nassar2025smoldocling
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67d7d1c68a15934c10b15841'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.11576'}]
tags: ["Datasets"]
short_authors: Nassar et al.
---
We introduce SmolDocling, an ultra-compact vision-language model targeting end-to-end document conversion. Our model comprehensively processes entire pages by generating DocTags, a new universal markup format that captures all page elements in their full context with location. Unlike existing approaches that rely on large foundational models, or ensemble solutions that rely on handcrafted pipelines of multiple specialized models, SmolDocling offers an end-to-end conversion for accurately capturing content, structure and spatial location of document elements in a 256M parameters vision-language model. SmolDocling exhibits robust performance in correctly reproducing document features such as code listings, tables, equations, charts, lists, and more across a diverse range of document types including business documents, academic papers, technical reports, patents, and forms -- significantly extending beyond the commonly observed focus on scientific papers. Additionally, we contribute novel publicly sourced datasets for charts, tables, equations, and code recognition. Experimental results demonstrate that SmolDocling competes with other Vision Language Models that are up to 27 times larger in size, while reducing computational requirements substantially. The model is currently available, datasets will be publicly available soon.

https://huggingface.co/discussions/paper/67d7d1c68a15934c10b15841