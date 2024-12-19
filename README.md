# A Study on the Impact of Urban Green Spaces and Human Geography on Residents' Mental Health Based on EEG Signals  


## Description  

This repository contains the materials, code, and research findings for the study **"A Study on the Impact of Urban Green Spaces and Human Geography on Residents' Mental Health Based on EEG Signals"**. The goal of this project is to investigate the dynamic relationship between urban green spaces, human geography, and mental health through the analysis of electroencephalography (EEG) signals.  

The research introduces and utilizes a novel method called **Dynamic Spatial Health Network (DSHN)**, which incorporates:  
- Graph neural networks (GNNs)  
- Temporal recurrent mechanisms  
- Multi-source data fusion  

Additionally, the **Adaptive Green Health Strategy (AGHS)** is proposed to enhance the DSHN through advanced techniques such as spatial regularization, temporal attention mechanisms, and scenario-specific constraints.  

This study contributes to the growing field of digital public health, urban planning, and mental health research, offering insights into how green spaces can be better utilized to improve public health outcomes.

---

## Features  

- **Dynamic Spatial Health Network (DSHN):** A novel framework for spatial-temporal modeling that integrates urban green spaces and EEG signal data.  
- **Adaptive Green Health Strategy (AGHS):** A strategy for context-aware optimization of green spaces for mental health improvement.  
- **EEG Signal Analysis:** Identification of signal patterns linked to stress reduction and mental health improvements related to green space exposure.  
- **Multi-source Data Fusion:** Incorporates data from green space attributes, EEG readings, human geography, and urban health indicators.  

---

## Research Objectives  

1. To study the impact of exposure to urban green spaces on EEG signal variations and mental health.  
2. To propose an advanced modeling approach for predicting health outcomes using spatial-temporal methods.  
3. To provide data-driven recommendations for urban planning and public health systems.  

---

## Technologies and Tools  

- **Programming Languages:** Python  
- **Machine Learning Frameworks:** PyTorch, TensorFlow  
- **Graph Neural Networks:** PyG (PyTorch Geometric)  
- **Data Visualization:** Matplotlib, Seaborn  
- **Data Sources:** EEG signal datasets, urban green space data, geographic information system (GIS) data  

---

## Repository Structure  

```plaintext  
├── data/  
│   ├── eeg_signals/                # Processed EEG signal data  
│   ├── green_space_attributes/     # Urban green space attributes  
│   ├── human_geography/            # Human geography data  
├── models/  
│   ├── DSHN/                       # Implementation of the Dynamic Spatial Health Network  
│   ├── AGHS/                       # Adaptive Green Health Strategy extensions  
├── notebooks/                      # Jupyter notebooks for data exploration and analysis  
├── results/                        # Results from experiments and visualizations  
├── scripts/                        # Scripts for preprocessing, training, and evaluation  
├── LICENSE                         # License file  
├── README.md                       # Project documentation  
└── requirements.txt                # List of dependencies  
