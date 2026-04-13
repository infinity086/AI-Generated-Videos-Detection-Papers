<div align="center">

# AI-Generated Content Detection

![Papers](https://img.shields.io/badge/Total_Papers-37-blue?style=for-the-badge)
![Datasets](https://img.shields.io/badge/Datasets-11-green?style=for-the-badge)
![Last Updated](https://img.shields.io/badge/Last_Updated-2026--04-orange?style=for-the-badge)

A curated collection of papers, datasets, and methods for detecting AI-generated content.

**If you find this resource helpful, please consider giving it a** :star:

[<img src="https://img.shields.io/badge/CCF_A-dc3545?style=flat-square" alt="CCF A">](#) CCF-A
&nbsp;&nbsp;
[<img src="https://img.shields.io/badge/CCF_B-ffc107?style=flat-square" alt="CCF B">](#) CCF-B
&nbsp;&nbsp;
[<img src="https://img.shields.io/badge/CCF_C-28a745?style=flat-square" alt="CCF C">](#) CCF-C
&nbsp;&nbsp;
[<img src="https://img.shields.io/badge/CCF_None-6c757d?style=flat-square" alt="CCF None">](#) Non-CCF

</div>

> :bulb: Papers are organized in **reverse chronological order** (newest first) within each category.

---

## :bookmark_tabs: Table of Contents

- [:movie_camera: AI-Generated Videos Detection](#-ai-generated-videos-detection-ai生成视频检测)
  - [Datasets](#datasets)
  - [Methods](#methods)
- [:framed_picture: Synthetic Image Detection Using LLMs](#-synthetic-image-detection-using-large-language-models-大模型微调算法)
- [:newspaper: Misinformation Detection Using LLMs](#-misinformation-detection-using-large-language-models-大模型检测虚假信息)
- [:bar_chart: Video Generation Evaluation](#-video-generation-evaluation-视频生成评估)

---

## :movie_camera: AI-Generated Videos Detection (AI生成视频检测)

### Datasets

| Dataset | Download | Paper | Count | Size |
|:--------|:---------|:------|------:|-----:|
| **AIGVDBench** | [HuggingFace](https://huggingface.co/datasets/AIGVDBench/AIGVDBench) | [AIGVDBench](https://arxiv.org/abs/2601.11035) `Arxiv 2601` | — | — |
| **Magic-Videos** | [HuggingFace](https://huggingface.co/datasets/mgiant/magic_videos) | [Preserving Forgery Artifacts](https://openreview.net/forum?id=XD43lfRCg6) `ICLR 2026` | — | — |
| **BrokenVideos** | [Baidu Pan](https://pan.baidu.com/s/1FQbUXuoPm3rOtamUzTtOWA?pwd=i38e) / [Project](https://broken-video-detection-datetsets.github.io/Broken-Video-Detection-Datasets.github.io/) | [BrokenVideos](https://dl.acm.org/doi/10.1145/3746027.3758305) `ACM MM 2025` | — | — |
| **IVY-FAKE** | [HuggingFace](https://huggingface.co/datasets/AI-Safeguard/Ivy-Fake) | [IVY-FAKE](https://arxiv.org/abs/2506.00979) `Arxiv 2506` | 160,000 | — |
| **GenVidBench** | [Baidu Pan](https://pan.baidu.com/s/1x4r0VYCrO8FMd_557thOIA?pwd=bu1q) | [GenVidBench](https://arxiv.org/abs/2501.11340) `Arxiv 2501` | — | — |
| **SafeWatch-Bench** | [HuggingFace](https://huggingface.co/datasets/Zhaorun/SafeWatch-Bench) | [SafeWatch](https://arxiv.org/abs/2412.06878) `ICLR 2025` | 1,400 | ~7.2GB |
| **DVF** | [GitHub](https://github.com/SparkleXFantasy/MM-Det?tab=readme-ov-file#diffusion-video-forensics-dataset) | [MM-Det](https://arxiv.org/abs/2410.23623) `NeurIPS 2024` | 6,688 | ~43GB |
| **Gen-Video** | Generated: [ModelScope](https://modelscope.cn/datasets/cccnju/Gen-Video) <br/> Real: [Kinetics-400](https://github.com/cvdfoundation/kinetics-dataset) / [Youku-mPLUG](https://modelscope.cn/datasets/cccnju/Gen-Video/files) / [MSR-VTT](https://modelscope.cn/datasets/cccnju/Gen-Video/file/view/master?id=28984&status=2&fileName=GenVideo-Val.zip) | [DeMamba](https://arxiv.org/abs/2405.19707) `Arxiv 2405` | 2,314,182 | ~2.08TB |
| **synth-vid-detect** | [HuggingFace](https://huggingface.co/datasets/ductai199x/synth-vid-detect) | [Beyond Deepfake Images](https://openaccess.thecvf.com/content/CVPR2024W/WMF/html/Vahdati_Beyond_Deepfake_Images_Detecting_AI-Generated_Videos_CVPRW_2024_paper.html) `CVPRW 2024` | — | — |
| **AIGVDet** | [GitHub](https://github.com/multimediaFor/AIGVDet?tab=readme-ov-file#dataset) | [Spatio-Temporal Anomaly Learning](https://arxiv.org/abs/2403.16638) `PRCV 2024` | — | — |
| **GVF** | Generated: [GitHub](https://github.com/wuwuwuyue/DeCoF/?tab=readme-ov-file#news-) / [Google Drive](https://drive.google.com/drive/folders/1X4Gw4hkWfka42IaBQ6ImkDTGAeA9Wlk4?usp=drive_link) <br/> Real: MSVD [OneDrive](https://pkueducn-my.sharepoint.com/:u:/g/personal/2101112290_pkueducn_onmicrosoft_com/ESi2AhDhuMpPsfv5E3N9xtsBhbraiiC4ZuAhwCdNS7kGYA?e=LPcfkl) / [PKU Drive](https://disk.pku.edu.cn/link/AA9E57BB3055344D98BCED580891278655) <br/> MSRVTT: [OneDrive](https://pkueducn-my.sharepoint.com/:u:/g/personal/2101112290_pkueducn_onmicrosoft_com/EW8dnlrbXrhPpHCzqUWYBmEBy_15l4nQuZBuIS2akdIWwg?e=mxCEwZ) / [PKU Drive](https://disk.pku.edu.cn/link/AACF5DF7B019D64AA7A956E99A5A3201ED) | [DeCoF](https://arxiv.org/abs/2402.02085) `Arxiv 2402` | — | — |

### Methods

<details open>
<summary><b>2026</b> (7 papers)</summary>

&nbsp;

|  | Paper | Links |
|:-|:------|:------|
| | **GenVideoLens**: Where LVLMs Fall Short in AI-Generated Video Detection? | [![paper](https://img.shields.io/badge/Arxiv-2603.18625-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2603.18625) |
| | **VideoVeritas**: AI-Generated Video Detection via Perception Pretext Reinforcement Learning | [![paper](https://img.shields.io/badge/Arxiv-2602.08828-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2602.08828) [![GitHub](https://img.shields.io/github/stars/EricTan7/VideoVeritas?style=flat)](https://github.com/EricTan7/VideoVeritas) [![Model](https://img.shields.io/badge/Model-ModelScope-624aff)](https://www.modelscope.cn/models/EricTanh/VideoVeritas) [![Datasets](https://img.shields.io/badge/Datasets-ff001)](https://www.modelscope.cn/datasets/EricTanh/MintVid) |
| | **MPF-Net**: Exposing High-Fidelity AI-Generated Video Forgeries via Hierarchical Manifold Deviation and Micro-Temporal Fluctuations | [![paper](https://img.shields.io/badge/Arxiv-2601.21408-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2601.21408) |
| | **AIGVDBench**: Your One-Stop Solution for AI-Generated Video Detection | [![paper](https://img.shields.io/badge/Arxiv-2601.11035-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2601.11035) [![GitHub](https://img.shields.io/github/stars/LongMa-2025/AIGVDBench?style=flat)](https://github.com/LongMa-2025/AIGVDBench) [![Datasets](https://img.shields.io/badge/Datasets-ff001)](https://huggingface.co/datasets/AIGVDBench/AIGVDBench) |
| | **Qwen2.5ViT-AIGVDetection**: Preserving Forgery Artifacts: AI-Generated Video Detection at Native Scale | [![paper](https://img.shields.io/badge/ICLR_'26-dc3545)](https://openreview.net/forum?id=XD43lfRCg6) [![GitHub](https://img.shields.io/github/stars/mgiant/Qwen2.5ViT-AIGVDetection?style=flat)](https://github.com/mgiant/Qwen2.5ViT-AIGVDetection) |
| | **VidGuard-R1**: AI-Generated Video Detection and Explanation via Reasoning MLLMs and RL | [![paper](https://img.shields.io/badge/ICLR_'26-dc3545)](https://openreview.net/forum?id=gXjOsBcXIR) [![GitHub](https://img.shields.io/github/stars/kyoungjunpark/VidGuard-R1?style=flat)](https://github.com/kyoungjunpark/VidGuard-R1) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://vidguard-r1.github.io/) |
| | **Skyra**: AI-Generated Video Detection via Grounded Artifact Reasoning | [![paper](https://img.shields.io/badge/CVPR_'26-dc3545)](https://arxiv.org/abs/2512.15693) [![GitHub](https://img.shields.io/github/stars/JoeLeelyf/Skyra?style=flat)](https://github.com/JoeLeelyf/Skyra) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://joeleelyf.github.io/Skyra/) [![Datasets](https://img.shields.io/badge/Datasets-ff001)](https://huggingface.co/collections/JoeLeelyf/skyra) |

</details>

<details open>
<summary><b>2025</b> (11 papers)</summary>

&nbsp;

|  | Paper | Links |
|:-|:------|:------|
| | **DeeptraceReward**: Learning Human-Perceived Fakeness in AI-Generated Videos via Multimodal LLMs | [![paper](https://img.shields.io/badge/Arxiv-2509.22646-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2509.22646) [![GitHub](https://img.shields.io/github/stars/deeptracereward/deeptracereward?style=flat)](https://github.com/deeptracereward/deeptracereward) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://deeptracereward.github.io/) |
| | **BrokenVideos**: A Benchmark Dataset for Fine-Grained Artifact Localization in AI-Generated Videos | [![paper](https://img.shields.io/badge/ACM_MM_'25-dc3545)](https://arxiv.org/abs/2506.20103) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://broken-video-detection-datetsets.github.io/Broken-Video-Detection-Datasets.github.io/) |
| | **WaveRep**: Seeing What Matters: Generalizable AI-generated Video Detection with Forensic-Oriented Augmentation | [![paper](https://img.shields.io/badge/NeurIPS_'25-dc3545)](https://arxiv.org/abs/2506.16802) [![GitHub](https://img.shields.io/github/stars/grip-unina/WaveRep-SyntheticVideoDetection?style=flat)](https://github.com/grip-unina/WaveRep-SyntheticVideoDetection) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://grip-unina.github.io/WaveRep-SyntheticVideoDetection/) |
| | **GenWorld**: Towards Detecting AI-generated Real-world Simulation Videos | [![paper](https://img.shields.io/badge/Arxiv-2506.10975-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2506.10975) |
| | **IVY-FAKE**: A Unified Explainable Framework and Benchmark for Image and Video AIGC Detection | [![paper](https://img.shields.io/badge/Arxiv-2506.00979-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2506.00979) [![Datasets](https://img.shields.io/badge/Datasets-ff001)](https://huggingface.co/datasets/AI-Safeguard/Ivy-Fake) |
| | **BusterX**: MLLM-Powered AI-Generated Video Forgery Detection and Explanation | [![paper](https://img.shields.io/badge/Arxiv-2505.12620-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2505.12620) [![Github](https://img.shields.io/github/stars/l8cv/BusterX?style=flat)](https://github.com/l8cv/BusterX) |
| | **LAVID**: An Agentic LVLM Framework for Diffusion-Generated Video Detection | [![paper](https://img.shields.io/badge/Arxiv-2502.14994-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2502.14994) |
| | **GenVidBench**: A Challenging Benchmark for Detecting AI-Generated Video | [![paper](https://img.shields.io/badge/Arxiv-2501.11340-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2501.11340) [![Github](https://img.shields.io/github/stars/genvidbench/GenVidBench?style=flat)](https://github.com/genvidbench/GenVidBench) |
| | **FVBench**: Benchmarking Deepfake Video Detection Capability of Large Multimodal Models | [![paper](https://img.shields.io/badge/OpenReview-6c757d)](https://openreview.net/forum?id=yxGPF62JUz) |
| | **NSG-VD**: Physics-Driven Spatiotemporal Modeling for AI-Generated Video Detection | [![paper](https://img.shields.io/badge/NeurIPS_'25_Spotlight-dc3545)](https://openreview.net/forum?id=HiBoJLCyEo) [![GitHub](https://img.shields.io/github/stars/ZSHsh98/NSG-VD?style=flat)](https://github.com/ZSHsh98/NSG-VD) |
| | **ReStraV**: AI-Generated Video Detection via Perceptual Straightening | [![paper](https://img.shields.io/badge/NeurIPS_'25-dc3545)](https://openreview.net/forum?id=LsmUgStXby) [![GitHub](https://img.shields.io/github/stars/ChristianInterno/ReStraV?style=flat)](https://github.com/ChristianInterno/ReStraV) |

</details>

<details open>
<summary><b>2024</b> (12 papers)</summary>

&nbsp;

|  | Paper | Links |
|:-|:------|:------|
| | **LOKI**: A Comprehensive Synthetic Data Detection Benchmark using Large Multimodal Models | [![paper](https://img.shields.io/badge/ICLR_'25_Spotlight-dc3545)](https://openreview.net/forum?id=z8sxoCYgmd) [![Github](https://img.shields.io/github/stars/opendatalab/LOKI?style=flat)](https://github.com/opendatalab/LOKI) |
| | **Towards a Universal Synthetic Video Detector**: From Face or Background Manipulations to Fully AI-Generated Content | [![paper](https://img.shields.io/badge/Arxiv-2412.12278-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2412.12278) |
| | **SafeWatch**: An Efficient Safety-Policy Following Video Guardrail Model with Transparent Explanations | [![paper](https://img.shields.io/badge/ICLR_'25-dc3545)](https://arxiv.org/abs/2412.06878) [![GitHub](https://img.shields.io/github/stars/BillChan226/SafeWatch?style=flat)](https://github.com/BillChan226/SafeWatch/) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://safewatch-aiguard.github.io/) |
| | **MM-Det**: On Learning Multi-Modal Forgery Representation for Diffusion Generated Video Detection | [![paper](https://img.shields.io/badge/NeurIPS_'24-dc3545)](https://arxiv.org/abs/2410.23623) [![GitHub](https://img.shields.io/github/stars/SparkleXFantasy/MM-Det?style=flat)](https://github.com/SparkleXFantasy/MM-Det) |
| | What Matters in Detecting AI-Generated Videos like **Sora**? | [![paper](https://img.shields.io/badge/Arxiv-2406.19568-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2406.19568) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://justin-crchang.github.io/3DCNNDetection.github.io/) |
| | **Turns Out I'm Not Real**: Towards Robust Detection of AI-Generated Videos | [![paper](https://img.shields.io/badge/Arxiv-2406.09601-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2406.09601) |
| | **DeMamba**: AI-Generated Video Detection on Million-Scale GenVideo Benchmark | [![paper](https://img.shields.io/badge/Arxiv-2405.19707-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2405.19707) [![GitHub](https://img.shields.io/github/stars/chenhaoxing/DeMamba?style=flat)](https://github.com/chenhaoxing/DeMamba) |
| | **Distinguish Any Fake Videos**: Unleashing the Power of Large-scale Data and Motion Features | [![paper](https://img.shields.io/badge/Arxiv-2405.15343-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2405.15343) |
| | **Exposing AI-generated Videos**: A Benchmark Dataset and a Local-and-Global Temporal Defect Based Detection Method | [![paper](https://img.shields.io/badge/Arxiv-2405.04133-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2405.04133) |
| | **Beyond Deepfake Images**: Detecting AI-Generated Videos | [![paper](https://img.shields.io/badge/CVPRW_'24-6c757d)](https://arxiv.org/abs/2404.15955) [![Datasets](https://img.shields.io/badge/Datasets-ffb6c1)](https://huggingface.co/datasets/ductai199x/synth-vid-detect) |
| | **AI-Generated Video Detection** via Spatio-Temporal Anomaly Learning | [![paper](https://img.shields.io/badge/PRCV_'24-28a745)](https://arxiv.org/abs/2403.16638) [![GitHub](https://img.shields.io/github/stars/multimediaFor/AIGVDet?style=flat)](https://github.com/multimediaFor/AIGVDet) |
| | **DeCoF**: Generated Video Detection via Frame Consistency | [![paper](https://img.shields.io/badge/Arxiv-2402.02085-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2402.02085) [![GitHub](https://img.shields.io/github/stars/wuwuwuyue/DeCoF?style=flat)](https://github.com/wuwuwuyue/DeCoF/) |

</details>

---

## :framed_picture: Synthetic Image Detection Using Large Language Models (大模型微调算法)

<details open>
<summary><b>2025</b> (5 papers)</summary>

&nbsp;

|  | Paper | Links |
|:-|:------|:------|
| | **Interpretable and Reliable Detection** of AI-Generated Images via Grounded Reasoning in MLLMs | [![paper](https://img.shields.io/badge/Arxiv-2506.07045-6c757d.svg?logo=arXiv)](https://www.arxiv.org/abs/2506.07045) |
| | **So-Fake**: Benchmarking and Explaining Social Media Image Forgery Detection | [![paper](https://img.shields.io/badge/Arxiv-2505.18660-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2505.18660) [![Github](https://img.shields.io/github/stars/hzlsaber/So-Fake?style=flat)](https://github.com/hzlsaber/So-Fake/) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://hzlsaber.github.io/projects/So-Fake/) |
| | **LEGION**: Learning to Ground and Explain for Synthetic Image Detection | [![paper](https://img.shields.io/badge/Arxiv-2503.15264-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2503.15264) [![Github](https://img.shields.io/github/stars/opendatalab/LEGION?style=flat)](https://github.com/opendatalab/LEGION) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://opendatalab.github.io/LEGION/) |
| | **Spot the Fake**: Large Multimodal Model-Based Synthetic Image Detection with Artifact Explanation | [![paper](https://img.shields.io/badge/Arxiv-2503.14905-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2503.14905) [![Github](https://img.shields.io/github/stars/opendatalab/FakeVLM?style=flat)](https://github.com/opendatalab/FakeVLM) |
| | **SIDA**: Social Media Image Deepfake Detection, Localization and Explanation with Large Multimodal Model | [![paper](https://img.shields.io/badge/CVPR_'25-dc3545)](https://arxiv.org/abs/2412.04292) [![Github](https://img.shields.io/github/stars/hzlsaber/SIDA?style=flat)](https://github.com/hzlsaber/SIDA) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://hzlsaber.github.io/projects/SIDA) |

</details>

---

## :newspaper: Misinformation Detection Using Large Language Models (大模型检测虚假信息)

<details open>
<summary><b>2024</b> (1 paper)</summary>

&nbsp;

|  | Paper | Links |
|:-|:------|:------|
| | **Deepfake Detection**: A Comprehensive Survey from the Reliability Perspective | [![paper](https://img.shields.io/badge/ACM-Computing_Surveys_'24-6c757d)](https://arxiv.org/abs/2211.10881) |

</details>

---

## :bar_chart: Video Generation Evaluation (视频生成评估)

<details open>
<summary><b>2024</b></summary>

&nbsp;

*Coming soon...*

</details>

---

<div align="center">

## :handshake: Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

If you find this survey useful for your research, please consider giving it a :star:

</div>
