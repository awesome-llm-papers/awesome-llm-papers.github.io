---
layout: publication
title: 'Autocrawler: A Progressive Understanding Web Agent For Web Crawler Generation'
authors: Wenhao Huang, Chenghao Peng, Zhixu Li, Jiaqing Liang, Yanghua Xiao, Liqian
  Wen, Zulong Chen
conference: No Venue
year: 2024
bibkey: huang2024autocrawler
additional_links: [{name: Code, url: 'https://github.com/EZ-hwh/AutoCrawler'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2404.12753'}]
tags: ["Agentic", "Tools"]
short_authors: Huang et al.
---
Web automation is a significant technique that accomplishes complicated web tasks by automating common web actions, enhancing operational efficiency, and reducing the need for manual intervention. Traditional methods, such as wrappers, suffer from limited adaptability and scalability when faced with a new website. On the other hand, generative agents empowered by large language models (LLMs) exhibit poor performance and reusability in open-world scenarios. In this work, we introduce a crawler generation task for vertical information web pages and the paradigm of combining LLMs with crawlers, which helps crawlers handle diverse and changing web environments more efficiently. We propose AutoCrawler, a two-stage framework that leverages the hierarchical structure of HTML for progressive understanding. Through top-down and step-back operations, AutoCrawler can learn from erroneous actions and continuously prune HTML for better action generation. We conduct comprehensive experiments with multiple LLMs and demonstrate the effectiveness of our framework. Resources of this paper can be found at https://github.com/EZ-hwh/AutoCrawler

https://huggingface.co/discussions/paper/6625f2f722668df9ad4f88ed