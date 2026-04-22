# LLM-Driven Automated EDA Pipeline

## 📌 Objective
An automated Exploratory Data Analysis (EDA) pipeline that bridges the gap between raw statistical datasets and actionable business intelligence. This project demonstrates how to leverage generative AI models to parse correlation matrices and descriptive statistics into human-readable insights.

## 🛠 Tech Stack
- **Data Processing:** Python (Pandas)
- **AI Analytics:** Amazon Bedrock (PartyRock Data Analytics Engine) / Claude 3
- **Data Source:** Biometric measurement dataset (n=2018)

## 📊 Key Insights Generated
1. **Variance Discrepancy:** High standard deviation in waist measurements (12.63) compared to height (9.33) indicates wider dispersion in lifestyle-driven body composition versus skeletal growth.
2. **Proportionality Constraints:** Thigh circumference exhibits weak correlation with height (r=0.268), rendering linear skeletal height a poor predictor for lower-body mass distribution.
3. **Multivariate Correlation:** Waist, chest, and hip measurements demonstrate strong positive correlation (r > 0.88), validating them as a unified cluster for total body mass estimation.

## 📂 Repository Structure
- `body-messurement-data-set.csv`: Raw data input.
- `eda_pipeline.py`: Python script simulating the pre-processing and correlation matrix generation.
- `body_measurement_analysis.csv`: The finalized statistical summary fed to the LLM for insight extraction.
