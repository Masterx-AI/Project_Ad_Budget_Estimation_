# Project_Ad_Budget_Estimation 📰
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/141647621-ca6115e0-6a19-4c89-b3fb-c6add24e5f90.jpg" style="width: 1000px;"/></p>

### Description:
The advertising dataset captures the sales revenue generated with respect to advertisement costs across multiple channels like radio, tv, and newspapers. It is required to understand the impact of ad budgets on the overall sales.

### Objective:
- Understand the Dataset & cleanup (if required).
- Build Regression models to predict the sales w.r.t a single & multiple feature.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### The Project is divided into the following steps:
1. Data Exploration
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Selection/Extraction
5. Data Manipulation
6. Simple Linear Regression Model
7. Multiple Linear Regression Model
8. Ridge, Lasso & Elastic Net Model
9. Polynomial Regression
10. Project Outcomes & Conclusions

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/140943369-489c9045-c24e-4c92-bc56-41109400ff62.png" /></p>

**2. Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/140944998-088f0b66-462f-4d1f-bae5-80642a0af48c.png)
![image](https://user-images.githubusercontent.com/54996245/140943392-91d0fcf8-476b-4db6-b25e-6b5f1370a963.png)

**3. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/140943438-ebd23f15-293c-41a2-9001-a7c293d40480.png)

**4. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/140943463-b41d8057-7c54-4ea2-984d-ade81228013b.png)

**5. Correlation Plot**

![image](https://user-images.githubusercontent.com/54996245/140943541-bf72d321-d55b-458f-8b7f-187a3d5aa152.png)

**6. Simple Linear Regression Prediction**

![image](https://user-images.githubusercontent.com/54996245/140943724-6195cbec-3a95-4298-882b-1888cea8ee8e.png)

**7. Multiple Linear Regression Prediction & Residual Normality Check**

![image](https://user-images.githubusercontent.com/54996245/140943903-1ad2ac92-11fa-4047-be5d-f912e496c55b.png)
![image](https://user-images.githubusercontent.com/54996245/140943978-3aeeea21-cf8d-4c1a-bbac-50d29d8d17ed.png)

**8. Polynomial (9th Degree) Regression Prediction & Residual Normality Check**

![image](https://user-images.githubusercontent.com/54996245/140944102-59df9c45-3c24-4e1b-a71a-8bb19d5cabad.png)
![image](https://user-images.githubusercontent.com/54996245/140944194-a27e761b-b865-4a32-bd6f-4935fa928540.png)

**9. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/140944285-cc9c979e-ebb1-404f-b41d-9677922b4d87.png)

**10. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/140944418-855955da-8fe1-4145-825a-8c634f93e4cf.png)
![image](https://user-images.githubusercontent.com/54996245/140944451-42983cef-a10d-4573-a934-000b41134156.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 200 samples & after preprocessing 1% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the target-feature.
- Feature selection or feature extracting as there were only 3 features, which all contributed towards the right prediction.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-6) gave the best overall scores for the current dataset, yet it wise to also consider simpler models like MLR & ENR as they are more generalisable.

