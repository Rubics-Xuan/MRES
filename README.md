# Unveiling Parts Beyond Objects: Towards Finer-Granularity Referring Expression Segmentation
Wenxuan Wang, Tongtian Yue, Yisi Zhang, Longteng Guo, Xingjian He, Xinlong Wang, Jing Liu

The repository contains the official code and data of our paper "Unveiling Parts Beyond Objects: Towards Finer-Granularity Referring Expression Segmentation".

<a href='https://arxiv.org/abs/2312.01623'><img src='https://img.shields.io/badge/ArXiv-2312.01623-red'></a>   [Paper](https://arxiv.org/abs/2312.01623)


## 🌕 Abstract
Referring expression segmentation (RES) aims at segmenting the foreground masks of the entities that match the descriptive natural language expression. Previous datasets and methods for classic RES task heavily rely on the prior assumption that one expression must refer to object-level targets. In this paper, we take a step further to finer-grained part-level RES task. To promote the object-level RES task towards finer-grained vision-language understanding, we put forward a new multi-granularity referring expression segmentation (MRES) task and construct an evaluation benchmark called RefCOCOm by manual annotations. By employing our automatic model-assisted data engine, we build the largest visual grounding dataset namely MRES-32M, which comprises over 32.2M high-quality masks and captions on the provided 1M images. Besides, a simple yet strong model named UniRES is designed to accomplish the unified object-level and part-level grounding task. Extensive experiments on our RefCOCOm for MRES and three datasets (\ie, RefCOCO(+/g)) for classic RES task demonstrate the superiority of our method over previous state-of-the-art methods.
<p align="center">
 <img src="Figures/intro.png" width="100%">
</p>

---
## 🌖 Benchmark RefCOCOm
<p align="center">
 <img src="Figures/RefCOCOm.png" width="100%">
</p>
<p align="center">
 <img src="Figures/RefCOCOm_analysis.png" width="100%">
</p>

## 🌗 Data Generation Engine & Training Set MRES-32M
<p align="center">
 <img src="Figures/data_engine.png" width="100%">
</p>
<p align="center">
 <img src="Figures/MRES-32M.png" width="100%">
</p>
<p align="center">
 <img src="Figures/MRES-32M_analysis.png" width="100%">
</p>

## 🌘 Simple Baseline Model UniRES
<p align="center">
 <img src="Figures/UniRES.png" width="100%">
</p>

## 🌑 Results
<p align="center">
 <img src="Figures/classic_RES.png" width="100%">
</p>
<p align="center">
 <img src="Figures/MRES.png" width="100%">
</p>

