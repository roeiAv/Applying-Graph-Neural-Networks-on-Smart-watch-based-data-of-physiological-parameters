# Project Overview

## Project Title
Enhancing ADHD Treatment Insights Through Machine Learning and Smartwatch Data

## Project Description
This project aims to leverage advanced machine learning techniques, specifically Graph Neural Networks (GNNs), to analyze smartwatch-based physiological and activity data collected from children diagnosed with ADHD. By integrating trial and observational data, the project seeks to better understand the impact of ADHD medication (e.g., methylphenidate) on behavior and activity patterns. The ultimate goal is to create predictive models that can interpret and predict medication effects, improving the understanding of ADHD treatment dynamics.

## Objectives
- Train GNN models on labeled trial data to develop robust prediction capabilities.
- Apply trained GNNs to observational data to gain deeper insights into real-world ADHD treatment responses.
- Explore the integration of different data sources, such as sensor measurements and behavioral data.
- Address challenges related to noise in data, electronic device biases, and data missingness.
- Investigate potential gender differences in ADHD presentation and treatment response.

## Methodology
1. **Data Collection**:
   - **Trial Data**: Collected during controlled settings where children wear smartwatches that monitor heart rate, accelerometer, and gyroscope data.
   - **Observational Data**: Gathered over several weeks while children are on ADHD medication during their daily activities.

2. **Data Preprocessing**:
   - Cleaning and transformation of raw sensor data into feature sets that include heart rate variability and movement patterns.
   - Addressing missing data and biases from electronic devices.

3. **Model Development**:
   - Training GNNs on the trial data to recognize patterns and predict medication intake effects.
   - Implementing Random Forest classifiers as additional models for comparative analysis.

4. **Evaluation Metrics**:
   - Performance evaluation using standard metrics such as accuracy, precision, recall, and F1-score.
   - Assessing model interpretability and robustness across different settings.

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
- The trained GNN models demonstrate potential in predicting medication status and assessing physiological changes.
- Comparative analysis with Random Forest classifiers shows the strengths and limitations of each approach.
- Insights from the project contribute to a deeper understanding of medication effects, offering potential clinical applications to support ADHD treatment strategies.

## Future Work
- Enhancing model training with more comprehensive data sets.
- Addressing model performance across diverse demographic groups.
- Exploring additional data features that could improve prediction accuracy.
- Incorporating feedback mechanisms for continuous learning and model updates.

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/username/project-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd project-repo
   ```
3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the data preprocessing script:
   ```bash
   python preprocess_data.py
   ```
5. Train and evaluate the models:
   ```bash
   python train_model.py
   ```

