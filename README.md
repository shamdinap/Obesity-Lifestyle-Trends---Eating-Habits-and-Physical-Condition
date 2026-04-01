# Obesity-Lifestyle Trends - Eating Habits and Physical Condition

#### 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on a dataset of obesity levels among individuals from Mexico, Peru, and Colombia. The goal is to identify the core demographic and behavioral drivers—such as eating habits, physical activity, and genetics—that lead to different obesity classifications.

#### Dataset Structure:

The dataset includes the following features:

RangeIndex: 2111 entries, 0 to 2110

Data columns (total 17 columns):

&#x20;#   Column                          Non-Null Count  Dtype  

\---  ------                          --------------  -----  

&#x20;0   Gender                          2111 non-null   str    

&#x20;1   Age                             2111 non-null   float64

&#x20;2   Height                          2111 non-null   float64

&#x20;3   Weight                          2111 non-null   float64

&#x20;4   family\_history\_with\_overweight  2111 non-null   str    

&#x20;5   FAVC                            2111 non-null   str    

&#x20;6   FCVC                            2111 non-null   float64

&#x20;7   NCP                             2111 non-null   float64

&#x20;8   CAEC                            2111 non-null   str    

&#x20;9   SMOKE                           2111 non-null   str    

&#x20;10  CH2O                            2111 non-null   float64

&#x20;11  SCC                             2111 non-null   str    

&#x20;12  FAF                             2111 non-null   float64

&#x20;13  TUE                             2111 non-null   float64

&#x20;14  CALC                            2111 non-null   str    

&#x20;15  MTRANS                          2111 non-null   str    

&#x20;16  NObeyesdad                      2111 non-null   str    

&#x20;

Selected columns have been renamed to enhance readability and maintain consistency across the dataset.

#### 📊 Key Insights \& Inferences

Our analysis revealed several critical patterns that define the "Obesity Story" in this dataset:



Gender-Specific Obesity Tracks: There is a sharp divergence in extreme obesity. Obesity Type III is almost exclusively found in females, while Obesity Type II is almost exclusively male.



The Age Factor: Obesity levels trend upward with age, peaking and stabilizing between ages 25–35.



Sedentary Lifestyle Trap: Over 96% of the participants rely on motorized transport (Public Transit or Automobiles), with less than 3% engaging in "active commuting" (walking/cycling).



Genetic Predisposition: A staggering 82% of participants have a family history of being overweight, marking it as the strongest baseline predictor.



Balanced Data: The dataset is perfectly balanced across all 7 obesity categories, making it an ideal candidate for high-accuracy Machine Learning classification.



#### 📈 Key Visualizations

&#x20;Obesity Level vs Age

&#x20;Obesity Level vs Gender

&#x20;Correlation Heatmap

&#x20;Histograms

&#x20;Pie Chart (Proportion of Obesity Levels)

&#x20;Bar Plot (Frequency of Transportation Types)

&#x20;Scatter Plot (Height vs Weight colored by Obesity Level)ox Plot (BMI Distribution by Obesity Level)

&#x20;Line Chart (Average BMI by Age)

&#x20;Plotly (BMI Distribution across Obesity Levels by Gender)





#### 🛠️ Technologies Used

Python (Core Analysis)



Pandas (Data Manipulation)



Matplotlib \& Seaborn (Static Visualizations)



Plotly (Interactive Box Plots)





#### 📝 Conclusion

The analysis suggests that while diet and transportation provide the environment for weight gain, gender and genetics are the primary factors determining the final classification. This project provides a robust foundation for building a predictive model to identify at-risk individuals based on their daily habits.



Author: \[Shamdina P]



LinkedIn: \[www.linkedin.com/in/shamdina-perinkadakkat-1237391a1]



