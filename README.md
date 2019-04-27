# heartML
**Heart Disease Classification problem**  

**Context**

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. 

**Variables**

1. age  = in years
2. sex  = (1 = male; 0 = female)
3. cp  = chest pain type (4 values) 
4. trestbps  = resting blood pressure in mm Hg
5. chol  = serum cholestoral in mg/dl 
6. fbs  = fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. restecg  = resting electrocardiographic results (values 0,1,2)
8. thalach  = maximum heart rate achieved 
9. exang  = exercise induced angina (1 = yes; 0 = no)
10. oldpeak  = ST depression induced by exercise relative to rest 
11. slope  = the slope of the peak exercise ST segment 
12. ca  = number of major vessels (0-3) colored by flourosopy 
13. thal  = thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. **target  = presence of heart disease (1 = true; 0 = false)**

**Creators** 
1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D. 
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D. 
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. 
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Data Source: https://www.kaggle.com/ronitf/heart-disease-uci

## Results

**Objecive:** Classify patients for presence of heart disease

**Approach:** Use Machine Learning to bifrocate patients for target

**Experiment Models:** Logistic Regression and Random Forest 70/30 Train Test Split

**Experiment Best Results:** 
**Logistic Regression**
* 88-90% Accuracy
* 88-90% Precision
* 92-94% Recall
* 88-90% AUC
* 85-95% Cross Validaiton (k-10)
