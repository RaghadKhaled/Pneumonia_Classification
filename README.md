# Chest X-Ray Images (Pneumonia) Classification

---

## Overview

In this project I build an X-ray image classification model from scratch to predict whether an X-ray scan shows presence of pneumonia.
This is a college project required for a Deep Learning course during my BSc studies.<br>
It is done as individual work.

--- 

## Dataset

Chest X-Ray Images dataset is a an X-ray imagery dataset collected during scanning of patients’ routine clinical care and selected from retrospective cohorts of paediatric patients of one to five years old from Guangzhou Women and Children’s Medical Centre, Guangzhou. 
It is provided in kaggle repositry. The disease of the patients is pneumonia. It can be either: 1) Bacterial pneumonia 2) Viral Pneumonia 3) Mycoplasma pneumonia and 4) Fungal pneumonia. 
The dataset consists pneumonia samples belonging to the first two classes. It consist of 5863 images devided among two claases, which are the normal and up-normal (or pneumonia). 
The labeling is done with two expert before training on AI system and with third expert that check the test image. The dataset consists of only very few samples and that too unbalanced.
The collection of this dataset is meant for the researchers in this field to develop AI systems for classification task. Therefore, in this notebook, my aim is to develop a robust deep learning model from scratch on this limited amount of data. Even though the deep learning are data hungry, I built good models even with a limited amount of data.
Dataset available [here](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/code?datasetId=17810&sortBy=voteCount&language=Python&tagIds=16631).

---

### Tools

Libraries: 
- PIL
- NumPy
- Pandas
- TensorFlow
- Sklearn
- OpenCV
- Seaborn
- Matplotlib

Softwares: 

- Google Colab.
- Microsoft Azure. 

---

## Running the project
The whole project is located in the jupyter notebook file ``` CS464-Raghad.ipynb ``` and , you can use the Anaconda environment to open the Jupyter Notebook and install the requirement.



