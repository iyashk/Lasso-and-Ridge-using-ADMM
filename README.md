# iyashk-Lasso-and-Ridge-using-ADMM
Analyzing LASSO and Ridge regressions using ADMM and Gradient Descent methods. Also the ADMM model is compared with that of Sci-Kit Learn's existing model. 

# Dataset:
As input for our model, we used the diabetes dataset gathered from the  [**Medical City Hospital**](https://data.mendeley.com/datasets/wj9rwkp9c2/1) in Baghdad. Dataset size 1000x14 contains *Patient number, gender, blood sugar level, age, body mass index (BMI), urea, cholesterol (Chol), creatinine ratio (Cr), and HbA1c, including total cholesterol, LDL cholesterol, and VLDL cholesterol, as well as triglycerides and HDL cholesterol.* Several data manipulation techniques have been applied on the dataset we converted the categorical feature  ‘Gender' into numeric values and we dropped the 'No Patient' and 'ID' features since neither contribute to the blood sugar level. Therefore, our final dataset contains 12 features.

