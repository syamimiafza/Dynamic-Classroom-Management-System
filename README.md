# 🏫 Dynamic Classroom Management System for Statistical Modelling and Simulation (SMS)

This project is a Dynamic Classroom Management System developed using R programming and R Markdown. The main purpose of this project is to analyse classroom-related factors and predict whether a classroom situation requires intervention or does not require intervention.

The dataset used in this project is a simulated classroom dataset named sms_data_classroom.csv. It contains 1,000 observations with several variables related to student engagement and classroom management. The variables include engagement score, classroom participation, attendance percentage, seating group size, class duration, teaching method, and the final classroom outcome. The outcome variable is classified into two categories: “Intervention Needed” and “No Intervention”.

This project begins by generating and saving the classroom dataset, followed by loading the dataset into R for analysis. The preprocessing stage includes changing suitable variables into factor data types, especially categorical variables such as seating group, teaching method, and class outcome. Exploratory data analysis is then performed using histograms to visualise the distribution of numerical variables such as engagement, participation, and attendance.

A binary logistic regression model is used to predict classroom outcomes. The dataset is divided into 70% training data and 30% testing data. An initial GLM model is built using predictors such as engagement, participation, attendance, class duration, seating group, and teaching method. Model adequacy is checked using diagnostic plots and Cook’s Distance to identify influential observations. After removing influential points, the model is refitted and improved using stepwise regression based on AIC.

The final model is evaluated using AIC, BIC, Chi-Square model comparison, confusion matrix, and accuracy. Additional checks for overdispersion and multicollinearity are also conducted using residual deviance and VIF values.

✨ Key Features:

📂 Simulated classroom dataset with 1,000 records

🧹 Data preprocessing and factor conversion

📊 Exploratory data analysis using histograms

📈 Binary logistic regression model

🔍 Cook’s Distance for influential observations

⚙️ Stepwise regression using AIC

✅ Model evaluation using accuracy, AIC, BIC, and confusion matrix

🧠 Overdispersion and multicollinearity checking

Overall, this project demonstrates how statistical modelling can support classroom management decisions by identifying whether intervention may be needed based on student engagement, attendance, and participation patterns.
