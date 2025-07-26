---
layout: publication
title: 'Paper2poster: Towards Multimodal Poster Automation From Scientific Papers'
authors: Wei Pang, Kevin Qinghong Lin, Xiangru Jian, Xi He, Philip Torr
conference: No Venue
year: 2025
bibkey: pang2025paper2poster
additional_links: [{name: Code, url: 'https://github.com/Paper2Poster/Paper2Poster'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/68366e5d2ae719660434bc70'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.21497'}]
tags: ["Has Code", "Tools"]
short_authors: Pang et al.
---
Academic poster generation is a crucial yet challenging task in scientific communication, requiring the compression of long-context interleaved documents into a single, visually coherent page. To address this challenge, we introduce the first benchmark and metric suite for poster generation, which pairs recent conference papers with author-designed posters and evaluates outputs on (i)Visual Quality-semantic alignment with human posters, (ii)Textual Coherence-language fluency, (iii)Holistic Assessment-six fine-grained aesthetic and informational criteria scored by a VLM-as-judge, and notably (iv)PaperQuiz-the poster's ability to convey core paper content as measured by VLMs answering generated quizzes. Building on this benchmark, we propose PosterAgent, a top-down, visual-in-the-loop multi-agent pipeline: the (a)Parser distills the paper into a structured asset library; the (b)Planner aligns text-visual pairs into a binary-tree layout that preserves reading order and spatial balance; and the (c)Painter-Commenter loop refines each panel by executing rendering code and using VLM feedback to eliminate overflow and ensure alignment. In our comprehensive evaluation, we find that GPT-4o outputs-though visually appealing at first glance-often exhibit noisy text and poor PaperQuiz scores, and we find that reader engagement is the primary aesthetic bottleneck, as human-designed posters rely largely on visual semantics to convey meaning. Our fully open-source variants (e.g. based on the Qwen-2.5 series) outperform existing 4o-driven multi-agent systems across nearly all metrics, while using 87% fewer tokens. It transforms a 22-page paper into a finalized yet editable .pptx poster - all for just $0.005. These findings chart clear directions for the next generation of fully automated poster-generation models. The code and datasets are available at https://github.com/Paper2Poster/Paper2Poster.

https://huggingface.co/discussions/paper/68366e5d2ae719660434bc70