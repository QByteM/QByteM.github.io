---
title: "AlignedNorm: Prompting Vision–Language Models via Coupled Prompt Field"
collection: publications
category: conferences
permalink: /publication/2026-06-26-paper-alignednorm-number-1
excerpt: 'AlignedNorm rethinks prompt learning for vision-language models as Coupled Prompt Field construction. By dynamically aligning prompt-token norms to the native scale of pretrained VLMs, it stabilizes task-agnostic coupling between base and new classes and improves generalization without external distillation or decoupled inference.'
date: 2026-06-26
venue: 'International Conference on Machine Learning (ICML)'
slidesurl: '/files/AlignedNorm_slide.pptx'
paperurl: '/files/AlignedNorm_EN.pdf'
paperurl_cn: '/files/AlignedNorm_CN.pdf'
projectpageurl:
interpretationurl_cn:
codeurl: 'https://github.com/QByteM/AlignedNorm'
officialurl: 'https://openreview.net/forum?id=aQAWAtrxxe'
bibtexurl: '/files/bibtex_AlignedNorm.bib'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Prompt learning has become an efficient way to adapt vision-language models (VLMs) to downstream tasks. However, existing end-to-end and decoupled methods often optimize base and new classes in isolated, task-specific feature spaces, which can lead to local optima and limited generalization.

We introduce AlignedNorm, a simple prompt-learning method built upon the concept of a Coupled Prompt Field. Instead of treating base and new classes independently, the coupled field places them in a shared optimization space where their learning dynamics mutually constrain each other. AlignedNorm realizes this coupling by dynamically aligning learnable prompts with the native feature scale of the pretrained VLM.
