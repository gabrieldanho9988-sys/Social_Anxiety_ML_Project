# Social Anxiety ML Project: a Linear Regression Lesson

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

A machine-learning lesson built as a teaching example for the upper-secondary subject **Artificial Intelligence** (ARTI, Sweden's Gy25 curriculum), developed at Malmö University in 2025.

📓 **[Open the notebook](Social_Anxiety_Project_Malm%C3%B6_University.ipynb)** · **[Open in Google Colab](https://colab.research.google.com/github/gabrieldanho9988-sys/Social_Anxiety_ML_Project/blob/main/Social_Anxiety_Project_Malm%C3%B6_University.ipynb)**

## 📘 Lesson purpose
Understand the basics of **linear regression** by analysing how social anxiety relates to factors such as **age** and **social-media use**.

## 🎯 Learning goals
Students should be able to:
- **practise data analysis and visualisation** by exploring the dataset
- **build a simple linear regression model** to examine relationships between variables
- **reflect on the ethical implications** of AI models, especially in psychology and other sensitive areas

## 📊 Dataset
The dataset is downloaded automatically with KaggleHub:

```python
import kagglehub
path = kagglehub.dataset_download("natezhang123/social-anxiety-dataset")
```

## 🛠️ Tools and libraries
- Python
- NumPy and pandas
- Matplotlib and Seaborn
- scikit-learn
- XGBoost (optional, for more advanced models)
- KaggleHub, to download the dataset

## 🔬 Modelling
- train/test split
- linear regression
- evaluation with mean squared error (MSE), mean absolute error (MAE) and the R² score
- visualisation of the regression line and the residuals

## ⚖️ Ethical reflection
The lesson raises questions about:
- the risks of using AI models on sensitive psychological data
- bias and wrong conclusions
- privacy and data protection
- responsible use of predictive models in psychology

---

**Gabriel Danho** · Licensed upper-secondary teacher in physics, mathematics and AI · [GitHub profile](https://github.com/gabrieldanho9988-sys)
