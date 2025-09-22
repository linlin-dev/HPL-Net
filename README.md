 <!-- The Full code of the paper "Bias-Aware Learning for Unbiased Scene Graph Generation in Remote Sensing Imagery" will be available soon. -->

<!-- [![License](https://img.shields.io/badge/license-apache%202.0-60C060.svg)](https://github.com/Zhuzi24/SGG-ToolKit?tab=Apache-2.0-1-ov-file)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Zhuzi24/SGG-ToolKit)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/Zhuzi24/SGG-ToolKit?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/Zhuzi24/SGG-ToolKit?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/Zhuzi24/SGG-ToolKit?style=social"> <img src="https://komarev.com/ghpvc/?username=SGG-ToolKit" /> -->

<h1 style="text-align: center;">Bias-Aware Learning for Unbiased Scene Graph Generation in Remote Sensing Imagery</h1>

The official implementation of the paper "Bias-Aware Learning for Unbiased Scene Graph Generation in Remote Sensing Imagery", which is the extended version of "ECCV2024-Fine-Grained-Scene-Graph-Generation-via-Sample-Level-Bias-Prediction".

<!-- ## 📢 Latest Updates
:fire::fire::fire: Last Updated on 2024-10-20 :fire::fire::fire:

📆 [**2024-10-20**] : We open-source the relationship prediction dataset and evaluation port of STAR, see "Download Links" in https://linlin-dev.github.io/project/STAR.html.

📆 [**2024-08-05**] : We open-source the object detection dataset and evaluation port of STAR, see "Download Links" in https://linlin-dev.github.io/project/STAR.html.

📆 [**2024-07-04**] : Update paper on arxiv, see [click here](https://arxiv.org/abs/2406.09410)

📆 [**2024-06-14**] : Our paper is available open on arxiv, [click here](https://arxiv.org/abs/2406.09410) to go to it!

📆 [**2024-06-13**] : Update project. -->

<!-- ## 🚀🚀🚀 Highlights

We construct STAR, the first large-scale dataset for scene graph generation in large-size VHR SAI. Containing  more than  `210,000` objects and over `400,000` triplets for SGG in large-size VHR SAI.

<p align="center">
<img src="demo/distr.jpg" alt="scatter" width="98%"/> 
</p>

[https://private-user-images.githubusercontent.com/29257168/339049597-2d027f2c-8911-45ba-b4dd-7f95111465a9.mp4](https://private-user-images.githubusercontent.com/29257168/345304070-0d1b8726-5a46-4182-95b9-bc70a050e49b.mp4)
 -->


<!-- ## 📌 Abstract
Scene graph generation (SGG) in satellite imagery (SAI) benefits promoting understanding of geospatial scenarios from perception to cognition. In SAI, objects exhibit great variations in scales and aspect ratios, and there exist rich relationships between objects (even between spatially disjoint objects), which makes it attractive to holistically conduct SGG in large-size very-high-resolution (VHR) SAI. However, there lack such SGG datasets. Due to the complexity of large-size SAI, mining triplets <subject, relationship, object> heavily relies on long-range contextual reasoning. Consequently, SGG models designed for small-size natural imagery are not directly applicable to large-size SAI. This paper constructs a large-scale dataset for SGG in large-size VHR SAI with image sizes ranging from <b>512 × 768</b> to <b>27,860 × 31,096</b> pixels, named <b>STAR</b> (<b>S</b>cene graph genera<b>T</b>ion in l<b>A</b>rge-size satellite image<b>R</b>y), encompassing over <b>210K</b> objects and over <b>400K</b> triplets. To realize SGG in large-size SAI, we propose a context-aware cascade cognition (CAC) framework to understand SAI regarding object detection (OBD), pair pruning and relationship prediction for SGG. We also release a SAI-oriented SGG toolkit with about <b>30</b> OBD and <b>10</b> SGG methods which need further adaptation by our devised modules on our challenging STAR dataset. **The STAR dataset will be made publicly available at [STAR](https://linlin-dev.github.io/project/STAR.html)**. -->

## 📝 Overview of BAL
<p align="center">
<img src="demo/BAL.png" alt="scatter" width="98%"/> 
</p>

## 🛠️ Installation
Check [INSTALL.md](INSTALL.md) for installation instructions.

<!-- ## 🔖 Dataset
Check [DATASET.md](DATASET.md) for instructions of dataset preprocessing. -->

<!-- ## ✏️ Metrics and Results
Explanation of metrics in our toolkit and reported results for OBD and SGG are given in [METRICS.md](METRICS.md).  -->

<!-- ## ✒️ Object Detection
If you are only involved in OBB/HBB object detection, you can refer to [STAR-MMRotate](https://github.com/yangxue0827/STAR-MMRotate) and [STAR-MMDetection](https://github.com/Zhuzi24/STAR-MMDetection). -->


## 🖊️ Citation

If you find this work helpful for your research, please consider giving this repo a star ⭐ and citing our papers:

```bibtex
# SGG in Remote Sensing Imagery
@ARTICLE{STAR,
    author={Li, Yansheng and Wang, Linlin and Wang, Tingzhu and Yang, Xue and Luo, Junwei and Wang, Qi and Deng, Youming and Wang, Wenbin and Sun, Xian and Li, Haifeng and Dang, Bo and Zhang, Yongjun and Yu, Yi and Yan, Junchi},
    journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
    title={STAR: A First-Ever Dataset and a Large-Scale Benchmark for Scene Graph Generation in Large-Size Satellite Imagery}, 
    year={2025},
    volume={47},
    number={3},
    pages={1832-1849},
    keywords={Stars;Annotations;Marine vehicles;Satellite images;Visualization;Object detection;Cognition;Benchmark testing;Complexity theory;Bridges;Large-size satellite imagery;object detection;relationship prediction;scene graph generation benchmark},
    doi={10.1109/TPAMI.2024.3508072}}

# SGG in Natural Imagery
@InProceedings{SBP,
    author="Li, Yansheng and Wang, Tingzhu and Wu, Kang and Wang, Linlin and Guo, Xin and Wang, Wenbin",
    editor="Leonardis, Ale{\v{s}} and Ricci, Elisa and Roth, Stefan and Russakovsky, Olga and Sattler, Torsten and Varol, G{\"u}l",
    title="Fine-Grained Scene Graph Generation via Sample-Level Bias Prediction",
    booktitle="Computer Vision -- ECCV 2024",
    year="2025",
    publisher="Springer Nature Switzerland",
    pages="18--35"}

# Remote Sensing Large Multi-Modal Models for SGG
@article{SkySenseGPT,
    title={SkySenseGPT: A Fine-Grained Instruction Tuning Dataset and Model for Remote Sensing Vision-Language Understanding},
    author={Luo, Junwei and Pang, Zhen and Zhang, Yongjun and Wang, Tingzhu and Wang, Linlin and Dang, Bo and Lao, Jiangwei and Wang, Jian and Chen, Jingdong and Tan, Yihua and Li, Yansheng},
    journal={arXiv preprint arXiv:2406.10100},
    year={2024}}

# Large-size Object Detection in Remote Sensing Imagery
@article{HBD,
    title={Learning to Holistically Detect Bridges From Large-Size VHR Remote Sensing Imagery},
    author={Li, Yansheng and Luo, Junwei and Zhang, Yongjun and Tan, Yihua and Yu, Jin-Gang and Bai, Song},
    journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
    volume={44},
    number={11},
    pages={7778--7796},
    year={2024},
    publisher={IEEE}}

# SGG in Natural Imagery
@inproceedings{HML,
    title={Hierarchical Memory Learning for Fine-grained Scene Graph Generation},
    author={Deng, Youming and Li, Yansheng and Zhang, Yongjun and Xiang, Xiang and Wang, Jian and Chen, Jingdong and Ma, Jiayi},
    booktitle={European Conference on Computer Vision},
    pages={266--283},
    year={2022},
    organization={Springer}}
```
## Acknowledgment
Our code is based on [SGG-ToolKit](https://github.com/Zhuzi24/SGG-ToolKit) in TPAMI2024-STAR, please see https://linlin-dev.github.io/project/STAR.html.

<!-- ## 📃 License

This project is released under the [Apache license](LICENSE). Parts of this project contain code and models from other sources, which are subject to their respective licenses. -->

# ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Zhuzi24/BAL&type=Date)](https://star-history.com/#Zuzhi/BAL&Date)
