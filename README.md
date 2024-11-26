# Awesome-Multimodal-Large-Language-Models


---

<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome Policy](#awesome-policy)
  - [Multimodal Instruction Tuning](#multimodal-instruction-tuning)
  - [Multimodal Hallucination](#multimodal-hallucination)
  - [Multimodal In-Context Learning](#multimodal-in-context-learning)
  - [Multimodal Chain-of-Thought](#multimodal-chain-of-thought)
  - [LLM-Aided Visual Reasoning](#llm-aided-visual-reasoning)
  - [Foundation Models](#foundation-models)
  - [Evaluation](#evaluation)
  - [Multimodal RLHF](#multimodal-rlhf)
  - [Others](#others)
- [Awesome Agent](#awesome-agents)
  - [Datasets of Pre-Training for Alignment](#datasets-of-pre-training-for-alignment)
  - [Datasets of Multimodal Instruction Tuning](#datasets-of-multimodal-instruction-tuning)
  - [Datasets of In-Context Learning](#datasets-of-in-context-learning)
  - [Datasets of Multimodal Chain-of-Thought](#datasets-of-multimodal-chain-of-thought)
  - [Datasets of Multimodal RLHF](#datasets-of-multimodal-rlhf)
  - [Benchmarks for Evaluation](#benchmarks-for-evaluation)
  - [Others](#others-1)
---

# Awesome Policy

## Multimodal Instruction Tuning
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/Vision-CAIR/LongVU.svg?style=social&label=Star) <br> [**LongVU: Spatiotemporal Adaptive Compression for Long Video-Language Understanding**](https://arxiv.org/pdf/2410.17434) <br> | arXiv | 2024-10-22 | [Github](https://github.com/Vision-CAIR/LongVU) | [Demo](https://huggingface.co/spaces/Vision-CAIR/LongVU) |
| ![Star](https://img.shields.io/github/stars/shikiw/Modality-Integration-Rate.svg?style=social&label=Star) <br> [**Deciphering Cross-Modal Alignment in Large Vision-Language Models with Modality Integration Rate**](https://arxiv.org/pdf/2410.07167) <br> | arXiv | 2024-10-09 | [Github](https://github.com/shikiw/Modality-Integration-Rate) | - |
| [**Molmo and PixMo: Open Weights and Open Data for State-of-the-Art Multimodal Models**](https://arxiv.org/pdf/2409.17146) | arXiv | 2024-09-25 | [Huggingface](https://huggingface.co/allenai/MolmoE-1B-0924) | [Demo](https://molmo.allenai.org) |
| ![Star](https://img.shields.io/github/stars/QwenLM/Qwen2-VL.svg?style=social&label=Star) <br> [**Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution**](https://arxiv.org/pdf/2409.12191) <br> | arXiv | 2024-09-18 | [Github](https://github.com/QwenLM/Qwen2-VL) | [Demo](https://huggingface.co/spaces/Qwen/Qwen2-VL) |
| ![Star](https://img.shields.io/github/stars/FreedomIntelligence/LongLLaVA.svg?style=social&label=Star) <br> [**LongLLaVA: Scaling Multi-modal LLMs to 1000 Images Efficiently via Hybrid Architecture**](https://arxiv.org/pdf/2409.02889) <br> | arXiv | 2024-09-04 | [Github](https://github.com/FreedomIntelligence/LongLLaVA) | - | 
| ![Star](https://img.shields.io/github/stars/NVlabs/Eagle.svg?style=social&label=Star) <br> [**EAGLE: Exploring The Design Space for Multimodal LLMs with Mixture of Encoders**](https://arxiv.org/pdf/2408.15998) <br> | arXiv | 2024-08-28 | [Github](https://github.com/NVlabs/Eagle) | [Demo](https://huggingface.co/spaces/NVEagle/Eagle-X5-13B-Chat) |
| ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star) <br> [**mPLUG-Owl3: Towards Long Image-Sequence Understanding in Multi-Modal Large Language Models**](https://www.arxiv.org/pdf/2408.04840) <br> | arXiv | 2024-08-09 | [Github](https://github.com/X-PLUG/mPLUG-Owl) | - |
| ![Star](https://img.shields.io/github/stars/VITA-MLLM/VITA.svg?style=social&label=Star) <br> [**VITA: Towards Open-Source Interactive Omni Multimodal LLM**](https://arxiv.org/pdf/2408.05211) <br> | arXiv | 2024-08-09 | [Github](https://github.com/VITA-MLLM/VITA) | - | 
| ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT.svg?style=social&label=Star) <br> [**LLaVA-OneVision: Easy Visual Task Transfer**](https://arxiv.org/pdf/2408.03326) <br> | arXiv | 2024-08-06 | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Demo](https://llava-onevision.lmms-lab.com) | 
| ![Star](https://img.shields.io/github/stars/VT-NLP/MultiInstruct.svg?style=social&label=Star) <br> [**MultiInstruct: Improving Multi-Modal Zero-Shot Learning via Instruction Tuning**](https://arxiv.org/pdf/2212.10773.pdf) <br> | ACL | 2022-12-21 | [Github](https://github.com/VT-NLP/MultiInstruct) | - | 



---

# Awesome Agent

## Datasets of Pre-Training for Alignment
| Name | Paper | Type | Modalities |
|:-----|:-----:|:----:|:----------:|
| **ShareGPT4Video** | [ShareGPT4Video: Improving Video Understanding and Generation with Better Captions](https://arxiv.org/pdf/2406.04325v1) | Caption | Video-Text |
| **COYO-700M** | [COYO-700M: Image-Text Pair Dataset](https://github.com/kakaobrain/coyo-dataset/) | Caption | Image-Text |
| **ShareGPT4V** | [ShareGPT4V: Improving Large Multi-Modal Models with Better Captions](https://arxiv.org/pdf/2311.12793.pdf) | Caption | Image-Text |
| **AS-1B** | [The All-Seeing Project: Towards Panoptic Visual Recognition and Understanding of the Open World](https://arxiv.org/pdf/2308.01907.pdf) | Hybrid | Image-Text |
| **InternVid** | [InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation](https://arxiv.org/pdf/2307.06942.pdf) | Caption | Video-Text |
| **MS-COCO** | [Microsoft COCO: Common Objects in Context](https://arxiv.org/pdf/1405.0312.pdf) | Caption | Image-Text |
| **SBU Captions** | [Im2Text: Describing Images Using 1 Million Captioned Photographs](https://proceedings.neurips.cc/paper/2011/file/5dd9db5e033da9c6fb5ba83c7a7ebea9-Paper.pdf) | Caption | Image-Text |
| **Conceptual Captions** | [Conceptual Captions: A Cleaned, Hypernymed, Image Alt-text Dataset For Automatic Image Captioning](https://aclanthology.org/P18-1238.pdf) | Caption | Image-Text |
| **LAION-400M** | [LAION-400M: Open Dataset of CLIP-Filtered 400 Million Image-Text Pairs](https://arxiv.org/pdf/2111.02114.pdf) | Caption | Image-Text |
| **VG Captions** |[Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations](https://link.springer.com/content/pdf/10.1007/s11263-016-0981-7.pdf) | Caption | Image-Text |
| **Flickr30k** | [Flickr30k Entities: Collecting Region-to-Phrase Correspondences for Richer Image-to-Sentence Models](https://openaccess.thecvf.com/content_iccv_2015/papers/Plummer_Flickr30k_Entities_Collecting_ICCV_2015_paper.pdf) | Caption | Image-Text |
| **AI-Caps** | [AI Challenger : A Large-scale Dataset for Going Deeper in Image Understanding](https://arxiv.org/pdf/1711.06475.pdf) | Caption | Image-Text | 
| **Wukong Captions** | [Wukong: A 100 Million Large-scale Chinese Cross-modal Pre-training Benchmark](https://proceedings.neurips.cc/paper_files/paper/2022/file/a90b9a09a6ee43d6631cf42e225d73b4-Paper-Datasets_and_Benchmarks.pdf) | Caption | Image-Text |
| **GRIT** | [Kosmos-2: Grounding Multimodal Large Language Models to the World](https://arxiv.org/pdf/2306.14824.pdf) | Caption | Image-Text-Bounding-Box |
| **Youku-mPLUG** | [Youku-mPLUG: A 10 Million Large-scale Chinese Video-Language Dataset for Pre-training and Benchmarks](https://arxiv.org/pdf/2306.04362.pdf) | Caption | Video-Text |
| **MSR-VTT** | [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://openaccess.thecvf.com/content_cvpr_2016/papers/Xu_MSR-VTT_A_Large_CVPR_2016_paper.pdf) | Caption | Video-Text |
| **Webvid10M** | [Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval](https://arxiv.org/pdf/2104.00650.pdf) | Caption | Video-Text |
| **WavCaps** | [WavCaps: A ChatGPT-Assisted Weakly-Labelled Audio Captioning Dataset for Audio-Language Multimodal Research](https://arxiv.org/pdf/2303.17395.pdf) | Caption | Audio-Text |
| **AISHELL-1** | [AISHELL-1: An open-source Mandarin speech corpus and a speech recognition baseline](https://arxiv.org/pdf/1709.05522.pdf) | ASR | Audio-Text |
| **AISHELL-2** | [AISHELL-2: Transforming Mandarin ASR Research Into Industrial Scale](https://arxiv.org/pdf/1808.10583.pdf) | ASR | Audio-Text |
| **VSDial-CN** | [X-LLM: Bootstrapping Advanced Large Language Models by Treating Multi-Modalities as Foreign Languages](https://arxiv.org/pdf/2305.04160.pdf) | ASR | Image-Audio-Text |
