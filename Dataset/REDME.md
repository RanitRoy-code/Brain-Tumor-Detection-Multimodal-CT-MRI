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
