# Diabetis prediction

Tech Stack: ML, Python, Visualization
Github Link: https://github.com/smit-0001/used-car-price-prediction
Summary: In this project we try predict if a patient has diabetes or not depending on different health parameters using logistic regression.

# Diabetes Prediction

# Contents

Part 0 - Info on Dataset

Part 1 - EDA and Visualization

Part 2 - Model Building

# Part 0 - Info on Dataset

The dataset consists of the following parameters.
Pregnancies,
Glucose,
BloodPressure,
SkinThickness,
Insulin,
BMI,
DiabetesPedigreeFunction,
Age

**Using these features we pridict the outcome if diabetes is there or not.**

---

# Part 1 - Visualizations

Some key visualizations include

- **The countplot shows that 2/3 of people in our dataset does not have diabetes.**
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled.png)
    

- **The displot shows that disbetis is more common in young age group and less common for older people.**
The skewness was 1.12 and krutosis of 0.6
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%201.png)
    

- **Seeing the change of diabetes with no of pregnancy**
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%202.png)
    

- **Histogram plot of Diabetic patient wrt age**
minimun age with diabetes = 21
q1 = 24
median = 29
q3 = 41
maximun age with diabetes = 66 with few outliers(6) of more than 66
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%203.png)
    

- **Heatmap of correlation**
We see that age and Glucose has higher correlation(0.5) for diabetes followed by BMI (0.3)
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%204.png)
    

- **Histplot of all features**
Glucose , blood pressure and BMI have a normal distribution
Age , insulin and DiabetesPedigreeFunction are skewed
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%205.png)
    

- **Box Plot of Age vs BMI** → shows the variation of BMI for age
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%206.png)
    

- **KDE plot of Outcome (Diabetic) wrt numerical features**
The numeric features are → 'Pregnancies','Glucose','BloodPressure','SkinThickness','Insulin', 'BMI','DiabetesPedigreeFunction','Age'
    
    ![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%207.png)
    

---

---

# Part 2 - Model Building

### Training a Logistic Regression Model

### Train-Test Split

33% of data was kept for testing

### HeatMap showing confusion Matrix

![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%208.png)

### Accuracy

<aside>
🎯 An Accuracy of 79.13% was achieved

</aside>

### Feature Importance

![Untitled](Diabetis%20prediction%20d9055c8355cd477ba07f89bfc457dfd7/Untitled%209.png)