---
layout: publication
title: Gold-medalist Performance In Solving Olympiad Geometry With Alphageometry2
authors: "Yuri Chervonyi, Trieu H. Trinh, Miroslav Ol\u0161\xE1k, Xiaomeng Yang, Hoang\
  \ Nguyen, Marcelo Menegali, Junehyuk Jung, Vikas Verma, Quoc V. Le, Thang Luong"
conference: No Venue
year: 2025
bibkey: chervonyi2025gold
additional_links: [{name: Code, url: 'https://dpmd.ai/imo-silver'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67a589ecb16fabcdd2dea259'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.03544'}]
tags: ["Model Architecture"]
short_authors: Chervonyi et al.
---
We present AlphaGeometry2, a significantly improved version of AlphaGeometry introduced in Trinh et al. (2024), which has now surpassed an average gold medalist in solving Olympiad geometry problems. To achieve this, we first extend the original AlphaGeometry language to tackle harder problems involving movements of objects, and problems containing linear equations of angles, ratios, and distances. This, together with other additions, has markedly improved the coverage rate of the AlphaGeometry language on International Math Olympiads (IMO) 2000-2024 geometry problems from 66% to 88%. The search process of AlphaGeometry2 has also been greatly improved through the use of Gemini architecture for better language modeling, and a novel knowledge-sharing mechanism that combines multiple search trees. Together with further enhancements to the symbolic engine and synthetic data generation, we have significantly boosted the overall solving rate of AlphaGeometry2 to 84% for all geometry problems over the last 25 years, compared to 54% previously. AlphaGeometry2 was also part of the system that achieved silver-medal standard at IMO 2024 https://dpmd.ai/imo-silver. Last but not least, we report progress towards using AlphaGeometry2 as a part of a fully automated system that reliably solves geometry problems directly from natural language input.

https://huggingface.co/discussions/paper/67a589ecb16fabcdd2dea259