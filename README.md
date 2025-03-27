## Hi there 👋, I'm Michael Zefanya!

### Predicting Diabetes Risk: A Comparative Analysis of ML Models

#### About This Project
Diabetes is a global health issue, and early detection is crucial for effective management and prevention. This project analyzes medical datasets to identify patterns and relationships between health metrics and diabetes risk using Machine Learning (ML) techniques.

The primary goal of this project is to develop a predictive model to classify whether a patient is at risk of diabetes. Various ML algorithms are tested and compared to determine the most effective classification method.

---

### Dataset and Preprocessing
The dataset used is sourced from Kaggle, containing various medical indicators such as Glucose, Blood Pressure, BMI, Insulin, Age, Number of Pregnancies, Skin Thickness, and Diabetes Pedigree Function.

#### Preprocessing Steps:
- **Handling Missing Values:** Replacing missing or zero values in Insulin and Skin Thickness with the median value.
- **Feature Scaling:** Using Min-Max Scaling to normalize Glucose, Insulin, BMI, and Blood Pressure to improve model performance.
- **Outlier Detection:**
  - Identifying outliers using box plots.
  - Applying Winsorization to limit outliers and enhance data consistency.
- **Final Dataset:** After cleaning and normalization, the dataset is ready for training Machine Learning models.

---

### Exploratory Data Analysis (EDA)
#### Correlation Analysis
- Glucose has the highest positive correlation with diabetes, followed by BMI and Age.
- Insulin and Skin Thickness have a moderate correlation with diabetes.
- Blood Pressure and Diabetes Pedigree Function show a weaker correlation.

#### Clustering with K-Means
- K-Means Clustering is used to group individuals based on their health characteristics.
- The Elbow Method determines the optimal number of clusters.
- The clustering results reveal three main groups based on diabetes risk levels:
  - Individuals with high glucose and BMI levels, likely at higher risk.
  - Individuals with moderate glucose and BMI levels, possibly in the borderline category.
  - Individuals with low glucose and BMI levels, likely at lower risk.

---

### Model Evaluation & Performance
Several ML models were tested to predict diabetes risk. The evaluation results are as follows:

- **SVM** achieved the highest accuracy (**85.4%**).
- **Logistic Regression** showed **83.7%** accuracy.
- **Naïve Bayes** had the fastest training time (**78.5% accuracy**).
- **KNN** experienced overfitting (training accuracy of **92.1%**, but only **79.6% on test data**).

---

### Conclusion & Future Work
- ML models effectively predict diabetes risk, with **Glucose (0.47), BMI (0.29), and Age (0.24)** as the primary predictors.
- **SVM** proved to be the best model, while **Naïve Bayes** excelled in training speed.
- Future improvements include **hyperparameter tuning, feature selection, and real-time data integration**.
- Developing a **web-based diagnostic tool** using the best model can enhance accessibility and implementation in healthcare services.

---

### 📬 Contact Me
📧 **Email:** michaelzefanya04@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/michaelzefanya](https://linkedin.com/in/michaelzefanya)  
🐙 **GitHub:** [github.com/michaelzefanya](https://github.com/michaelzefanya)  

---

### 🌟 Let's Connect & Collaborate!
If you're passionate about Data Science and Machine Learning, feel free to reach out! 🚀

#DataScience #ClassificationModelling #EDA #dibimbing.id
