# awesome-discrete-diffusion-models

 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub stars](https://img.shields.io/github/stars/isjakewong/awesome-discrete-diffusion-models?color=yellow)  ![GitHub forks](https://img.shields.io/github/forks/isjakewong/awesome-discrete-diffusion-models?color=green&label=Fork)

A curated list for awesome dicrete diffusion models resources.

## Contribution

This repo is maintained by [Yingheng Wang](https://isjakewong.github.io), [Yair Schiff](https://yair-schiff.github.io/), and [Subham Sahoo](https://s-sahoo.com/). Feel free to send [pull requests](https://github.com/isjakewong/awesome-discrete-diffusion-models/pulls) to add more links! While adding papers, please follow the following format: 
```
{paper_name}, {conference}-{year} [[link-to-the-abstract-page], [code-if-available]]
```
## Table of Contents

* [Introductory Posts](#introduction)
* [Papers](#papers)
  * [Surveys](#surveys)
  * [Discrete Diffusion with Gaussian Noise](#gaussian)
  * [Discrete Diffusion with Discrete Noise](#discrete)
  * [Guidance Mechanisms]("#guidance")
  * [Custom Noise Processes]("#custom")
  * [Theory](#theory)
  * [Applications](#applications)

## Introductory Posts  <a name="introduction"></a>
* A "simple and effective" tutorial on Masked Diffusion Language Models, 2024.
<p align="center">
  <a href="https://youtu.be/WjAUX23vgfg?si=bM1E-Bt-nwOmsVif" title="Click">
    <img src="https://github.com/user-attachments/assets/1f6b7ba2-b423-483a-9d11-bbbeb8a11860" alt="Everything Is AWESOME" style="width:50%;">
  </a>
</p>

* Diffusion Language Models, 2023 [[URL](https://benanne.github.io/2023/01/09/diffusion-language.html)]
* My notes on discrete denoising diffusion models (D3PMs), 2022 [[URL](https://beckham.nz/2022/07/11/d3pms.html)]

## Papers  <a name="papers"></a>

### Surveys   <a name="surveys"></a>

* Diffusion Models for Non-autoregressive Text Generation: A Survey, IJCAI 2023 Survey Track [[arXiv](https://arxiv.org/abs/2303.06574)]
* A Survey of Diffusion Models in Natural Language Processing, arXiv 2023 [[arXiv](https://arxiv.org/abs/2305.14671)]

### Discrete Diffusion with Gaussian Noise  <a name="gaussian"></a>

* Continuous diffusion for categorical data, arXiv 2022  [[arXiv](https://arxiv.org/abs/2211.15089)]
* SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control, ACL 2023  [[arXiv](https://openreview.net/forum?id=HJlWWJSFDH), [code](https://github.com/xhan77/ssd-lm)]
* Diffusion-LM Improves Controllable Text Generation, NeurIPS 2022  [[arXiv](https://arxiv.org/abs/2205.14217), [code](https://github.com/XiangLi1999/Diffusion-LM.git)]
* Self-conditioned Embedding Diffusion for Text Generation, NeurIPS 2022 [[arXiv](https://arxiv.org/abs/2211.04236)]
  
### Discrete Diffusion with Discrete Noise   <a name="discrete"></a>
* Simple and Effective Masked Diffusion Language Models, NeurIPS 2024 [[arXiv](https://arxiv.org/abs/2406.07524), [code](https://github.com/kuleshov-group/mdlm)]
* Simplified and Generalized Masked Diffusion for Discrete Data, NeurIPS 2024 [[arXiv](https://arxiv.org/abs/2406.04329)]
* Your Absorbing Discrete Diffusion Secretly Models the Conditional Distributions of Clean Data, arXiv 2024 [[arXiv](https://arxiv.org/abs/2406.03736), [code](https://github.com/ML-GSAI/RADD)]
* Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution, ICML 2024 [[arXiv](https://arxiv.org/abs/2310.16834), [code](https://github.com/louaaron/Score-Entropy-Discrete-Diffusion)]
* Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design, ICML 2024 [[arXiv](https://arxiv.org/abs/2402.04997)]
* DiffusER: Discrete Diffusion via Edit-based Reconstruction, ICLR 2023  [[arXiv](https://arxiv.org/abs/2210.16886), [code](https://github.com/machelreid/diffuser)]
* Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning, ICLR 2023  [[arXiv](https://arxiv.org/abs/2208.04202), [code](https://github.com/google-research/pix2seq)]
* DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models, ICLR 2023 [[arXiv](https://arxiv.org/abs/2210.08933), [code](https://github.com/Shark-NLP/DiffuSeq)]
* EdiT5: Semi-Autoregressive Text Editing with T5 Warm-Start, arXiv 2022  [[arXiv](https://arxiv.org/abs/2205.12209), [code](https://edit5.page.link/code)]
* A Continuous Time Framework for Discrete Denoising Models, EMNLP 2022 [[arXiv](https://arxiv.org/abs/2205.14987), [code](https://github.com/andrew-cr/tauLDR)]
* Autoregressive Diffusion Models, ICLR 2022  [[arXiv](https://arxiv.org/abs/2110.02037)]
* Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions, NeurIPS 2021  [[arXiv](https://arxiv.org/abs/2102.05379)]
* Structured Denoising Diffusion Models in Discrete State-Spaces, NeurIPS 2021  [[arXiv](https://arxiv.org/abs/2107.03006), [code](https://arxiv.org/pdf/2305.20009)]

### Guidance Mechanisms  <a name="guidance"></a>

* Unlocking Guidance for Discrete State-Space Diffusion and Flow Models, arXiv 2024 [[arXiv](https://arxiv.org/abs/2406.01572)]
* Protein Design with Guided Discrete Diffusion, NeurIPS 2023 [[arXiv](https://arxiv.org/abs/2305.20009), [code](https://github.com/ngruver/NOS)]

### Custom Noise Processes  <a name="custom"></a>

* DINOISER: Diffused Conditional Sequence Learning By Manipulating Noises, TACL 2024 [[arXiv](https://arxiv.org/abs/2302.10025), [code](https://github.com/yegcjs/DINOISER)]
* DiffusionBERT: Improving Generative Masked Language Models with Diffusion Models, ACL 2023 [[arXiv](), [code](https://github.com/Hzfinfdu/Diffusion-BERT)]

### Theory  <a name="theory"></a>

* Formulating Discrete Probability Flow Through Optimal Transport, NeurIPS 2023 [[arXiv](https://arxiv.org/abs/2311.03886)]
* Categorical SDEs with Simplex Diffusion, arXiv 2022  [[arXiv](https://arxiv.org/abs/2210.14784)]

### Applications  <a name="applications"></a>

* Diffusion Language Models Can Perform Many Tasks with Scaling and Instruction-Finetuning, arXiv 2023 [[arXiv](https://arxiv.org/abs/2308.12219), [code](https://github.com/yegcjs/DiffusionLLM)]

