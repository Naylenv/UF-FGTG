# A User-Friendly Framework for Generating Model-Preferred Prompts in Text-to-Image Synthesis

This is a PyTorch implementation for the paper accepted by AAAI 2024

> Nailei Hei, Qianyu Guo, Zihao Wang, Yan Wang, Haofen Wang, Wenqiang Zhang

# Overview

Well-designed prompts have demonstrated the potential to guide text-to-image models in generating amazing images. Although existing prompt engineering methods can provide high-level guidance, it is challenging for novice users to achieve the desired results by manually entering prompts due to a discrepancy between novice-user-input prompts and the model-preferred prompts. To bridge the distribution gap between user input behavior and model training datasets, we first construct a novel Coarse-Fine Granularity Prompts dataset (CFP) and propose a novel User-Friendly Fine-Grained Text Generation framework (UF-FGTG) for automated prompt optimization. For CFP, we construct a novel dataset for text-to-image tasks that combines coarse and fine-grained prompts to facilitate the development of automated prompt generation methods. For UF-FGTG, we propose a novel framework that automatically translates user-input prompts into model-preferred prompts. Specifically, we propose a prompt refiner that continually rewrites prompts to empower users to select results that align with their unique needs. Meanwhile, we integrate image-related loss functions from the text-to-image model into the training process of text generation to generate model-preferred prompts. Additionally, we propose an adaptive feature extraction module to ensure diversity in the generated results. Experiments demonstrate that our approach is capable of generating more visually appealing and diverse images than previous state-of-the-art methods, achieving an average improvement of $5\%$ across six quality and aesthetic metrics.

# Reference

If you find our codes and datasets useful for your research, please cite:

```
@inproceedings{Hei2024UF-FGTG,
  title={A User-Friendly Framework for Generating Model-Preferred Prompts in Text-to-Image Synthesis},
  author={Nailei Hei and Qianyu Guo and Zihao Wang and Yan Wang and Haofen Wang and Wenqiang Zhang},
  year={2024},
  booktitle={The 38th Annual AAAI Conference on Artificial Intelligence}
}
```
