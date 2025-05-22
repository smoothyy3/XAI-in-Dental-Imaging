# XAI-in-Dental-Imaging

This repository accompanies the seminar paper *"XAI in Dental Imaging: A Review with Applications in Caries Detection"* submitted as part of an academic project in the summer semester 2025.


---

## Objective

This project explores the use of **explainable AI (XAI)** in the detection of **dental caries** from radiographic images.  
Three widely used XAI methods are implemented and compared:

- **Grad-CAM**: Gradient-weighted Class Activation Mapping  
- **LIME**: Local Interpretable Model-Agnostic Explanations  
- **SHAP**: SHapley Additive exPlanations 

**Goals:**

- Evaluate ease of integration for each method in real-world diagnostic pipelines  
- Generate visual explanations to highlight caries-relevant regions  
- Compare clarity, runtime, and interpretability  
- (Optional) Compare performance across models

---

## Experiments

- Base model: **ResNet-50** pretrained on ImageNet
- Fine-tuned for binary classification (caries vs. healthy)
- Explanations generated for both correct and incorrect predictions
- Visualizations created using **Matplotlib** and **Seaborn**
  
Example visualizations are included in:
- `outputs/gradcam_XX`
- `outputs/lime_XX`
- `outputs/shap_XX`

## Dataset
This project uses the public [Dental Caries Detection Dataset](https://www.kaggle.com/datasets/tahuuanh/tooth-decay-datasetraw) from Kaggle.

Due to Kaggle's terms, you must download the dataset yourself and place it in the `data/` folder.  
