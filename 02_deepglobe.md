# DeepGlobe Land Cover Classification Dataset

## Overview

The DeepGlobe Land Cover Classification Dataset is a satellite imagery dataset developed as part of the DeepGlobe Challenge. It is designed for semantic segmentation, where each pixel in a satellite image is assigned a land-cover class.

Unlike traditional image classification datasets, DeepGlobe provides pixel-level annotations, enabling deep learning models to identify different land-cover regions such as urban areas, forests, water bodies, and agricultural land.

---

## Dataset Information

**Dataset Name:** DeepGlobe Land Cover Classification

**Challenge:** DeepGlobe CVPR Challenge 2018

**Dataset Type:** Satellite Images (Semantic Segmentation)

**File Format:** RGB Images + Segmentation Masks

**Approximate Size:** ~3 GB

---

## Source

Kaggle

https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset

Official Challenge

http://deepglobe.org/

---

## Classes

The dataset contains seven land-cover classes.

| Class | Description |
|--------|-------------|
| Urban Land | Cities, roads, buildings and developed areas |
| Agriculture Land | Agricultural fields and cropland |
| Rangeland | Grasslands and open vegetation |
| Forest Land | Dense forest regions |
| Water | Rivers, lakes and water bodies |
| Barren Land | Dry land with little or no vegetation |
| Unknown | Unclassified pixels |

---

## Why We Selected This Dataset

This dataset provides detailed spatial information about land use and urban infrastructure. Since our project focuses on estimating the City Development Index, identifying urban regions, vegetation, water resources and land utilization is highly valuable.

The pixel-level annotations allow semantic segmentation models to calculate the proportion of urban land, green cover and water bodies, which can later be integrated with socioeconomic indicators.

---

## Role in Our Project

This dataset will be used to extract spatial features from satellite imagery.

The extracted features may include:

- Urban Area Percentage
- Forest Coverage
- Water Coverage
- Agricultural Land
- Barren Land

These features can be combined with socioeconomic indicators from the World Bank dataset to estimate urban development.

---

## Suitable Deep Learning Models

- U-Net
- DeepLabV3+
- PSPNet
- SegNet

---

## Advantages

- High-quality annotated satellite images
- Pixel-level ground truth labels
- Widely used benchmark dataset
- Suitable for semantic segmentation
- Directly supports urban land analysis

---

## Limitations

- Large dataset (~3 GB)
- Focused on land-cover rather than socioeconomic indicators
- Requires significant computational resources for training

---

## Why We Chose DeepGlobe Instead of EuroSAT

DeepGlobe provides pixel-level semantic segmentation, allowing detailed analysis of urban land, vegetation, water bodies and other land-cover classes.

EuroSAT performs image-level classification, assigning only one label to an entire image. Since our project requires detailed urban infrastructure analysis, DeepGlobe offers richer spatial information and is therefore a better fit.

---

## References

DeepGlobe Challenge

http://deepglobe.org/

Kaggle Dataset

https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset
