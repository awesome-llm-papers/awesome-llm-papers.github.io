---
layout: publication
title: 'SPECTER: Document-level Representation Learning Using Citation-informed Transformers'
authors: Arman Cohan, Sergey Feldman, Iz Beltagy, Doug Downey, Daniel S. Weld
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: cohan2020specter
citations: 306
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.07180'}]
tags: ["Applications", "Evaluation", "Model Architecture"]
short_authors: Cohan et al.
---
Representation learning is a critical ingredient for natural language
processing systems. Recent Transformer language models like BERT learn powerful
textual representations, but these models are targeted towards token- and
sentence-level training objectives and do not leverage information on
inter-document relatedness, which limits their document-level representation
power. For applications on scientific documents, such as classification and
recommendation, the embeddings power strong performance on end tasks. We
propose SPECTER, a new method to generate document-level embedding of
scientific documents based on pretraining a Transformer language model on a
powerful signal of document-level relatedness: the citation graph. Unlike
existing pretrained language models, SPECTER can be easily applied to
downstream applications without task-specific fine-tuning. Additionally, to
encourage further research on document-level models, we introduce SciDocs, a
new evaluation benchmark consisting of seven document-level tasks ranging from
citation prediction, to document classification and recommendation. We show
that SPECTER outperforms a variety of competitive baselines on the benchmark.