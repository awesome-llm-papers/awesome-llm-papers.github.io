---
layout: publication
title: Semantic Compression With Large Language Models
authors: Henry Gilbert, Michael Sandborn, Douglas C. Schmidt, Jesse Spencer-smith,
  Jules White
conference: Arxiv
year: 2023
citations: 17
bibkey: gilbert2023semantic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.12512'}]
tags: [RAG, GPT, Model Architecture, Prompting]
---
The rise of large language models (LLMs) is revolutionizing information
retrieval, question answering, summarization, and code generation tasks.
However, in addition to confidently presenting factually inaccurate information
at times (known as "hallucinations"), LLMs are also inherently limited by the
number of input and output tokens that can be processed at once, making them
potentially less effective on tasks that require processing a large set or
continuous stream of information. A common approach to reducing the size of
data is through lossless or lossy compression. Yet, in some cases it may not be
strictly necessary to perfectly recover every detail from the original data, as
long as a requisite level of semantic precision or intent is conveyed.
  This paper presents three contributions to research on LLMs. First, we
present the results from experiments exploring the viability of approximate
compression using LLMs, focusing specifically on GPT-3.5 and GPT-4 via ChatGPT
interfaces. Second, we investigate and quantify the capability of LLMs to
compress text and code, as well as to recall and manipulate compressed
representations of prompts. Third, we present two novel metrics -- Exact
Reconstructive Effectiveness (ERE) and Semantic Reconstruction Effectiveness
(SRE) -- that quantify the level of preserved intent between text compressed
and decompressed by the LLMs we studied. Our initial results indicate that
GPT-4 can effectively compress and reconstruct text while preserving the
semantic essence of the original text, providing a path to leverage
\\(\sim\\)5\\(\times\\) more tokens than present limits allow.