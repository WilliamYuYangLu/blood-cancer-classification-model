# Blood Cancer Classification Model

Full-stack web app that uses a ResNet50 CNN to classify acute lymphoblastic leukemia subtypes from blood smear images, with explainable Grad-CAM heatmaps.

## Problem Statement <!--- do not change this line -->

Acute Lymphoblastic Leukemia (ALL) is a rapidly progressing cancer that affects the blood and bone marrow, specifically targeting white blood cells known as lymphocytes. It is the most common type of cancer in children, where it accounts for nearly a third of all childhood cancers [1]. Despite its fast-acting nature, ALL is more treatable than many other forms of cancer and can often be cured with timely treatment when identified. As such, early and accurate detection of ALL is especially significant.

Traditionally, diagnosis is done via microscopic analysis by trained pathologists, which can be time-consuming and prone to human error. In this project, we will explore the use of ResNet-50 in classifying various subtypes of ALL, ranging from benign to malignant. Our goal is to develop a reliable model capable of distinguishing between ALL cells and healthy white blood cells.

## Key Results <!--- do not change this line -->

1. Built a model achieving 95% validation accuracy that classified blood cancer cells across four subtypes
2. Preprocessed and cleaned 3,000~  medical data images to improve model generalization

## Methodologies <!--- do not change this line -->

To accomplish this, we utilized a supervised learning approach using the ResNet-50 convolutional neural network architecture. The model was implemented using PyTorch and TorchVision. Data preprocessing included removing low-quality or blurry images and resizing images to 224x224, which is the default input size for ResNet-50.

The model was trained to classify images as either benign (healthy) cells or various subtypes of malignant (ALL) cells. We also built a simple user interface using Gradio or Streamlit, where users could upload an image and receive a prediction, alongside a Grad-Cam heatmap to highlight important regions. 

## Data Sources <!--- do not change this line -->

(UPDATE IN README.md)
Include any relevant data sources that were used in your project.

*Kaggle Datasets: [Blood Cells Cancer (ALL) Dataset](https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class)*

## Technologies Used <!--- do not change this line -->

(UPDATE IN README.md)

- *Python*
- *pandas*
- *ResNet-50*
- *Grad-Cam*

## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Allyson Keightley*
- *William Lu*
- *Rohit Karnik*
- *Karen Liu*
- *Gloria Yip*
