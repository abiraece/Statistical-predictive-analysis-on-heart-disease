Statistical-predictive-analysis-on-heart-disease

Table of Content:
1. Project Introduction
2. Dataset Description
3. Data Preprocessing
4. Statistical Analysis
5.Conclusion

Project Introduction:

This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

Data Description (Heart Disease Data)

The dataset contains information about the individuals' age, gender, and several attributes affecting the heart disease in a person.

**age:** Age various from young to old

**sex:** Gender with 0 and 1

**cp:** chest pain type (4 values)

**restbps:** resting blood pressure

**chol:** serum cholestoral in mg/dl

**fbs:** fasting blood sugar > 120 mg/dl

**restecg:** resting electrocardiographic results (values 0,1,2)

**maxheart:** maximum heart rate achieved

**exang:** exercise induced angina

**oldpeak:** oldpeak = ST depression induced by exercise relative to rest

**slope:** the slope of the peak exercise ST segment

**ca:** number of major vessels (0-3) colored by flourosopy

**thal:** thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

**target:** 0 = no Disease; 1 = Disease

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

Data Pre-processing:

First step of Data Preprocessing is finding Null Value and computing Null value. In this Dataset there is no null value and all the data's are in numerical datatype.
Before Proceeding to Statistical Prediction, some of Data Analysis and visualization are performed to measure of central tendency,measure of spread and statstical characteistic,impact of one feature with other feature using pairplot or heatmap or scatterplot in the dataset.

Statistical Analysis:

One Sample Mean and Proportion test is performed in the given dataset. From that we can conclude that,
Healthy person average heart rate > 70 and Person with mean age > 45 has cardiac problem

In case of Two sample Mean and Proportion test is performed in the given dataset. From that we can conclude that,
Average Cholestral level for male is higher than Average cholestral level of Female.
In the given dataset, there exist a mean difference between Blood Pressure with Blood sugar and Blood Pressure without Blood sugar. So we can conclude that Blood Pressure has effect on Blood Sugar.
cholestoral has effect on age, and Exercise induce angina has no effect on blood pressure.
Age_group,Blood Pressure, Cholestral,Serum Cholestral has effect on Heart Disease.


