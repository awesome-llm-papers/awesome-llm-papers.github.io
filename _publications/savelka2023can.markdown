---
layout: publication
title: Can GPT-4 Support Analysis Of Textual Data In Tasks Requiring Highly Specialized
  Domain Expertise?
authors: Jaromir Savelka, Kevin D. Ashley, Morgan A Gray, Hannes Westermann, Huihui
  Xu
conference: Proceedings of the 2023 Conference on Innovation and Technology in Computer
  Science Education V. 1
year: 2023
bibkey: savelka2023can
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.13906'}]
tags: ["Model Architecture", "Prompting"]
short_authors: Savelka et al.
---
We evaluated the capability of generative pre-trained transformers~(GPT-4) in
analysis of textual data in tasks that require highly specialized domain
expertise. Specifically, we focused on the task of analyzing court opinions to
interpret legal concepts. We found that GPT-4, prompted with annotation
guidelines, performs on par with well-trained law student annotators. We
observed that, with a relatively minor decrease in performance, GPT-4 can
perform batch predictions leading to significant cost reductions. However,
employing chain-of-thought prompting did not lead to noticeably improved
performance on this task. Further, we demonstrated how to analyze GPT-4's
predictions to identify and mitigate deficiencies in annotation guidelines, and
subsequently improve the performance of the model. Finally, we observed that
the model is quite brittle, as small formatting related changes in the prompt
had a high impact on the predictions. These findings can be leveraged by
researchers and practitioners who engage in semantic/pragmatic annotations of
texts in the context of the tasks requiring highly specialized domain
expertise.