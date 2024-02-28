# Unveiling Parts Beyond Objects: Towards Finer-Granularity Referring Expression Segmentation ——accepted by CVPR 2024

Wenxuan Wang, Tongtian Yue, Yisi Zhang, Longteng Guo, Xingjian He, Xinlong Wang, Jing Liu

<p align="center">
 <a href='https://rubics-xuan.github.io/MRES/'><img src='https://img.shields.io/badge/Project_Page-Green' alt='Paper PDF'></a> <a href='https://arxiv.org/abs/2312.08007'><img src='https://img.shields.io/badge/arXiv_Paper-red' alt='Project Page'></a> <a href=''><img src='https://badges.aleen42.com/src/youtube.svg'> </a>
</p>

## 🚩 **News**
Welcome to this official repository for the latest updates.

✅ **[2023.12.13]** : Release our paper on arXiv, project page and our newly built RefCOCOm benchmark data.

✅ **[2024.2.27]** : Our paper is officially accepted by CVPR 2024!

## 🌕 Abstract
Referring expression segmentation (RES) aims at segmenting the foreground masks of the entities that match the descriptive natural language expression. Previous datasets and methods for classic RES task heavily rely on the prior assumption that one expression must refer to object-level targets. In this paper, we take a step further to finer-grained part-level RES task. To promote the object-level RES task towards finer-grained vision-language understanding, we put forward a new multi-granularity referring expression segmentation (MRES) task and construct an evaluation benchmark called RefCOCOm by manual annotations. By employing our automatic model-assisted data engine, we build the largest visual grounding dataset namely MRES-32M, which comprises over 32.2M high-quality masks and captions on the provided 1M images. Besides, a simple yet strong model named UniRES is designed to accomplish the unified object-level and part-level grounding task. Extensive experiments on our RefCOCOm for MRES and three datasets (\ie, RefCOCO(+/g)) for classic RES task demonstrate the superiority of our method over previous state-of-the-art methods.
<p align="center">
 <img src="Figures/intro.png" width="100%">
</p>

---
## 🌖 Benchmark RefCOCOm
The newly bulit benchmark RefCOCOm can be found at [here](https://drive.google.com/file/d/1Qzt4cxyexe0xspsH_2oexylOKBI4Jim_/view?usp=drive_link). We follow the same specific data processing details as [CRIS](https://github.com/DerrickWang005/CRIS.pytorch), which can be found at [here](https://github.com/DerrickWang005/CRIS.pytorch/blob/master/tools/prepare_datasets.md).
<p align="center">
 <img src="Figures/RefCOCOm.png" width="80%">
</p>

## 🌗 Data Generation Engine & Training Set MRES-32M
<p align="center">
 <img src="Figures/data_engine.png" width="90%">
</p>
<p align="center">
 <img src="Figures/MRES-32M_information.png" width="70%">
</p>
<p align="center">
 <img src="Figures/MRES-32M.png" width="80%">
</p>

## 🌘 Simple Baseline Model UniRES
<p align="center">
 <img src="Figures/UniRES.png" width="90%">
</p>

## 🌑 Results
<p align="center">
 <img src="Figures/classic_RES.png" width="90%">
</p>
<p align="center">
 <img src="Figures/MRES.png" width="70%">
</p>

## 🚀 Citation
If you use our data or model in your work or find it is helpful, please cite the corresponding paper:

```
@article{wang2023unveiling,
  title={Unveiling Parts Beyond Objects: Towards Finer-Granularity Referring Expression Segmentation},
  author={Wang, Wenxuan and Yue, Tongtian and Zhang, Yisi and Guo, Longteng and He, Xingjian and Wang, Xinlong and Liu, Jing},
  journal={arXiv preprint arXiv:2312.08007},
  year={2023}
}
```

## 🏭 Acknowledgement
This work is built on many excellent research works and open-source projects, thanks a lot to all the authors for sharing!

1.[CRIS](https://github.com/DerrickWang005/CRIS.pytorch)

2.[LAVT](https://github.com/yz93/LAVT-RIS)

3.[X-Decoder](https://github.com/microsoft/X-Decoder)
