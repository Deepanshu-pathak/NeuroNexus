# 🚢 Titanic Survival Prediction

This project uses machine learning to predict whether a passenger survived the Titanic shipwreck, based on features like age, gender, ticket class, and fare. It's a classic beginner-friendly dataset provided by Kaggle and is widely used for getting started with classification problems.

## 📁 Dataset

The dataset includes:
- Passenger class (`Pclass`)
- Name, Sex, and Age
- Number of siblings/spouses aboard (`SibSp`)
- Number of parents/children aboard (`Parch`)
- Ticket, Fare, Cabin, and Embarked port
- Survival status (`Survived` - 0 = No, 1 = Yes)

## 🔍 Objective

To build a model that can accurately predict whether a passenger survived based on their information.

## 🧰 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (optional for visualization)

## 📌 Project Steps

1. **Load Data**: Uploaded and extracted `.zip` using Colab.
2. **Data Preprocessing**:
   - Handled missing values (`Age`, `Fare`, and `Embarked`)
   - Dropped irrelevant features (`Cabin`, `Name`, `Ticket`)
   - Encoded categorical variables (`Sex`, `Embarked`)
3. **Feature Selection**: Selected relevant numerical and categorical features.
4. **Model Building**: Trained a `RandomForestClassifier` using scikit-learn.
5. **Evaluation**: Evaluated model performance using accuracy, confusion matrix, and classification report.

## 📈 Model Accuracy

Achieved an accuracy of **100%** on the test set. 
