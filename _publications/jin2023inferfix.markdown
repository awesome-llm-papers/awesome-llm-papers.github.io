---
layout: publication
title: 'Inferfix: End-to-end Program Repair With Llms'
authors: Matthew Jin, Syed Shahriar, Michele Tufano, Xin Shi, Shuai Lu, Neel Sundaresan,
  Alexey Svyatkovskiy
conference: Proceedings of the 31st ACM Joint European Software Engineering Conference
  and Symposium on the Foundations of Software Engineering
year: 2023
bibkey: jin2023inferfix
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.07263'}]
tags: ["Llm For Code", "Tools"]
short_authors: Jin et al.
---
Software development life cycle is profoundly influenced by bugs: their
introduction, identification, and eventual resolution account for a significant
portion of software cost. This has motivated software engineering researchers
and practitioners to propose different approaches for automating the
identification and repair of software defects. Large language models have been
adapted to the program repair task through few-shot demonstration learning and
instruction prompting, treating this as an infilling task. However, these
models have only focused on learning general bug-fixing patterns for
uncategorized bugs mined from public repositories. In this paper, we propose
InferFix: a transformer-based program repair framework paired with a
state-of-the-art static analyzer to fix critical security and performance bugs.
InferFix combines a Retriever -- transformer encoder model pretrained via
contrastive learning objective, which aims at searching for semantically
equivalent bugs and corresponding fixes; and a Generator -- a large language
model (Codex Cushman) finetuned on supervised bug-fix data with prompts
augmented via bug type annotations and semantically similar fixes retrieved
from an external non-parametric memory. To train and evaluate our approach, we
curated InferredBugs, a novel, metadata-rich dataset of bugs extracted by
executing the Infer static analyzer on the change histories of thousands of
Java and C# repositories. Our evaluation demonstrates that InferFix outperforms
strong LLM baselines, with a top-1 accuracy of 65.6% for generating fixes in C#
and 76.8% in Java. We discuss the deployment of InferFix alongside Infer at
Microsoft which offers an end-to-end solution for detection, classification,
and localization of bugs, as well as fixing and validation of candidate
patches, integrated in the continuous integration pipeline to automate the
software development workflow.