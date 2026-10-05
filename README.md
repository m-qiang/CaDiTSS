# Cardiac Digital Twin Summer School (CaDiTSS)

## Cardiac Image Analysis and Mesh Fitting

In this practical session, we will build a deep learning-based processing pipeline for cine cardiac magnetic resonance (CMR) image analysis and mesh fitting based on the [ACDC dataset](https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html). This practical session will work through the following steps:

- Automated CMR image segmentation.
- CMR image-derived phenotypes calculation and analysis.
- Bi-ventricular heart mesh template construction.
- Bi-ventricular heart mesh fitting using a deep learning-based approach.

## Part I. Cardiac MRI Segmentation and Analysis
In Part I, we train a 2D U-Net model for cardiac MR segmentation. The practical notebook can be accessed in `CMR_Segmentation_Demo.ipynb` or via [Google Colab link](https://colab.research.google.com/drive/1KCUsa9p50ZH96q4oDIx_hdGBEutbic8d). The solutions are available in `CMR_Segmentation_Solution.ipynb` or via [Google Colab link](https://colab.research.google.com/drive/1uSpIL5RswsIgU0kUesy_4zgMe0qlPAbF).
![Cardiac MR segmentation with U-Net](https://raw.githubusercontent.com/m-qiang/CaDiTSS/main/figures/segmentation.png)


## Part II. Cardiac Mesh Fitting
In Part II, we train a 3D U-Net model for cardiac mesh fitting. The practical notebook can be accessed in `CMR_Mesh_Fit_Demo.ipynb` or via [Google Colab link](https://colab.research.google.com/drive/17vP-R-ulV2vmYgNYG6RYYLBDE0D7ex-q). The solutions are available in `CMR_Mesh_Fit_Solution.ipynb` or via [Google Colab link](https://colab.research.google.com/drive/1KHqkwkRu1Qkh3-AwsV_QkmpbI8-e9QCO).
![Cardiac Mesh Fitting](https://raw.githubusercontent.com/m-qiang/CaDiTSS/main/figures/mesh_fitting.png)