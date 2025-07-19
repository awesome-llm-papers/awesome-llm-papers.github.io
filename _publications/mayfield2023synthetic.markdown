---
layout: publication
title: Synthetic Cross-language Information Retrieval Training Data
authors: Mayfield et al.
conference: Arxiv
year: 2023
bibkey: mayfield2023synthetic
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.00331'}]
tags: [Training Techniques]
---
A key stumbling block for neural cross-language information retrieval (CLIR)
systems has been the paucity of training data. The appearance of the MS MARCO
monolingual training set led to significant advances in the state of the art in
neural monolingual retrieval. By translating the MS MARCO documents into other
languages using machine translation, this resource has been made useful to the
CLIR community. Yet such translation suffers from a number of problems. While
MS MARCO is a large resource, it is of fixed size; its genre and domain of
discourse are fixed; and the translated documents are not written in the
language of a native speaker of the language, but rather in translationese. To
address these problems, we introduce the JH-POLO CLIR training set creation
methodology. The approach begins by selecting a pair of non-English passages. A
generative large language model is then used to produce an English query for
which the first passage is relevant and the second passage is not relevant. By
repeating this process, collections of arbitrary size can be created in the
style of MS MARCO but using naturally-occurring documents in any desired genre
and domain of discourse. This paper describes the methodology in detail, shows
its use in creating new CLIR training sets, and describes experiments using the
newly created training data.