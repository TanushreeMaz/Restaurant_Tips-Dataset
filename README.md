# Predicting Restaurant Tips Using Predictive Analytics on Excel
An Business Analysis with Excel, on Restaurant Tips received as per time, gender, holidays, meals and many more ways to check the tips to restaurants

The project focuses on developing a mathematical model to forecast restaurant tip amounts using a predictive equation. 

I attempted to complete the project in two ways: first, by using Excel, and then by utilizing Power Query for data cleaning and preparation for analysis.

I used Pivot Charts to conduct a thorough analysis of the data, examining various aspects to identify where tipping habits differ across different scenarios.

Determine the independent and dependent variables.

I then calculated the linear relationship with the dependent variables using correlation.

I developed a regression model to examine the coefficient, R-squared value, and p-value.

 Also calculated the predicted tip and error percentage to assess the accuracy of the predictions.


# Data cleaning – 
Raw Data often consist of errors, blanks, duplicates, missing values, incomplete value, format error, etc. which can cause undermine the quality and reliability of any analysis or decision-making process. Irrelevant dataset could cause can clutter, and avoid performance and decision-making. 

<img width="1694" height="552" alt="image" src="https://github.com/user-attachments/assets/441a7908-15d2-401e-acb0-562a87928a3f" />


# Exploratory Data Analysis (EDA) 
  EDA helps to understand data deeply before diving into complex analysis, a       preliminary step that allows data to be studied in various steps like Trends, seasonality, or recurring patterns through descriptive statistics and visualizations. 

  <img width="943" height="1293" alt="image" src="https://github.com/user-attachments/assets/2b222de5-9c2a-4981-9ac6-7ef670508ce3" />

  <img width="982" height="1148" alt="image" src="https://github.com/user-attachments/assets/cbdba12f-0394-4b48-93e9-65ea6a0fc70d" />

# Feature engineering  
An appropriate model needed proper and structured data. Feature is defined as Independent Variables. The process of creating or modifying existing ones to improve the quality of Performance Model 
In simpler terms we call it creating new data points to help a machine learning model work better. 
 
To improve the Dataset, we are converting categorical data into numeric form. 

<img width="825" height="322" alt="image" src="https://github.com/user-attachments/assets/999fb674-ff79-47f2-b379-aec2ff8f783a" />


# Feature selection 
To predict the restaurant tips, first initial step to check the independent and dependent variable for regression model. As we are predicting tip, tip is dependent variable, and rest variables are independent variable. 
 
Next, to check the covariance, correlation, and multicollinearity between independent and dependent variable. In simpler term, Correlation, and to a lesser extent covariance, helps reveal variable relationships, improving feature selection and model understanding. 

<img width="834" height="403" alt="image" src="https://github.com/user-attachments/assets/864ebc96-224a-4c84-acd8-4d4400b75da6" />

<img width="1011" height="275" alt="image" src="https://github.com/user-attachments/assets/84223e07-3437-4edf-adbb-603b2cf287c0" />

<img width="894" height="194" alt="image" src="https://github.com/user-attachments/assets/df5c58b9-822d-496d-ac7f-6f2adf7c04c1" />


# Model Building 
 The next and important stage of the project involves constructing a model to monitor decision-making processes, forecast outcomes, optimize performance, and analyze trends. This model will help estimate future expenses and predict the tips the restaurant is likely to receive in the upcoming days. 

 <img width="1017" height="533" alt="image" src="https://github.com/user-attachments/assets/60eec3cb-75cc-4dd7-9efd-cd27a199e166" />


# Output and Model Evaluation Measure 
- R – Squared and P - Value

<img width="1017" height="533" alt="image" src="https://github.com/user-attachments/assets/89db7959-d91f-4f38-a85f-f68eec6c6368" />

-	Predicted Tip

<img width="940" height="712" alt="image" src="https://github.com/user-attachments/assets/31229682-a3ee-414f-a5f6-b703a8b5b3d2" />

-	Error Calculation  
- Squared Error:  Square of Error
- MSME: Average of Squared Error 
-	RSME: Square of MSME 
-	Error (%)

  <img width="236" height="264" alt="image" src="https://github.com/user-attachments/assets/62e3a972-4d49-4821-b91e-62d5b6ccf3f8" />


 
