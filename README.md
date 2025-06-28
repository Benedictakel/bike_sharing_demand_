# 🚲 Bike Sharing Demand Prediction

This project focuses on **predicting the demand for bike-sharing services** using historical data and machine learning regression models. The goal is to build a model that accurately estimates the number of bike rentals based on various environmental and seasonal factors.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

Bike sharing systems are becoming increasingly popular in urban areas as a mode of green transportation. Being able to **predict bike rental demand** helps providers manage their fleet effectively, improve service delivery, and maximize operational efficiency.

This project utilizes regression techniques to predict bike demand based on features such as **temperature, humidity, time of day, season, and weather conditions**.



## 📊 Dataset

* **Source:** [ Bike Sharing Dataset]()
* **Description:** Contains hourly and daily count of rental bikes from the Capital Bikeshare system in Washington, D.C.
* **Key Columns:**

  * `datetime`: Hourly or daily timestamp
  * `season`: 1 = spring, 2 = summer, 3 = fall, 4 = winter
  * `holiday`: Whether the day is a holiday
  * `workingday`: Whether the day is neither a weekend nor holiday
  * `weather`: Weather condition (clear, mist, light rain/snow, heavy rain/snow)
  * `temp`: Normalized temperature in Celsius
  * `atemp`: Normalized feeling temperature in Celsius
  * `humidity`: Humidity percentage
  * `windspeed`: Wind speed
  * `casual`: Count of casual users
  * `registered`: Count of registered users
  * `count`: Total count of bike rentals (target variable)



## ✨ Features

✅ Data preprocessing and cleaning

✅ Exploratory Data Analysis (EDA) with visualization

✅ Feature engineering (e.g. extracting hour, day, month)

✅ Machine learning models:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
  ✅ Model evaluation with metrics such as RMSE and R²
  
  ✅ Prediction plots vs actual values



## 🛠️ Technologies Used

* **Python 3**
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* **Jupyter Notebook**



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/bike_sharing_demand.git
cd bike_sharing_demand
```

2. **Create and activate a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook
```



## ▶️ Usage

1. Open `Bike_Sharing_Demand_Prediction.ipynb` in Jupyter Notebook.
2. Run cells sequentially to:

   * Load and explore the data
   * Perform feature engineering
   * Train machine learning models
   * Evaluate and compare model performances
   * Predict bike demand on test data



## 📁 Project Structure

```
bike_sharing_demand/
 ┣ data/
 ┃ ┣ day.csv
 ┃ ┗ hour.csv
 ┣ images/
 ┃ ┗ (plots and visualizations)
 ┣ Bike_Sharing_Demand_Prediction.ipynb
 ┣ requirements.txt
 ┗ README.md
```



## 📈 Results

* **Best Model:** Random Forest Regressor
* **Performance:**

  * **RMSE:** *e.g. 100.5 ()*
  * **R² Score:** *e.g. 0.92 ()*

The Random Forest model performed best, capturing the nonlinear relationships and seasonality patterns effectively.



## 🤝 Contributing

Contributions are welcome to:

* Improve feature engineering techniques
* Try advanced models like Gradient Boosting or XGBoost
* Build an API to serve predictions
* Develop a web dashboard to visualize bike demand

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi@gmail.com) | [Portfolio Website](#)



### ⭐️ If you find this project useful, please give it a star!


