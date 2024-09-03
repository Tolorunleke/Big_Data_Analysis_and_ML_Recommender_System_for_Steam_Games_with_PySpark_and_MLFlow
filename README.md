# Advanced Steam Game Recommender System with PySpark and MLFlow

Welcome to the **Advanced Steam Game Recommender System**! This project focuses on analyzing Steam game data and building a personalized game recommendation system using PySpark and MLFlow. By leveraging big data technologies, we aim to create a scalable solution that provides tailored game recommendations for Steam users based on their gaming behavior and preferences.

## 🚀 Project Highlights

### 🔍 Data Loading and Preparation
- We start by loading the dataset (`steam_200k.csv`), which contains essential information about user interactions, including:
  - **`Member_Id`**: Unique identifier for each user.
  - **`NameOfGames`**: Titles of the games played.
  - **`Behaviour`**: User actions (e.g., purchase, play).
  - **`Hours_Played`**: Total hours spent playing each game.
- Using PySpark, we define a schema to accurately load and process the data, followed by data cleaning to handle missing values and ensure consistency.

### 📊 Exploratory Data Analysis (EDA)
- We perform an initial exploration of the dataset to uncover key insights and trends in user behavior, such as:
  - Popular games based on user activity.
  - Patterns in gaming behavior (e.g., hours played, purchase trends).
- Visualizations are created using `matplotlib` and `seaborn` to enhance understanding and inform the model-building process.

### 🧠 Building the Recommender System
- Utilizing the **Alternating Least Squares (ALS)** algorithm from PySpark’s `ml.recommendation` module, we create a collaborative filtering-based recommendation system.
- The ALS model learns user preferences by analyzing historical interaction data, making personalized game suggestions for each user.

### 🎯 Model Tuning and Evaluation
- To maximize the performance of the recommender system, we implement hyperparameter tuning with **Cross-Validation**.
- Model evaluation is carried out using metrics like **Mean Squared Error (MSE)** and **Root Mean Squared Error (RMSE)** to ensure accuracy and effectiveness.

### 📝 Experiment Tracking with MLFlow
- **MLFlow** is integrated to automatically log all experiments, model parameters, and metrics, ensuring a reproducible and well-documented workflow.
- This enables efficient model management and version control, making it easy to track the progress and performance of different models.

### 🏆 Results and Insights
- The final model provides accurate and meaningful game recommendations, enhancing user engagement and satisfaction.
- Key findings are summarized, and actionable insights are derived from the data analysis and model predictions.

## 🛠️ How to Get Started

Follow these steps to set up and run the project on your local machine or cloud environment:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tolorunleke/Efficient-Game-Analytics-and-Recommender-System-for-Steam-with-PySpark
