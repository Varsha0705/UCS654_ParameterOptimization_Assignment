# UCS654_ParameterOptimization_Assignment
# SVM Parameter Optimization Assignment UCS654

## Project Title
Support Vector Machine (SVM) Parameter Optimization Using GridSearchCV

## Dataset
The dataset used in this assignment includes a classification problem where the target variable is `quality`. The features are preprocessed using `StandardScaler` for normalization.

## Methodology
1. **Data Preprocessing**
   * The dataset is loaded using `pandas`.
   * The target variable is separated from the feature set.
   * Features are standardized using `StandardScaler` to improve model performance.
2. **Model Selection**
   * A **Support Vector Machine (SVM)** classifier is selected from `sklearn.svm`.
3. **Parameter Optimization**
   * A **GridSearchCV** is used to perform hyperparameter tuning over a specified parameter grid (e.g., `C`, `gamma`, and `kernel`).
   * Cross-validation is used to ensure the generalizability of the model.
4. **Model Evaluation**
   * Accuracy score is used as the primary performance metric.
   * Additional visualizations (like count plots) are created using `seaborn` to explore class distributions.

## Results
The results are summarized in a structured format, showing performance metrics for each parameter combination. The best parameter set is selected based on the highest cross-validated accuracy.
![Image](https://github.com/user-attachments/assets/f80435b6-fb67-457e-b956-7925b1d64e14)


## 📈 Result Graphs
![Image](https://github.com/user-attachments/assets/276317ee-9601-446e-8aa9-e63cc4ba310d)

## Conclusion
* SVM performs well with properly scaled features.
* Parameter tuning via GridSearchCV significantly improves model accuracy.
* Visualization helps in understanding the dataset distribution and model behavior.

## Libraries Used
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

## How to Run
1. Open the notebook in Google Colab
2. Execute all cells to reproduce the analysis
3. Examine visualization outputs and results table
4. Experiment with different parameter settings as desired
