
# 😀 Overview

> [CCF-Rankings](https://www.ccf.org.cn/en/About_CCF/Media_Center/) now marked with different colors(![arXiv](https://img.shields.io/badge/CCF_A-dc3545) ![Static Badge](https://img.shields.io/badge/CCF_B-ffc107) ![Static Badge](https://img.shields.io/badge/CCF_C-28a745) ![Static Badge](https://img.shields.io/badge/CCF_None-6c757d))
>
> Newly added papers will be organized at the top of every category now.


## AI-Generated Videos Detection
**AI生成视频检测**

### Datasets

⭐️ ***Video Detection Datasets***

| Datasets Name    | Download Link                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Papers                                                                                                                                                                                                            | Total Count | Size     |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|----------|
| GVF              | Generated Videos: [GeneratedVideoForensics dataset](https://github.com/wuwuwuyue/DeCoF/?tab=readme-ov-file#news-) or [Google Drive](https://drive.google.com/drive/folders/1X4Gw4hkWfka42IaBQ6ImkDTGAeA9Wlk4?usp=drive_link) <br/> Real Videos: (1) MSVD [OneDrive](https://pkueducn-my.sharepoint.com/:u:/g/personal/2101112290_pkueducn_onmicrosoft_com/ESi2AhDhuMpPsfv5E3N9xtsBhbraiiC4ZuAhwCdNS7kGYA?e=LPcfkl) or [PKU Drive](https://disk.pku.edu.cn/link/AA9E57BB3055344D98BCED580891278655)  <br/> (2) MSRVTT: [OneDrive](https://pkueducn-my.sharepoint.com/:u:/g/personal/2101112290_pkueducn_onmicrosoft_com/EW8dnlrbXrhPpHCzqUWYBmEBy_15l4nQuZBuIS2akdIWwg?e=mxCEwZ) or [PKU Drive](https://disk.pku.edu.cn/link/AACF5DF7B019D64AA7A956E99A5A3201ED) | [DeCoF: Generated Video Detection via Frame Consistency: The First Benchmark Dataset](https://arxiv.org/abs/2402.02085) Arxiv 2402                                                                                |             |          |
| AIGVDet Dataset  | [AIGVDet Dataset](https://github.com/multimediaFor/AIGVDet?tab=readme-ov-file#dataset)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | [AI-Generated Video Detection via Spatio-Temporal Anomaly Learning](https://arxiv.org/abs/2403.16638) PRCV 2024                                                                                                   |             |          |
| synth-vid-detect | [synth-vid-detect dataset](https://huggingface.co/datasets/ductai199x/synth-vid-detect)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [Beyond Deepfake Images: Detecting AI-Generated Videos](https://openaccess.thecvf.com/content/CVPR2024W/WMF/html/Vahdati_Beyond_Deepfake_Images_Detecting_AI-Generated_Videos_CVPRW_2024_paper.html)  CVPR 2024 Workshop |             |          |
| Gen-Video        | Generated Videos: [ModelScope](https://modelscope.cn/datasets/cccnju/Gen-Video)<br/> Real Videos: [Kinetics-400](https://github.com/cvdfoundation/kinetics-dataset)、[Youku-mPLUG](https://modelscope.cn/datasets/cccnju/Gen-Video/files)、[MSR-VTT](https://modelscope.cn/datasets/cccnju/Gen-Video/file/view/master?id=28984&status=2&fileName=GenVideo-Val.zip)                                                                                                                                                                                                                                                                                                                                                                                                | [DeMamba: AI-Generated Video Detection on Million-Scale GenVideo Benchmark](https://arxiv.org/abs/2405.19707) Arxiv 2405                                                                                          | 2,314,182   | ~2.51TB  |
| DVF              | [Diffusion Video Forensics Dataset](https://github.com/SparkleXFantasy/MM-Det?tab=readme-ov-file#diffusion-video-forensics-dataset)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [On Learning Multi-Modal Forgery Representation for Diffusion Generated Video Detection](https://arxiv.org/abs/2410.23623) NeurIPS 2024 poster                                                                    |             |          |
| SafeWatch-Bench  | [SafeWatch-Bench Dataset](https://huggingface.co/datasets/Zhaorun/SafeWatch-Bench)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | [SafeWatch: An Efficient Safety-Policy Following Video Guardrail Model with Transparent Explanations](https://arxiv.org/abs/2412.06878) ICLR 2025                                                                              |             |          |



### Methods

<details open>
<summary>2024</summary>

* [ ] LAVID: An Agentic LVLM Framework for Diffusion-Generated Video Detection [![paper](https://img.shields.io/badge/Arxiv-2502.14994-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2502.14994)
* [ ] SafeWatch: An Efficient Safety-Policy Following Video Guardrail Model with Transparent Explanations [![paper](https://img.shields.io/badge/ICLR_'25-dc3545)](https://arxiv.org/abs/2412.06878) [![GitHub](https://img.shields.io/github/stars/BillChan226/SafeWatch?style=flat)](https://github.com/BillChan226/SafeWatch/) [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://safewatch-aiguard.github.io/)
* [ ] On Learning Multi-Modal Forgery Representation for Diffusion Generated Video Detection [![paper](https://img.shields.io/badge/NeurIPS_'24-dc3545)](https://arxiv.org/abs/2410.23623) [![GitHub](https://img.shields.io/github/stars/SparkleXFantasy/MM-Det?style=flat)](https://github.com/SparkleXFantasy/MM-Det)
* [ ] What Matters in Detecting AI-Generated Videos like Sora? [![paper](https://img.shields.io/badge/Arxiv-2406.19568-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2406.19568)  [![Project](https://img.shields.io/badge/Project-ffb6c1)](https://justin-crchang.github.io/3DCNNDetection.github.io/)
* [ ] Turns Out I’m Not Real: Towards Robust Detection of AI-Generated Videos [![paper](https://img.shields.io/badge/Arxiv-2406.09601-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2406.09601)
* [ ] DeMamba: AI-Generated Video Detection on Million-Scale GenVideo Benchmark [![paper](https://img.shields.io/badge/Arxiv-2405.19707-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2405.19707) [![GitHub](https://img.shields.io/github/stars/chenhaoxing/DeMamba?style=flat)](https://github.com/chenhaoxing/DeMamba)
* [ ] Distinguish Any Fake Videos: Unleashing the Power of Large-scale Data and Motion Features [![paper](https://img.shields.io/badge/Arxiv-2405.15343-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2405.15343)
* [ ] Exposing AI-generated Videos: A Benchmark Dataset and a Local-and-Global Temporal Defect Based Detection Method [![paper](https://img.shields.io/badge/Arxiv-2405.04133-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2405.04133)
* [ ] Beyond Deepfake Images: Detecting AI-Generated Videos [![paper](https://img.shields.io/badge/CVPRW_'24-6c757d)](https://arxiv.org/abs/2404.15955) [![Datasets](https://img.shields.io/badge/Datasets-ffb6c1)](https://huggingface.co/datasets/ductai199x/synth-vid-detect)
* [ ] AI-Generated Video Detection via Spatio-Temporal Anomaly Learning [![paper](https://img.shields.io/badge/PRCV_'24-28a745)](https://arxiv.org/abs/2403.16638) [![GitHub](https://img.shields.io/github/stars/multimediaFor/AIGVDet?style=flat)](https://github.com/multimediaFor/AIGVDet)
* [ ] DeCoF: Generated Video Detection via Frame Consistency: The First Benchmark Dataset [![paper](https://img.shields.io/badge/Arxiv-2402.02085-6c757d.svg?logo=arXiv)](https://arxiv.org/abs/2402.02085) [![GitHub](https://img.shields.io/github/stars/wuwuwuyue/DeCoF?style=flat)](https://github.com/wuwuwuyue/DeCoF/)
</details>


### Misinformation Detection Using Large Language Models

**大模型检测虚假信息**

<details open>
<summary>2024</summary>

* [ ] Deepfake Detection: A Comprehensive Survey from the Reliability Perspective [![paper](https://img.shields.io/badge/ACM-Computing_Surveys_'24-6c757d)](https://arxiv.org/abs/2211.10881)
* [ ] 

</details>


### Video Generation Evaluation

**视频生成评估**

<details open>
<summary>2024</summary>

</details>
