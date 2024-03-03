# **Hackathon Category: Best Real-World AI Application Built with Microsoft Fabric**

# Vehicle Dimensions Efficiency Predictor

## Introduction

This project develops a model to predict energy efficiency metrics using vehicle dimension data. It represents a novel approach in the automotive industry, addressing both environmental and economic challenges. This document details the innovation, technical merits, and potential impact of the model.

### **Innovation**

#### Conceptual Novelty

- **Integration of Physical Attributes**: This project is pioneering in its use of vehicle dimensions as a predictive basis for energy efficiency, blending physical engineering principles with advanced data science.
- **Advanced Analytics**: It employs sophisticated machine learning techniques to analyze and predict energy efficiency, surpassing traditional empirical or simulation-based methods.

#### Technical Merits

- **Precision Modeling**: Focusing on vehicle dimensions allows for the discovery of subtle correlations, leading to highly accurate predictions.
- **Adaptability**: The model is designed for ongoing improvement, capable of integrating new data to enhance its precision and relevance.

### **Impact**

#### Real-world Relevance

- **Environmental Sustainability**: Predictive insights from the model enable stakeholders to make choices favoring more sustainable vehicle designs.
- **Economic Benefits**: It helps manufacturers and consumers identify vehicles likely to offer superior fuel economy, thus lowering costs and environmental footprints.

#### Problem Solving

- **Design Optimization**: Assists manufacturers in optimizing vehicle designs for energy efficiency without sacrificing performance or aesthetics.
- **Regulatory Compliance**: Supports manufacturers in adhering to strict emissions and efficiency standards.

#### Potential Supplementary Use Cases

- **Urban Planning**: Can inform vehicle size regulations in urban areas to reduce congestion and pollution.
- **Fleet Management**: Enables fleet operators to select energy-efficient vehicles, lowering operational costs and carbon emissions.
- **Consumer Guidance**: A public version of the model could help consumers choose vehicles based on energy efficiency, promoting environmental sustainability.

### **Conclusion**

The development of a model that predicts energy efficiency from vehicle dimensions is an innovative breakthrough with broad implications. It addresses the critical issue of vehicle energy efficiency, offering a valuable tool for manufacturers, policymakers, and consumers to make informed, sustainable decisions.

## Project Structure

```
Vehicle Dimensions Efficiency Predictor
│
├── data/
│   ├── raw/               # Original, unmodified data
│   ├── intermediate/      # Data after initial processing
│   └── processed/         # Fully processed data ready for analysis
│   
│
├── README.md
│
│
└── notebooks/
    ├── 01_data_collection
    ├── 02_data_cleaning__vehicle_energy_consumption.ipynb
    ├── 02_data_cleaning__vehicle_dimnsions.ipynb
    ├── 02_data_cleaning__consolidated.ipynb
    ├── 03_feature_build.ipynb
    ├── 04_model_training__classical.ipynb
    └── 04_model_training__deep_learning.ipynb
```
