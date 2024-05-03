# University & Course Details
- Course: CS 502 - Statistical Methods For Data Science
- University: Worcester Polytechnic Institute
- Semester: Spring 2024

# ♟️ Chess Player Performance Prediction

Welcome to the Chess Player Performance Prediction project! This repository contains the code, analysis, and documentation for our project focused on predicting player performance in chess games. By exploring a large dataset from Lichess, we aim to understand the strategic patterns, player characteristics, and factors that influence chess game outcomes.

## 🌟 Project Overview

Chess is a game with endless possibilities and complexities. With the advent of AI, chess engines can evaluate positions and make decisions faster and more accurately than any human player. Our project uses machine learning and statistical analysis to predict chess game outcomes and provide insights into player performance.

- **Dataset**: The "[Chess Game Dataset (Lichess)](https://www.kaggle.com/datasets/datasnaek/chess/data)" from Kaggle, containing over 20,000 chess games with 16 features, including game outcomes, player ratings, moves played, time controls, and opening information.
- **Objective**: Develop predictive models that can accurately forecast the outcome of a chess game based on various attributes and uncover strategic insights from recurring patterns and tactics.
- **Techniques**: Data preprocessing, exploratory data analysis (EDA), machine learning classification algorithms, and advanced data visualization techniques.

## 📂 Repository Contents

- **[InputCSV](./games.csv)**: The dataset used for analysis, contains over 20,000 chess games with various features.
- **[Presentation](./DS502_Team_1_Leveraging_Chess_Game_Presentation.pdf)**: A summary of our project's key findings and results.
- **[Final Report](./DS502_Team_1_Leveraging_Chess_Game_Report.pdf)**: A comprehensive analysis of the dataset, including preprocessing steps, methods used, and detailed results.
- **[Machine Learning Models (Python)](./ML_Chess_Outcome_Prediction.ipynb)**: Jupyter notebook containing machine learning models and predictive analysis.
- **[Statistical Analysis (R)](./Statistical_Analysis.ipynb)**: Jupyter notebook with exploratory data analysis and statistical techniques in R.

## 🔍 Exploratory Data Analysis (EDA)

Our EDA involved descriptive statistics, data visualization, and grouping techniques to understand the dataset better. We utilized Python libraries like 'matplotlib', 'seaborn', and 'pandas' to visualize patterns, distributions, and correlations.

## 🧠 Machine Learning Techniques

We employed various machine learning algorithms, including:
- Logistic Regression
- Decision Trees
- Random Forests
- Gradient Boosting
- LDA
- QDA
- K-Nearest Neighbors

To evaluate these models, we used metrics like accuracy, precision, recall, MCC, and F1-score. Techniques such as cross-validation were applied to ensure model stability and generalization.

## 🌈 Results and Insights

Our results revealed key insights into the factors influencing game outcomes and player performance. Notable findings include:
- The impact of player ratings, with 'white_rating' and 'black_rating' being significant predictors.
- The number of moves ('turns') played during a game and its effect on outcomes.
- The importance of strategic moves and player skills in chess games.

## ⚠️ Limitations and Considerations

Despite the insights gained, there are several limitations and concerns with the dataset, including:
- Inaccurate or fluctuating player ratings.
- Potential sampling bias due to the dataset's focus on games from a specific online platform.
- Limited contextual information about the games.
- Inconsistencies in opening classification.

These factors should be considered when interpreting the results and applying the insights.

## 📅 Future Directions

Based on our findings, future work could include:
- Developing player profiles based on playing style and strategic tendencies.
- Implementing recommendation systems for optimal moves or openings.
- Identifying communities of players with similar playing styles using network analysis techniques.
- Integrating external data for broader contextual analysis.

## 👏 Contributing

We welcome contributions! If you'd like to contribute to the project, please submit a pull request with your changes or suggestions.

Thank you for exploring our project! We hope you find the insights valuable and inspiring for your own chess endeavors. Happy playing!
