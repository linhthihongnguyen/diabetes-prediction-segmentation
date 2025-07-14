# diabetes-prediction-segmentation
The growing global burden of diabetes presents serious challenges for healthcare systems, emphasizing the need for improved early detection, risk assessment, and personalized intervention strategies. This project investigates how data-driven methods can support these goals through predictive modeling and patient segmentation.

We address the following key questions, each with a specific purpose aimed at enhancing diabetes care and prevention:

1. Can we build accurate predictive models to identify individuals at high risk of developing diabetes, and which demographic, clinical, and lifestyle factors contribute most to this risk?
Purpose: To support early identification of at-risk individuals and inform targeted public health strategies by understanding the most influential risk factors, allowing for timely intervention and prevention efforts.

2. Can we reliably estimate individuals’ HbA1c levels—a critical indicator of long-term blood glucose control—using available features?
Purpose: To explore the feasibility of using routine clinical and lifestyle data to monitor glycemic health. Accurate HbA1c prediction can help guide personalized treatment plans, especially in settings with limited lab testing access.

3. How can we segment patients based on metabolic profiles to uncover distinct risk groups and guide personalized care strategies?
Purpose: To enable healthcare providers to stratify populations based on shared clinical characteristics, allowing more precise interventions, efficient resource allocation, and tailored disease management programs.

To address these questions, we applied supervised learning methods (Random Forest, Linear Regression, and Lasso Regression) and unsupervised clustering techniques (K-Means and Hierarchical Clustering). These methods enabled us to build predictive models, reveal key influencing factors, and uncover meaningful patterns in patient risk profiles that can inform real-world healthcare decisions.

Dataset Overview: Diabetes Prediction
Link: https://www.kaggle.com/datasets/marshalpatel3558/diabetes-prediction-dataset/data

Dataset Description: This dataset comprises medical, lifestyle and demographic information from patients. It includes features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level.