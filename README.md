# Lung Cancer Detection Using Pretrained VGG16 Model

This model is built upon the pretrained model VGG16 built in keras library. It can distinguish between three types of lung status (e.g., adenocarcinoma infected lung, normal lung, squamous cell carcinoma infected lung) using histopathological coloured images.

## Data Description

This dataset contains 25,000 histopathological images with 5 classes. All images are 768 x 768 pixels in size and are in jpeg file format. The images were generated from an original sample of HIPAA compliant and validated sources, consisting of 750 total images of lung tissue (250 benign lung tissue, 250 lung adenocarcinomas, and 250 lung squamous cell carcinomas) and 500 total images of colon tissue (250 benign colon tissue and 250 colon adenocarcinomas) and augmented to 25,000 using the Augmentor package.

There are five classes in the dataset, each with 5,000 images, being:
- Lung benign tissue
- Lung adenocarcinoma
- Lung squamous cell carcinoma
- Colon adenocarcinoma
- Colon benign tissue

## Reference

Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM. Lung and Colon Cancer Histopathological Image Dataset (LC25000). arXiv:1912.12142v1 [eess.IV], 2019

## Relevant Links

- [arXiv:1912.12142v1](https://arxiv.org/abs/1912.12142v1)
- [GitHub Repository](https://github.com/tampapath/lung_colon_image_set)
```
