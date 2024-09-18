# 🚀Parallel Inference and traing Diffusion model
*Read this in [Chinese](README_CN.md).*

This repository serves as a review of parallel inference and training for diffusion models (both UNet and Transformer backbones), using my custom methods alongside other open-source repositories.

I have tested all open-source methods for parallel inference and training of diffusion models, listed them below, and conducted comparative experiments in the experiments section to evaluate their performance.

Additionally, based on these foundations, I developed my own parallelization solutions and extended support for more models.

## ⚙️ Structure
```bash
.
├── docs
├── examples #examples not for mine but also distrifuser,xdit,megatron-lm(tensor parallel),deepspeed(ulysses),Ring attention...
├── experiments # performance comparative experiment between all the methods
├── infer 
├── scripts #bash for quick start
├── thirdparty
└── train
```
## 🛠️ Prerequisites
```bash
pip install distrifuser
```

## 🐼 Usage Example

```bash 
sh scripts/run_distrifuser_sdxl.py
```