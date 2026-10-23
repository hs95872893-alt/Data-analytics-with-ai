# Student Performance Analysis and Prediction Using Data Analytics and Machine Learning

**Student:** Hemant Sharma  
**Father's Name:** Ashok  
**Roll Number:** 24202855  
**Enrollment Number:** 23/133726  
**Course / Department:** To be confirmed by student/college  
**College:** Govt. P.G. College, Dholpur  
**University:** Maharaja Surajmal Brij University

## Project overview
This academic demonstration analyses learning-related indicators and compares two regression models that estimate a synthetic final score. It illustrates data validation, descriptive statistics, visualization, feature encoding, train/test splitting, model evaluation, and responsible interpretation.

## Files
- `HemantSharma_StudentPerformanceAnalysis.ipynb` — complete executable notebook.
- `HemantSharma_ProjectReport.docx` — formatted project report.
- `requirements.txt` — Python dependencies.
- `student_performance_dataset.csv` — included synthetic example dataset (600 records).
- `score_distribution.png`, `study_score_scatter.png`, `actual_predicted.png`, `feature_importance.png` — figures used in the report.

## Dataset
The dataset is generated for teaching and reproducibility and is **not real student data**. It contains no actual personal records. Since no public dataset was supplied, a synthetic dataset is included rather than claiming that real institutional data was collected.

## Setup and run
1. Install Python 3.10 or later.
2. Open a terminal in this folder.
3. Install dependencies: `pip install -r requirements.txt`.
4. Launch the notebook: `jupyter notebook HemantSharma_StudentPerformanceAnalysis.ipynb`.
5. Run all cells from top to bottom. Keep the CSV in the same folder as the notebook.

## Reproducibility and evaluation
The train/test split uses `random_state=42` and reserves 20% of records for testing. The notebook compares Linear Regression and Random Forest Regression using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE) and R-squared (R²). Metrics are illustrative and may vary if data or settings are changed.

## Responsible use
Predictions must not be used to label, rank, admit, punish or otherwise make high-impact decisions about real students. Any real-world application would require lawful and ethical data collection, consent where appropriate, privacy protections, representative data, fairness evaluation, domain oversight, and human review. Feature importance is descriptive, not causal.

## References
- pandas: https://pandas.pydata.org/docs/
- scikit-learn: https://scikit-learn.org/stable/
- Matplotlib: https://matplotlib.org/stable/
- Jupyter: https://docs.jupyter.org/
