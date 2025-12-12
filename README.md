# Predicting Zebra Activity in the Serengeti: A Robust Evaluation of Weather-Driven AI Models

### **Authors:** Jiaying Wang, Zhuopeng Peng

### AI for Conservation (Fall 2025)

### 📌 Abstract

The movement of the plains zebra is an important ecological force in the Serengeti, but global warming is affecting established movement patterns. This study analyses the feasibility of forecasting local zebra behaviour using remotely sensed weather data and camera trap records as an alternative to GPS collaring. We created a binary classification problem and tested four models: Logistic Regression, Random Forest, Gradient Boosting and a PyTorch MLP. Using four data splitting strategies, we found that there was high accuracy (AUC ~0.65–0.79) with a random split, but a collapse in performance (AUC ~0.55–0.67) with a rigorous spatial and seasonal split. This demonstrates the 'spatial gap'. While weather affects regional biological clocks, it is insufficient for predicting the location of an individual zebra without site-specific features. We concluded that meteorological models should not be used as autonomous detectors, but rather as 'climatic suitability' filters to optimise ranger patrol allocation.

### 🌍 Data Sources & Ethics

This project adheres to **FAIR** (Findable, Accessible, Interoperable, Reusable) and **CARE** principles.

1.  **Biological Data:** [Snapshot Serengeti (S1-11)](https://lila.science/datasets/snapshot-serengeti)
    *   *Citation:* Swanson, A., et al. (2015). Scientific Data, 2, 150026.
2.  **Meteorological Data:** [NASA POWER Project](https://power.larc.nasa.gov/)
    *   *Citation:* NASA POWER Project. (2025). POWER Single Point Data Access (Version 2.0).
