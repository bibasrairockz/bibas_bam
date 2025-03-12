# Video Views Prediction & Audience Retention Optimization

This project aims to predict video views and optimize audience retention using machine learning techniques. The main focus is to develop a pipeline that analyzes key features of videos and predicts both their view count and how well they engage viewers.

## Overview
The project is divided into two main tasks:
1. **Task 1: Video Views Prediction** – Predicting the number of views a video will receive based on key video features.
2. **Task 2: Audience Retention Optimization** – Improving video engagement and retention by leveraging GPT-4 to optimize video scripts.

## Task 1: Video Views Prediction
In this task, the goal was to develop a **machine learning pipeline** that predicts the number of views a video will receive based on various key video features such as title, description, tags, video length, and past performance.
![image](https://github.com/user-attachments/assets/cd4d20b8-7924-4e9b-a054-b9582a3aca5f)

### Steps:
1. **Data Collection and Feature Engineering**:
   - Gathered historical data of videos, including metadata such as title, description, tags, and video performance (views, likes, shares).
   - Engineered features like video length, content type, and audience demographics.
   - Preprocessed the data by handling missing values, encoding categorical variables, and scaling numerical features.

2. **Model Development**:
   - Applied **Linear Regression** to predict the number of views. This regression model learned the relationship between the features and video views.
   - Employed **Gradient Boosting** for better accuracy in predicting video views, as it effectively handled complex patterns in the data.

3. **Model Evaluation**:
   - Evaluated the models using appropriate metrics (e.g., Mean Absolute Error, R-squared) to assess prediction accuracy.

## Task 2: Audience Retention Optimization
The second task focused on **optimizing audience retention**. The goal was to enhance video scripts using **GPT-4** to improve viewer engagement and encourage longer watch times.

### Steps:
1. **Leveraging GPT-4 for Script Enhancement**:
   - Used **GPT-4** to analyze existing video scripts and suggest modifications that could improve viewer engagement, such as restructuring content or suggesting compelling calls to action.
   
2. **Impact Measurement**:
   - After script optimization, analyzed the change in audience retention by measuring viewer drop-off points and re-engagement after implementing the improved scripts.
   - The result was a significant increase in viewer engagement and retention, leading to higher overall performance for videos.

   
Before:
![Screenshot 2025-03-12 142439](https://github.com/user-attachments/assets/a8aa2b81-da43-422d-b652-588bfc1314c8)  
  
After:  
![image](https://github.com/user-attachments/assets/925adf02-c198-40d9-8f61-5fa685608ede)

