# Breast Cancer Histopathology Classification (Hybrid CNN–Transformer Model)

**Project Creator:** Shakiba Zakeri Nejad  

Breast cancer remains one of the leading causes of death among women worldwide, and early detection plays a vital role in reducing mortality.  
This project presents a hybrid deep learning model that combines the strengths of Transformers, Convolutional Neural Networks (CNNs), and fully connected layers for automated classification of breast cancer histopathology images.

## Overview

The proposed model integrates multiple pre-trained Transformer architectures — including ViT, Swin, BEiT, ConvNeXt, CLIP, and Phikon — to extract high-level visual representations.  
These features are further processed through CNN layers and fed into a fully connected neural network for final classification.  
Using transfer learning, the model achieves improved accuracy, robustness, and reduced training cost.

## Key Results

- **Accuracy:** 99.37%  
- **AUC:** 0.9976  
- **Task:** Binary classification (Benign vs. Malignant)

These results demonstrate that integrating Transformer-based and convolutional feature extractors enhances diagnostic precision and reduces dependence on manual interpretation.

## Highlights

- Hybrid architecture combining Transformers, CNNs, and dense layers  
- Transfer learning for efficient and accurate feature extraction  
- High performance and strong generalization on histopathology datasets  
- Ready for integration into intelligent medical diagnosis systems

## Future Work

This model provides a foundation for explainable and multimodal AI tools to assist pathologists in early breast cancer detection.
