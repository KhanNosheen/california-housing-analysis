# California Housing Price Prediction

## 📌 Project Overview & Key Findings
This project analyzes the California Housing Dataset to predict median house values using advanced regression techniques. By implementing a robust Scikit-Learn pipeline and comparing multiple models, I achieved a high-accuracy predictive framework.

📊 Exploratory Data Analysis (EDA)


<p align="center"><br>
  <img src="images/num_var_before.png" width="700" alt="Numerical Distributions">
  <br>
  <em>Figure 1: Distribution of all numerical features in the dataset.</em>
</p>

<p align="center"><br>
  <img src="images/box_plots_num_var_before.png" width="700" alt="Numerical Distributions">
  <br>
  <em>Figure 2: Distribution of all numerical features in the dataset.</em>
</p>

<p align="center"><br>
  <img src="images/heatmap_before.png" width="700" alt="Correlation Heatmap">
  <br>
  <em>Figure 3: Correlation matrix showing relationships between features and the target variable.</em>
</p>
⚙️ Data Preprocessing & Pipeline

<p align="center"><br>
  <img src="images/target_variable_dist_before.png" width="400" alt="Before Log">
  <img src="images/target_var_after_log_trans.png" width="400" alt="After Log">
  <br>
  <em>Figure 4: Target variable distribution before (skewed) and after (normalized) log transformation.</em>
</p>

<p align="center"><br>
  <img src="images/pipeline.png" width="600" alt="Scikit-Learn Pipeline">
  <br>
  <em>Figure 5: Automated preprocessing pipeline using ColumnTransformer and PowerTransformer.</em>
</p>

<p align="center"><br>
  <img src="images/baseline_regression_model.png" width="600" alt="Scikit-Learn Pipeline">
  <br>
  <em>Figure 6: Automated preprocessing pipeline using ColumnTransformer and PowerTransformer.</em>
</p>

🏆 Model Performance & Evaluation

<p align="center"><br>
  <img src="images/multi_models_metrics_eval.png" width="550" alt="Model Comparison Table">
  <br>
  <em>Figure 7: Comparison of RMSE, MAE, and R² scores across multiple regression models.</em>
</p>

<p align="center"><br>
  <img src="images/R2_vis.png" width="700" alt="Feature Importance">
  <br>
  <em>Figure 8: Impact of specific features on model accuracy.</em>
</p>---

## 🛠️ The Machine Learning Pipeline
I implemented a robust pipeline to handle scaling and model training. The following algorithms were tested:

* **Linear Regression**: Baseline performance.
* **Ridge & Lasso**: Regularization analysis.
* **Random Forest**: Ensemble patterns.
* **HistGradientBoosting**: Histogram-based boosting.

---

## 🏆 Key Results
After evaluating the models using Mean Squared Error (RMSE) and $R^2$ scores:

**The Winner:** `HistGradientBoostingRegressor`

This model outperformed the others by efficiently handling the feature set and providing the lowest error rates.

---

## 🚀 How to Run
1. **Clone the repo:** `git clone https://github.com/your-username/repo-name.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Execute the Notebook:** Run `California_Housing_Analysis.ipynb`.
1. **Clone the repo:** `git clone https://github.com/your-username/repo-name.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Execute the Notebook:** Run `California_Housing_Analysis.ipynb`.
