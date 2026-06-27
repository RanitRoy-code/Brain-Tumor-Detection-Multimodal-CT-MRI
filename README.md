# Brain Tumor Detection Multimodal (CT + MRI)

## Proposed Approach

This repository presents an interpretable multimodal deep learning framework for **binary brain tumor detection** using **CT** and **MRI** brain images.

The proposed architecture employs **Vision Mamba** as the feature extraction backbone for both imaging modalities. Modality-specific features are projected into a shared embedding space and optimized using **Supervised Contrastive Learning** to improve cross-modal representation alignment. The projected features are then processed through a **Prototype Cross-Attention** module, where learnable prototypes capture representative tumor and healthy tissue characteristics. Finally, an **L2 Distance Classifier** performs binary classification (**Healthy** or **Tumor**) based on feature-to-prototype similarity.

To improve model transparency and clinical interpretability, the framework integrates multiple **Explainable AI (XAI)** techniques, including **Grad-CAM++**, **Attention Maps**, **Prototype Similarity Analysis**, and **UMAP Visualization**.

---

# Repository Structure

```text
Brain-Tumor-Detection-Multimodal-CT-MRI/
│
├── Architecture/
│   └── model_architecture.png
│
├── Dataset/
│   └── README.md
│
├── Notebook/
│   └── MODEL_code.ipynb
│
├── README.md
└── requirements.txt
```

---

# Files

### Brain_Tumor_Detection_Multimodal_CT_MRI.ipynb

Complete implementation of the proposed multimodal brain tumor detection framework, including:

* Dataset preprocessing
* Vision Mamba feature extraction
* Supervised Contrastive Learning
* Prototype Cross-Attention
* L2 Distance Classification
* Model training
* Model evaluation
* Explainable AI (Grad-CAM++, Attention Maps, Prototype Similarity, and UMAP)

---

### proposed_model_architecture.png

Visual representation of the proposed multimodal brain tumor detection architecture.

---

# Installation

Install the required dependencies before running the notebook.

```bash
pip install -r requirements.txt
```

---

# Dataset

The project uses two publicly available multimodal brain tumor datasets.

### Dataset 1

https://tinyurl.com/2rx35peu

### Dataset 2

https://tinyurl.com/5jfvdwr9

Both datasets contain:

* CT Images
* MRI Images
* Healthy Class
* Tumor Class

> **Important:** Update the dataset paths inside the notebook before executing the code.

---

# Training

1. Download both datasets.
2. Update the dataset paths in the notebook.
3. Install the required dependencies.
4. Open:

```text
Brain_Tumor_Detection_Multimodal_CT_MRI.ipynb
```

5. Execute the notebook sequentially from the first cell to the last.

---

# Model Components

* Vision Mamba Backbone
* Shared Projection Head
* Supervised Contrastive Learning
* Prototype Cross-Attention
* Learnable Prototypes
* L2 Distance Classifier
* Explainable AI (Grad-CAM++, Attention Maps, Prototype Similarity, UMAP)

---

# Explainable AI

The proposed framework provides multiple interpretability techniques:

* Grad-CAM++
* Attention Maps
* Prototype Similarity Analysis
* UMAP Feature Visualization

These visualizations help explain the model's decision-making process and improve clinical interpretability.

---

# Results

The proposed multimodal framework is designed for accurate and interpretable **binary brain tumor detection (Healthy vs. Tumor)** using complementary CT and MRI information.
