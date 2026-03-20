# Sports-Bet-Final-Capstone Author: Dennis Nowicki
Final Capstone Project for Machine Learning Artificial Intelligence
NFL Game Outcome Prediction Using Machine Learning
Problem Overview
Predicting the outcome of NFL games is challenging due to many influencing factors such as team performance, betting odds, and game conditions. Accurate predictions can help inform better decision-making in sports analytics and betting strategies.
This project explores whether machine learning models can effectively predict game outcomes using historical NFL data and betting spreads.
Project Goal
The goal of this project is to build and evaluate predictive models that determine whether the home team will win a game. The project also aims to assess whether these models can provide insights beyond traditional betting markets.
Dataset Overview
The dataset includes historical NFL game data and betting information.
Source: Historical NFL game records and betting spreads
Key Features:
•	Team names (home and away)
•	Game scores
•	Betting spread
•	Game outcomes (home win or loss)
The betting spread represents the expected point difference between teams and serves as a key predictive feature.
Data Preparation
To prepare the data for modeling:
•	Cleaned missing and inconsistent values
•	Created a target variable indicating whether the home team won
•	Engineered features such as point difference
•	Removed irrelevant columns to focus on predictive variables


Key Insights
Exploratory analysis revealed several important patterns:
•	The betting spread is strongly correlated with game outcomes
•	Larger spreads generally indicate a higher likelihood of the favored team winning
•	Game outcomes are not perfectly balanced, which affects model behavior
Modeling Approach
Three machine learning models were developed and compared:
•	Logistic Regression – a simple, interpretable baseline model
•	Decision Tree – captures non-linear relationships but can overfit
•	Random Forest – an ensemble method that improves stability and performance
To ensure reliable results:
•	Cross-validation was used to test model consistency
•	Grid Search was applied to optimize model parameters
Results
The Random Forest model performed best overall.
•	It achieved the most balanced performance across evaluation metrics
•	It handled variability in the data better than simpler models
•	It reduced overfitting compared to the Decision Tree
Key Findings
•	The betting spread is the strongest predictor of game outcomes
•	Machine learning models largely confirm existing betting market expectations
•	This suggests that betting markets are highly efficient
•	Opportunities for significant predictive advantage may be limited
Business Recommendations
•	Use the model to identify games where predictions differ from betting spreads
•	Focus on potential “edge cases” where the model disagrees with market expectations
•	Avoid relying solely on model predictions for high-confidence betting decisions


Next Steps
Future improvements could include:
•	Incorporating additional features such as player statistics, injuries, and weather
•	Testing more advanced models (e.g., gradient boosting)
•	Deploying the model for real-time game predictions
Repository Structure
•	`/data` → Dataset files
•	`/notebooks` → Jupyter Notebook(s)
•	`/images` → Visualizations
•	`README.md` → Project summary

