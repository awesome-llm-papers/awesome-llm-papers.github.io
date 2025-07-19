---
layout: publication
title: Lost In OCR Translation? Vision-based Approaches To Robust Document Retrieval
authors: Most et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2025
bibkey: most2025lost
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.05666'}]
tags: [Efficiency And Optimization, Evaluation, LLM for Code, RAG, Multimodal Models,
  Datasets]
---
Retrieval-Augmented Generation (RAG) has become a popular technique for enhancing the reliability and utility of Large Language Models (LLMs) by grounding responses in external documents. Traditional RAG systems rely on Optical Character Recognition (OCR) to first process scanned documents into text. However, even state-of-the-art OCRs can introduce errors, especially in degraded or complex documents. Recent vision-language approaches, such as ColPali, propose direct visual embedding of documents, eliminating the need for OCR. This study presents a systematic comparison between a vision-based RAG system (ColPali) and more traditional OCR-based pipelines utilizing Llama 3.2 (90B) and Nougat OCR across varying document qualities. Beyond conventional retrieval accuracy metrics, we introduce a semantic answer evaluation benchmark to assess end-to-end question-answering performance. Our findings indicate that while vision-based RAG performs well on documents it has been fine-tuned on, OCR-based RAG is better able to generalize to unseen documents of varying quality. We highlight the key trade-offs between computational efficiency and semantic accuracy, offering practical guidance for RAG practitioners in selecting between OCR-dependent and vision-based document retrieval systems in production environments.