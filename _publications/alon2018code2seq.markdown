---
layout: publication
title: 'Code2seq: Generating Sequences From Structured Representations Of Code'
authors: Uri Alon, Shaked Brody, Omer Levy, Eran Yahav
conference: Arxiv
year: 2018
bibkey: alon2018code2seq
citations: 400
additional_links: [{name: Code, url: 'http://code2seq.org'}, {name: Code, url: 'http://github.com/tech-srl/code2seq'},
  {name: Paper, url: 'https://arxiv.org/abs/1808.01400'}]
tags: ["Applications", "Has Code", "Llm For Code"]
short_authors: Alon et al.
---
The ability to generate natural language sequences from source code snippets
has a variety of applications such as code summarization, documentation, and
retrieval. Sequence-to-sequence (seq2seq) models, adopted from neural machine
translation (NMT), have achieved state-of-the-art performance on these tasks by
treating source code as a sequence of tokens. We present \\(\{\rm \{\scriptsize
CODE2SEQ\}\}\\): an alternative approach that leverages the syntactic structure of
programming languages to better encode source code. Our model represents a code
snippet as the set of compositional paths in its abstract syntax tree (AST) and
uses attention to select the relevant paths while decoding. We demonstrate the
effectiveness of our approach for two tasks, two programming languages, and
four datasets of up to \\(16\\)M examples. Our model significantly outperforms
previous models that were specifically designed for programming languages, as
well as state-of-the-art NMT models. An interactive online demo of our model is
available at http://code2seq.org. Our code, data and trained models are
available at http://github.com/tech-srl/code2seq.