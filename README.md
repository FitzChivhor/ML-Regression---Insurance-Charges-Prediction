ML Regression - Insurance Charges Prediction

Objective:

The aim of this project is to build a predictive model that estimates health insurance charges based on user attributes. By understanding the correlation between various factors and insurance costs, this analysis provides valuable insights into what significantly impacts insurance premiums.

Dataset Description:

We used the insurance.csv dataset, which comprises 1338 observations and includes attributes such as age, sex, BMI, number of children, smoking status, and region. The target variable is "charges," indicating the insurance charges for each individual.

Data Exploration and Cleaning:

The dataset was thoroughly examined for quality and consistency. Key findings include:

No missing values.
Right-skewed distribution of insurance charges.
Relationships between attributes and charges explored through pairplots.
Feature Engineering

Categorical variables were converted into numerical features using one-hot encoding. The data was subsequently divided into training and testing sets with an 80-20 split.

Model Training and Evaluation:

Three types of linear regression models were evaluated:

Linear Regression
Polynomial Regression
Ridge Regression
Performance was assessed using metrics such as Mean Squared Error (MSE) and R-squared values across models, with cross-validation to ensure robustness.

Conclusions:

The predictive modeling process demonstrated significant relationships between certain features and insurance charges. The models provided a range of effectiveness, with Polynomial Regression showing particular promise in capturing complex patterns in the data.

Usage:

The code is structured into sections for easy replication and testing. Users can run the notebook cells sequentially to reproduce the analysis and experiment with different regression techniques.
