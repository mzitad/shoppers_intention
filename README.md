# Online Shoppers Purchasing Intention Analysis

This project aims to predict whether an online shopping session will result in revenue using the "Online Shoppers Purchasing Intention Dataset" from the UCI Machine Learning Repository.

## Project Overview
The dataset contains 12,330 anonymized user sessions collected over one year. It includes behavioral attributes (page durations, bounce rates), technical data (operating systems, browsers), and user-related attributes (visitor type, weekend visits).

The primary goal is to develop a binary classification model to identify high-intent sessions in real-time, enabling targeted marketing interventions.

## Repository Structure
- `Shoppers_intention.ipynb`: Main analysis and model training notebook.
- `data/online_shoppers_intention.csv`: The raw dataset.
- `figures/`: Visualizations generated during data exploration (histograms, correlation matrices, etc.).
- `requirements.txt`: List of Python dependencies.

## Installation & Setup
1. **Create a Conda Environment:**
   
   ```bash
   conda create -n BI2025 python=3.11 -y
   conda activate BI2025
   ```
   
2. **Install Dependencies:**
    
    ```bash
    pip install -r requirements.txt
    ```