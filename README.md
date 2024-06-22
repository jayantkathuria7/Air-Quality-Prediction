# Air Quality Prediction: Machine Learning Project

This repository holds the code and resources for a project that investigates how machine learning models can predict relative humidity (RH) based on air quality data.

**Abstract:**

Air pollution is a growing concern worldwide, and accurate prediction of air quality parameters is essential. This project explores applying regression algorithms to an Air Quality dataset to predict RH. The dataset includes measurements of various air pollutants, meteorological variables, and the target variable, RH. We implement and evaluate five regression models: Linear Regression, Random Forest Regression, Decision Tree Regression, Support Vector Regression (SVR), and Lasso Regression. The project analyzes these models' performance in predicting RH and offers insights into air quality analysis.

**Keywords:**

* Regression Analysis
* Air Quality
* Relative Humidity
* Machine Learning

**Getting Started**

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/Air-Quality-Prediction.git
```

2. **Install dependencies:** Refer to `requirements.txt` for the specific packages needed.

3. **Explore the data:** The data is located in the `data` folder.

4. **Run the Jupyter Notebooks:** The `notebooks` folder contains Jupyter Notebooks for data exploration, preprocessing, model training and evaluation, and visualization.

**Project Structure:**

* `data`: Contains the Air Quality dataset used for analysis.
* `notebooks`: Contains Jupyter Notebooks for data exploration, preprocessing, model training, evaluation, and visualization.
* `requirements.txt`: Lists the required Python libraries for this project.
* `README.md`: This file (you are reading it now).

**Results and Discussion:**

The project explores the performance of various regression models in predicting RH. The Random Forest Regression model achieved the best results based on evaluation metrics like Mean Squared Error (MSE) and R-squared (R2) score. This suggests its effectiveness in capturing complex relationships within the data and reducing overfitting.

**Future Work:**

* Explore additional regression algorithms (e.g., Gradient Boosting Regression, Neural Networks) for potentially improved prediction accuracy.
* Investigate the inclusion of additional relevant features or external data sources.
* Conduct a more in-depth analysis of feature importance and interactions to understand the factors influencing RH.
* Evaluate the models on different time periods or locations to assess their generalizability.
* Expand the project to predict other air quality metrics or classifications.

**Contribution:**

We welcome contributions to this project. Feel free to fork the repository, make improvements, and submit pull requests.
