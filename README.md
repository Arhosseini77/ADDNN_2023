<br/>
<p align="center">
  <h3 align="center">Analysis and Design of Deep Neural Networks - Homework Submission</h3>

  <p align="center">
    Analyse and Design Deep Neural Network, Dr.Kalhor and Dr. Nadjar Araabi, University of Tehran
    <br/>
    <br/>
  </p>
</p>
<br/>
<div align="center">
  <img src="https://img.shields.io/github/contributors/Arhosseini77/ADDNN_2023?color=dark-green" alt="Contributors"> 
  <img src="https://img.shields.io/github/stars/Arhosseini77/ADDNN_2023?style=social" alt="Stargazers"> 
  <img src="https://img.shields.io/github/issues/Arhosseini77/ADDNN_2023" alt="Issues"> 

  </a>
</div>
<br/>

## About 

This repository contains homework submissions for the course "Analysis and Design of Deep Neural Networks," instructed by Dr. Ahmad Kalhor and Dr. Babak Nadjar Araabi. 


## Course Overview

The course delves into the intricacies of designing and analyzing deep neural networks, emphasizing two key concepts:
- **Separation Index (SI)** 
- **Smoothness Index (SMI)**
- **Similiraty Learning**



## Contents

- [Homework 1: Data Evaluation - Subset Selection and Feature Selection](https://github.com/Arhosseini77/ADDNN_2023/tree/main/HW1)
    - Techniques for evaluating and selecting subsets of data
        - Separation Index
        - Smoothness Index
    - Feature selection methods to improve model accuracy and efficiency

- [Homework 2: Model and Layer Evaluation](https://github.com/Arhosseini77/ADDNN_2023/tree/main/HW2)
    - Evaluation of models and their layers
        - Testing model performance
        - Analyzing layer outputs
        - Understanding layer contributions to final predictions

- [Homework Extra: Feature Representation](https://github.com/Arhosseini77/ADDNN_2023/tree/main/Extra1)
    - Additional assignment focusing on feature representation techniques
        - Examples of enhancing model learning and prediction accuracy through effective feature representation

- [Homework 3: Layer-wise Learning - Image Segmentation Network](https://github.com/Arhosseini77/ADDNN_2023/tree/main/HW3)
    - Implementation and training of segmentation models
    - Train a model with Layer-wise Learning
      
- [Homework 4: Model Compression](https://github.com/Arhosseini77/ADDNN_2023/tree/main/HW4)
    - Exploration of model compression techniques
        - Reducing deep learning model size without significant performance loss
        - Crucial for deployment on devices with limited computational resources

- **Homework 5: Metric Learning**
    - Coverage of metric learning techniques
        - Triplet loss
        - Contrastive loss
        - [Fisher Discriminant Contrastive Loss (FDT)](https://arxiv.org/abs/2004.04674)
        - [Fisher Discriminant triplet Loss (FCT)](https://arxiv.org/abs/2004.04674)
        - Learning from relative comparisons between data points
          
## Included in this repository:
- Code implementations for all homework assignments.
- Detailed reports for each homework assignment.
- Descriptive files providing comprehensive instructions and guidelines for each homework assignment.


## Key Features

- Implementation of Separation Index and Smoothness Index found at [data_complexity_measures GitHub repository](https://github.com/Arhosseini77/data_complexity_measures).

## Environment and Dependencies

- **Python Version:** 3.10
- **PyTorch Version:** 2.1.1+cuda 11.8 
### Setting up Conda Environment
- Create the Conda environment using the provided YML file (`env_addnn.yml`):
```bash
conda env create -f env_addnn.yml
```
- Activate the created Conda environment:
```bash
conda activate torch2
```
## Acknowledgments

Special thanks to Dr. Ahmad Kalhor and Dr. Babak Nadjar Araabi for their invaluable guidance and instruction throughout the course.

---

