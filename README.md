DermAI_AI_Model_Training
This Google Colab notebook has been prepared for the preparation and training of a machine learning model specialized in skin cancer detection. The model performs binary classification of skin lesion images into two categories: Benign and Malignant.

Dataset Source
The dataset used in this project was collected from the following sources: ( _____ )

The dataset contains approximately 13,249 benign and 6,211 malignant images, providing a total of around 19,460 samples used for training, validation, and testing.

Notebook Structure
This notebook is organized into three main sections:

-Data Loading, Verification, and Preprocessing

This section focuses on importing the dataset, verifying its structure, cleaning inconsistencies, and performing Exploratory Data Analysis (EDA). Steps include resizing, normalization, data augmentation, and splitting the dataset into training, validation, and testing subsets.

-Model Training and Evaluation

In this section, a machine learning model is implemented and trained for skin lesion classification. The process includes model configuration, training, and performance evaluation using metrics such as accuracy, precision, recall, and F1-score. Optimization methods are also applied to ensure stable and efficient training.

-Result Interpretation and Visualization

This part is dedicated to analyzing the model’s predictions and interpreting its decision-making process using Grad-CAM and other visualization tools. It highlights how the model distinguishes between benign and malignant lesions, providing insights into reliability and interpretability.

Note: This notebook represents a core component of the DermAI Graduation Project at Palestine Technical University – Kadoorie. It aims to demonstrate the end-to-end process of building an intelligent, interpretable, and efficient system for skin cancer classification, contributing to early detection and supporting clinical decision-making.
