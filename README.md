# Project Overview

## Project Goal
Enhancing ADHD Treatment Insights Through Machine Learning and Smartwatch Data

## Project Description
This project aims to leverage Graph Neural Networks (GNNs), to analyze smartwatch-based physiological and activity data collected from children diagnosed with ADHD. By integrating trial and observational data, the project seeks to better understand the impact of ADHD medication (e.g., methylphenidate) on behavior and activity patterns.

## Objectives
- Train GNN models on labeled trial data to develop robust prediction capabilities.
- Apply trained GNNs to observational data to gain deeper insights into real-world ADHD treatment responses.
- Investigate potential gender differences in ADHD presentation and treatment response.(Empatica data Experiment)

## Methodology
1. **Data Collection**:
   - **Trial Data**: Collected during controlled settings where children wear smartwatches that monitor heart rate, accelerometer, and gyroscope data.
   - **Observational Data**: Gathered over several weeks while children are on ADHD medication during their daily activities.

2. **Data Preprocessing**:
   - Cleaning and transformation of raw sensor data into feature sets that include heart rate variability and movement patterns.
   - Addressing missing data and biases from electronic devices.(missingness was added as a feature)

3. **Model Development**:
   - Training GNNs on the trial data to enrich data vectors and add contextual value to datapoints.

4. **Evaluation Metrics**:
   The evaluation of the models focused on a robust set of performance metrics to ensure comprehensive assessment:
   - LDA (Linear Discriminant Analysis): Used for dimensionality reduction and to evaluate and understand the variance the across different medication conditions
   - ROC Curves: Employed to assess the trade-off between true positive rate (sensitivity) and false positive rate (1-specificity).
   - Confusion Matrix: Provided a detailed breakdown of model predictions, including true positives, true negatives, false positives, and false negatives. were more informative from ROC at Empatica experiment because of larger data amount.  
   - Weekly Consolidated Graphs: used evaluate the observational by comparing them with established medication concentration profiles from the literature to identify potential correlations or patterns.

## Challenges
- Handling noise and variability in observational data.
- Dealing with electronic device biases and ensuring data reliability.
- Managing missing data to maintain model performance.
- Accounting for potential gender differences in ADHD types and treatment responses.

## Team Members
- **Tzuf Bechor**
- **Uriah Asulin**
- **Yoav Kehat**
- **Roei Avraham**

## Key Results
- the trained GNN models demonstrated strong predictive capabilities for medication status within trial data, showing improved accuracy and interpretability compared to baseline models.
- Observations indicated potential gender differences in treatment responses, suggesting areas for further research.

## Future Work
- Enhancing model architecture, both GNN layers and graph representation of the data.
- Addressing model performance across diverse demographic groups.

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/username/project-repo.git](https://github.com/roeiAv/Applying-Graph-Neural-Networks-on-Smart-watch-based-data-of-physiological-parameters.git
   ```
2. Navigate to project directory and run LabProject.ipynb via Jupyter notebook:
   

