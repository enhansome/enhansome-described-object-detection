[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 499,883 | 🐛 106 | 📅 2026-08-21
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/Charles-Xie/awesome-described-object-detection) ⭐ 360 | 🐛 1 | 📅 2025-11-06

# Awesome Described Object Detection with stars

A curated list of papers and resources related to [Described Object Detection](https://arxiv.org/abs/2307.12813), Open-Vocabulary/Open-World Object Detection and Referring Expression Comprehension.

If you find any work or resources missing, please send a [pull requests](https://github.com/Charles-Xie/awesome-described-object-detection/pulls) ⭐ 360 | 🐛 1 | 📅 2025-11-06. Thanks!

***

<br> **📑 If you find our projects helpful to your research, please consider citing:** <br>

```bibtex
@inproceedings{xie2023DOD,
  title={Described Object Detection: Liberating Object Detection with Flexible Expressions},
  author={Xie, Chi and Zhang, Zhao and Wu, Yixuan and Zhu, Feng and Zhao, Rui and Liang, Shuang},
  booktitle={Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS)},
  year={2023}
}
```

***

## Table of Contents

* [Awesome Papers](#awesome-papers)
  * [Described Object Detection](#described-object-detection)
    * [Methods with Potential for DOD](#methods-with-potential-for-dod)
  * [Open-Vocabulary Object Detection](#open-vocabulary-object-detection)
  * [Referring Expression Comprehension/Visual Grounding](#referring-expression-comprehensionvisual-grounding)
* [Awesome Datasets](#awesome-datasets)
  * [Datasets for DOD and Similar Tasks](#datasets-for-dod-and-similar-tasks)
  * [Detection datasets](#detection-datasets)
  * [Grounding Datasets](#grounding-datasets)
* [Related Surveys and Resources](#related-surveys-and-resources)

# Awesome Papers

## Described Object Detection

* An Open and Comprehensive Pipeline for Unified Object Grounding and Detection (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2401.02361) [\[code\]](https://github.com/open-mmlab/mmdetection/tree/main/configs/mm_grounding_dino) ⭐ 32,892 | 🐛 1,960 | 🌐 Python | 📅 2024-08-21![Star](https://img.shields.io/github/stars/open-mmlab/mmdetection.svg?style=social\&label=Star)

* VLM-R1: A Stable and Generalizable R1-style Large Vision-Language Model (arxiv 2025) [\[paper\]](https://arxiv.org/abs/2504.07615) [\[code\]](https://github.com/om-ai-lab/VLM-R1) ⭐ 6,015 | 🐛 166 | 🌐 Python | 📅 2026-07-07

* GLIPv2: Unifying Localization and Vision-Language Understanding (NeurIPS 2022) [\[paper\]](https://arxiv.org/abs/2206.05836) [\[code\]](https://github.com/microsoft/GLIP) ⭐ 2,607 | 🐛 119 | 🌐 Python | 📅 2024-01-24![Star](https://img.shields.io/github/stars/microsoft/GLIP.svg?style=social\&label=Star)

* Grounded Language-Image Pre-training (CVPR 2022) [\[paper\]](https://arxiv.org/abs/2112.03857) [\[code\]](https://github.com/microsoft/GLIP) ⭐ 2,607 | 🐛 119 | 🌐 Python | 📅 2024-01-24![Star](https://img.shields.io/github/stars/microsoft/GLIP.svg?style=social\&label=Star)

* Aligning and Prompting Everything All at Once for Universal Visual Perception (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2312.02153) [\[code\]](https://github.com/shenyunhang/APE) ⭐ 609 | 🐛 59 | 🌐 Python | 📅 2024-05-08![Star](https://img.shields.io/github/stars/shenyunhang/APE.svg?style=social\&label=Star)

* Groma: Localized Visual Tokenization for Grounding Multimodal Large Language Models (ECCV 2024) [\[paper\]](https://arxiv.org/abs/2404.13013) [\[code\]](https://github.com/FoundationVision/Groma) ⭐ 586 | 🐛 17 | 🌐 Python | 📅 2024-06-07

* Described Object Detection: Liberating Object Detection with Flexible Expressions (NeurIPS 2023) [\[paper\]](https://arxiv.org/abs/2307.12813) [\[dataset\]](https://github.com/shikras/d-cube/) ⭐ 138 | 🐛 7 | 🌐 Python | 📅 2024-03-20 [\[code\]](https://github.com/shikras/d-cube/) ⭐ 138 | 🐛 7 | 🌐 Python | 📅 2024-03-20![Star](https://img.shields.io/github/stars/shikras/d-cube.svg?style=social\&label=Star)

* Coarse-to-Fine Vision-Language Pre-training with Fusion in the Backbone (NeurIPS 2022) [\[paper\]](https://arxiv.org/abs/2206.07643) [\[code\]](https://github.com/microsoft/FIBER) ⭐ 131 | 🐛 11 | 🌐 Python | 📅 2023-10-10![Star](https://img.shields.io/github/stars/microsoft/FIBER.svg?style=social\&label=Star)

* RefDrone: A Challenging Benchmark for Referring Expression Comprehension in Drone Scenes (arxiv 2025) [\[paper\]](https://arxiv.org/abs/2502.00392) [\[code\]](https://github.com/sunzc-sunny/refdrone) ⭐ 47 | 🐛 7 | 🌐 Python | 📅 2026-07-08

* DetToolChain: A New Prompting Paradigm to Unleash Detection Ability of MLLM (ECCV 2024) [\[paper\]](https://arxiv.org/abs/2403.12488) [\[code\]](https://github.com/yixuan730/DetToolChain) ⭐ 45 | 🐛 7 | 🌐 Python | 📅 2024-10-12

* Re-Aligning Language to Visual Objects with an Agentic Workflow (ICLR 2025) [\[paper\]](https://arxiv.org/abs/2503.23508) [\[code\]](https://github.com/FishAndWasabi/Real-LOD) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2025-04-20

* DesCo: Learning Object Recognition with Rich Language Descriptions (NeurIPS 2023) [\[paper\]](https://arxiv.org/abs/2306.14060) [\[code\]](https://github.com/liunian-harold-li/DesCo) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2024-03-13

* Generating Enhanced Negatives for Training Language-Based Object Detectors (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2401.00094) [\[code\]](https://github.com/xiaofeng94/Gen-Enhanced-Negs) ⭐ 6 | 🐛 3 | 🌐 Python | 📅 2025-06-17

* Ground-V: Teaching VLMs to Ground Complex Instructions in Pixels (CVPR 2025) [\[paper\]](https://arxiv.org/abs/2505.13788)

* ROD-MLLM: Towards More Reliable Object Detection in Multimodal Large Language Models (CVPR 2025) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Yin_ROD-MLLM_Towards_More_Reliable_Object_Detection_in_Multimodal_Large_Language_CVPR_2025_paper.pdf)

* RelationLMM: Large Multimodal Model as Open and Versatile Visual Relationship Generalist (TPAMI 2025) [\[paper\]](https://ieeexplore.ieee.org/document/10845195)

* A Multimodal Chain of Tools for Described Object Detection (NeurIPS 2024 Workshop) [\[paper\]](https://openreview.net/pdf?id=N4i4PfcrK6)

* Weak-to-Strong Compositional Learning from Generative Models for Language-based Object Detection (ECCV 2024) [\[paper\]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03307.pdf)

* Learning Compositional Language-based Object Detection with Diffusion-based Synthetic Data (CVPR 2024 Workshop) [\[paper\]](https://generative-vision.github.io/workshop-CVPR-24/papers/28.pdf)

* LLM-Optic: Unveiling the Capabilities of Large Language Models for Universal Visual Grounding (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2405.17104)

A leaderboard for DOD methods are available [here](https://github.com/shikras/d-cube/tree/main/eval_sota) ⭐ 138 | 🐛 7 | 🌐 Python | 📅 2024-03-20.

### Methods with Potential for DOD

These methods are either MLLM with capabilities related to detection/localization, or multi-task models handling both OD/OVD and REC. Though they are not directly handling DOD and not evaluated on DOD benchmarks in their original papers, it is possible that they obtain a performance similar to the DOD baseline.

* FindIt: Generalized Localization with Natural Language Queries (ECCV 2022) [\[paper\]](https://arxiv.org/abs/2203.17273) [\[code\]](https://github.com/google-research/google-research/tree/master/findit) ⭐ 38,618 | 🐛 1,988 | 🌐 Jupyter Notebook | 📅 2026-08-25![Star](https://img.shields.io/github/stars/google-research/google-research.svg?style=social\&label=Star) (REC, OD, etc.)

* Kosmos-2: Grounding Multimodal Large Language Models to the World (ICLR 2024) [\[paper\]](https://arxiv.org/abs/2306.14824) [\[demo\]](https://huggingface.co/spaces/ydshieh/Kosmos-2) [\[code\]](https://github.com/microsoft/unilm/tree/master/kosmos-2) ⭐ 22,193 | 🐛 684 | 🌐 Python | 📅 2026-01-23![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social\&label=Star)

* Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2303.05499) [\[code (eval)\]](https://github.com/IDEA-Research/GroundingDINO) ⭐ 10,515 | 🐛 325 | 🌐 Python | 📅 2024-08-12![Star](https://img.shields.io/github/stars/IDEA-Research/GroundingDINO.svg?style=social\&label=Star) (REC, OD, etc.)

* Ferret: Refer and Ground Anything Anywhere at Any Granularity [\[paper\]](https://arxiv.org/abs/2310.07704) [\[code\]](https://github.com/apple/ml-ferret) ⭐ 8,674 | 🐛 7 | 🌐 Python | 📅 2024-10-09![Star](https://img.shields.io/github/stars/apple/ml-ferret.svg?style=social\&label=Star)

* Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2308.12966) [\[demo\]](https://modelscope.cn/studios/qwen/Qwen-VL-Chat-Demo/summary) [\[code\]](https://github.com/QwenLM/Qwen-VL) ⭐ 6,727 | 🐛 324 | 🌐 Python | 📅 2024-08-07![Star](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social\&label=Star)

* SPHINX: The Joint Mixing of Weights, Tasks, and Visual Embeddings for Multi-modal Large Language Models (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2311.07575) [\[code\]](https://github.com/Alpha-VLLM/LLaMA2-Accessory) ⭐ 2,800 | 🐛 57 | 🌐 Python | 📅 2025-01-13![Star](https://img.shields.io/github/stars/Alpha-VLLM/LLaMA2-Accessory.svg?style=social\&label=Star)

* Universal Instance Perception as Object Discovery and Retrieval (CVPR 2023) [\[paper\]](https://arxiv.org/abs/2303.06674v2) [\[code\]](https://github.com/MasterBin-IIAU/UNINEXT) ⭐ 1,278 | 🐛 32 | 🌐 Python | 📅 2023-07-18![Star](https://img.shields.io/github/stars/MasterBin-IIAU/UNINEXT.svg?style=social\&label=Star) (REC, OVD, etc.)

* Shikra: Unleashing Multimodal LLM’s Referential Dialogue Magic (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2306.15195) [\[demo\]](http://demo.zhaozhang.net:7860/) [\[code\]](https://github.com/shikras/shikra) ⭐ 816 | 🐛 48 | 🌐 Python | 📅 2024-07-08![Star](https://img.shields.io/github/stars/shikras/shikra.svg?style=social\&label=Star)

* GRiT: A Generative Region-to-text Transformer for Object Understanding (arxiv 2022) [\[paper\]](https://arxiv.org/abs/2212.00280) [\[demo (colab)\]](https://colab.research.google.com/github/taskswithcode/GriT/blob/master/TWCGRiT.ipynb) [\[code\]](https://github.com/JialianW/GRiT) ⭐ 342 | 🐛 17 | 🌐 Python | 📅 2024-01-08![Star](https://img.shields.io/github/stars/JialianW/GRiT.svg?style=social\&label=Star)

* Contextual Object Detection with Multimodal Large Language Models (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2305.18279) [\[demo\]](https://huggingface.co/spaces/yuhangzang/ContextDet-Demo) [\[code\]](https://github.com/yuhangzang/ContextDET) ⭐ 261 | 🐛 7 | 🌐 Python | 📅 2024-10-14![Star](https://img.shields.io/github/stars/yuhangzang/ContextDET.svg?style=social\&label=Star)

* Griffon: Spelling out All Object Locations at Any Granularity with Large Language Models (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2311.14552) [\[code\]](https://github.com/jefferyZhan/Griffon) ⭐ 250 | 🐛 4 | 🌐 Python | 📅 2026-04-17![Star](https://img.shields.io/github/stars/jefferyZhan/Griffon.svg?style=social\&label=Star)

* Generative Region-Language Pretraining for Open-Ended Object Detection (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2403.10191) [\[code\]](https://github.com/FoundationVision/GenerateU) ⭐ 196 | 🐛 15 | 🌐 Python | 📅 2025-03-29![Star](https://img.shields.io/github/stars/FoundationVision/GenerateU.svg?style=social\&label=Star)

* Pink: Unveiling the Power of Referential Comprehension for Multi-modal LLMs (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2310.00582) [\[code\]](https://github.com/SY-Xuan/Pink) ⭐ 100 | 🐛 10 | 🌐 Python | 📅 2025-01-16![Star](https://img.shields.io/github/stars/SY-Xuan/Pink.svg?style=social\&label=Star)

* GROUNDHOG: Grounding Large Language Models to Holistic Segmentation (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2402.16846)

* LLMs Meet VLMs: Boost Open Vocabulary Object Detection with Fine-grained Descriptors (ICLR 2024) [\[paper\]](https://arxiv.org/abs/2402.04630)

## Open-Vocabulary Object Detection

Note that some generic object detection methods accepting language prompts are also listed here. Though they may not be evaluated on OVD benchmarks, they are essentially capable of this setting.

* Region-Aware Pretraining for Open-Vocabulary Object Detection with Vision Transformers (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Region-Aware_Pretraining_for_Open-Vocabulary_Object_Detection_With_Vision_Transformers_CVPR_2023_paper.pdf) [\[code\]](https://github.com/google-research/google-research/tree/master/fvlm/rovit) ⭐ 38,618 | 🐛 1,988 | 🌐 Jupyter Notebook | 📅 2026-08-25

* F-VLM: Open-Vocabulary Object Detection upon Frozen Vision and Language Models (ICLR 2023) [\[paper\]](https://openreview.net/pdf?id=MIMwy4kh9lf) [\[code\]](https://github.com/google-research/google-research/tree/master/fvlm) ⭐ 38,618 | 🐛 1,988 | 🌐 Jupyter Notebook | 📅 2026-08-25 [\[website\]](https://sites.google.com/view/f-vlm/home)

* YOLO-World: Real-Time Open-Vocabulary Object Detection (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2401.17270) [\[code\]](https://github.com/AILab-CVC/YOLO-World) ⭐ 6,529 | 🐛 422 | 🌐 Python | 📅 2025-02-26

* Open-vocabulary Object Detection via Vision and Language Knowledge Distillation (ICLR 2022) [\[paper\]](https://openreview.net/forum?id=lL3lnMbR4WU) [\[code\]](https://github.com/tensorflow/tpu/tree/master/models/official/detection/projects/vild) ⭐ 5,278 | 🐛 320 | 🌐 Jupyter Notebook | 📅 2026-06-22

* Scaling Open-Vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2306.09683) [\[code (jax)\]](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit) ⭐ 3,821 | 🐛 303 | 🌐 Python | 📅 2026-08-10

* Simple Open-Vocabulary Object Detection with Vision Transformers (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136700714.pdf) [\[code (jax)\]](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit) ⭐ 3,821 | 🐛 303 | 🌐 Python | 📅 2026-08-10 [\[code (huggingface)\]](https://huggingface.co/docs/transformers/model_doc/owlvit)

* Simple Open-Vocabulary Object Detection with Vision Transformers (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136700714.pdf) [\[code\]](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit) ⭐ 3,821 | 🐛 303 | 🌐 Python | 📅 2026-08-10

* T-Rex2: Towards Generic Object Detection via Text-Visual Prompt Synergy (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2403.14610) [\[code\]](https://github.com/IDEA-Research/T-Rex) ⭐ 2,699 | 🐛 16 | 🌐 Python | 📅 2025-10-15

* Real-time Transformer-based Open-Vocabulary Detection with Efficient Fusion Head (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2403.06892) [\[code\]](https://github.com/om-ai-lab/OmDet) ⭐ 1,393 | 🐛 6 | 🌐 Python | 📅 2026-03-12

* RegionCLIP: Region-Based Language-Image Pretraining (CVPR 2022) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2022/html/Zhong_RegionCLIP_Region-Based_Language-Image_Pretraining_CVPR_2022_paper.html) [\[code\]](https://github.com/microsoft/RegionCLIP) ⭐ 817 | 🐛 21 | 🌐 Python | 📅 2024-03-20

* A Simple Framework for Open-Vocabulary Segmentation and Detection (ICCV 2023) [\[paper\]](https://arxiv.org/abs/2303.08131) [\[code\]](https://github.com/IDEA-Research/OpenSeeD) ⭐ 764 | 🐛 21 | 🌐 Python | 📅 2024-01-22

* LLMDet: Learning Strong Open-Vocabulary Object Detectors under the Supervision of Large Language Models (CVPR 2025 Highlight) [\[paper\]](https://arxiv.org/abs/2501.18954) [\[code\]](https://github.com/iSEE-Laboratory/LLMDet) ⭐ 614 | 🐛 4 | 🌐 Python | 📅 2026-02-04

* OVLW-DETR: Open-Vocabulary Light-Weighted Detection Transformer (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2407.10655) [\[code (TBD)\]](https://github.com/Atten4Vis/LW-DETR) ⭐ 509 | 🐛 15 | 🌐 Python | 📅 2025-02-18

* OV-DINO: Unified Open-Vocabulary Detection with Language-Aware Selective Fusion (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2407.07844) [\[code\]](https://github.com/wanghao9610/OV-DINO) ⭐ 411 | 🐛 6 | 🌐 Python | 📅 2025-03-12

* Bridging the Gap between Object and Image-level Representations for Open-Vocabulary Detection (NeurIPS 2022) [\[paper\]](https://openreview.net/forum?id=aKXBrj0DHm) [\[code\]](https://github.com/hanoonaR/object-centric-ovd) ⭐ 296 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-10-12

* Open-Vocabulary Object Detection Using Captions (CVPR 2021) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zareian_Open-Vocabulary_Object_Detection_Using_Captions_CVPR_2021_paper.pdf) [\[code\]](https://github.com/alirezazareian/ovr-cnn) ⭐ 249 | 🐛 9 | 🌐 Python | 📅 2023-02-11

* Open-Vocabulary DETR with Conditional Matching (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136690107.pdf) [\[code\]](https://github.com/yuhangzang/OV-DETR) ⭐ 241 | 🐛 22 | 🌐 Python | 📅 2022-08-03

* CORA: Adapting CLIP for Open-Vocabulary Detection with Region Prompting and Anchor Pre-Matching (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_CORA_Adapting_CLIP_for_Open-Vocabulary_Detection_With_Region_Prompting_and_CVPR_2023_paper.pdf) [\[code\]](https://github.com/tgxs002/CORA) ⭐ 202 | 🐛 23 | 🌐 Python | 📅 2023-04-16

* Learning Object-Language Alignments for Open-Vocabulary Object Detection (ICLR 2023) [\[paper\]](https://openreview.net/pdf?id=mjHlitXvReu) [\[code\]](https://github.com/clin1223/VLDet) ⭐ 191 | 🐛 11 | 🌐 Python | 📅 2024-03-22

* Aligning Bag of Regions for Open-Vocabulary Object Detection (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Aligning_Bag_of_Regions_for_Open-Vocabulary_Object_Detection_CVPR_2023_paper.pdf) [\[code\]](https://github.com/wusize/ovdet) ⭐ 188 | 🐛 21 | 🌐 Python | 📅 2023-10-25

* Learning to Prompt for Open-Vocabulary Object Detection with Vision-Language Model (CVPR 2022) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Du_Learning_To_Prompt_for_Open-Vocabulary_Object_Detection_With_Vision-Language_Model_CVPR_2022_paper.pdf) [\[code\]](https://github.com/dyabel/detpro) ⭐ 188 | 🐛 15 | 🌐 Python | 📅 2022-11-07

* PromptDet: Towards Open-vocabulary Detection using Uncurated Images (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136690691.pdf) [\[website\]](https://fcjian.github.io/promptdet/) [\[code\]](https://github.com/fcjian/PromptDet) ⭐ 173 | 🐛 11 | 🌐 Python | 📅 2022-09-18

* Distilling DETR with Visual-Linguistic Knowledge for Open-Vocabulary Object Detection (ICCV 2023) [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Distilling_DETR_with_Visual-Linguistic_Knowledge_for_Open-Vocabulary_Object_Detection_ICCV_2023_paper.pdf) [\[code\]](https://github.com/hikvision-research/opera/tree/main/configs/dk-detr) ⭐ 168 | 🐛 28 | 🌐 Python | 📅 2023-11-05

* CoDet: Co-Occurrence Guided Region-Word Alignment for Open-Vocabulary Object Detection (NeurIPS 2023) [\[paper\]](https://arxiv.org/abs/2310.16667) [\[code\]](https://github.com/CVMI-Lab/CoDet) ⭐ 123 | 🐛 4 | 🌐 Python | 📅 2024-04-26

* SHiNe: Semantic Hierarchy Nexus for Open-vocabulary Object Detection (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2405.10053) [\[code\]](https://github.com/naver/shine) ⭐ 101 | 🐛 2 | 🌐 Python | 📅 2024-07-24

* Exploiting Unlabeled Data with Vision and Language Models for Object Detection (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136690156.pdf) [\[code\]](https://github.com/xiaofeng94/VL-PLM) ⭐ 96 | 🐛 12 | 🌐 Python | 📅 2024-01-16

* Multi-Modal Classifiers for Open-Vocabulary Object Detection (ICML 2023) [\[paper\]](http://arxiv.org/abs/2306.05493) [\[code (eval)\]](https://github.com/prannaykaul/mm-ovod) ⭐ 95 | 🐛 7 | 🌐 Python | 📅 2023-06-22

* OV-DQUO: Open-Vocabulary DETR with Denoising Text Query Training and Open-World Unknown Objects Supervision (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2405.17913) [\[code\]](https://github.com/xiaomoguhz/OV-DQUO) ⭐ 88 | 🐛 5 | 🌐 Python | 📅 2024-12-15

* Language-conditioned Detection Transformer (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2311.17902) [\[code\]](https://github.com/janghyuncho/DECOLA) ⭐ 86 | 🐛 3 | 🌐 Python | 📅 2024-06-17

* Toward Open Vocabulary Aerial Object Detection with CLIP-Activated Student-Teacher Learning (ECCV 2024) [\[paper\]](https://link.springer.com/chapter/10.1007/978-3-031-73016-0_25) [\[code\]](https://github.com/lizzy8587/CastDet) ⭐ 85 | 🐛 6 | 🌐 Python | 📅 2026-03-15

* Enhancing Novel Object Detection via Cooperative Foundational Models （WACV 2025) [\[paper\]](https://arxiv.org/abs/2311.12068) [\[code\]](https://github.com/rohit901/cooperative-foundational-models) ⭐ 84 | 🐛 2 | 🌐 Python | 📅 2026-01-02

* Dynamic-DINO: Fine-Grained Mixture of Experts Tuning for Real-time Open-Vocabulary Object Detection (ICCV 2025) [\[paper\]](https://arxiv.org/abs/2507.17436) [\[code\]](https://github.com/wengminghe/Dynamic-DINO) ⭐ 81 | 🐛 2 | 📅 2025-07-29

* The devil is in the fine-grained details: Evaluating open-vocabulary object detectors for fine-grained understanding (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2311.17518) [\[code\]](https://github.com/lorebianchi98/FG-OVD) ⭐ 68 | 🐛 2 | 🌐 Python | 📅 2025-04-04

* Open Vocabulary Object Detection with Pseudo Bounding-Box Labels (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136700263.pdf) [\[code\]](https://github.com/salesforce/PB-OVD) ⚠️ Archived

* Object-Aware Distillation Pyramid for Open-Vocabulary Object Detection (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Object-Aware_Distillation_Pyramid_for_Open-Vocabulary_Object_Detection_CVPR_2023_paper.pdf) [\[code\]](https://github.com/LutingWang/OADP) ⭐ 64 | 🐛 6 | 🌐 Python | 📅 2026-01-06

* How to Evaluate the Generalization of Detection? A Benchmark for Comprehensive Open-Vocabulary Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2308.13177) [\[dataset\]](https://github.com/om-ai-lab/OVDEval) ⭐ 63 | 🐛 1 | 🌐 Python | 📅 2026-04-10

* Retrieval-Augmented Open-Vocabulary Object Detection (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2404.05687) [\[code (TBD)\]](https://github.com/mlvlab/RALF) ⭐ 47 | 🐛 2 | 📅 2024-09-12

* Open-Vocabulary Instance Segmentation via Robust Cross-Modal Pseudo-Labeling (CVPR 2022) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2022/html/Huynh_Open-Vocabulary_Instance_Segmentation_via_Robust_Cross-Modal_Pseudo-Labeling_CVPR_2022_paper.html) [\[code\]](https://github.com/hbdat/cvpr22_cross_modal_pseudo_labeling) ⭐ 44 | 🐛 6 | 🌐 Python | 📅 2022-10-10

* DitHub: A Modular Framework for Incremental Open-Vocabulary Object Detection (NeurIPS 2025) [\[paper\]](https://arxiv.org/abs/2503.09271) [\[code\]](https://github.com/chiara-cap/DitHub) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2025-10-06

* Open-Vocabulary One-Stage Detection With Hierarchical Visual-Language Knowledge Distillation (CVPR 2022) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Open-Vocabulary_One-Stage_Detection_With_Hierarchical_Visual-Language_Knowledge_Distillation_CVPR_2022_paper.pdf) [\[code\]](https://github.com/mengqiDyangge/HierKD) ⭐ 39 | 🐛 9 | 🌐 Python | 📅 2022-08-25

* DST-Det: Simple Dynamic Self-Training for Open-Vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2310.01393) [\[code\]](https://github.com/xushilin1/dst-det) ⭐ 35 | 🐛 7 | 🌐 Python | 📅 2025-06-03

* CLIFF: Continual Latent Diffusion for Open-Vocabulary Object Detection (ECCV 2024) [\[paper\]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07221.pdf) [\[code\]](https://github.com/CUHK-AIM-Group/CLIFF) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2024-09-26

* CLIM: Contrastive Language-Image Mosaic for Region Representation (AAAI 2024) [\[paper\]](https://arxiv.org/abs/2312.11376) [\[code\]](https://github.com/wusize/CLIM) ⭐ 30 | 🐛 3 | 🌐 Python | 📅 2024-02-04

* Simple Image-level Classification Improves Open-vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2312.10439) [\[code\]](https://github.com/mala-lab/SIC-CADS) ⭐ 30 | 🐛 8 | 🌐 Python | 📅 2024-01-12

* LP-OVOD: Open-Vocabulary Object Detection by Linear Probing (WACV 2024) [\[paper\]](https://arxiv.org/abs/2310.17109) [\[code\]](https://github.com/VinAIResearch/LP-OVOD) ⭐ 30 | 🐛 6 | 🌐 Python | 📅 2024-07-23

* Open Vocabulary Object Detection with Proposal Mining and Prediction Equalization (arXiv 2022) [\[paper\]](https://arxiv.org/abs/2206.11134) [\[code\]](https://github.com/PeixianChen/MEDet) ⭐ 23 | 🐛 6 | 🌐 Python | 📅 2022-12-23

* Taming Self-Training for Open-Vocabulary Object Detection (CVPR 2024) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_Taming_Self-Training_for_Open-Vocabulary_Object_Detection_CVPR_2024_paper.pdf) [\[code\]](https://github.com/xiaofeng94/SAS-Det) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2023-12-30

* Localized Vision-Language Matching for Open-vocabulary Object Detection (GCPR 2022) [\[paper\]](https://arxiv.org/abs/2205.06160) [\[code\]](https://github.com/lmb-freiburg/locov) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2022-08-11

* Training-free Boost for Open-Vocabulary Object Detection with Confidence Aggregation (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2404.08603) [\[code\]](https://github.com/WarlockWendell/AggDet) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2024-04-15

* MarvelOVD: Marrying Object Recognition and Vision-Language Models for Robust Open-Vocabulary Object Detection (ECCV 2024) [\[paper\]](https://arxiv.org/abs/2407.21465) [\[code\]](https://github.com/wkfdb/MarvelOVD) ⭐ 12 | 🐛 5 | 🌐 Python | 📅 2024-11-04

* Benefit From Seen: Enhancing Open-Vocabulary Object Detection by Bridging Visual and Textual Co-Occurrence Knowledge (ICCV 2025)

* Cyclic Contrastive Knowledge Transfer for Open-Vocabulary Object Detection (ICLR 2025) [\[paper\]](https://arxiv.org/abs/2503.11005)

* A Hierarchical Semantic Distillation Framework for Open-Vocabulary Object Detection (TMM 2025) [\[paper\]](https://arxiv.org/abs/2503.10152)

* Sampling Bag of Views for Open-Vocabulary Object Detection (arxiv 2024) [\[paper\]](https://arxiv.org/pdf/2412.18273)

* Multimodal Inplace Prompt Tuning for Open-set Object Detection (ACM MM 2024) [\[paper\]](https://openreview.net/pdf?id=J6c0sRkWop)

* OpenSight: A Simple Open-Vocabulary Framework for LiDAR-Based Object Detection (ECCV 2024) [\[paper\]](https://link.springer.com/chapter/10.1007/978-3-031-72907-2_1)

* LaMI-DETR: Open-Vocabulary Detection with Language Model Instruction (ECCV 2024) [\[paper\]](https://arxiv.org/abs/2407.11335)

* Multi-modal Prompts with Feature Decoupling for Open-Vocabulary Object Detection (IJCAI 2024 Workshop) [\[paper\]](https://link.springer.com/chapter/10.1007/978-981-97-6125-8_14)

* Learning Background Prompts to Discover Implicit Knowledge for Open Vocabulary Object Detection (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2406.00510)

* Open-Vocabulary Object Detection via Neighboring Region Attention Alignment (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2405.08593)

* Exploring Region-Word Alignment in Built-in Detector for Open-Vocabulary Object Detection (CVPR 2024) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Exploring_Region-Word_Alignment_in_Built-in_Detector_for_Open-Vocabulary_Object_Detection_CVPR_2024_paper.html)

* DetCLIPv3: Towards Versatile Generative Open-vocabulary Object Detection (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2404.09216)

* Hyperbolic Learning with Synthetic Captions for Open-World Detection (CVPR 2024) [\[paper\]](https://arxiv.org/abs/2404.05016)

* InstaGen: Enhancing Object Detection by Training on Synthetic Dataset (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2402.05937)

* Weakly Supervised Open-Vocabulary Object Detection (AAAI 2024) [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/28127)

* ProxyDet: Synthesizing Proxy Novel Classes via Classwise Mixup for Open Vocabulary Object Detection (AAAI 2024) [\[paper\]](https://arxiv.org/abs/2312.07266)

* OpenSD: Unified Open-Vocabulary Segmentation and Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2312.06703) [\[code (TBD)\]](https://github.com/strongwolf/OpenSD)

* Boosting Segment Anything Model Towards Open-Vocabulary Learning (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2312.03628)

* Learning Pseudo-Labeler beyond Noun Concepts for Open-Vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2312.02103)

* Meta-Adapter: An Online Few-shot Learner for Vision-Language Model (NeurIPS 2023) [\[paper\]](https://arxiv.org/abs/2311.03774)

* Open-Vocabulary Object Detection with Meta Prompt Representation and Instance Contrastive Optimization (BMVC 2023) [\[paper\]](https://papers.bmvc2023.org/0093.pdf)

* Detection-Oriented Image-Text Pretraining for Open-Vocabulary Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2310.00161)

* Exploring Multi-Modal Contextual Knowledge for Open-Vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2308.15846)

* Improving Pseudo Labels for Open-Vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2308.06412)

* Unified Open-Vocabulary Dense Visual Prediction (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2307.08238)

* TIB: Detecting Unknown Objects Via Two-Stream Information Bottleneck (TPAMI 2023) [\[paper\]](https://ieeexplore.ieee.org/abstract/document/10275124)

* Fine-grained Visual-Text Prompt-Driven Self-Training for Open-Vocabulary Object Detection (TNNLS 2023) [\[paper\]](https://ieeexplore.ieee.org/abstract/document/10197240)

* Open-Vocabulary Object Detection via Scene Graph Discovery (ACM MM 2023) [\[paper\]](https://arxiv.org/abs/2307.03339)

* Three Ways to Improve Feature Alignment for Open Vocabulary Detection (arXiv 2023) [\[paper\]](https://arxiv.org/abs/2303.13518)

* Prompt-Guided Transformers for End-to-End Open-Vocabulary Object Detection (arXiv 2023) [\[paper\]](https://arxiv.org/abs/2303.14386)

* Open-Vocabulary Object Detection using Pseudo Caption Labels (arXiv 2023) [\[paper\]](https://arxiv.org/abs/2303.13040)

* What Makes Good Open-Vocabulary Detector: A Disassembling Perspective (KDD 2023 Workshop) [\[paper\]](https://arxiv.org/abs/2309.00227)

* Open-Vocabulary Object Detection With an Open Corpus (ICCV 2023) [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Open-Vocabulary_Object_Detection_With_an_Open_Corpus_ICCV_2023_paper.pdf)

* EdaDet: Open-Vocabulary Object Detection Using Early Dense Alignment (ICCV 2023) [\[paper\]](https://arxiv.org/abs/2309.01151) [\[website\]](https://chengshiest.github.io/edadet/)

* Contrastive Feature Masking Open-Vocabulary Vision Transformer (ICCV 2023) [\[paper\]](https://arxiv.org/abs/2309.00775)

* DetCLIPv2: Scalable Open-Vocabulary Object Detection Pre-training via Word-Region Alignment (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yao_DetCLIPv2_Scalable_Open-Vocabulary_Object_Detection_Pre-Training_via_Word-Region_Alignment_CVPR_2023_paper.pdf)

* Learning to Detect and Segment for Open Vocabulary Object Detection (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_To_Detect_and_Segment_for_Open_Vocabulary_Object_Detection_CVPR_2023_paper.pdf)

* OmDet: Large‐scale vision‐language multi‐dataset pre‐trainingwith multimodal detection network (IET Computer Vision 2023) [\[paper\]](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cvi2.12268)

* X-DETR: A Versatile Architecture for Instance-wise Vision-Language Tasks (ECCV 2022) [\[paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136960288.pdf)

## Referring Expression Comprehension/Visual Grounding

* OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework (ICML 2022) [\[paper\]](https://arxiv.org/abs/2202.03052) [\[code\]](https://github.com/OFA-Sys/OFA) ⭐ 2,557 | 🐛 113 | 🌐 Python | 📅 2024-04-24

* ONE-PEACE: Exploring One General Representation Model Toward Unlimited Modalities (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2305.11172) [\[code\]](https://github.com/OFA-Sys/ONE-PEACE) ⭐ 1,060 | 🐛 10 | 🌐 Python | 📅 2024-10-06

* MDETR -- Modulated Detection for End-to-End Multi-Modal Understanding (ICCV 2021) [\[paper\]](https://arxiv.org/abs/2104.12763) [\[website\]](https://ashkamath.github.io/mdetr_page/) [\[code\]](https://github.com/ashkamath/mdetr) ⭐ 1,052 | 🐛 32 | 🌐 Python | 📅 2022-10-03

* Unleashing Text-to-Image Diffusion Models for Visual Perception (ICCV 2023) [\[paper\]](https://arxiv.org/abs/2303.02153) [\[website\]](https://vpd.ivg-research.xyz/) [\[code\]](https://github.com/wl-zhao/VPD) ⭐ 541 | 🐛 32 | 🌐 Jupyter Notebook | 📅 2023-12-21

* Unified-IO: A Unified Model for Vision, Language, and Multi-Modal Tasks (ICLR 2023) [\[paper\]](https://arxiv.org/abs/2206.08916) [\[code (eval)\]](https://github.com/allenai/unified-io-inference) ⭐ 231 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2023-12-18

* PolyFormer: Referring Image Segmentation as Sequential Polygon Generation (CVPR 2023) [\[paper\]](https://arxiv.org/abs/2302.07387) [\[website\]](https://polyformer.github.io/) [\[code\]](https://github.com/amazon-science/polygon-transformer) ⭐ 165 | 🐛 3 | 🌐 Python | 📅 2023-07-19 [\[demo\]](https://huggingface.co/spaces/koajoel/PolyFormer)

* Pseudo-Q: Generating Pseudo Language Queries for Visual Grounding (CVPR 2022) [\[paper\]](https://arxiv.org/abs/2203.08481) [\[code\]](https://github.com/LeapLabTHU/Pseudo-Q) ⭐ 153 | 🐛 0 | 🌐 Python | 📅 2024-07-13

* SeqTR: A Simple yet Universal Network for Visual Grounding (ECCV 2022) [\[paper\]](https://arxiv.org/abs/2203.16265) [\[code\]](https://github.com/sean-zhuh/SeqTR) ⭐ 144 | 🐛 15 | 🌐 Python | 📅 2024-10-30

* CLIP-VG: Self-paced Curriculum Adapting of CLIP for Visual Grounding (TMM 2023) [\[paper\]](https://arxiv.org/abs/2305.08685) [\[code\]](https://github.com/linhuixiao/CLIP-VG) ⭐ 135 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2025-11-10

* Improving Visual Grounding with Visual-Linguistic Verification and Iterative Reasoning (CVPR 2022) [\[paper\]](https://arxiv.org/abs/2205.00272) [\[code\]](https://github.com/yangli18/VLTVG) ⭐ 98 | 🐛 7 | 🌐 Python | 📅 2022-12-02

* InstanceRefer: Cooperative Holistic Understanding for Visual Grounding on Point Clouds through Instance Multi-level Contextual Referring (ICCV 2021) [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yuan_InstanceRefer_Cooperative_Holistic_Understanding_for_Visual_Grounding_on_Point_Clouds_ICCV_2021_paper.pdf) [\[code\]](https://github.com/CurryYuan/InstanceRefer) ⭐ 74 | 🐛 5 | 🌐 Python | 📅 2025-03-22

* GroundVLP: Harnessing Zero-shot Visual Grounding from Vision-Language Pre-training and Open-Vocabulary Object Detection (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2312.15043) [\[code\]](https://github.com/om-ai-lab/GroundVLP) ⭐ 73 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-04-10

* Referring Transformer: A One-step Approach to Multi-task Visual Grounding (NeurIPS 2021) [\[paper\]](https://arxiv.org/abs/2106.03089) [\[code\]](https://github.com/ubc-vision/RefTR) ⭐ 67 | 🐛 4 | 🌐 Python | 📅 2022-05-26

* HiVG: Hierarchical Multimodal Fine-grained Modulation for Visual Grounding (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2404.13400) [\[code\]](https://github.com/linhuixiao/HiVG) ⭐ 66 | 🐛 5 | 🌐 Python | 📅 2025-11-10

* DQ-DETR: Dual Query Detection Transformer for Phrase Extraction and Grounding (AAAI 2023) [\[paper\]](https://arxiv.org/abs/2211.15516) [\[code\]](https://github.com/IDEA-Research/DQ-DETR) ⭐ 58 | 🐛 3 | 📅 2022-11-28

* TextRegion: Text-Aligned Region Tokens from Frozen Image-Text Models (arxiv 2025) [\[paper\]](https://arxiv.org/abs/2505.23769) [\[code\]](https://github.com/avaxiao/TextRegion) ⭐ 54 | 🐛 0 | 🌐 Python | 📅 2025-12-24

* Advancing Visual Grounding With Scene Knowledge: Benchmark and Method (CVPR 2023) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Song_Advancing_Visual_Grounding_With_Scene_Knowledge_Benchmark_and_Method_CVPR_2023_paper.pdf) [\[code\]](https://github.com/zhjohnchan/SK-VG) ⭐ 34 | 🐛 1 | 📅 2023-07-12

* OV-VG: A Benchmark for Open-Vocabulary Visual Grounding (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2310.14374) [\[code\]](https://github.com/cv516Buaa/OV-VG) ⭐ 31 | 🐛 10 | 📅 2024-03-25

* Context Disentangling and Prototype Inheriting for Robust Visual Grounding (TPAMI 2023) [\[paper\]](https://arxiv.org/abs/2312.11967) [\[code\]](https://github.com/WayneTomas/TransCP) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2025-05-08

* Visual Grounding with Transformers (ICME 2022) [\[paper\]](https://arxiv.org/abs/2105.04281) [\[code\]](https://github.com/usr922/vgtr) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2022-05-27

* Multi-Modal Dynamic Graph Transformer for Visual Grounding (CVPR 2022) [\[paper\]](https://github.com/iQua/M-DGT) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2022-03-26 [\[code\]](https://github.com/iQua/M-DGT) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2022-03-26

* MC-Bench: A Benchmark for Multi-Context Visual Grounding in the Era of MLLMs (arxiv 2025) [\[paper\]](https://arxiv.org/abs/2410.12332) [\[code\]](https://github.com/XuYunqiu/MC-Bench) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-10-22

* Continual Referring Expression Comprehension via Dual Modular Memorization (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2311.14909) [\[code\]](https://github.com/zackschen/DMM) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-11-15

* Multi-Perspective Cross-Modal Object Encoding for Referring Expression Comprehension (TIP 2025) [\[paper\]](https://ieeexplore.ieee.org/abstract/document/11206016?casa_token=mLtCg0GdYpYAAAAA:x_J4SaFGFXuqdJ7YIaP_0kalsfqPazC3DaufU_q8B93iLs2xq_zMfWfLqQMcoQOnX9afQkc1cCMc) [\[code\]](https://github.com/freedom6927/ELR_CCS) ⭐ 0 | 🐛 0 | 📅 2024-12-28

* LLM-wrapper: Black-Box Semantic-Aware Adaptation of Vision-Language Models for Referring Expression Comprehension (ECCV 2024 Workshop) [\[paper\]](https://arxiv.org/abs/2409.11919)

* Visual Grounding with Dual Knowledge Distillation (TCSVT 2024) [\[paper\]](https://ieeexplore.ieee.org/abstract/document/10543065)

* Learning from Models and Data for Visual Grounding (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2403.13804)

* Cycle-Consistency Learning for Captioning and Grounding (AAAI 2024) [\[paper\]](https://arxiv.org/abs/2312.15162)

* Zero-shot Referring Expression Comprehension via Structural Similarity Between Images and Captions (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2311.17048)

* ViLaM: A Vision-Language Model with Enhanced Visual Grounding and Generalization Capability (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2311.12327)

* VGDiffZero: Text-to-image Diffusion Models Can Be Zero-shot Visual Grounders (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2309.01141)

* Language-Guided Diffusion Model for Visual Grounding (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2308.09599) [\[code (TBD)\]](https://github.com/iQua/vgbase/tree/DiffusionVG)

* Fine-Grained Visual Prompting (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2306.04356)

* Focusing On Targets For Improving Weakly Supervised Visual Grounding (ICASSP 2023) [\[paper\]](https://arxiv.org/abs/2302.11252)

* Language Adaptive Weight Generation for Multi-task Visual Grounding (CVPR 2023) [\[paper\]](https://arxiv.org/abs/2306.04652)

* From Coarse to Fine-grained Concept based Discrimination for Phrase Detection (CVPR 2023 Workshop) [\[paper\]](https://arxiv.org/abs/2112.03237)

* Referring Expression Comprehension Using Language Adaptive Inference (AAAI 2023) [\[paper\]](https://arxiv.org/abs/2306.04451)

* One for All: One-stage Referring Expression Comprehension with Dynamic Reasoning (arxiv 2022) [\[paper\]](https://arxiv.org/abs/2208.00361)

* Self-paced Multi-grained Cross-modal Interaction Modeling for Referring Expression Comprehension (arxiv 2022) [\[paper\]](https://arxiv.org/abs/2204.09957)

* SiRi: A Simple Selective Retraining Mechanism for Transformer-based Visual Grounding (ECCV 2022) [\[paper\]](https://arxiv.org/abs/2207.13325)

* Towards Unifying Reference Expression Generation and Comprehension (EMNLP 2022) [\[paper\]](https://arxiv.org/abs/2210.13076)

* Correspondence Matters for Video Referring Expression Comprehension (ACM MM 2022) [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3503161.3547756)

* Towards Language-guided Visual Recognition via Dynamic Convolutions (arxiv 2021) [\[paper\]](https://arxiv.org/abs/2110.08797)

<!-- ![Star](https://img.shields.io/github/stars/ashkamath/mdetr.svg?style=social&label=Star) -->

* UNITER: UNiversal Image-TExt Representation Learning (ECCV 2020) [\[paper\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750103.pdf) [\[code\]](https://github.com/ChenRocks/UNITER) ⭐ 799 | 🐛 46 | 🌐 Python | 📅 2021-06-30

* MAttNet: Modular Attention Network for Referring Expression Comprehension (CVPR 2018) [\[paper\]](https://arxiv.org/abs/1801.08186) [\[code\]](https://github.com/lichengunc/MAttNet) ⭐ 299 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2022-11-29

* A Fast and Accurate One-Stage Approach to Visual Grounding (ICCV 2019) [\[paper\]](https://arxiv.org/abs/1908.06354) [\[code\]](https://github.com/zyang-ur/onestage_grounding) ⭐ 149 | 🐛 3 | 🌐 Python | 📅 2020-11-18

* Multi-task Collaborative Network for Joint Referring Expression Comprehension and Segmentation (CVPR 2020) [\[paper\]](https://arxiv.org/abs/2003.08813) [\[code\]](https://github.com/luogen1996/MCN) ⭐ 139 | 🐛 7 | 🌐 Python | 📅 2022-08-04

* Large-Scale Adversarial Training for Vision-and-Language Representation Learning (NeurIPS 2020) [\[paper\]](https://arxiv.org/abs/2006.06195) [\[code\]](https://github.com/zhegan27/VILLA) ⭐ 119 | 🐛 7 | 🌐 Python | 📅 2021-01-13 [\[poster\]](https://zhegan27.github.io/Papers/villa_poster.pdf)

* Improving One-stage Visual Grounding by Recursive Sub-query Construction (ECCV 2020) [\[paper\]](https://arxiv.org/abs/2008.01059) [\[code\]](https://github.com/zyang-ur/ReSC) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2021-09-30

* Look Before You Leap: Learning Landmark Features for One-Stage Visual Grounding (CVPR 2021) [\[paper\]](https://arxiv.org/abs/2104.04386) [\[code\]](https://github.com/svip-lab/LBYLNet) ⭐ 51 | 🐛 3 | 🌐 Python | 📅 2021-08-31

* Relation-aware Instance Refinement for Weakly Supervised Visual Grounding (CVPR 2021) [\[paper\]](https://arxiv.org/abs/2103.12989) [\[code\]](https://github.com/youngfly11/ReIR-WeaklyGrounding.pytorch) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2021-10-09

* Interactive Visual Grounding of Referring Expressions for Human-Robot Interaction (RSS 2018) [\[paper\]](https://www.roboticsproceedings.org/rss14/p28.pdf) [\[code\]](https://github.com/MohitShridhar/ingress) ⭐ 26 | 🐛 2 | 🌐 Shell | 📅 2018-11-16

* Rethinking Diversified and Discriminative Proposal Generation for Visual Grounding (IJCAI 2018) [\[paper\]](https://arxiv.org/abs/1805.03508) [\[code\]](https://github.com/XiangChenchao/DDPN) ⭐ 23 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2018-06-27

* Co-Grounding Networks with Semantic Attention for Referring Expression Comprehension in Videos (CVPR 2021) [\[paper\]](https://arxiv.org/abs/2103.12346) [\[code\]](https://github.com/SijieSong/CVPR21-Cogrounding_semantic_attention) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2021-07-13

* A Real-Time Cross-modality Correlation Filtering Method for Referring
  Expression Comprehension (CVPR 2020) [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liao_A_Real-Time_Cross-Modality_Correlation_Filtering_Method_for_Referring_Expression_Comprehension_CVPR_2020_paper.pdf)

* Dynamic Graph Attention for Referring Expression Comprehension (ICCV 2019) [\[paper\]](https://openaccess.thecvf.com/content_ICCV_2019/html/Yang_Dynamic_Graph_Attention_for_Referring_Expression_Comprehension_ICCV_2019_paper.html)

* Neighbourhood Watch: Referring Expression Comprehension via Language-Guided Graph Attention Networks (CVPR 2019) [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Neighbourhood_Watch_Referring_Expression_Comprehension_via_Language-Guided_Graph_Attention_Networks_CVPR_2019_paper.pdf)

* Comprehension-Guided Referring Expressions (CVPR 2017) [\[paper\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Luo_Comprehension-Guided_Referring_Expressions_CVPR_2017_paper.pdf)

* Modeling Context Between Objects for Referring Expression Understanding (ECCV 2016) [\[paper\]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_48)

# Awesome Datasets

This part is still in progress.

## Datasets for DOD and Similar Tasks

| Name          |                                                                           Paper                                                                          |                Website               |                                                Code                                                | Train/Eval | Notes |
| :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------: | :------------------------------------------------------------------------------------------------: | :--------: | :---: |
| **$D^3$**     |           [Described Object Detection: Liberating Object Detection with Flexible Expressions (NeurIPS 2023)](https://arxiv.org/abs/2307.12813)           |                   -                  |       [Github](https://github.com/shikras/d-cube) ⭐ 138 \| 🐛 7 \| 🌐 Python \| 📅 2024-03-20      |  eval only |   -   |
| **OmniLabel** |                  [OmniLabel: A Challenging Benchmark for Language-Based Object Detection (ICCV 2023)](https://arxiv.org/abs/2304.11463)                  | [Project](https://www.omnilabel.org) | [Github](https://github.com/samschulter/omnilabeltools) ⭐ 23 \| 🐛 4 \| 🌐 Python \| 📅 2025-02-01 |  eval only |   -   |
| **OVDEval**   | [How to Evaluate the Generalization of Detection? A Benchmark for Comprehensive Open-Vocabulary Detection (AAAI 2024)](https://arxiv.org/pdf/2308.13177) |                   -                  |      [Github](https://github.com/om-ai-lab/OVDEval) ⭐ 63 \| 🐛 1 \| 🌐 Python \| 📅 2026-04-10     |  eval only |   -   |

## Detection Datasets

| Name             |                                                                                                                 Paper                                                                                                                 |   Task  |                              Website                             |                                                    Code                                                    |             Train/Eval             |                                              Notes                                             |
| :--------------- | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----: | :--------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------: | :--------------------------------: | :--------------------------------------------------------------------------------------------: |
| **Bamboo**       |                                                         [Bamboo: Building Mega-Scale Vision Dataset Continually with Human-Machine Synergy](https://arxiv.org/abs/2203.07845)                                                         |    OD   |                                 -                                |       [Github](https://github.com/ZhangYuanhan-AI/Bamboo) ⭐ 180 \| 🐛 4 \| 🌐 Python \| 📅 2024-04-07      |        detector pretraining        | build upon public datasets; 69M image classification annotations and 32M object bounding boxes |
| **BigDetection** |                                                [BigDetection: A Large-scale Benchmark for Improved Object Detector Pre-training (CVPR 2022 Workshop)](https://arxiv.org/abs/2203.13249)                                               |    OD   |                                 -                                |    [Github](https://github.com/amazon-science/bigdetection) ⭐ 399 \| 🐛 6 \| 🌐 Python \| 📅 2024-10-23    |        detector pretraining        |                                                -                                               |
| **Object365**    | [Objects365: A Large-Scale, High-Quality Dataset for Object Detection (ICCV 2019)](https://openaccess.thecvf.com/content_ICCV_2019/html/Shao_Objects365_A_Large-Scale_High-Quality_Dataset_for_Object_Detection_ICCV_2019_paper.html) |    OD   |                [Link](https://www.objects365.org)                |                [BAAI platform for download](https://data.baai.ac.cn/details/Objects365_2020)               | detector pretraining; train & eval |                                                -                                               |
| **OpenImages**   |                                                                                                                   -                                                                                                                   |    OD   | [Link](https://storage.googleapis.com/openimages/web/index.html) |                [Tensorflow API](https://www.tensorflow.org/datasets/catalog/open_images_v4)                |            train & eval            |                                                -                                               |
| **LVIS**         |                                                               [LVIS: A Dataset for Large Vocabulary Instance Segmentation (CVPR 2019)](https://arxiv.org/abs/1908.03195)                                                              | OD\&OVD |               [Link](https://www.lvisdataset.org/)               |       [Github](https://github.com/lvis-dataset/lvis-api) ⭐ 429 \| 🐛 13 \| 🌐 Python \| 📅 2024-02-21      |            train & eval            |                       long-tail; federated annotation; also used for OVD                       |
| **COCO**         |                                                                        [Microsoft COCO: Common Objects in Context (ECCV 2014)](https://arxiv.org/abs/1405.0312)                                                                       | OD\&OVD |               [Link](https://cocodataset.org/#home)              | [Github](https://github.com/cocodataset/cocoapi) ⭐ 6,385 \| 🐛 471 \| 🌐 Jupyter Notebook \| 📅 2024-04-17 |            train & eval            |                                        also used for OVD                                       |
| **VOC**          |                                                      [The PASCAL Visual Object Classes (VOC) Challenge (IJCV 2010)](https://link.springer.com/article/10.1007/s11263-009-0275-4)                                                      |    OD   |     [Link](http://host.robots.ox.ac.uk/pascal/VOC/index.html)    |                                                      -                                                     |            train & eval            |                                                -                                               |

## Grounding Datasets

| Name                                           |                                                                                                                   Paper                                                                                                                  |                    Task                   |                                 Website                                 |                                                                                                                     Code                                                                                                                     |                 Train/Eval                 |                                       Notes                                      |
| :--------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------: | :---------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------: | :------------------------------------------------------------------------------: |
| **GRIT (Ground-and-Refer Instruction-Tuning)** |                                                              [Ferret: Refer and Ground Anything Anywhere at Any Granularity (arxiv 2023)](https://arxiv.org/abs/2310.07704)                                                              |              ground-and-refer             |                                    -                                    |                                                                          [Github](https://github.com/apple/ml-ferret) ⭐ 8,674 \| 🐛 7 \| 🌐 Python \| 📅 2024-10-09                                                                          |             instruction tuning             |                                   1.1M samples                                   |
| **Ferret-Bench**                               |                                                              [Ferret: Refer and Ground Anything Anywhere at Any Granularity (arxiv 2023)](https://arxiv.org/abs/2310.07704)                                                              |              ground-and-refer             |                                    -                                    |                                                                          [Github](https://github.com/apple/ml-ferret) ⭐ 8,674 \| 🐛 7 \| 🌐 Python \| 📅 2024-10-09                                                                          |                  eval only                 |                                         -                                        |
| **GRIT (Grounded Image-Text)**                 |                                                            [Kosmos-2: Grounding Multimodal Large Language Models to the World (arxiv 2023)](https://arxiv.org/abs/2306.14824)                                                            | visual grounding (REC & Phrase Grounding) |                                    -                                    | [Github](https://github.com/microsoft/unilm/tree/master/kosmos-2#grit-large-scale-training-corpus-of-grounded-image-text-pairs) ⭐ 22,193 \| 🐛 684 \| 🌐 Python \| 📅 2026-01-23 [Huggingface](https://huggingface.co/datasets/zzliang/GRIT) |                 train only                 | created based on image-text pairs from a subset of COYO-700M and LAION-2B; 20.5M |
| **SK-VG**                                      | [Advancing Visual Grounding With Scene Knowledge: Benchmark and Method (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Song_Advancing_Visual_Grounding_With_Scene_Knowledge_Benchmark_and_Method_CVPR_2023_paper.pdf) |                    REC                    |                                    -                                    |                                                                                  [Github](https://github.com/zhjohnchan/SK-VG) ⭐ 34 \| 🐛 1 \| 📅 2023-07-12                                                                                 |                train & eval                |                  scene knowledge in natural language is required                 |
| **GRiT (General Robust Image Task)**           |                                                                        [GRIT: General Robust Image Task Benchmark (arxiv 2022)](https://arxiv.org/abs/2204.13653)                                                                        |                    REC                    |              [Link](https://allenai.org/project/grit/home)              |                                                                    [Github](https://github.com/allenai/grit_official) ⭐ 56 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2023-03-29                                                                   |                  eval only                 |                                         -                                        |
| **Cops-Ref**                                   |                                                   [Cops-Ref: A new Dataset and Task on Compositional Referring Expression Comprehension (CVPR 2020)](https://arxiv.org/abs/2003.00403)                                                   |             Compositional REC             |                                    -                                    |                                                                               [Github](https://github.com/zfchenUnique/Cops-Ref) ⭐ 27 \| 🐛 3 \| 📅 2024-07-11                                                                               |                  eval only                 |                                 A variant of REC                                 |
| **Visual Genome**                              |                                    [Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations (IJCV 2017)](https://link.springer.com/article/10.1007/s11263-016-0981-7)                                   |           OD & Phrase Grounding           | [Link](https://homes.cs.washington.edu/~ranjay/visualgenome/index.html) |                                                         [Github](https://github.com/ranjaykrishna/visual_genome_python_driver) ⭐ 371 \| 🐛 20 \| 🌐 Jupyter Notebook \| 📅 2023-09-21                                                        | multiple multi-modal tasks (including REC) |                                                                                  |
| **RefCOCOg**                                   |                   [Generation and Comprehension of Unambiguous Object Descriptions (CVPR 2016)](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Mao_Generation_and_Comprehension_CVPR_2016_paper.pdf)                  |                    REC                    |                                    -                                    |                                                               [Github](https://github.com/mjhucla/Google_Refexp_toolbox) ⭐ 166 \| 🐛 3 \| 🌐 Jupyter Notebook \| 📅 2017-03-01                                                               |                train & eval                |                                 images from COCO                                 |
| **RefClef**                                    |                                                            [ReferItGame: Referring to Objects in Photographs of Natural Scenes (EMNLP 2014)](https://arxiv.org/abs/2204.13653)                                                           |                    REC                    |                                    -                                    |                                                                     [Github](https://github.com/lichengunc/refer) ⭐ 576 \| 🐛 20 \| 🌐 Jupyter Notebook \| 📅 2024-08-27                                                                     |                train & eval                |                                         -                                        |
| **RefCOCO+**                                   |                                                            [ReferItGame: Referring to Objects in Photographs of Natural Scenes (EMNLP 2014)](https://arxiv.org/abs/2204.13653)                                                           |                    REC                    |                                    -                                    |                                                                     [Github](https://github.com/lichengunc/refer) ⭐ 576 \| 🐛 20 \| 🌐 Jupyter Notebook \| 📅 2024-08-27                                                                     |                train & eval                |                                 images from COCO                                 |
| **RefCOCO**                                    |                                                            [ReferItGame: Referring to Objects in Photographs of Natural Scenes (EMNLP 2014)](https://arxiv.org/abs/2204.13653)                                                           |                    REC                    |                                    -                                    |                                                                     [Github](https://github.com/lichengunc/refer) ⭐ 576 \| 🐛 20 \| 🌐 Jupyter Notebook \| 📅 2024-08-27                                                                     |                train & eval                |                                 images from COCO                                 |

# Related Surveys and Resources

Some survey papers regarding relevant tasks (open-vocabulary learning, etc.)

* Towards Open Vocabulary Learning: A Survey (TPAMI 2024) [\[paper\]](https://arxiv.org/abs/2306.15880) [\[repo\]](https://github.com/jianzongwu/Awesome-Open-Vocabulary) ⭐ 1,002 | 🐛 2 | 📅 2026-05-12
* Towards Visual Grounding: A Survey (arxiv 2024) [\[paper\]](https://arxiv.org/abs/2412.20206) [\[repo\]](https://github.com/linhuixiao/Awesome-Visual-Grounding) ⭐ 324 | 🐛 4 | 🌐 Shell | 📅 2025-11-18
* A Survey on Open-Vocabulary Detection and Segmentation: Past, Present, and Future (arxiv 2023) [\[paper\]](https://arxiv.org/abs/2307.09220)
* Referring Expression Comprehension: A Survey of Methods and Datasets (TMM 2020) [\[paper\]](https://arxiv.org/abs/2007.09554)

Some similar github repos like awesome lists:

* [TheShadow29/awesome-grounding](https://github.com/TheShadow29/awesome-grounding) ⭐ 1,127 | 🐛 3 | 📅 2025-09-21: A list of visual grounding (REC) paper roadmaps and datasets.
* [MarkMoHR/Awesome-Referring-Image-Segmentation](https://github.com/MarkMoHR/Awesome-Referring-Image-Segmentation) ⭐ 828 | 🐛 2 | 📅 2026-01-28: A list of Referring Expression Segmentation (RES) papers and resources.
* [witnessai/Awesome-Open-Vocabulary-Object-Detection](https://github.com/witnessai/Awesome-Open-Vocabulary-Object-Detection/blob/main/README.md?plain=1) ⭐ 423 | 🐛 0 | 📅 2025-05-13: A list of Open-Vocabulary Object Detection papers.
* [daqingliu/awesome-rec](https://github.com/daqingliu/awesome-rec) ⭐ 46 | 🐛 0 | 📅 2021-05-13: A curated list of REC papers. Not maintained in recent years.
* [qy-feng/awesome-visual-grounding](https://github.com/qy-feng/awesome-visual-grounding): A curated list of visual grounding papers. Not maintained in recent years.

# Acknowledgement

The structure and format of this repo is inspired by [BradyFU/Awesome-Multimodal-Large-Language-Models](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) ⭐ 17,990 | 🐛 110 | 📅 2026-08-21.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
