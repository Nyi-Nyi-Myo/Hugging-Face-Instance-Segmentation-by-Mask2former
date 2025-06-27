# Hugging-Face Instance Segmentation by Mask2former

[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-3B4252?style=flat&logo=huggingface&logoColor=)](https://huggingface.co/)
![Static Badge](https://img.shields.io/badge/Instance-Segmentation-cyan)
![Static Badge](https://img.shields.io/badge/Mask2former-8A2BE2)

Instance Segmentation for the caps of marker pens using **Mask2former** Deep Learning Algorithm in **Hugging Face**.

## Dataset
- Marker Pens' Caps (Custom)

Annotation Type - Polygon

Class &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &ensp; - CAP

## Methodology
![Hugging Face](https://img.shields.io/badge/-HuggingFace-yellow?style=for-the-badge&logo=HuggingFace&logoColor=black&logoHeight=20)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

- `"facebook/mask2former-swin-small-coco-instance"` Model
- Used Trainer from transformers, epochs=5
- Used COCOeval for evaluation

## Results
- ### Evaluation of trained model

Precision: `0.7497`

Recall: `0.7767`

F1 Score: `0.7629`

---
⭐ Example Images results in `mask2former_Huggingface_seg.ipynb`
