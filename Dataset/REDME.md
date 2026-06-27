# Dataset

## Overview

This project uses two publicly available multimodal brain tumor datasets. Each dataset contains both **CT** and **MRI** brain images, organized into **Healthy** and **Tumor** classes.

## Dataset 1

**Download Link:**  
https://tinyurl.com/2rx35peu

### Contents

* CT Images
  * Healthy
  * Tumor
* MRI Images
  * Healthy
  * Tumor

### Dataset Description

Dataset 1 consists of **22,782** multimodal brain images acquired from two imaging modalities for binary brain tumor classification.

| Modality | Tumor | Healthy | Total |
|----------|-------:|--------:|------:|
| MRI | 5,900 | 5,600 | 11,500 |
| CT | 5,662 | 5,620 | 11,282 |
| **Total** | **11,562** | **11,220** | **22,782** |

The dataset includes both **MRI** and **CT** brain images categorized into **Tumor** and **Healthy** classes. It provides a balanced multimodal collection that enables the proposed framework to learn complementary diagnostic information from both imaging modalities for binary brain tumor detection.

---

## Dataset 2

**Download Link:**  
https://tinyurl.com/5jfvdwr9

### Contents

* CT Images
  * Healthy
  * Tumor
* MRI Images
  * Healthy
  * Tumor

### Dataset Description

Dataset 2 consists of **9,618** multimodal brain images collected from **CT** and **MRI** modalities for binary brain tumor classification.

| Modality | Tumor | Healthy | Total |
|----------|-------:|--------:|------:|
| MRI | 3,000 | 2,000 | 5,000 |
| CT | 2,318 | 2,300 | 4,618 |
| **Total** | **5,318** | **4,300** | **9,618** |

The dataset contains both **MRI** and **CT** brain images divided into **Tumor** and **Healthy** classes. Combining this dataset with Dataset 1 increases the diversity of imaging samples, improving the robustness and generalization capability of the proposed multimodal brain tumor detection framework.

---

## Recommended Directory Structure

After downloading and extracting the datasets, organize them as follows:

```text
dataset/
├── CT/
│   ├── Healthy/
│   └── Tumor/
│
└── MRI/
    ├── Healthy/
    └── Tumor/
```

---

## Instructions

1. Download both datasets using the links above.
2. Extract the downloaded datasets.
3. Merge the CT images from both datasets into the `CT` directory and the MRI images into the `MRI` directory, if required by your preprocessing pipeline.
4. Ensure that the final directory structure matches the one shown above before training or evaluating the model.

---

## Notes

* Both datasets contain CT and MRI brain images for the **Healthy** and **Tumor** classes.
* This repository does not include the datasets; only the download links are provided.
* Ensure the datasets are correctly organized before running the training or evaluation pipeline.
