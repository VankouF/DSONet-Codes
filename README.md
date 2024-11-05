# Textual Decomposition Then Sub-motion-space Scattering for Open-Vocabulary Motion Generation

[Ke Fan](https://vankouf.github.io/)$^{1}$, [Jiangning Zhang](https://zhangzjn.github.io/)$^{2}$, [Ran Yi](https://yiranran.github.io/)$^{1}$, [Jingyu Gong]()$^{1,4}$, [Yabiao Wang]()$^{2,3}$, [Yating Wang]()$^{1}$, [Xin Tan]()$^{4}$, [Chengjie Wang]()$^{1,2}$, [Lizhuang Ma]()$^{1,4}$

$^1$ Shanghai Jiao Tong University, $^2$ Tencent Youtu Lab, $^3$ Zhejiang University, $^4$ East China Normal University

<p align="center">
  <a href=''>
  <img src='https://img.shields.io/badge/Arxiv-2410.18977-A42C25?style=flat&logo=arXiv&logoColor=A42C25'>
  </a> 
  <a href=''>
  <img src='https://img.shields.io/badge/Paper-PDF-yellow?style=flat&logo=arXiv&logoColor=yellow'>
  </a> 
  <a href=''>
  <img src='https://img.shields.io/badge/Project-Page-%23df5b46?style=flat&logo=Google%20chrome&logoColor=%23df5b46'></a> 
  <a href='https://github.com/VankouF/DSONet-Codes/'>
  <img src='https://img.shields.io/badge/GitHub-Code-black?style=flat&logo=github&logoColor=white'></a> 
</p>

![Teaser]()

## Abstract
> Text-to-motion generation is a crucial task in computer vision, which generates the target 3D motion by the given text. The existing annotated datasets are limited in scale, resulting in most existing methods overfitting to the small datasets and unable to generalize to the motions of the open domain. Some methods attempt to solve the open-vocabulary motion generation problem by aligning to the CLIP space or using the Pretrain-then-Finetuning paradigm. However, the current annotated dataset's limited scale only allows them to achieve mapping from sub-text-space to sub-motion-space, instead of mapping between full-text-space and full-motion-space (full mapping), which is the key to attaining open-vocabulary motion generation. To this end, this paper proposes to leverage the atomic motion (simple body part motions over a short time period) as an intermediate representation, and leverage two orderly coupled steps, i.e., **Textual Decomposition** and **Sub-motion-space Scattering**, to address the full mapping problem. For Textual Decomposition, we design a fine-grained description conversion algorithm, and combine it with the generalization ability of a large language model to convert any given motion text into atomic texts. Sub-motion-space Scattering learns the compositional process from atomic motions to the target motions, to make the learned sub-motion-space scattered to form the full-motion-space. For a given motion of the open domain, it transforms the extrapolation into interpolation and thereby significantly improves generalization. Our network, ***DSO***-Net, combines textual **d**ecomposition and sub-motion-space **s**cattering to solve the **o**pen-vocabulary motion generation. Extensive experiments demonstrate that our DSO-Net achieves significant improvements over the state-of-the-art methods on open-vocabulary motion generation.

## 📢 News

+ **[2024-11-05] Code is comming soon.**

## 📜 Citation

If you find this work useful, please consider citing our paper:

```bash
@article{,
  title={Textual Decomposition Then Sub-motion-space Scattering for Open-Vocabulary Motion Generation},
  author={Ke Fan, Jiangning Zhang, Ran Yi, Jingyu Gong, Yabiao Wang, Yating Wang, Xin Tan, Chengjie Wang, Lizhuang Ma},
  year={2024},
  eprint={},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```
