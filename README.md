# awesome-discrete-diffusion-models

 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub stars](https://img.shields.io/github/stars/isjakewong/awesome-discrete-diffusion-models?color=yellow)  ![GitHub forks](https://img.shields.io/github/forks/isjakewong/awesome-discrete-diffusion-models?color=green&label=Fork)

A curated list of awesome discrete diffusion models resources.

## Contribution

This repo is maintained by [Subham Sahoo](https://s-sahoo.com/), [Yingheng Wang](https://isjakewong.github.io), and [Yair Schiff](https://yair-schiff.github.io/). Feel free to send [pull requests](https://github.com/isjakewong/awesome-discrete-diffusion-models/pulls) to add more papers! Papers must be added in a chronological sequence, with the most recent accepted papers taking precedence over unaccepted papers. Please use the following format: 
```
{paper-name}, {conference} {year} [[link-to-the-abstract-page], [code-if-available]]
```

## Table of Contents

* [Introductory Materials](#introduction)
* Topic areas
  * [Discrete Diffusion with Discrete Noise](#discrete)
  * [Discrete Diffusion with Gaussian Noise](#gaussian)
  * [Samplers](#samplers)
  * [Guidance Mechanisms](#guidance)
  * [Custom Noise Processes](#custom)
  * [Theory](#theory)
  * [Applications](#applications)
  * [Surveys](#surveys)
  
## Introductory Materials  <a name="introduction"></a>
* Getting started with Diffusion Language Models, 2024.
<p align="center">
  <a href="https://youtu.be/WjAUX23vgfg?si=bM1E-Bt-nwOmsVif" title="Click">
    <img src="https://github.com/user-attachments/assets/1f6b7ba2-b423-483a-9d11-bbbeb8a11860" alt="Everything Is AWESOME" style="width:50%;">
  </a>
</p>

* Diffusion Language Models, 2023 [[URL](https://benanne.github.io/2023/01/09/diffusion-language.html)]
* My notes on discrete denoising diffusion models (D3PMs), 2022 [[URL](https://beckham.nz/2022/07/11/d3pms.html)]

## Papers  <a name="papers"></a>

### Discrete Diffusion with Discrete Noise   <a name="discrete"></a>
* Simple and Effective Masked Diffusion Language Models, NeurIPS 2024 [[arXiv](https://arxiv.org/abs/2406.07524), [code](https://github.com/kuleshov-group/mdlm)]
* Simplified and Generalized Masked Diffusion for Discrete Data, NeurIPS 2024 [[arXiv](https://arxiv.org/abs/2406.04329)]
* Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution, ICML 2024 [[arXiv](https://arxiv.org/abs/2310.16834), [code](https://github.com/louaaron/Score-Entropy-Discrete-Diffusion)]
* Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design, ICML 2024 [[arXiv](https://arxiv.org/abs/2402.04997)]
* Think While You Generate: Discrete Diffusion with Planned Denoising, arXiv 2024 [[arXiv](https://arxiv.org/pdf/2410.06264), [code](https://github.com/liusulin/DDPD)]
* Your Absorbing Discrete Diffusion Secretly Models the Conditional Distributions of Clean Data, arXiv 2024 [[arXiv](https://arxiv.org/abs/2406.03736), [code](https://github.com/ML-GSAI/RADD)]
* DiffusER: Discrete Diffusion via Edit-based Reconstruction, ICLR 2023  [[arXiv](https://arxiv.org/abs/2210.16886), [code](https://github.com/machelreid/diffuser)]
* Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning, ICLR 2023  [[arXiv](https://arxiv.org/abs/2208.04202), [code](https://github.com/google-research/pix2seq)]
* DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models, ICLR 2023 [[arXiv](https://arxiv.org/abs/2210.08933), [code](https://github.com/Shark-NLP/DiffuSeq)]
* FiLM: Fill-in Language Models for Any-Order Generation, arXiv 2023 [[arXiv](https://arxiv.org/abs/2310.09930), [code](https://github.com/shentianxiao/FiLM)]
* A Continuous Time Framework for Discrete Denoising Models, NeurIPS 2022 [[arXiv](https://arxiv.org/abs/2205.14987), [code](https://github.com/andrew-cr/tauLDR)]
* Autoregressive Diffusion Models, ICLR 2022  [[arXiv](https://arxiv.org/abs/2110.02037)]
* EdiT5: Semi-Autoregressive Text Editing with T5 Warm-Start, arXiv 2022  [[arXiv](https://arxiv.org/abs/2205.12209), [code](https://edit5.page.link/code)]
* Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions, NeurIPS 2021  [[arXiv](https://arxiv.org/abs/2102.05379), [code](https://github.com/didriknielsen/argmax_flows)]
* Structured Denoising Diffusion Models in Discrete State-Spaces, NeurIPS 2021  [[arXiv](https://arxiv.org/abs/2107.03006), [code](https://github.com/google-research/google-research/tree/master/d3pm)]

### Discrete Diffusion with Gaussian Noise  <a name="gaussian"></a>

* SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control, ACL 2023  [[arXiv](https://arxiv.org/abs/2210.17432), [code](https://github.com/xhan77/ssd-lm)]
* Diffusion-LM Improves Controllable Text Generation, NeurIPS 2022  [[arXiv](https://arxiv.org/abs/2205.14217), [code](https://github.com/XiangLi1999/Diffusion-LM.git)]
* Self-conditioned Embedding Diffusion for Text Generation, NeurIPS 2022 [[arXiv](https://arxiv.org/abs/2211.04236)]
* Continuous Diffusion for Categorical Data, arXiv 2022  [[arXiv](https://arxiv.org/abs/2211.15089)]
  
### Samplers  <a name="samplers"></a>
* Beyond Autoregression: Fast LLMs via Self-Distillation Through Time, arXiv 2024 [[arXiv](https://arxiv.org/abs/2410.21035)]
* Masked Diffusion Models are Secretly Time-Agnostic Masked Models and Exploit Inaccurate Categorical Sampling, arXiv 2024 [[arXiv](https://arxiv.org/abs/2409.02908)]
* Jump Your Steps: Optimizing Sampling Schedule of Discrete Diffusion Models, arXiv 2024 [[arXiv](https://arxiv.org/abs/2410.07761)]

### Guidance Mechanisms  <a name="guidance"></a>
* Steering Masked Discrete Diffusion Models via Discrete Denoising Posterior Prediction, arXiv 2024 [[arXiv](https://arxiv.org/abs/2410.08134)]
* Unlocking Guidance for Discrete State-Space Diffusion and Flow Models, arXiv 2024 [[arXiv](https://arxiv.org/abs/2406.01572)]
* Protein Design with Guided Discrete Diffusion, NeurIPS 2023 [[arXiv](https://arxiv.org/abs/2305.20009), [code](https://github.com/ngruver/NOS)]

### Custom Noise Processes  <a name="custom"></a>

* DINOISER: Diffused Conditional Sequence Learning By Manipulating Noises, TACL 2024 [[arXiv](https://arxiv.org/abs/2302.10025), [code](https://github.com/yegcjs/DINOISER)]
* DiffusionBERT: Improving Generative Masked Language Models with Diffusion Models, ACL 2023 [[arXiv](https://arxiv.org/abs/2211.15029), [code](https://github.com/Hzfinfdu/Diffusion-BERT)]

### Theory  <a name="theory"></a>
* Discrete Copula Diffusion, arXiv 2024 [[arXiv](https://arxiv.org/abs/2410.01949)]
* Formulating Discrete Probability Flow Through Optimal Transport, NeurIPS 2023 [[arXiv](https://arxiv.org/abs/2311.03886), [code](https://github.com/PangzeCheung/Discrete-Probability-Flow)]
* Categorical SDEs with Simplex Diffusion, arXiv 2022  [[arXiv](https://arxiv.org/abs/2210.14784)]

### Applications  <a name="applications"></a>
* Diffusion Language Models Are Versatile Protein Learners, ICML 2024 [[arXiv](https://arxiv.org/abs/2402.18567)], [code](https://github.com/bytedance/dplm)]
* Fine-Tuning Discrete Diffusion Models via Reward Optimization with Applications to DNA and Protein Design, arXiv 2024 [[arXiv](https://arxiv.org/pdf/2410.13643), [code](https://github.com/ChenyuWang-Monica/DRAKES)]
* Scaling Diffusion Language Models via Adaptation from Autoregressive Models, arXiv 2024 [[arXiv](https://arxiv.org/abs/2410.17891)]
* Scaling up Masked Diffusion Models on Text, arXiv 2024 [[arXiv](https://arxiv.org/abs/2410.18514)]
* Likelihood-Based Diffusion Language Models, NeurIPS 2023 [[arXiv](https://arxiv.org/abs/2305.18619), [code](https://github.com/igul222/plaid)]
* Diffusion Language Models Can Perform Many Tasks with Scaling and Instruction-Finetuning, arXiv 2023 [[arXiv](https://arxiv.org/abs/2308.12219), [code](https://github.com/yegcjs/DiffusionLLM)]

### Surveys   <a name="surveys"></a>

* Diffusion Models for Non-autoregressive Text Generation: A Survey, IJCAI 2023 Survey Track [[arXiv](https://arxiv.org/abs/2303.06574)]
* A Survey of Diffusion Models in Natural Language Processing, arXiv 2023 [[arXiv](https://arxiv.org/abs/2305.14671)]
