# Capstone-Classification-Project
Machine learning project predicting engineering graduate salaries as High or Low using demographic, academic, and aptitude features. Applied models include Logistic Regression, Decision Tree, Random Forest, SVM, Naïve Bayes, Boosting, and ANN, with Random Forest achieving the best accuracy (~72.5%).
Engineering Graduate Salary Classification

This project focuses on predicting the salary category of engineering graduates—classified as either High or Low—using machine learning classification models. The dataset consists of 2,998 graduate records, with 33 input features and one target attribute (Salary). These features include demographic details, academic scores, college tier, specialization, and aptitude test results.

The primary objective is to develop predictive models capable of determining whether a graduate’s salary falls into the high or low category, based on their profile. Data preprocessing steps included calculating age from date of birth, dropping irrelevant fields such as IDs and board names, and applying one-hot encoding to transform categorical variables into numerical form suitable for modeling.

Exploratory data analysis (EDA) provided several key insights. The distribution of salaries is highly right-skewed: most graduates earn modest salaries, while a small proportion secure significantly higher incomes. College tier plays a vital role, with Tier 1 graduates achieving higher median salaries and a broader range of high-paying opportunities compared to Tier 2. Quantitative, logical, and English test scores showed positive correlations with higher salaries, though the relationships were weak. Specializations in computer-related fields, particularly Computer Engineering and Information Technology, consistently led to higher average salaries compared to other disciplines.

A range of machine learning models was implemented and compared, including Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, Support Vector Machine (SVM), Naïve Bayes, Bagging, Boosting algorithms (Gradient Boosting, XGBoost, AdaBoost), and Artificial Neural Networks (ANN). Performance was evaluated across different train-test splits to ensure robustness.

Among the models, Random Forest achieved the highest accuracy of 72.5% with a 75:25 train-test split. Other strong performers included ANN (72.3%), AdaBoost (72%), and Logistic Regression (72%). These results highlight that ensemble methods and neural networks provide competitive performance for this classification task.

Overall, this project demonstrates the application of machine learning in salary prediction and offers valuable insights into the factors influencing compensation among engineering graduates. It emphasizes the importance of technical specialization, aptitude skills, and institutional background in shaping career outcomes.

Tech Stack: Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn), XGBoost, TensorFlow/Keras, Google Colab.
