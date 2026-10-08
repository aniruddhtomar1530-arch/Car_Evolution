# Car Evolution — Car Evaluation & Classification

A Machine Learning project that analyzes car purchasing attributes and predicts the **acceptability/classification of cars** using multiple classification algorithms.

## Project Overview

This project uses the **Car Evaluation Dataset** to explore how factors such as buying price, maintenance cost, number of doors, passenger capacity, luggage space, and safety influence car acceptability. The dataset contains **1,728 records and 7 categorical features**.

The project follows a complete ML workflow:

* Dataset loading and exploratory data analysis
* Categorical feature encoding using `LabelEncoder`
* Data visualization and correlation analysis
* Train-test data splitting
* Training multiple classification models
* Model accuracy comparison
* Confusion matrix analysis
* Random Forest feature-importance analysis

## Machine Learning Models

The following classification algorithms are implemented:

| Model               |   Accuracy |
| ------------------- | ---------: |
| Decision Tree       | **97.98%** |
| Random Forest       | **96.24%** |
| K-Nearest Neighbors | **92.20%** |

Based on the recorded results, the **Decision Tree Classifier achieved the highest accuracy** among the evaluated models.

## 🛠️ Technologies Used

* **Python**
* **Pandas** — Data manipulation
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Scikit-learn** — Machine Learning
* **Google Colab / Jupyter Notebook**

## Dataset Features

The project uses the following attributes:

* `buying` — Buying price
* `maint` — Maintenance cost
* `doors` — Number of doors
* `persons` — Passenger capacity
* `lug_boot` — Luggage boot size
* `safety` — Safety level
* `class` — Car acceptability category

## Feature Importance

Random Forest feature importance is also analyzed to identify which attributes contribute most to the model's predictions.

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/aniruddhtomar1530-arch/Car_Evolution.git
cd Car_Evolution
```

### 2. Open the notebook

Open:

```text
Car_Evolution.ipynb
```

You can run it using **Google Colab** or **Jupyter Notebook**.

### 3. Dataset

The notebook uses the Car Evaluation dataset and loads:

```text
car.data
```

The dataset can be uploaded directly when running the notebook in Google Colab.

## Results

The project demonstrates that classical Machine Learning algorithms can effectively classify car acceptability based on categorical purchasing and vehicle attributes. The **Decision Tree model achieved the best recorded performance with approximately 97.98% accuracy**.

## Author

**Aniruddh Tomar**

GitHub: [aniruddhtomar1530-arch](https://github.com/aniruddhtomar1530-arch)

---

⭐ If you find this project useful, consider giving the repository a star!
