---
layout: publication
title: 'TRIE: End-to-end Text Reading And Information Extraction For Document Understanding'
authors: Peng Zhang, Yunlu Xu, Zhanzhan Cheng, Shiliang Pu, Jing Lu, Liang Qiao, Yi
  Niu, Fei Wu
conference: Proceedings of the 28th ACM International Conference on Multimedia
year: 2020
bibkey: zhang2020trie
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.13118'}]
tags: ["Datasets", "Efficiency"]
short_authors: Zhang et al.
---
Since real-world ubiquitous documents (e.g., invoices, tickets, resumes and
leaflets) contain rich information, automatic document image understanding has
become a hot topic. Most existing works decouple the problem into two separate
tasks, (1) text reading for detecting and recognizing texts in images and (2)
information extraction for analyzing and extracting key elements from
previously extracted plain text. However, they mainly focus on improving
information extraction task, while neglecting the fact that text reading and
information extraction are mutually correlated. In this paper, we propose a
unified end-to-end text reading and information extraction network, where the
two tasks can reinforce each other. Specifically, the multimodal visual and
textual features of text reading are fused for information extraction and in
turn, the semantics in information extraction contribute to the optimization of
text reading. On three real-world datasets with diverse document images (from
fixed layout to variable layout, from structured text to semi-structured text),
our proposed method significantly outperforms the state-of-the-art methods in
both efficiency and accuracy.