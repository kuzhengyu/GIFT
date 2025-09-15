# GIFT: A Generative Imagined Fine-Tuning Framework for Visual Place Recognition

This repository contains the official dataset for our paper: **"GIFT: A Generative Imagined Fine-Tuning Framework for Visual Place Recognition"**.

## Datasets

We provide the complete set of synthesized images used in our experiments. The data is generated from three source cities (LosAngeles, Medellin, and BuenosAires) from the GSV-Cities dataset, under six distinct environmental and illumination conditions.

- **Total Images**: ~140,000
- **Conditions**: Snow, Fog, Sun, Night, Rain, Overcast
- **Source Cities**: LosAngeles, Medellin, BuenosAires

You can download the full dataset from the following link: https://drive.google.com/drive/folders/1UyPd49ASx6WDTdjYS6fYX7_AAficnnQS?usp=sharing


## Training and Evaluation
Our framework is designed to be easily integrated with existing VPR pipelines. The training procedures used in our paper are heavily based on the excellent official implementations of **BoQ** and **VLAD-BuFF**.

-   **For BoQ models**: Please refer to the official [Bag-of-Queries (BoQ)](https://github.com/amaralibey`/Bag-of-Queries) repository.
-   **For VLAD-BuFF models**: Please refer to the official [VLAD-BuFF](https://github.com/Ahmedest61/VLAD-BuFF) repository.
-   **For GSV-Cities dataset**：Please refer to the official [GSV-Cities](https://github.com/amaralibey/gsv-cities) repository.


Our work builds upon these strong foundations, and we extend our sincere gratitude to the authors for their significant contributions to the VPR community and for making their code publicly available.
