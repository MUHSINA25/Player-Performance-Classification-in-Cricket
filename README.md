# From Data to Decisions: Classifying Man of the Match in IPL

## Overview
This project aims to develop a classification model to identify the "Man of the Match" in Indian Premier League (IPL) cricket matches based on player performance metrics. The goal is to use data-driven insights to make accurate predictions.
## Dataset Information
### Source
- **Link**: [IPL Data till 2017](https://data.world/mkhuzaima/ipl-data-till-2017)

### Table: Player_match.csv
- **Player_match_SK**: Unique identifier for the player match.
- **PlayerMatch_key**: Key for the player-match combination.
- **Match_Id**: Unique identifier for the match.
- **Player_Id**: Player's ID.
- **Player_Name**: Player's name.
- **DOB**: Date of birth.
- **Batting_hand**: Batting hand of the player.
- **Bowling_skill**: Bowling skill of the player.
- **Country_Name**: Player's country.
- **Role_Desc**: Player's role in the match (e.g., bowler, batsman).
- **Player_team**: Team the player belongs to.
- **Opposit_Team**: Opponent team.
- **Season_year**: Year of the match.
- **is_manofThematch**: Target variable - whether the player was "Man of the Match."
- **Age_As_on_match**: Player's age during the match.
- **IsPlayers_Team_won**: Whether the player's team won the match.
- **Batting_Status**: Player's batting status in the match.
- **Bowling_Status**: Player's bowling status in the match.
- **Player_Captain**: Whether the player was the captain in the match.
- **Opposit_captain**: Opponent team's captain.
- **Player_keeper**: Whether the player was the wicketkeeper in the match.
- **Opposit_keeper**: Opponent team's wicketkeeper.


## Problem Statement
The primary objective is to classify players as the "Man of the Match" or not based on their performances in different matches. This classification problem will utilize machine learning techniques to create an effective model.

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Feature Selection**: Identifying the most relevant features for the classification.
3. **Model Training**: Utilizing various algorithms, including:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - AdaBoost
   - MLP Classifier
   - Naive Bayes
   - Random Forest
   - K-Nearest Neighbors
   - Gradient Boost
##  Model Evaluation and Steps

- **Classification Metrics**: Evaluate model performance using metrics such as:
  - Confusion Matrix
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC Curve

- **Hyperparameter Tuning**: Optimize model performance by adjusting hyperparameters.

- **Save the Model**: Save the trained model for future use.

- **Test with Unseen Data**: Assess the model's performance on data it hasn't encountered before.



## Results
- **Best Performing Model**: SVM, Logistic Regression, and AdaBoost achieved an accuracy of **76.4%**.
- **Class Imbalance**: Addressed to improve the model's performance on unseen data.
## Conclusion

The SVM model achieved 76.4% accuracy in initial tests but dropped to 60% on unseen data. This drop was due to class imbalance in the unseen data, leading to poor classification for class 0. The model favored predicting class 1, resulting in high recall but low precision. The small size of the unseen dataset limited performance assessment, showing the need for a more balanced dataset and further improvements.



##  Future Work
- **Explore Deep Learning**: Try neural networks to improve prediction accuracy.
  
- **Regular Updates**: Update the model with new player and match data regularly.

- **Fix Class Imbalance**: Use resampling techniques to balance the dataset.

- **Add Features**: Include factors like match location and weather to improve predictions.

- **Cross-Validation**: Implement cross-validation to ensure model robustness.

- **Advanced Feature Engineering**: Create new features that enhance prediction accuracy.

## Acknowledgments
I would like to express my gratitude to my mentors and peers for their constant guidance and support throughout this project.

1. Clone the repository:
   ```bash
   git clone https://github.com/MUHSINA25/Player-Performance-Classification-in-Cricket.git



