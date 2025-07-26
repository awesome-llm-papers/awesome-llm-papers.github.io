---
layout: publication
title: 'Pdftriage: Question Answering Over Long, Structured Documents'
authors: Jon Saad-falcon, Joe Barrow, Alexa Siu, Ani Nenkova, Ryan A. Rossi, Franck
  Dernoncourt
conference: No Venue
year: 2023
bibkey: saadfalcon2023pdftriage
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.08872'}]
tags: ["Memory & Context"]
short_authors: Saad-falcon et al.
---
Large Language Models (LLMs) have issues with document question answering (QA) in situations where the document is unable to fit in the small context length of an LLM. To overcome this issue, most existing works focus on retrieving the relevant context from the document, representing them as plain text. However, documents such as PDFs, web pages, and presentations are naturally structured with different pages, tables, sections, and so on. Representing such structured documents as plain text is incongruous with the user's mental model of these documents with rich structure. When a system has to query the document for context, this incongruity is brought to the fore, and seemingly trivial questions can trip up the QA system. To bridge this fundamental gap in handling structured documents, we propose an approach called PDFTriage that enables models to retrieve the context based on either structure or content. Our experiments demonstrate the effectiveness of the proposed PDFTriage-augmented models across several classes of questions where existing retrieval-augmented LLMs fail. To facilitate further research on this fundamental problem, we release our benchmark dataset consisting of 900+ human-generated questions over 80 structured documents from 10 different categories of question types for document QA.

https://huggingface.co/discussions/paper/65090c24c2d4c8fc37854aab