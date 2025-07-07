---
layout: default
title: A Comprehensive Overview of Large Language Models (LLMs) with Papers, Resources and Colab Notebooks
---

### Welcome to the LLM Bible!

Large Language Models (LLMs) represent a groundbreaking leap in artificial intelligence, enabling machines to interpret, generate, and engage with human language in ways that are both profound and transformative. These models, trained on diverse datasets containing trillions of words, have become the backbone of numerous applications that influence how we gather information, make decisions, and interact with technology.

![Emergent capabilities of LLMs with growing parameter count](llm-tree.gif)

This website is dedicated to exploring the fascinating world of LLMs. Here, you will find a curated collection of research papers and educational materials to learn about LLMs. 

#### 🏷 Browse Papers by Tag
{% assign rawtags = Array.new %}
{% for publication in site.publications %}
  {% assign ttags = publication.tags  %}  
  {% assign rawtags = rawtags | concat: ttags %}  
{% endfor %}
{% assign rawtags = rawtags | uniq | sort_natural %}
{% for tag in rawtags %}<tag><a href="/tags.html#{{ tag }}">{{ tag }}</a></tag> {% endfor %}

---

### 📰 Stay Updated with the LLM News Digest

Get the latest research in your inbox every morning. Join thousands of researchers and engineers who subscribe to our [**LLM News Digest**](/digest.html) — a daily curated summary of the most important new papers on transformers, GPT, RLHF, RAG, and more.

[Subscribe now →](/digest.html)

---

### About This Site

This site is an experiment: a [living literature review](https://en.wikipedia.org/wiki/Living_review) that allows
you to explore, [search and navigate]({% link papers.html %}) the literature in this area.

### Contributing

This research area is evolving so fast that a static review cannot keep up.
But a website can! We hope to make this site a living document.
Anyone can add a paper to this website by completing a [web form](contributing.html).

---

Copyright © [Sean Moran](https://sjmoran.github.io/) 2025. All opinions are my own. Please see [Privacy Notice](privacy.html).
