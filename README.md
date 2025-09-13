# airfoil-noise-prediction-pyspark
Predict airfoil noise using PySpark MLlib with a complete pipeline: data cleaning, feature engineering, linear regression modeling, evaluation, and deployment-ready model saving.


Here’s a suggestion for your **repository name** and a **README file** for your Airfoil Noise Prediction ML Pipeline project:

---

**Repository Name:**

```
airfoil-noise-prediction-pyspark
```

---

**README.md:**

```markdown
# Airfoil Noise Prediction ML Pipeline

## Project Overview
This project demonstrates the creation of a complete Machine Learning pipeline using PySpark for predicting airfoil noise levels. The dataset used is a modified version of the [NASA Airfoil Self-Noise dataset](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise). The pipeline includes data cleaning, feature engineering, model training, evaluation, and model persistence for production use.

---

## Objectives
- Perform ETL on the raw airfoil dataset.
- Remove duplicates and handle missing values.
- Transform the data and store it in Parquet format.
- Create a Machine Learning pipeline with:
  1. VectorAssembler for feature vectorization
  2. StandardScaler for feature scaling
  3. Linear Regression for predicting sound levels
- Evaluate the model using metrics: MSE, MAE, R².
- Persist the trained model and reload it for predictions.

---

## Technologies Used
- Python 3.x
- PySpark 3.1.2
- Findspark
- Apache Spark MLlib

---

## Project Structure
```

airfoil-noise-prediction-pyspark/
│
├── NASA\_airfoil\_noise\_raw\.csv          # Original dataset
├── NASA\_airfoil\_noise\_cleaned.parquet  # Cleaned dataset
├── pipeline\_model/                     # Saved pipeline model
├── main.py                             # Python script with ETL and ML pipeline code
├── README.md                           # Project documentation
└── requirements.txt                    # Python dependencies

````

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/airfoil-noise-prediction-pyspark.git
cd airfoil-noise-prediction-pyspark
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Project

```bash
python main.py
```

The script will:

1. Load and clean the dataset.
2. Build and train the ML pipeline.
3. Evaluate the model.
4. Save and reload the trained pipeline.
5. Make predictions on test data.

---

## Evaluation Metrics

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **R-Squared (R²)**

---

## Author

**Sooraj Aryan**
Data Engineer / AI Enthusiast

---

## License

This project uses the [NASA Airfoil Self-Noise dataset](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

```

---

If you want, I can also **write a ready-to-run `main.py` script** that combines all your ETL, pipeline, evaluation, and persistence code into one Python file for the repo.  

Do you want me to do that?
```
