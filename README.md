AI-Powered Resume Analyzer
Project Summary
This project analyzes resume data to predict candidate suitability and performance using machine learning models. It assists in automating resume screening and extracting actionable insights to enhance recruitment decisions.

Objectives
Extract and preprocess features from resumes systematically.

Predict candidate job fit using classification models.

Compare model performance across KNN and Random Forest.

Provide insights to assist recruiters in data-driven decision-making.

Approach
Supervised classification with categorical and numerical resume features.

Applied label encoding, standardization, and correlation analysis for feature selection.

Trained models: K-Nearest Neighbors (KNN) and Random Forest Classifier.

Evaluated models using accuracy, F1-score, and runtime to identify the most effective approach for resume analysis.

Results
Random Forest: ~92% accuracy (best model).

K-Nearest Neighbors (KNN): ~88% accuracy.

Insights
Skills match, years of experience, and recent relevant roles strongly influence suitability predictions.

Random Forest demonstrated higher stability across multiple feature subsets compared to KNN.

Recommendations
Use Random Forest for primary resume suitability predictions due to its higher accuracy and feature handling robustness.

Integrate resume preprocessing pipelines for consistent feature extraction.

Periodically retrain models with new data to adapt to evolving hiring trends.

This project enables efficient and accurate resume analysis using machine learning to improve recruitment workflows.
