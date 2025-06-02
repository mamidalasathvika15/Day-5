# Day-4  
# 🚀 Decision Trees & Random Forests on Titanic Dataset

## 📌 Objective  
This project demonstrates the implementation and understanding of **tree-based models** — Decision Trees and Random Forests — for classification, applied to predict Titanic passenger survival based on their features.

---

## 🛠️ Tools & Libraries Used  
- Python 3  
- Pandas – for data handling  
- Scikit-learn – for model training, visualization, and evaluation  
- Matplotlib & Seaborn – for plotting graphs and feature importances  

---

## 📂 Dataset  
- Dataset used: `titanic_cleaned.csv`  
- Preprocessed Titanic dataset with features like `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and embarked indicators  
- Target column: `Survived` (0 = did not survive, 1 = survived)  

---

## 📈 Project Workflow  

1. **Data Import & Preprocessing**  
   - Load dataset with `pd.read_csv()`  
   - Select relevant features and target  
   - Handle missing values (age, embarked)  
   - Encode categorical variables using `LabelEncoder`  

2. **Train Decision Tree Classifier & Visualization**  
   - Train Decision Tree model with default parameters  
   - Visualize the tree using text-based output (due to Graphviz limitations)  

3. **Overfitting Analysis & Tree Depth Control**  
   - Limit maximum depth of Decision Tree to reduce overfitting  
   - Compare training and testing accuracy for different depths  

4. **Train Random Forest Classifier & Accuracy Comparison**  
   - Train Random Forest model with 100 trees  
   - Compare its accuracy against Decision Tree  

5. **Interpret Feature Importances**  
   - Extract and plot feature importances from Random Forest model  

6. **Model Evaluation Using Cross-Validation**  
   - Use 5-fold cross-validation to evaluate stability and performance of models  

---

## 📊 Output & Results  
- Decision Tree accuracy and controlled depth results  
- Random Forest accuracy comparison (usually higher than single tree)  
- Visualization of feature importances indicating most influential variables for survival prediction  
- Cross-validation scores summarizing model robustness  

---

## 📌 Conclusion  
This project builds and compares tree-based models on the Titanic dataset, highlighting the importance of model complexity control, ensemble learning via Random Forests, and interpreting feature contributions to predictions.

---

M.Sathvika  
02-06-2025
