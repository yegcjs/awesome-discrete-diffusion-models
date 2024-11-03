# awesome-discrete-diffusion-models

 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub stars](https://img.shields.io/github/stars/isjakewong/awesome-discrete-diffusion-models?color=yellow)  ![GitHub forks](https://img.shields.io/github/forks/isjakewong/awesome-discrete-diffusion-models?color=green&label=Fork)

A curated list for awesome dicrete diffusion models resources.

## Contribution

This repo is maintained by [Yingheng Wang](https://isjakewong.github.io), [Yair Schiff](https://yair-schiff.github.io/), and [Subham Sahoo](https://s-sahoo.com/). Feel free to send [pull requests](https://github.com/isjakewong/awesome-discrete-diffusion-models/pulls) to add more links! While adding papers, please include the link to the abstract page instead of the PDF.

## Table of Contents

* [Introduction](#introduction)
* [Papers](#papers)
  * [Surveys](#surveys)
  * [Papers](#papers)

## Introductory Posts
* A "simple and effective" tutorial on Masked Diffusion Language Models.
<p align="center">
  <a href="https://youtu.be/WjAUX23vgfg?si=bM1E-Bt-nwOmsVif" title="Click">
    <img src="https://github.com/user-attachments/assets/1f6b7ba2-b423-483a-9d11-bbbeb8a11860" alt="Everything Is AWESOME" style="width:50%;">
  </a>
</p>

* Diffusion Language Models  [[URL](https://benanne.github.io/2023/01/09/diffusion-language.html)]
* My notes on discrete denoising diffusion models (D3PMs)[[URL](https://beckham.nz/2022/07/11/d3pms.html)]

## Papers

### Surveys

* Diffusion Models for Non-autoregressive Text Generation: A Survey [[arXiv](https://arxiv.org/abs/2303.06574)]
* A Survey of Diffusion Models in Natural Language Processing [[arXiv](https://arxiv.org/abs/2305.14671)]

### Discrete Diffusion with Gaussian Noise

* Continuous diffusion for categorical data, arXiv 2022  [[arXiv](https://dl.acm.org/doi/10.1145/3394486.3403237)]
* SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control, arXiv 2022  [[arXiv](https://openreview.net/forum?id=HJlWWJSFDH), [Code](https://github.com/xhan77/ssd-lm)]
* Diffusion-LM Improves Controllable Text Generation, NeurIPS 2022  [[arXiv](https://arxiv.org/abs/2205.14217), [Code](https://github.com/XiangLi1999/Diffusion-LM.git)]
* Self-conditioned Embedding Diffusion for Text Generation, NeurIPS 2022 [[arXiv](https://arxiv.org/abs/2211.04236)]
  
### Discrete Diffusion with Discrete Noise
* Simple and Effective Masked Diffusion Language Models [[arXiv](https://arxiv.org/abs/2406.07524), [Code](https://github.com/kuleshov-group/mdlm)]
* Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution [[arXiv](https://arxiv.org/abs/2310.16834), [Code](https://github.com/louaaron/Score-Entropy-Discrete-Diffusion)]
* DiffusER: Discrete Diffusion via Edit-based Reconstruction, ICLR 2023  [[arXiv](https://arxiv.org/abs/2210.16886), [Code](https://github.com/machelreid/diffuser)]
* Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning, ICLR 2023  [[arXiv](https://arxiv.org/abs/2208.04202), [Code](https://github.com/google-research/pix2seq)]
* EdiT5: Semi-Autoregressive Text Editing with T5 Warm-Start, arXiv 2022  [[arXiv](https://arxiv.org/abs/2205.12209), [Code](https://edit5.page.link/code)]
* Autoregressive Diffusion Models, ICLR 2022  [[arXiv](https://arxiv.org/abs/2110.02037)]
* Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions, NeurIPS 2021  [[arXiv](https://arxiv.org/abs/2102.05379)]
* Structured Denoising Diffusion Models in Discrete State-Spaces, NeurIPS 2021  [[arXiv](https://arxiv.org/abs/2107.03006)]

### Guidance Mechanisms

* Unlocking Guidance for Discrete State-Space Diffusion and Flow Models [[arXiv](https://arxiv.org/abs/2406.01572)]

### Custom Noise Processes

* DINOISER: Diffused Conditional Sequence Learning By Manipulating Noises, TACL [[arXiv](https://arxiv.org/abs/2302.10025), [Code](https://github.com/yegcjs/DINOISER)]


### Theory

* Categorical SDEs with Simplex Diffusion, arXiv 2022  [[arXiv](https://arxiv.org/abs/2210.14784)]
* Formulating Discrete Probability Flow Through Optimal Transport [[arXiv](https://arxiv.org/abs/2311.03886)]

### Applications

* Diffusion Language Models Can Perform Many Tasks with Scaling and Instruction-Finetuning, arXiv 2023 [[arXiv](https://arxiv.org/abs/2308.12219), [Code](https://github.com/yegcjs/DiffusionLLM)]

