# Lasso-and-Ridge-using-ADMM
Analyzing LASSO and Ridge regressions using ADMM and Gradient Descent methods. Also the ADMM model is compared with that of Sci-Kit Learn's existing model. 

**Augmented LaGrange form for ADMM:**
$$L_p(x,z,u) = f(x) + g(z) + \mu^{T}(Ax+bz-c) + (\rho/2) ||Ax+Bz-c||^{2}_2$$

## Dataset:
As input for our model, we used the diabetes dataset gathered from the  [**Medical City Hospital**](https://data.mendeley.com/datasets/wj9rwkp9c2/1) in Baghdad. Dataset size 1000x14 contains 14 features Several data manipulation techniques have been applied on the dataset we converted the categorical features into numeric values and we dropped the  features that do not contribute to the blood sugar level. Therefore, our final dataset contains 12 features.

### Attributes: 
Patient number, ID, Age, Gender, Creatinine ratio (Cr), Body mass index (BMI), Urea, Cholesterol (Chol), as well as fasting lipid profile, including total cholesterol, triglycerides(TG) and HDL , LDL , VLDL cholesterol, and Diabetic/Predictive Diabetes or Non-Diabetic Diabetes Class .

## Evaluation Metrics
| Model  | RMSE | MAE | Std. Error | Time |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| LASSO using Scikit-Learn  | 2.565  |  1.8425  | 0.0639 |  0.00570 s |
| LASSO using ADMM  |  2.2204 | 1.7872 | 0.0952 | 0.00110 s |
| Ridge using Scikit-Learn |  2.2480 | 1.8340 | 0.0673 | 0.01186 s |
| Ridge using ADMM |  2.2249 | 1.7889 | 0.0947 | 0.00177 s |

## Contributers
[![portfolio](https://img.shields.io/badge/Yashwanth_Kiran-1e90ff?style=for-the-badge)](https://github.com/iyashk)<br>
[![portfolio](https://img.shields.io/badge/Koganti_Sri_Sai_Harshith-072F5F?style=for-the-badge)](https://github.com/kssh18)<br>
[![portfolio](https://img.shields.io/badge/Likhit_Kalla-E23?style=for-the-badge)](https://github.com/likhitkalla)<br>
[![portfolio](https://img.shields.io/badge/Abhishek_Sai-F08080?style=for-the-badge)](https://github.com/Abhishek-Sai-14)<br>
[![portfolio](https://img.shields.io/badge/Perumula_Raghavendra-000?style=for-the-badge)](https://github.com)<br>
