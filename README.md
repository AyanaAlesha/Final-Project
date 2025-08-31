Spotify Listening Behavior Analysis

Project Overview
This project analyzes Spotify listening history data to predict user engagement behaviors such as track skipping and listening duration (`ms_played`). The analysis involves building baseline models (Logistic Regression, Linear Regression) and advanced Neural Network models (MLPClassifier and MLPRegressor). Scenario analysis was also performed to simulate potential real-world situations and understand how listening behaviors may change under different conditions.

## Key Steps
1. Data Preprocessing**: Cleaned and engineered features such as hour, day, month, and encoded artist/track names.
2. Baseline Models: Logistic Regression for classification (skip prediction) and Linear Regression for regression (listening time prediction).
3. Neural Networks: Implemented MLP models for both classification and regression, improving prediction accuracy.
4. Scenario Analysis: Defined three scenarios to test model sensitivity to real-world shifts:
   - Late-night Surge (1 AM, July)
   - **Weekend Binge (8 PM, December)
   - New Artist Dominance** (trending artist, April)

Results Summary
- Baseline: Provided a benchmark for typical listening conditions (midday, mid-month, June).
- Late-night Surge: Higher skip probability and shorter average listening time compared to baseline.
- Weekend Binge: Lower skip probability and longer playtime, reflecting holiday binge behavior.
- New Artist Dominance: Significant drop in skip probability with a rise in predicted listening duration, showing strong influence of trending artists.

These insights highlight how temporal factors and cultural trends impact listening behavior, offering strategic opportunities for playlist curation, marketing, and personalization.

Dependencies
Ensure the following Python packages are installed:
- pandas
- numpy
- scikit-learn
- matplotlib (optional, for visualization)
- seaborn (optional, for visualization)
- jupyter (for running notebooks)


Repository Structure
- `Spotify_Baseline_and_NN.ipynb` — Main Jupyter notebook containing preprocessing, models, and scenario analysis.
- `clean_dataframe.csv` — Preprocessed dataset used in analysis.
- `scenario_results.csv` — Output of scenario analysis for Tableau/Power BI dashboard integration.
- `README.md` — Project introduction and summary (this file).

Author
Prepared by Ayana Aiken as part of a data analytics project on predictive modeling and scenario analysis using Spotify listening data.
