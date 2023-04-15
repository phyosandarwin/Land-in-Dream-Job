# JobMatch 
<img src="https://static.vecteezy.com/system/resources/previews/006/575/001/original/we-are-hiring-free-vector.jpg" width="150" height="150">

**About**
---
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on **job placement statuses in developing countries** from [Job Placement Status Kaggle Dataset](https://www.kaggle.com/datasets/ahsan81/job-placement-dataset). 

For detailed walkthrough, please view the source code in order from:

1. [Data Preparation and Cleaning](https://github.com/phyosandarwin/Jobmatch/blob/67408c71741bf5a087cbbba03199483cd6affe04/Data_Preparation_and_Cleaning.ipynb)
2. Exploratory Data Analysis (EDA)
   - [Numeric](https://github.com/phyosandarwin/Jobmatch/blob/38707bf6dcb011d3331f317f7b01096b5704419d/EDA%20(Numeric).ipynb)
   - [Categorical](https://github.com/phyosandarwin/Jobmatch/blob/38707bf6dcb011d3331f317f7b01096b5704419d/EDA%20(Categorical).ipynb)
3. [Machine Learning Models](https://github.com/phyosandarwin/Jobmatch/blob/0b75465dad5b0048b4aa47ac0e3e7ce95dd978cb/Machine_Learning_Models.ipynb)

[Presentation Slides](https://github.com/phyosandarwin/Jobmatch/blob/27859ca595f2a9fab3ac8e127e2501faee96888d/B126%20Group%208%20Presentation%20Slides.pdf)
[Video]

**Problem Definition**
---
Which variables are the most important in predicting whether one gets hired or not?
> Growing need for educated and talented individuals, especially in developing countries, recruiting fresh graduates is a routine practice for organizations. 
> As undergraduate students, we felt that this issue was relevant to us. 
> As individuals who are not so familiar with trends in developing countries, we decided to investigate the hiring practices of fresh graduates there. 


**Models used**
---
   >- Decision Tree Classifier
   >- Logistic Regression
   >- Support Vector Machine (SVM)
  
**Conclusion/Data-driven insights**
---
![image](https://user-images.githubusercontent.com/120161341/231919542-ba25a7ef-a597-48e9-a72e-643b67001740.png)


* Logistic Regression performs the best out of the three models, especially in terms of F1 score (good balance between precision and recall)
> features selected are SSC%, HSC%, Degree %, MBA %, and the lack of work experience
* Unexpectedly in developing countries, hiring practices have an increasing focus on work experience (although academic qualifications remain to be highly desirable) and a decreasing focus on gender for job roles.
* Our recommendations to students from LDC are:
> 1. Do well academically across all levels
> 2. Gain some work experience before entering the workforce, e.g. internships

**What did we learn from the project?**
---
- Use of chi-square statistic for correlation analysis of categorical varibles
- Use of F1 score, precision, recall, ROC-AUC score as model performance evaluation metrics
- Use of RFE (Recursive Feature Elimination) as a feature selection technique
- Logistic regression and SVM from sklearn
- Collaborating on GitHub


**References**
---
- [Chi-square Test](https://www.analyticsvidhya.com/blog/2021/06/decoding-the-chi-square-test%E2%80%8A-%E2%80%8Ause-along-with-implementation-and-visualization/)
- [Logistic Regression Code Explanation](https://www.youtube.com/watch?v=VCJdg7YBbAQ)
- [SVM](https://datagy.io/python-support-vector-machines/)
- [One Hot Encoding](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
- [EDA on categorical variables](https://medium.com/analytics-vidhya/tutorial-exploratory-data-analysis-eda-with-categorical-variables-6a569a3aea55)

**Contributors**
---
- [@phyosandarwin](https://github.com/phyosandarwin): EDA (Numeric), Logistic Regression, Chi-Square Statistic in EDA (Categoric), Data-driven insights
- [@cheyenneseet](https://github.com/cheyenneseet): Data Preparation and Cleaning, Decision Tree Classifier, Data-driven insights, Video Presentation
- [@senchiagladine](https://github.com/senchiagladine): EDA (Categoric), Support Vector Machine, Data-driven insights, Video Presentation
