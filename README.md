<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1B2A,1B3A5C,2E6DA4&height=200&section=header&text=Youcef%20Abdelhalim&fontSize=48&fontColor=FFFFFF&fontAlignY=38&desc=AI%20Engineer%20%7C%20Computer%20Vision%20Researcher&descSize=16&descAlignY=58&descColor=8DBBE8" width="100%"/>

</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=800&color=2E9FD4&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Vision+Transformers+%7C+Hybrid+CNN%E2%80%93Transformer+Architectures;Medical+Imaging+%7C+Explainable+AI+%7C+Multimodal+Perception)](https://git.io/typing-svg)

</div>

---

## 👤 About Me

```python
researcher = {
    "name"       : "Youcef Abdelhalim",
    "degree"     : "MSc Artificial Intelligence (M2) — Mohamed Khider University, Biskra",
    "focus"      : ["Medical Imaging", "Semantic & Instance Segmentation",
                    "Explainable AI (XAI)", "Multimodal Perception"],
    "publication": "ICECET 2026 — Post-Hoc Explainability for Generative Volumetric VLMs",
    "club"       : "Debug Scientific Club",
    "location"   : "Biskra, Algeria 🇩🇿",
}
```

I build interpretable, high-performance vision systems — from low-level **CUDA kernels** to **multimodal RAG pipelines**.  
My research sits at the intersection of **deep learning transparency** and **clinical relevance**, with a focus on making model decisions trustworthy in medical contexts.

---

## 🏆 Highlights

| 🥇 | National Winner — Huawei ICT Competition, Cloud Track (2025) |
|---|---|
| 🥉 | 3rd Place — National AI Hackathon, University of El Oued (2025) |
| 📄 | First-Author Paper accepted @ **ICECET 2026**, Rome, Italy |
| 🛰️ | Team Lead — NASA Space Apps Challenge (2025) |
| 🥉 | 3rd Place — CSBIS AI Competition, University of Mohamed Khider (2023) |

---

## 🔬 Featured Projects

<details>
<summary><b>🧠 CT & MRI Multimodal Explainability for Generative Volumetric Models</b></summary>
<br/>

> *Tied to the ICECET 2026 accepted paper.*

- Adapted post-hoc XAI techniques to **generative volumetric multimodal models**
- Developed **modality-specific attribution alignment** and volumetric saliency aggregation across slices
- Implemented **gradient-based & perturbation-based attributions** tailored to generative outputs
- Consistency regularization across neighboring slices + anatomical overlay visualizations
- Reproducible evaluation: quantitative faithfulness/localization metrics + expert qualitative assessment
- Stack: `PyTorch` · `Captum` · `NiBabel` · `SimpleITK`

</details>

<details>
<summary><b>🔍 Prompt-Guided Image Segmentation (PromptSeg)</b></summary>
<br/>

- Lightweight multimodal framework generating **pixel-accurate masks from free-text prompts**
- Fused frozen **DINOv2** visual features with **CLIP** text embeddings via trainable SAM-based decoder (~9.3M params)
- Trained on **RefCOCO** with multi-scale FPN fusion → best validation **IoU: 0.42**
- Documented failure modes; proposed **LoRA fine-tuning** + token-level text fusion improvements

</details>

<details>
<summary><b>⚡ CuVision Engine — Native C++/CUDA CV Framework</b></summary>
<br/>

- Low-latency CV framework targeting **cuDNN & cuBLAS primitives directly** — zero framework overhead
- **20 custom CUDA kernels**: classification, RetinaNet-based detection (FPN), Attention U-Net (ASPP)
- Designed for edge deployment on **NVIDIA Jetson** hardware

</details>

<details>
<summary><b>🗂️ Multimodal RAG Platform</b></summary>
<br/>

- Modular RAG pipeline over **text + images + audio**
- Integrated **Florence-2** (captioning) · **Whisper** (transcription) · **DocLayout-YOLO** (parsing)
- **E5-small-v2** embeddings + **FAISS** retrieval → **94% faithfulness**, **250ms** avg latency
- Deployed via **Docker** with **MLflow** tracking + LLM-as-a-judge evaluation suite

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Core**  
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Deep Learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**MLOps & Deployment**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**Research Tools**  
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

</div>

---

## 📊 Research Interests

```
Computer Vision  ████████████████████  Semantic / Instance Segmentation
Medical Imaging  ████████████████░░░░  3D Volumetric Analysis
Explainable AI   ███████████████░░░░░  Grad-CAM · IG · Guided Backprop
Multimodal AI    ████████████░░░░░░░░  Vision-Language · RAG · CLIP/DINO
Edge Systems     ██████████░░░░░░░░░░  CUDA · cuDNN · Jetson Deployment
```

---

## 📫 Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-abdelhalim__youcef%40univ--biskra.dz-0D1B2A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdelhalim_youcef@univ-biskra.dz)
[![Kaggle](https://img.shields.io/badge/Kaggle-abdelhalimyoucef-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/abdelhalimyoucef)

</div>

---

## 📈 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=halim7youcef&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=halim7youcef&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=halim7youcef&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1B2A,1B3A5C,2E6DA4&height=100&section=footer" width="100%"/>

</div>
