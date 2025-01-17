<p align="center">
    <img src="./imgs/COD-Logo.png"/> <br />
</p>

# <p align=center>`Awesome List for Camouflaged Object Detection (COD)`

![Badge](https://img.shields.io/badge/-As%20awesome%20as%20you%20think!-red)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/GewelsJI/SINet-V2)
![GitHub issues](https://img.shields.io/github/issues/GewelsJI/SINet-V2)
![GitHub stars](https://img.shields.io/github/stars/GewelsJI/SINet-V2)

This awesome list is under construction. If you have anything to recommend or any suggestions, please feel free to contact us via e-mail (gepengai.ji@gmail.com) or directly push a PR. 

< **Last updated: March/07/2024** >

Please refer to our recent survey paper for more details: Advances in Deep Concealed Scene Understanding, Visual Intelligence (VI), 2023. <br>
Link: https://link.springer.com/article/10.1007/s44267-023-00019-6

##  1. Content

- [`Awesome List for Camouflaged Object Detection (COD)`](#awesome-list-for-camouflaged-object-detection-cod)
  - [1. Content](#1-content)
  - [2. Paper List](#2-paper-list)
    - [2.1. Datasets \& Benchmarks](#21-datasets--benchmarks)
      - [2.1.1. Video-level COD](#211-video-level-cod)
      - [2.1.2. Image-level COD](#212-image-level-cod)
    - [2.2. Camouflaged/Concealed Object Detection (COD)](#22-camouflagedconcealed-object-detection-cod)
      - [2.2.1. YEAR 2024](#221-year-2024)
      - [2.2.2. YEAR 2023](#222-year-2023)
      - [2.2.3. YEAR 2022](#223-year-2022)
      - [2.2.4. YEAR 2021](#224-year-2021)
      - [2.2.5. Before YEAR 2020](#225-before-year-2020)
    - [2.3. Camouflaged/Concealed Instance Segmentation (CIS)](#23-camouflagedconcealed-instance-segmentation-cis)
    - [2.4. Camouflaged/Concealed Object Counting (COC)](#24-camouflagedconcealed-object-counting-coc)
    - [2.5. Video Camouflaged/Concealed Object Detection (VCOD)](#25-video-camouflagedconcealed-object-detection-vcod)
    - [2.6. Referring COD](#26-referring-cod)

##  2. Paper List

###  2.1. Datasets & Benchmarks

####  2.1.1. Video-level COD

| **Dataset Name** | **Year** | **Publication** | **Links** |
| :------: | :------: | :-------: | :---------|
[MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 | CVPR | [Paper](https://arxiv.org/abs/2203.07363) |
[MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/) | 2020 | ACCV | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.html) |


####  2.1.2. Image-level COD

| **Dataset Name** | **Year** | **Publication** | **Links** |
| :------: | :------: | :-------: | :---------|
[CDS2K]() | 2023 | VI | [Paper](https://arxiv.org/abs/2304.11234)/[Intro](https://github.com/DengPingFan/CSU?tab=readme-ov-file#defect-segmentation-dataset----cds2k)/[Download](https://drive.google.com/file/d/1OGPR34qCNWHVYwyf9OY6IH-7WHzPkC7-/view)
[PlantCamo](https://github.com/yjybuaa/PlantCamo) | 2023 | - | -
[IOCfish5K](https://github.com/GuoleiSun/Indiscernible-Object-Counting) |2023 | CVPR | [Paper](https://arxiv.org/abs/2304.11677)/[Website](https://github.com/GuoleiSun/Indiscernible-Object-Counting)/[Download](https://drive.google.com/file/d/1ETY_AdJB9azzja6L9URN58KtL4OH98SL/view)
[NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf) |
[COD10K](http://dpfan.net/camouflage/) | 2020 | CVPR | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf) |
<!-- [CAMO](https://sites.google.com/view/ltnghia/research/camo) | 2019 | CVIU | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) |
[CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2019 | SPL | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8336933&casa_token=h25eiro16rcAAAAA:qeSoquItkaBK8QKGFvbiX2DJA0MycSjJ-5nK-2y0QSGxQY97b8b6BsLmoo8QJCQVD3HYPstW&tag=1) | 
[CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 | Online | [Website](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | -->


###  2.2. Camouflaged/Concealed Object Detection (COD)

#### 2.2.1. YEAR 2024

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2024 |  CVPR  | LAKE-RED: Camouflaged Images Generation by Latent Background Knowledge Retrieval-Augmented Diffusion   <br> <sup><sub>*Pancheng Zhao, Peng Xu, Pengda Qin, Deng-Ping Fan, Zhicheng Zhang, Guoli Jia, Bowen Zhou, Jufeng Yang*</sub></sup>  | [Paper](https://arxiv.org/abs/2404.00292)/[Code](https://github.com/PanchengZhao/LAKE-RED)
| 2024 |  CVPR  | VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning   <br> <sup><sub>*Ziyang Luo, Nian Liu, Wangbo Zhao, Xuguang Yang, Dingwen Zhang, Deng-Ping Fan, Fahad Khan, Junwei Han*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.15011)/[Code](https://github.com/Sssssuperior/VSCode)
| 2024 |  ICLR  | Strategic Preys Make Acute Predators: Enhancing Camouflaged Object Detectors by Generating Camouflaged Objects   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Yulun Zhang, Zhenhua Guo, Xiu Li, Martin Danelljan, Fisher Yu*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.03166)/[Code](https://github.com/ChunmingHe/Camouflageator)
| 2024 |  WACV  | CamoFocus: Enhancing Camouflage Object Detection With Split-Feature Focal Modulation and Context Refinement   <br> <sup><sub>*Abbas Khan, Mustaqeem Khan, Wail Gueaieb, Abdulmotaleb El Saddik, Giulia De Masi, Fakhri Karray*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Khan_CamoFocus_Enhancing_Camouflage_Object_Detection_With_Split-Feature_Focal_Modulation_and_WACV_2024_paper.html)/Code
| 2024 | AAAI | CamoDiffusion: Camouflaged Object Detection via Conditional Diffusion Models   <br> <sup><sub>*Zhongxi Chen, Ke Sun, Xianming Lin*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27890)/[Code](https://github.com/Rapisurazurite/CamoDiffusion)
| 2024 |  AAAI  | Relax Image-Specific Prompt Requirement in SAM: A Single Generic Prompt for Segmenting Camouflaged Objects   <br> <sup><sub>*Jian Hu, Jiayi Lin, Weitong Cai, Shaogang Gong*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.07374)/[Proj](https://lwpyh.github.io/GenSAM/)/<br>[Code](https://github.com/jyLin8100/GenSAM)
| 2024 | Neucom | A systematic review of image-level camouflaged object detection with deep learning  <br> <sup><sub>*Yanhua Liang, Guihe Qin, Minghui Sun, Xinchao Wang, Jie Yan, Zhonghan Zhang*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223011736)/Code


####  2.2.2. YEAR 2023

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2023 | SCIS | SAM Struggles in Concealed Scenes--Empirical Study on "Segment Anything" <br> <sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Peng Xu, Bowen Zhou, Ming-Ming Cheng & Luc Van Gool*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s11432-023-3881-x)
| 2023 | CVPR Workshop | Segment anything is not always perfect: An investigation of sam on different real-world applications <br> <sup><sub>*Wei Ji, Jingjing Li, Qi Bi, Tingwei Liu, Wenbo Li, Li Cheng*</sub></sup> | [Paper](https://arxiv.org/abs/2304.05750v3)/[Github](https://github.com/LiuTingWed/SAM-Not-Perfect)
| 2023 | ICCV Workshop | SAM Fails to Segment Anything? – SAM-Adapter: Adapting SAM in Underperformed Scenes: Camouflage, Shadow, Medical Image Segmentation, and More <br> <sup><sub>*Tianrun Chen, Lanyun Zhu, Chaotao Deng, Runlong Cao, Yan Wang, Shangzhan Zhang, Zejian Li, Lingyun Sun, Ying Zang, Papa Mao*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ICCV2023W/VCL/html/Chen_SAM-Adapter_Adapting_Segment_Anything_in_Underperformed_Scenes_ICCVW_2023_paper.html)/[Website](https://tianrun-chen.github.io/SAM-Adaptor/)
| 2023  | arXiv | Open-Vocabulary Camouflaged Object Segmentation   <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Jiaming Zuo, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.11241)/Code
| 2023  | NeurIPS | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.11003)/[Code](https://github.com/ChunmingHe/WS-SAM)
| 2023  | ACM MM | Frequency Perception Network for Camouflaged Object Detection  <br> <sup><sub>*Runmin Cong, Mengyao Sun, Sanyi Zhang, Xiaofei Zhou, Wei Zhang, Yao Zhao*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.08924)/[Code](https://github.com/rmcong/FPNet_ACMMM23)
| 2023  | ACM MM | Frequency Representation Integration for Camouflaged Object Detection  <br> <sup><sub>*Chenxi Xie, Changqun Xia, Tianshu Yu, Jia Li*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611773)/Code
| 2023  | ACM MM | Depth-aided Camouflaged Object Detection  <br> <sup><sub>*Qingwei Wang, Jinyu Yang, Xiaosheng Yu, Fangyi Wang, Peng Chen, Feng Zheng*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611874)/[Code](https://github.com/qingwei-wang/DaCOD) 
| 2023  | ACM MM | Object Segmentation by Mining Cross-Modal Semantics <br> <sup><sub>*Zongwei Wu, Jingjing Wang, Zhuyun Zhou, Zhaochong An, Qiuping Jiang, Cédric Demonceaux, Guolei Sun, Radu Timofte*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.10469)/[Code](https://github.com/Zongwei97/XMSNet)
| 2023 | IJCAI | Locate, Refine and Restore: A Progressive Enhancement Network for Camouflaged Object Detection <br> <sup><sub>*Xiaofei Li; Jiaxin Yang; Shuohao Li; Jun Lei; Jun Zhang; Dong Chen*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2023/0124.pdf)
| 2023 | arXiv | Strategic Preys Make Acute Predators: Enhancing Camouflaged Object Detectors by Generating Camouflaged Objects <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Yulun Zhang, Zhenhua Guo, Xiu Li, Martin Danelljan, Fisher Yu*</sub></sup> | [Paper](https://arxiv.org/abs/2308.03166)/Code
| 2023 | SCIS | Distraction-aware camouflaged object segmentation <br> <sup><sub>*Haiyang Mei, Xin Yang, Yunduo Zhou, Ge-Peng Ji, Xiaopeng Wei, and Deng-Ping Fan*</sub></sup> | [Paper](https://mhaiyang.github.io/SSI2023-PFNet-Plus/index.html)/[Code](https://github.com/Mhaiyang/PFNet_Plus)
| 2023 | CVPR | Feature Shrinkage Pyramid for Camouflaged Object Detection with Transformers <br> <sup><sub>*Zhou Huang, Hang Dai, Tian-Zhu Xiang, Shuo Wang, Huai-Xin Chen, Jie Qin, and Huan Xiong*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Feature_Shrinkage_Pyramid_for_Camouflaged_Object_Detection_With_Transformers_CVPR_2023_paper.pdf)/[Code](https://github.com/ZhouHuang23/FSPNet)
| 2023  | CVPR | Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/He_Camouflaged_Object_Detection_With_Feature_Decomposition_and_Edge_Reconstruction_CVPR_2023_paper.pdf)/[Code](https://github.com/ChunmingHe/FEDER)
| 2023 | Electronics | [FLCNet] Camouflaged Object Detection with a Feature Lateral Connection Network <br> <sup><sub>*Tao Wang, Jian Wang, and Ruihao Wang*</sub></sup> | [Paper](https://www.mdpi.com/2079-9292/12/12/2570)/[Code](https://github.com/Tao-Wang-CV/FLCNet)
| 2023 | arXiv | Camoformer: Masked separable attention for camouflaged object detection <br><sup><sub>*Bowen Yin, Xuying Zhang, Qibin Hou, Bo-Yuan Sun, Deng-Ping Fan, and Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2212.06570)/[Code](https://github.com/HVision-NKU/CamoFormer)
| 2023 | arXiv | Source-free depth for object pop-out <br><sup><sub>*Zongwei Wu, Danda Pani Paudel, Deng-Ping Fan, Jingjing Wang, Shuo Wang, Cédric Demonceaux, Radu Timofte, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/pdf/2212.05370.pdf)/[Code](https://github.com/Zongwei97/PopNet)
| 2023 | WACV | MFFN: Multi-view Feature Fusion Network for Camouflaged Object Detection <br><sup><sub>*Dehua Zheng, Xiaochen Zheng, Laurence T. Yang, Yuan Gao, Chenlu Zhu, Yiheng Ruan*</sub></sup> | [Paper](https://arxiv.org/abs/2210.06361)/[Code](https://github.com/dwardzheng/MFFN_COD)
| 2023  | AAAI | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations <br><sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup> | [Paper](https://arxiv.org/abs/2207.14083)
|   2023   |  AAAI   | High-resolution Iterative Feedback Network for Camouflaged Object Detection <br> <sup><sub>*Xiaobin Hu, Shuo Wang, Xuebin Qin, Hang Dai, Wenqi Ren, Donghao Luo, Ying Tai, Ling Shao*</sub></sup> | [Paper](https://arxiv.org/abs/2203.11624)/[Code](https://github.com/HUuxiaobin/HitNet) 
| 2023  | MIR   | **Deep Gradient Learning for Efficient Camouflaged Object Detection** (`DGNet model`) <br><sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Yu-Cheng Chou, Dengxin Dai, Alexander Liniger, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2205.12853v2)/[Code](https://github.com/GewelsJI/DGNet)

####  2.2.3. YEAR 2022

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2022   |   TPAMI   | **Concealed Object Detection** (`SINetV2 model & COD10K dataset`)                       <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Ming-Ming Cheng, Ling Shao*</sub></sup>                             | [Paper](https://arxiv.org/abs/2102.10274)/[Code](https://github.com/GewelsJI/SINet-V2)  
| 2022 | arXiv | Global-Local Aggregation with Deformable Point Sampling for Camouflaged Object Detection <br><sup><sub>*Lee, Minhyeok, Suhwan Cho, Chaewon Park, Dogyoon Lee, Jungho Lee, and Sangyoun Lee*</sub></sup> | [Paper](https://arxiv.org/pdf/2211.12048.pdf)/Code
| 2022 | TIP | Feature Aggregation and Propagation Network for Camouflaged Object Detection <br><sup><sub>*Tao Zhou, Yi Zhou, Chen Gong, Jian Yang, Yu Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9940173/authors#authors)/[Code](https://github.com/taozh2017/FAPNet)
| 2022	| CICAI | AGFNet: Attention Guided Fusion Network for Camouflaged Object Detection <br><sup><sub>*Zeyu Zhao, Zhihao Liu & Chenglei Peng*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-20497-5_39)/Code 
|   2022   |  arXiv   | **Boundary-Aware Segmentation Network for Mobile and Web Applications** (`BAS model`) <br> <sup><sub>*Xuebin Qin, Deng-Ping Fan, Chenyang Huang, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.04704.pdf)/[Code](https://github.com/xuebinqin/BASNet) 
| 2022     | arXiv | Towards Deeper Understanding of Camouflaged Object Detection (`LSR extension`) <br> <sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2205.11333)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)
|   2022   |   ACM MM     | PreyNet: Preying on camouflaged objects <br> <sup><sub>*M Zhang, S Xu, Yongri Piao, D Shi, S Lin, H Lu*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548178)/[Code](https://github.com/sxu1997/PreyNet)
|   2022   |  IJCAI   | Boundary-Guided Camouflaged Object Detection <br> <sup><sub>*Yujia Sun, Shuo Wang, Chenglizhao Chen, Tian-Zhu Xiang*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2022/186)/[Code](https://github.com/thograce/BGNet)
|   2022   |   CVPR   | Segment, Magnify and Reiterate: Detecting Camouflaged Objects the Hard Way <br> <sup><sub>*Qi Jia, S. Yao, Yu Liu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jia_Segment_Magnify_and_Reiterate_Detecting_Camouflaged_Objects_the_Hard_Way_CVPR_2022_paper.pdf)/[Code](https://github.com/dlut-dimt/SegMaR) 
|   2022   |   CVPR   | Detecting Camouflaged Object in Frequency Domain <br> <sup><sub>*Yijie Zhong, Bo Li, Lv Tang, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Detecting_Camouflaged_Object_in_Frequency_Domain_CVPR_2022_paper.pdf)/Code
|   2022   |   CVPR   | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://arxiv.org/abs/2203.02688)/[Code](https://github.com/lartpang/ZoomNet) |
|   2022   |  AAAI    | I can find you! Boundary-guided Separated Attention Network for Camouflaged Object Detection <br><sup><sub>*Hongwei Zhu, Peng Li, Haoran Xie, Mingqiang Wei, et al.*</sub></sup> | [Paper](https://www.aaai.org/AAAI22Papers/AAAI-6565.ZhuH.pdf)/[Code](https://github.com/WolfberryCoke/BSA-Net) | 
|   2022   |  WACV    | Modeling Aleatoric Uncertainty for Camouflaged Object Detection <br> <sup><sub>*Jiawei Liu, Jing Zhang, Nick Barnes*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Liu_Modeling_Aleatoric_Uncertainty_for_Camouflaged_Object_Detection_WACV_2022_paper.pdf)/[Code](https://github.com/Carlisle-Liu/OCENet)
|   2022   | TCSVT | Camouflaged Object Detection via Context-aware Cross-level Fusion (`C2FNet Extension`)  <br> <sup><sub>*Geng Chen, Si-Jie Liu, Yu-Jia Sun, Ge-Peng Ji, Ya-Feng Wu, Tao Zhou*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.13362)/[Code](https://github.com/Ben57882/C2FNet-TSCVT)
|   2022   |  TMM  | Deep Texton-Coherence Network for Camouflaged Object Detection <br> <sup><sub>*Wei Zhai, Yang Cao, HaiYong Xie, Zheng-Jun Zha*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9815160)/Code
|   2022   |  KBS     | Boundary-guided network for camouflage object detection <br> <sup><sub>*Tianyou Chen, Jin Xiao, Xiaoguang Hu, Guofeng Zhang, Shaojie Wang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122004294)/[Code](https://github.com/clelouch/BgNet)
|   2022   |  PR      | CubeNet: X-shape connection for camouflaged object detection <br> <sup><sub>*Mingchen Zhuge, Xiankai Lu, Yiyou Guo, Zhihua Cai, Shuhan Chen*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S003132032200125X?dgcid=raven_sd_recommender_email)/[Code](https://github.com/mczhuge/CubeNet)
|   2022   |  PR      | Fast Camouflaged Object Detection via Edge-based Reversible Re-calibration Network <br><sup><sub>*Ge-Peng Ji, Lei Zhu, Mingchen Zhuge, Keren Fu*</sub></sup> | [Paper](https://arxiv.org/abs/2111.03216)/[Code](https://github.com/GewelsJI/ERRNet) 
|   2022   |  TOMM | Frequency-aware Camouflaged Object Detection <br> <sup><sub>*Jiaying Lin, Xin Tan, Ke Xu, Lizhuang Ma, Rynson W.H. Lau*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3545609)/Code 


####  2.2.4. YEAR 2021

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2021   |   ICCV   | Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection <br><sup><sub>*Fan Yang, Qiang Zhai, Xin Li, Rui Huang, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Uncertainty-Guided_Transformer_Reasoning_for_Camouflaged_Object_Detection_ICCV_2021_paper.pdf)/[Code](https://github.com/fanyang587/UGTR)                                                   |
|   2021   |   CVPR   | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection <br><sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Bowen Liu, Tong Zhang, Yuchao Dai*</sub></sup>                     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Uncertainty-Aware_Joint_Salient_Object_and_Camouflaged_Object_Detection_CVPR_2021_paper.html)/[Code](https://github.com/JingZhang617/Joint_COD_SOD) |
|   2021   |   CVPR   | Simultaneously Localize, Segment and Rank the Camouflaged Objects (`NC4K`)  <br><sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)                                                   |
|   2021   |   CVPR   | Mutual Graph Learning for Camouflaged Object Detection       <br><sup><sub>*Qiang Zhai, Xin Li, Fan Yang, Chenglizhao Chen, Hong Cheng, Deng-Ping Fan*</sub></sup>                                   | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Mutual_Graph_Learning_for_Camouflaged_Object_Detection_CVPR_2021_paper.pdf)/[Code](https://github.com/fanyang587/MGL)                                                   |
|   2021   |   CVPR   | Camouflaged Object Segmentation with Distraction Mining      <br><sup><sub>*Haiyang Mei, Ge-Peng Ji, Ziqi Wei, Xin Yang, Xiaopeng Wei, Deng-Ping Fan*</sub></sup>                               | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Camouflaged_Object_Segmentation_With_Distraction_Mining_CVPR_2021_paper.pdf)/[Code](https://mhaiyang.github.io/CVPR2021_PFNet/index)                                                   |
|   2021   |  IJCAI   | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup>                                  | [Paper](https://arxiv.org/abs/2105.12555)/[Code](https://github.com/thograce/C2FNet) |
|   2021   |   AAAI   | Inferring Camouflaged Objects by Texture-Aware Interactive Guidance Network <br><sup><sub>*Jinchao Zhu, Xiaoyu Zhang, Shuo Zhang, Junnan Liu*</sub></sup>                                           | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16475)/Code |
| 2021 | AAAI | CamouFinder: Finding Camouflaged Instances in Images <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)
|   2021   | TIFS | Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection  <br><sup><sub>*Yi Liu, Dingwen Zhang, Qiang Zhang, and Jungong Han*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9600863/)/[Code](https://github.com/liuyi1989/TSPORTNet)
|   2021   | TIE | D2C-Net: A Dual-branch, Dual-guidance and Cross-refine Network for Camouflaged Object Detection <br><sup><sub>*Kang Wang, Hongbo Bi, Yi Zhang, Cong Zhang, Ziqi Liu, Shuang Zheng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9430677)/[Code](https://github.com/MS-KangWang/COD-D2Net)
|   2021   |  TCSVT   | Deep Texture-Aware Features for Camouflaged Object Detection <br><sup><sub>*Jingjing Ren, Xiaowei Hu, Lei Zhu, Xuemiao Xu, et al.*</sub></sup>  | [Paper](https://arxiv.org/pdf/2102.02996.pdf)/Code 
|  2021   |  TCSVT  | Rethinking Camouflaged Object Detection: Models and Datasets <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup>   | [Paper](https://ieeexplore.ieee.org/document/9598866)/Code
|   2021   |   Access | MirrorNet: Bio-Inspired Camouflaged Object Segmentation <br><sup><sub>*Jinnan Yan, Trung-Nghia Le, Khanh-Duy Nguyen, Minh-Triet Tran, Thanh-Toan Do, Tam V. Nguyen*</sub></sup>  | [Paper](https://arxiv.org/abs/2007.12881)/[Project](https://sites.google.com/view/ltnghia/research/camo)
|   2021   |  arXiv   | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2106.13217v3)/Code
|   2021   |  arXiv   | Accurate Camouflaged Object Detection via Mixture Convolution and Interactive Fusion <br> <sup><sub>*Bo Dong, Mingchen Zhuge, Yongxiong Wang, Hongbo Bi, Geng Chen*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.05687.pdf)/[Code](https://github.com/BigHeartDB/MCIFNet)  

####  2.2.5. Before YEAR 2020 

| **Year** | **Publication** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2020   |   CVPR   | **Camouflaged Object Detection** (`SINet & COD10K dataset`)                            <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao*</sub></sup>                                         | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)/[Code](https://github.com/DengPingFan/SINet)           |
|   2019   |   CVIU   | Anabranch network for camouflaged object segmentation (`CAMO dataset`) <br><sup><sub>*Trung-Nghia Le, Tam V. Nguyen, Zhongliang Nie, Minh-Triet Tran, Akihiro Sugimoto*</sub></sup>  | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf)/[Code](https://sites.google.com/view/ltnghia/research/camo)
|   2019   |   SPL    | Detection of People With Camouflage Pattern Via Dense Deconvolution Network (`CPD1K dataset`) <br><sup><sub>*Yunfei Zheng, Xiongwei Zhang, Feng Wang, Tieyong Cao, Meng Sun, Xiaobing Wang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/8336933)/Code
|   2018   |   TIP    | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup>                                              | [Paper](https://arxiv.org/abs/1804.05984)/Code                                                   |
|   2016   |   IJCV   | <span style="white-space:nowrap;">Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour&emsp;&emsp;&emsp;</span> <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5)/Code        



###  2.3. Camouflaged/Concealed Instance Segmentation (CIS)


| **Year** | **Publication** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2023  | arXiv | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation  <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)/Code 
| 2023  | ACM MM | A Unified Query-based Paradigm for Camouflaged Instance Segmentation  <br> <sup><sub>*Bo Dong, Jialun Pei, Rongrong Gao, Tian-Zhu Xiang, Shuo Wang, Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.07392)/[Code](https://github.com/dongbo811/UQFormer)
| 2023     | CVPR     | Camouflaged Instance Segmentation via Explicit De-camouflaging  <br> <sup><sub>*Naisong Luo, Yuwen Pan, Rui Sun, Tianzhu Zhang, Zhiwei Xiong, Feng Wu*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Luo_Camouflaged_Instance_Segmentation_via_Explicit_De-Camouflaging_CVPR_2023_paper.pdf)/[Code](https://github.com/USTCL/DCNet)
| 2022   |  ECCV    | **OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers** <br> <sup><sub>*Jialun Pei, Tianyang Cheng, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2207.02255)/[Code](https://github.com/PJLallen/OSFormer)
| 2022   |  TIP  | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite <br> <sup><sub>*Trung-Nghia Le, Yubo Cao, Tan-Cong Nguyen, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2103.17123)/[Project](https://sites.google.com/view/ltnghia/research/camo_plus_plus)

	
### 2.4. Camouflaged/Concealed Object Counting (COC)

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2023   |   CVPR   | **Indiscernible Object Counting in Underwater Scenes** <br><sup><sub>*Guolei Sun, Zhaochong An, Yun Liu, Ce Liu, Christos Sakaridis, Deng-Ping Fan, Luc Van Gool*</sub></sup>                             | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_Indiscernible_Object_Counting_in_Underwater_Scenes_CVPR_2023_paper.pdf)/[Code](https://github.com/GuoleiSun/Indiscernible-Object-Counting)  
	
###  2.5. Video Camouflaged/Concealed Object Detection (VCOD)

| **Year** | **Publication** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2024 | arXiv | Explicit Motion Handling and Interactive Prompting for Video Camouflaged Object Detection <br> <sup><sub>*Xin Zhang, Tao Xiao, Ge-Peng Ji, Xuan Wu, Keren Fu, Qijun Zhao*</sub></sup> | [Paper](https://arxiv.org/pdf/2403.01968v1.pdf)/Code
|   2022   |   CVPR   | **Implicit Motion Handling for Video Camouflaged Object Detection** (`MoCA-Mask dataset`) <br> <sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://dengpingfan.github.io/papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)/[Code](https://github.com/XuelianCheng/SLT-Net)
| 2022 | TPAMI | EM-driven unsupervised learning for efficient motion segmentation <br> <sup><sub>*Etienne Meunier, Ana¨ıs Badoual, and Patrick Bouthemy.*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9855882)/[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation)
| 2022 | NeurIPS |Segmenting Moving Objects via an Object-Centric Layered Representation <br> <sup><sub>*Junyu Xie, Weidi Xie, Andrew Zisserman.*</sub></sup> | [Paper](https://openreview.net/pdf?id=tUH1Or4xblM)/Code
| 2022 | arXiv | The Right Spin: Learning Object Motion from Rotation-Compensated Flow Fields <br> <sup><sub>*Pia Bideau, Erik Learned-Miller, Cordelia Schmid, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2203.00115.pdf)/Code
| 2021 | ICCV | Self-Supervised Video Object Segmentation by Motion Grouping <br> <sup><sub>*Charig Yang, Hala Lamdouar, Erika Lu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Self-Supervised_Video_Object_Segmentation_by_Motion_Grouping_ICCV_2021_paper.pdf)/[Code](https://charigyang.github.io/motiongroup/)
| 2021 | BMVC | Segmenting Invisible Moving Objects <br> <sup><sub>*Hala Lamdouar, Weidi Xie, and Andrew Zisserman.*</sub></sup> | [Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0056.pdf)/[Code](https://www.robots.ox.ac.uk/~vgg/research/simo/)
| 2020 | ACCV |Betrayed By Motion: Camouflaged Object Discovery via Motion Segmentation  (`MoCA dataset`)<br> <sup><sub>*Hala Lamdouar, Charig Yang, Weidi Xie,et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.pdf)/[Code](https://github.com/hlamdouar/MoCA/)	
| 2019 | CVPR |Object discovery in videos as foreground motion clustering <br> <sup><sub>*Christopher Xie, Yu Xiang, Zaid Harchaoui, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xie_Object_Discovery_in_Videos_as_Foreground_Motion_Clustering_CVPR_2019_paper.pdf)/Code
| 2018 | CVPR |The best of both worlds: Combining cnns and geometric constraints for hierarchical motion segmentation <br> <sup><sub>*Pia Bideau, Aruni RoyChowdhury, Rakesh R. Menon,et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bideau_The_Best_of_CVPR_2018_paper.pdf)/[Code](https://github.com/pbideau/hierarchical-motion-segmentation)
| 2016 | ECCV | <span style="white-space:nowrap;">It’s Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos&emsp;&emsp;&emsp;</span> <br><sup><sub>*Bideau, Pia, and Erik Learned-Miller.*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_26)/Code


### 2.6. Referring COD

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2023  | arXiv | Large Model Based Referring Camouflaged Object Detection   <br> <sup><sub>*Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.17122)/Code
| 2023  | arXiv | Referring Camouflaged Object Detection   <br> <sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup>  | [Paper](https://arxiv.org/abs/2306.07532)/[Code]([https://github.com/ChunmingHe/WS-SAM](https://github.com/zhangxuying1004/RefCOD))
