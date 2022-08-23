# Gender, Race, and Age Bias in Complaints Against the NYPD

This project is split into two files:

1. NYPD Racial Bias: An exploratory and confirmatory data analyis of the reuslts of over 12000 civilian complaints made against the NYPD. Specifically, we see how race and other physiological characteristics of the complainant have an impact on the length the complaint is open for. The file includes the summary of findings in a report format and also includes the code for data cleaning, EDA, CDA, and a missingness assesment of the data.

2. NYPD Prediction Model: The cleaned and analyzed data from the above file is used to create an end-to-end prediction pipeline using scikit-learn. The file includes the summary of findings along with the feature engineering, model selection, and analysis performed in order to choose the best-performing model. The final model is evaluated for basic fairness.


Data is collected from New York City’s Civilian Complaint Review Board.
  - Data/allegations.csv: contains the data of the civilian complaints made against the NYPD
  - Data/nypd_data_dictionary.csv: contains the description of the dataset and it's columns
  - Data/CCRB Data Layout Table.xlsx: contains the definition of the three possible results assigned to each complaint and officer
