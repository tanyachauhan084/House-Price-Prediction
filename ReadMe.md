# 🏡 California House Price Prediction

This Machine Learning project uses the **California Housing dataset** from `sklearn.datasets` to predict house prices based on various numerical features such as population, number of rooms, and income levels. The model is trained to estimate **median house values** in different California districts.




## 📖 About the Project

The goal is to build a regression model that can predict median house prices in California districts using features like:
- Median income
- House age
- Average rooms
- Population, etc.

This dataset is widely used in regression problems and is built-in with `sklearn`.

---

## 🛠 Tech Stack

- **Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries Used**:
  - `scikit-learn` – ML algorithms and dataset
  - `pandas` – data handling
  - `numpy` – numerical computing
  - `matplotlib`, `seaborn` – data visualization

---

## 📊 Dataset Description

The **California Housing dataset** contains data collected from the 1990 California census.

- 📦 Source: `from sklearn.datasets import fetch_california_housing`
- 📐 Shape: `(20640, 8)`
- 🎯 Target: `Median House Value (in 100,000s)`

| Feature Name        | Description                             |
|---------------------|-----------------------------------------|
| MedInc              | Median income in block group            |
| HouseAge            | Median house age in block group         |
| AveRooms            | Average number of rooms per household   |
| AveBedrms           | Average number of bedrooms per household|
| Population          | Block group population                  |
| AveOccup            | Average house occupancy                 |
| Latitude            | Block group latitude                    |
| Longitude           | Block group longitude                   |

---

## 📈 Project Pipeline

1. **Load Dataset**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing** (Scaling, Train/Test split)
4. **Model Training** (Linear Regression, etc.)
5. **Model Evaluation** (R² Score, MSE, RMSE)


---

## 🧪 How to Run

1. Clone the repository:
 
   git clone https://github.com/tanyachauhan084/House-Price-Prediction.git <br>
   cd House-Price-Prediction

## Author

Tanya Chauhan
