---
layout: publication
title: 'Essential-web V1.0: 24T Tokens Of Organized Web Data'
authors: Essential Ai, Andrew Hojel, Michael Pust, Tim Romanski, Yash Vanjani, Ritvik
  Kapila, Mohit Parmar, Adarsh Chaluvaraju, Alok Tripathy, Anil Thomas, Ashish Tanwer,
  Darsh J Shah, Ishaan Shah, Karl Stratos, Khoi Nguyen, Kurt Smith, Michael Callahan,
  Peter Rushton, Philip Monk, Platon Mazarakis, Saad Jamal, Saurabh Srivastava, Somanshu
  Singla, Ashish Vaswani
conference: No Venue
year: 2025
bibkey: ai2025essential
additional_links: [{name: Code, url: 'https://huggingface.co/datasets/EssentialAI/essential-web-v1.0'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6852072b0164cd1316710420'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.14111'}]
tags: ["Datasets"]
short_authors: Ai et al.
---
Data plays the most prominent role in how language models acquire skills and knowledge. The lack of massive, well-organized pre-training datasets results in costly and inaccessible data pipelines. We present Essential-Web v1.0, a 24-trillion-token dataset in which every document is annotated with a twelve-category taxonomy covering topic, format, content complexity, and quality. Taxonomy labels are produced by EAI-Distill-0.5b, a fine-tuned 0.5b-parameter model that achieves an annotator agreement within 3% of Qwen2.5-32B-Instruct. With nothing more than SQL-style filters, we obtain competitive web-curated datasets in math (-8.0% relative to SOTA), web code (+14.3%), STEM (+24.5%) and medical (+8.6%). Essential-Web v1.0 is available on HuggingFace: https://huggingface.co/datasets/EssentialAI/essential-web-v1.0

https://huggingface.co/discussions/paper/6852072b0164cd1316710420