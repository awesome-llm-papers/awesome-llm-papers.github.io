---
layout: publication
title: 'Syn-qg: Syntactic And Shallow Semantic Rules For Question Generation'
authors: Dhole Kaustubh D., Manning Christopher D.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: dhole2020syn
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.08694'}]
tags: [ACL, RAG, Evaluation]
---
Question Generation (QG) is fundamentally a simple syntactic transformation;
however, many aspects of semantics influence what questions are good to form.
We implement this observation by developing SynQG, a set of transparent
syntactic rules leveraging universal dependencies, shallow semantic parsing,
lexical resources, and custom rules which transform declarative sentences into
question-answer pairs. We utilize PropBank argument descriptions and VerbNet
state predicates to incorporate shallow semantic content, which helps generate
questions of a descriptive nature and produce inferential and semantically
richer questions than existing systems. In order to improve syntactic fluency
and eliminate grammatically incorrect questions, we employ back-translation
over the output of these syntactic rules. A set of crowd-sourced evaluations
shows that our system can generate a larger number of highly grammatical and
relevant questions than previous QG systems and that back-translation
drastically improves grammaticality at a slight cost of generating irrelevant
questions.