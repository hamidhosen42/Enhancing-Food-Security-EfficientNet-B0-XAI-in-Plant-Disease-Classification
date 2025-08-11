# Advance Step to Protect Agriculture: A Deep Dive into Enhancing Food Security Through EfficientNet-B0 and XAI in Plant Disease Classification

## Authors
- Sadia Nawar
- Altaf Uddin
- Arnob Saha
- Md. Hamid Hosen
- Safa Asgar
- Linkon Chowdhury

## Abstract
This paper explores plant disease classification using deep learning models and image segmentation techniques to protect food security. EfficientNet-B0, among other models, is tested on a large dataset of 38 plant disease classes, achieving an accuracy of 99.86%. XAI techniques such as SHAP are utilized to enhance interpretability.

## Key Contributions
- **Deep Learning Models:** EfficientNet-B0 outperforms other models like CNN, VGG16, and MobileNetV2.
- **SHAP for Explainability:** Provides insights into how the model classifies diseases.
- **High Accuracy:** Achieved 99.86% accuracy for plant disease classification.

## Dataset
- **Source:** Kaggle (Plant Disease Dataset)
- **Size:** 87,900 images across 38 disease classes.

## Methodology
1. **Image Augmentation & Segmentation:** Preprocessing using DeePLabV3+.
2. **Model Training:** Multiple deep learning models including CNN, EfficientNet-B0.
3. **Evaluation:** Metrics like accuracy, precision, recall, and F1-score used to compare models.

## Results
| Model          | Accuracy | Precision | Recall | F1-Score |
|----------------|----------|-----------|--------|----------|
| CNN            | 97.03%   | 96.72%    | 96.82% | 97.00%   |
| MobileNetV2    | 96.85%   | 99.68%    | 97.78% | 96.37%   |
| EfficientNet-B0| 99.86%   | 99.01%    | 98.81% | 99.34%   |

## Conclusion
EfficientNet-B0 provides the most accurate and efficient results for plant disease classification, offering a promising approach to improving food security through early detection of plant diseases.

## Citation
```
@inproceedings{10.1145/3723178.3723315,
author = {Nawar, Sadia and Uddin, Altaf and Saha, Arnob and Hosen, Md. Hamid and Asgar, Safa and Chowdhury, Linkon},
title = {Advance Step to Protect Agriculture: A Deep Dive into Enhancing Food Security Through EfficientNet-B0 and XAI in Plant Disease Classification},
year = {2025},
isbn = {9798400713828},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3723178.3723315},
doi = {10.1145/3723178.3723315},
abstract = {The global economy heavily relies on the agricultural industry, making crop health crucial for both survival and economic stability. Significant production losses are caused by plant diseases in agriculture. It is often difficult for experienced farmers to detect diseases with traditional methods, which are often insufficient. Modern frameworks that combine deep learning approaches and image segmentation look to be viable alternatives to prior techniques. The study begins with image augmentation and segmentation. The image segmentation is carried out using DeePLabV3+ for image preprocessing, followed by feature extraction. Subsequently, the classification ability of several deep learning models is studied, including Convolutional Neural Network (CNN), VGG16, MobileNetV2, AlexNet, InceptionV3, DenseNet201, and EfficientNet-B0, for the classification of 38 plant disease classes. Among the top-performing models, EfficientNet-B0 achieved 99.86\% accuracy, 99.01\% precision, 98.81\% recall, and 99.34\% F1 score. EfficientNet-B0 is also explained through SHAP (SHapley Additive exPlanations), which provides insight into how the model classifies leaf diseases. Based on the results of the implementation of EfficientNet-B0, it is possible to significantly reduce crop destruction caused by plant diseases, which improves food security and economic stability.},
booktitle = {Proceedings of the 3rd International Conference on Computing Advancements},
pages = {1034–1041},
numpages = {8},
keywords = {Deep Learning, XAI, Plant Diseases, CNN, VGG16, MobileNetV2, AlexNet, InceptionV3, DenseNet201, and EfficientNet-B0},
location = {
},
series = {ICCA '24}
}
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
