This project is a Machine Learning-based Vote Prediction System that predicts the winning political party in a given constituency using election dataset features such as province, population, gender-based voter count, polling stations, and obtained votes.

It applies Linear Regression with encoded categorical features to train on past election data and provides predictions based on new inputs.

🚀 Features

🔍 Cleans and preprocesses missing values (median/mode imputation).

🏷️ Encodes categorical data (province, district, constituency, party).

📊 Splits dataset into training and testing sets.

🤖 Trains a Linear Regression model on election data.

📈 Evaluates using RMSE, MAE, and R² score.

🗳️ Takes user input (e.g., province, population, polling stations) and predicts the winning party.

🛠️ Technologies Used

Python 3

Libraries:

pandas (data handling)

numpy (numerical operations)

matplotlib (visualization)

scikit-learn (machine learning model, metrics, encoding)

⚙️ Dataset

The dataset used:
📂 Pak_Election_Voting_Results_Dawn_API_Combine.csv

Contains details like province, district, constituency name, population, male/female voters, polling stations, parties, and obtained votes.

📌 Workflow

Data Cleaning & Preprocessing

Fill missing values with median (numerical) and mode (categorical).

Encode string columns (province, district, constituency_name, party).
