---
layout: archive
title: "Towards Usable and Useful Explainable AI"
permalink: /portfolio/
author_profile: true
---

My research interests are responsible AI, particularly in explainable AI (XAI) and privacy-preserving machine learning. For XAI, specifically, my research is to develop <b>Usable XAI-as-a-Service systems (Usable XAI)</b> and <b>Useful Explainable AI toolkits (Useful XAI)</b>. The ultimate goal of my research is to advance <b>XAI that enables trust, control, and meaningful human–AI interaction</b>. 

<div align="center">
<img src='/images/framework.png' width=600>
</div>

Here, Usable XAI refers to <b>human-centric explanation services</b> that support model understanding with strong faithfulness and practical utility. The central question is: "<i>How can models explain themselves in terms that people can actually understand and use?</i>" Useful XAI focuses on <b>model-centric interpretability</b>, where explanation toolkits reveal the model’s underlying computational graph and provide actionable insights for improving performance and trustworthiness. This line of work asks: “<i>What computation is actually implemented inside large models?</i>” Building on Usable XAI and Useful XAI, my research further explores <b>Interactive XAI</b>, which treats explanations as interfaces for human–AI interaction. By grounding human-centric explanations in model-centric computational understanding, Interactive XAI enables a progression from trust, to control, and ultimately to sustained human–AI interaction. My research helps realize these goals by making progress in the following five directions:

- <b>Theoretical Foundations of Usable XAI:</b> stability(<a href="https://openreview.net/pdf?id=YdwwWRX20q">[ICML'24 Spotlight]</a>,<a href="https://openreview.net/pdf?id=rp0EdI8X4e">[ICLR'24]</a>,<a href="https://ojs.aaai.org/index.php/AAAI/article/view/26517">[AAAI'23 Oral]</a>,<a href="https://openreview.net/forum?id=Y8EspxaksH">[TMLR]</a>), controllability(<a href="https://arxiv.org/abs/2411.11667">[ICML'25,a]</a>,<a href="https://arxiv.org/abs/2405.15476" >[ICLR'26,b]</a>), consistency(<a href="https://arxiv.org/abs/2406.18992">[ICCV'25]</a>,<a href="https://arxiv.org/abs/2410.21494">[NeurIPS'24]</a>,<a href="https://arxiv.org/pdf/2410.06606">[EMNLP'24,a]</a>)
- <b>Useful XAI in Large Models:</b> enhance safety(<a href="https://ojs.aaai.org/index.php/AAAI/article/view/34710">[AAAI'25 Oral,a]</a>,<a href="https://arxiv.org/abs/2410.06331">[ICML'25,b]</a>,<a href="https://arxiv.org/pdf/2502.09022">[NAACL'25]</a>,<a href="https://arxiv.org/abs/2311.17695" >[AAAI'25 Oral,b]</a>,<a href="https://openreview.net/forum?id=Nd950RAcCW#discussion">[COLM'24,a]</a>,<a href="https://openreview.net/forum?id=FX4fUThO9H#discussion">[COLM'24,b]</a>,<a href="https://arxiv.org/pdf/2410.06606">[EMNLP'24 Oral,b]</a>), boost model performance(<a href="https://openreview.net/pdf?id=yrnrvfXFaV">[ArXiv]</a>), steer model behavior([WWW'26],<a href="https://arxiv.org/pdf/2410.03595">[ArXiv]</a>)
- <b>System for XAI:</b> acceleration([ICLR'26,b],[ICLR'26,c],[ICLR'26,d]), reproducibility, accessibility
- <b>Interactive XAI:</b> alignment(WWW'26), interaction, co-adaptation
- <b>XAI for Science:</b> protein([ICLR'26,a]), healthcare(<a href="https://openreview.net/pdf?id=rp0EdI8X4e">[ICLR'24]</a>,<a href="https://arxiv.org/abs/2410.21494">[NeurIPS'24]</a>,<a href="https://arxiv.org/abs/2506.05286">[ECML-PKDD'25]</a>), autonomous driving(<a href="https://arxiv.org/abs/2409.10330">[ICRA'25]</a>), material science([Advanced Science]), marine science

For privacy-preserving machine learning, I mainly focused on private statistical estimation(<a href="https://jmlr.org/papers/v24/21-0523.html">[JMLR,a]</a>,<a href="https://jmlr.org/papers/v25/22-0079.html">[JMLR,b]</a>,<a href="https://arxiv.org/abs/2010.13520">[ECAI'23]</a>,<a href="https://proceedings.mlr.press/v206/hu23a/hu23a.pdf">[AISTATS'23]</a>,<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10314000">[TKDE]</a>,<a href="https://dl.acm.org/doi/abs/10.1145/3517804.3524144">[PODS'22]</a>,<a href="https://proceedings.mlr.press/v167/su22a/su22a.pdf">[ALT'22]</a>) and its application to natural language models(<a href="https://arxiv.org/abs/2410.08027">[EMNLP'24 Oral,c]</a>,<a href="https://aclanthology.org/2024.findings-eacl.33/">[EACL'24]</a>).

## Theoretical Foundations of Usable XAI
Several interpretation techniques have been developed to enhance the explainability of deep learning models. However, few of them have delved into a fundamental question: do we truly trust these explainers? In other words, are these interpretable methods faithful to the underlying models? This problem hinders the practical application of XAI. Thus, a usable XAI should provide faithful interpretations. I mainly focused on achieving Usable XAI from three aspects. Specifically, my research mainly focuses on improving the explanation faithfulness for current methods from three aspects: <b>stability</b>, <b>controllability</b>, and <b>consistency</b>.

<div align="center">
<img src='/images/framework1.jpg' width=600>
</div>

<hr />

## Towards Useful XAI in Large Models
I also applied Useful XAI as a toolkit, which can serve as a guide for boosting utility and enhancing the trustworthiness of deep learning models. I mainly focus on the following three aspects via interpretability. First, <b>Enhancing Trustworthiness</b>. Useful XAI can serve as a tool to enhance trustworthiness, which is essential for LLMs. I mainly focus on using interpretability to mitigate safety challenges in LLM, such as hallucination, jailbreaking, privacy, and copyright infringement. Second, <b>Boosting Utility.</b> Useful XAI can also be a powerful tool to boost model performance. For example, XAI can be used as a modality for alignment with LLMs and Graph, reducing time and costs by 100X. Additionally, XAI can be used to fine-tune LLMs, equipping them with capabilities for self-aware error identification and correction. Third, <b>Analyzing Models.</b> Useful XAI can also serve as an analytical tool to reveal the deeper behaviors of LLMs.

<div align="center">
<img src='/images/framework2.jpg' width=600>
</div>

<hr />

## Towards Usable XAI for Science
Usable XAI models are essential in AI applications for the science field because they enable researchers and practitioners to understand and trust the decisions made by complex models. Through a wide range of interdisciplinary collaborations, I have deployed these technologies for impactful applications in <b>healthcare</b>, <b>traffic</b>, <b>material science</b>, and <b>marine science</b>. 

<div align="center">
<img src='/images/framework3.jpg' width=600>
</div>
