# NBA MVP Predictor [View in Github](https://github.com/iantavarez/iantavarez.github.io/blob/main/project-nba-mvp-predictor/NBA%20MVP%20Predictor.ipynb)

## Objective
The objective of this data analysis project is to develop a predictive model for identifying the most likely candidate for the NBA Most Valuable Player (MVP) award. By analyzing historical player performance data, team statistics, and other relevant factors, the goal is to create a robust and accurate algorithm that can forecast the MVP winner for the current NBA season. This model aims to provide insights into the key metrics that influence MVP selection and to enhance the understanding of what makes an MVP-caliber season.

## Tools and Technologies 
- Python
- Pandas
- Scikit-learn
- BeautifulSoup
- Selenium

## Dataset
The dataset for predicting the NBA MVP was webscraped from Basketball-Reference.com and includes comprehensive player and team statistics from past NBA seasons. It contains data on individual player performance metrics (e.g., points, rebounds, assists), team performance indicators (e.g., wins, offensive and defensive ratings), and historical MVP winners and finalists, providing a robust foundation for developing a predictive model.

## Process
1. **Data Collection:** The data for predicting the NBA MVP was collected by webscraping Basketball-Reference.com using BeautifulSoup and Selenium. BeautifulSoup was used for parsing the HTML content of the web pages, while Selenium was employed to automate the browsing and extraction of dynamic content.
2. **Data Cleaning:** The data was cleaned using pandas, a powerful data manipulation library in Python. This involved handling missing values, correcting inconsistencies, and converting data types to ensure the dataset was accurate and ready for analysis.
3. **Modeling:** The predictive model for the NBA MVP was implemented using ridge regression from scikit-learn. The model's accuracy was evaluated using the average precision score, achieving a final accuracy of approximately 81.5%.

## Results
WIP

## Conclusion
WIP
