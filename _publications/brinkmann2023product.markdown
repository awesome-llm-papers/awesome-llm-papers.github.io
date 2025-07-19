---
layout: publication
title: Product Information Extraction Using Chatgpt
authors: Brinkmann et al.
conference: International Journal of Medical Informatics
year: 2023
bibkey: brinkmann2023product
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.14921'}]
tags: [Training Techniques, GPT, Prompting, Model Architecture, Few Shot, Applications,
  Fine Tuning]
---
Structured product data in the form of attribute/value pairs is the
foundation of many e-commerce applications such as faceted product search,
product comparison, and product recommendation. Product offers often only
contain textual descriptions of the product attributes in the form of titles or
free text. Hence, extracting attribute/value pairs from textual product
descriptions is an essential enabler for e-commerce applications. In order to
excel, state-of-the-art product information extraction methods require large
quantities of task-specific training data. The methods also struggle with
generalizing to out-of-distribution attributes and attribute values that were
not a part of the training data. Due to being pre-trained on huge amounts of
text as well as due to emergent effects resulting from the model size, Large
Language Models like ChatGPT have the potential to address both of these
shortcomings. This paper explores the potential of ChatGPT for extracting
attribute/value pairs from product descriptions. We experiment with different
zero-shot and few-shot prompt designs. Our results show that ChatGPT achieves a
performance similar to a pre-trained language model but requires much smaller
amounts of training data and computation for fine-tuning.