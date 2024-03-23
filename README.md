[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/zytx121/Awesome-RSFM/pulls)
<br />
<p align="center">
  <h1 align="center">Towards Vision-Language Geo-Foundation Models: A Survey</h1>
  <p align="center">
    <b> arXiv, 2024 </b>
    <br />
    <a href="https://zytx121.github.io/"><strong>Yue Zhou </strong></a>
    .
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=PnNAAasAAAAJ"><strong> Litong Feng </strong></a>
    ·
    <a href="https://dr.ntu.edu.sg/cris/rp/rp00908/"><strong> Yiping Ke <sup>*</sup></strong></a>
    .
<!--     <a href="https://yangxue0827.github.io/"><strong> Xue Yang </strong></a>
    ·
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=rFv0cHYAAAAJ"><strong> Lin Chen </strong></a>
    ·
    <a href="https://sp.sjtu.edu.cn/"><strong> Xue Jiang </strong></a>
    ·
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=5GtyVooAAAAJ"><strong> Wayne Zhang </strong></a>
    . -->
  </p>

  <p align="center">
    <a href='https://arxiv.org/abs/xxx'>
      <img src='https://img.shields.io/badge/arXiv-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
    </a>
<!--     <a href='https://ieeexplore.ieee.org/document/10420487'>
      <img src='https://img.shields.io/badge/TPAMI-PDF-blue?style=flat&logo=IEEE&logoColor=green' alt='TPAMI PDF'>
    </a> -->
  </p>
<br />

This repo is used for recording, tracking, and benchmarking several recent vision-language geo-foundation models (VLGFM) to supplement our [survey](https://arxiv.org/abs/).  
If you find any work missing or have any suggestions (papers, implementations, and other resources), feel free to [pull requests](https://github.com/zytx121/Awesome-VLGFM/pulls).
We will add the missing papers to this repo as soon as possible.

### 🔥Add Your Paper in our Repo and Survey!!!!!

[-] You are welcome to give us an issue or PR for your VLGFM work !!!!!

[-] Note that: Due to the huge paper in Arxiv, we are sorry to cover all in our survey. You can directly present a PR into this repo and we will record it for next version update of our survey.

<!-- [-] **Our survey will be updated in 2024.3.** -->


### 🔥New

<!-- [-] Our work is accepted by T-PAMI !!! 🔥🔥🔥 -->

[-] We update GitHub to record the available paper by the end of **2024/4/1**.


### 🔥Highlight!!

[1]  The first survey for vision-language geo-foundation models, including contrastive/conversational/generative/agent geo-foundation models.

[2]  It also contains several related works, including exploration and application of some downstream tasks. 

[3]  We list detailed results for the most representative works and give a fairer and clearer comparison of different approaches.



## Introduction

This survey presents the first detailed survey on remote sensing vision language foundation models, including CLIP-based foundation models, LLM-based foundation models, and generative foundation models.

![Alt Text](figs/vlgfm.png)

## Summary of Contents

- [Introduction](#introduction)
- [Summary of Contents](#summary-of-contents)
- [Methods: A Survey](#methods-a-survey)
  - [Contrastive VLGFMs](#contrastive-vlgfms)
  - [Conversational VLGFMs](#conversational-vlgfms)
  - [Generative VLGFMs](#generative-vlgfms)
  - [Agent VLGFMs](#agent-vlgfms)
  - [Datasets](#datsets)
  - [Benchmarks](#benchmarks)
- [Application](#application)
  - [Captioning](#captioning)
  - [Retrieval](#retrieval)
  - [Change Detection](#change-detection)
  - [Scene Classification](#scene-classification)
  - [Segmentation](#segmentation)
  - [Visual Question Answering](#visual-question-answering)
  - [Geospatial Localization](#geospatial-localization)
  - [Super-Resolution](#super-resolution)
- [Exploration](#exploration)
- [Survey](#survey)
- [Acknowledgement](#acknowledgement)
- [Contact](#contact)

## Methods: A Survey

**Keywords**

- `clip`: Use CLIP
- `llm`: Use LLM (Large Language Model)
- `sam`: Use SAM (Segment Anything Model)


### Contrastive VLGFMs

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv|`clip`|[RemoteCLIP: A Vision Language Foundation Model for Remote Sensing](https://arxiv.org/abs/2306.11029)|[Code](https://github.com/ChenDelong1999/RemoteCLIP)|
|2023|arXiv|`clip`|[RS5M and GeoRSCLIP: A Large Scale Vision-Language Dataset and A Large Vision-Language Model for Remote Sensing](https://arxiv.org/abs/2306.11300)|[Code](https://github.com/om-ai-lab/RS5M)|
|2024|ICLR |`clip`|[GRAFT: Remote Sensing Vision-Language Foundation Models without Annotations via Ground Remote Alignment](https://arxiv.org/abs/2312.06960)|[Project](https://graft.cs.cornell.edu)|
|2024|AAAI|`clip`|[SkyScript: A Large and Semantically Diverse Vision-Language Dataset for Remote Sensing](https://arxiv.org/abs/2312.12856)|[Code](https://github.com/wangzhecheng/SkyScript)|
|2024|arXiv|`clip`|[Mind the Modality Gap: Towards a Remote Sensing Vision-Language Model via Cross-modal Alignment](https://arxiv.org/abs/2402.09816)|N/A|


### Conversational VLGFMs

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv|`llm`|[Rsgpt: A remote sensing vision language model and benchmark](https://arxiv.org/abs/2307.15266)|[Code](https://github.com/Lavender105/RSGPT)|
|2024|CVPR|`llm`|[GeoChat: Grounded Large Vision-Language Model for Remote Sensing](https://arxiv.org/abs/2311.15826)|[Code](https://github.com/mbzuai-oryx/geochat)|
|2024|arXiv|`llm`|[SkyEyeGPT: Unifying Remote Sensing Vision-Language Tasks via Instruction Tuning with Large Language Model](https://arxiv.org/abs/2401.09712)|[Code](https://github.com/ZhanYang-nwpu/SkyEyeGPT)|
|2024|arXiv|`llm`|[Earthgpt: A universal multi-modal large language model for multi-sensor image comprehension in remote sensing domain](https://arxiv.org/pdf/2401.16822.pdf)|N/A|
|2024|arXiv|`llm`|[LHRS-Bot: Empowering Remote Sensing with VGI-Enhanced Large Multimodal Language Model](https://arxiv.org/abs/2402.02544)|[Code](https://github.com/NJU-LHRS/LHRS-Bot)|
|2024|arXiv|`llm`|[Large Language Models for Captioning and Retrieving Remote Sensing Images](https://arxiv.org/pdf/2402.06475.pdf)|N/A|


### Generative VLGFMs

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv|`clip`|[Stable Diffusion For Aerial Object Detection](https://arxiv.org/abs/2311.12345)|N/A|
|2024|ICLR|`clip`|[DiffusionSat: A Generative Foundation Model for Satellite Imagery](https://arxiv.org/abs/2312.03606)|[Code](https://github.com/samar-khanna/DiffusionSat)|
|2024|arXiv|`clip`|[CRS-Diff: Controllable Generative Remote Sensing Foundation Model](https://arxiv.org/abs/2403.11614)|N/A|


### Agent VLGFMs
|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2024|arXiv|`llm`|[Remote Sensing ChatGPT: Solving Remote Sensing Tasks with ChatGPT and Visual Model](https://arxiv.org/abs/2401.09083)|[Code](https://github.com/HaonanGuo/Remote-Sensing-ChatGPT)|



### Datasets
|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|TGRS||[RSVG: Exploring Data and Models for Visual Grounding on Remote Sensing Data](https://ieeexplore.ieee.org/abstract/document/10056343)|N/A|
|2024|arXiv|`llm`|[ChatEarthNet: A Global-Scale, High-Quality Image-Text Dataset for Remote Sensing](https://arxiv.org/abs/2402.11325)|N/A|


### Benchmark
|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv||[Satin: A multi-task metadataset for classifying satellite imagery using vision-language models](https://arxiv.org/abs/2304.11619)|[Project](https://satinbenchmark.github.io/)|
|2024|arXiv||[Good at captioning, bad at counting: Benchmarking GPT-4V on Earth observation data](https://arxiv.org/abs/2401.17600)|[Code](https://vleo.danielz.ch/)|


### Application

#### Captioning

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|TGRS|`llm`|[A Decoupling Paradigm With Prompt Learning for Remote Sensing Image Change Captioning](https://ieeexplore.ieee.org/abstract/document/10271701)|[Code](https://github.com/Chen-Yang-Liu/PromptCC)|
|2023|JSEE|`llm`|[VLCA: vision-language aligning model with cross-modal attention for bilingual remote sensing image captioning](https://ieeexplore.ieee.org/abstract/document/10066217)|N/A|


#### Retrieval

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2022|VT|`llm`|[CLIP-RS: A Cross-modal Remote Sensing Image Retrieval Based on CLIP, a Northern Virginia Case Study](https://vtechworks.lib.vt.edu/items/beb6f813-0cc6-4594-a4ef-0068cc16b0bd)|N/A|
|2024|arXiv|`llm`|[Multi-Spectral Remote Sensing Image Retrieval Using Geospatial Foundation Models](https://arxiv.org/abs/2403.02059)|[Code](https://github.com/IBM/remote-sensing-image-retrieval)|



#### Change Detection

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv|`sam`|[Time Travelling Pixels: Bitemporal Features Integration with Foundation Model for Remote Sensing Image Change Detection](https://arxiv.org/abs/2312.16202)|[Code](https://github.com/KyanChen/TTP)|
|2024|JPRS|`clip`|[ChangeCLIP: Remote sensing change detection with multimodal vision-language representation learning](https://www.sciencedirect.com/science/article/pii/S0924271624000042)|[Code](https://github.com/dyzy41/ChangeCLIP)|
|2024|TGRS|`llm`|[A New Learning Paradigm for Foundation Model-Based Remote-Sensing Change Detection](https://ieeexplore.ieee.org/abstract/document/10438490)|[Code](https://github.com/likyoo/BAN)|
|2024|arXiv|`sam`|[Change Detection Between Optical Remote Sensing Imagery and Map Data via Segment Anything Model (SAM)](https://arxiv.org/abs/2401.09019)|N/A|
|2024|arXiv|`sam`|[Segment Any Change](https://arxiv.org/abs/2402.01188)|N/A|


#### Scene Classification

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|IJAEOG|`clip`|[RS-CLIP: Zero shot remote sensing scene classification via contrastive vision-language supervision](https://www.sciencedirect.com/science/article/pii/S1569843223003217)|[Code](https://github.com/lx709/RS-CLIP)|


#### Segmentation

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv|`sam` `llm`|[Text2Seg: Remote Sensing Image Semantic Segmentation via Text-Guided Vision Foundation Models](https://arxiv.org/abs/2304.10597)|[Code](https://github.com/Douglas2Code/Text2Seg)|
|2024|arXiv|`sam` `llm`|[RSAM-Seg: A SAM-based Approach with Prior Knowledge Integration for Remote Sensing Image Semantic Segmentation](https://arxiv.org/abs/2402.19004)|[Code](https://chief-byte.github.io/RSAM-Seg-Site)|


#### Visual Question Answering

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2022|CVPRW||[Prompt-RSVQA: Prompting visual context to a language model for remote sensing visual question answering](https://openaccess.thecvf.com/content/CVPR2022W/EarthVision/html/Chappuis_Prompt-RSVQA_Prompting_Visual_Context_to_a_Language_Model_for_Remote_CVPRW_2022_paper.html)|N/A|
|2024|AAAI||[EarthVQA: Towards Queryable Earth via Relational Reasoning-Based Remote Sensing Visual Question Answering](https://arxiv.org/abs/2312.12222)|[Project](https://junjuewang.top/EarthVQA)|



#### Geospatial Localization

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|ICML|`clip`|[CSP: Self-Supervised Contrastive Spatial Pre-Training for Geospatial-Visual Representations](https://arxiv.org/abs/2305.01118)|[Code](https://gengchenmai.github.io/csp-website/)|
|2023|NeurIPS|`clip`|[GeoCLIP: Clip-Inspired Alignment between Locations and Images for Effective Worldwide Geo-localization](https://arxiv.org/abs/2309.16020)|[Code](https://github.com/VicenteVivan/geo-clip)|
|2023|arXiv|`clip`|[SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery](https://arxiv.org/abs/2311.17179)|[Code](https://github.com/microsoft/satclip)|


#### Super-Resolution

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|arXiv|`clip`|[Zooming Out on Zooming In: Advancing Super-Resolution for Remote Sensing](https://arxiv.org/abs/2311.18082)|[Code](https://github.com/allenai/satlas-super-resolution)|


### Exploration

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2022|TGRS||[An Empirical Study of Remote Sensing Pretraining](https://arxiv.org/abs/2204.02825)|[Code](https://github.com/ViTAE-Transformer/RSP)|
|2023|arXiv||[Autonomous GIS: the next-generation AI-powered GIS](https://arxiv.org/abs/2305.06453)|N/A|
|2023|arXiv||[GPT4GEO: How a Language Model Sees the World's Geography](https://arxiv.org/abs/2306.00020)|[Code](https://github.com/jonathan-roberts1/GPT4GEO)|
|2023|arXiv||[Charting New Territories: Exploring the Geographic and Geospatial Capabilities of Multimodal LLMs](https://arxiv.org/abs/2311.14656)|[Code](https://github.com/jonathan-roberts1/charting-new-territories)|
|2023|arXiv||[The Potential of Visual ChatGPT For Remote Sensing](https://arxiv.org/abs/2304.13009)|N/A|




### Survey

|Year|Venue|Keywords|Paper Title|Code/Project|
|:-:|:-:|:-:|-|-|
|2023|IGARSS||[An Agenda for Multimodal Foundation Models for Earth Observation](https://ieeexplore.ieee.org/abstract/document/10282966)|N/A|
|2023|TGRS||[Self-Supervised Remote Sensing Feature Learning: Learning Paradigms, Challenges, and Future Works](https://ieeexplore.ieee.org/abstract/document/10126079)|N/A|
|2023|arXiv||[Vision-Language Models in Remote Sensing: Current Progress and Future Trends](https://arxiv.org/abs/2305.05726)|N/A|
|2023|GISWU||[Large Remote Sensing Model: Progress and Prospects](http://ch.whu.edu.cn/cn/article/doi/10.13203/j.whugis20230341)|N/A|
|2023|JSTARS||[Brain-Inspired Remote Sensing Foundation Models and Open Problems: A Comprehensive Survey](https://ieeexplore.ieee.org/abstract/document/10254282)|N/A|
|2023|arXiv||[On the Promises and Challenges of Multimodal Foundation Models for Geographical, Environmental, Agricultural, and Urban Planning Applications](https://arxiv.org/abs/2312.17016)|N/A|



## Acknowledgement

If you find our survey and repository useful for your research project, please consider citing our paper:

```bibtex
@article{zhou2024rsfm
      title={Towards Vision-Language Geo-Foundation Models: A Survey}, 
      author={Yue Zhou},
      year={2024},
      journal={arXiv},
}
```

## Contact

```
sjtu_zy@sjtu.edu.cn
```
