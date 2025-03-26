# Iris-Flower-Classifier
This project classifies Iris flowers into Setosa, Versicolor, or Virginica using a Random Forest model trained on sepal and petal dimensions. It offers high accuracy and can predict species from new flower measurements. 🚀

### **Iris Flower Color Classification - Project Summary**  

#### **Objective:**  
To build a **Machine Learning model** that classifies **Iris flowers** into three species (**Setosa, Versicolor, Virginica**) based on their **sepal and petal dimensions**.

#### **Steps Involved:**  

1. **Data Collection & Preprocessing:**  
   - Used the built-in **Iris dataset** from `sklearn.datasets`.  
   - Converted species labels into numerical format using `LabelEncoder`.  
   - Split the data into **training (80%) and testing (20%)** sets.  

2. **Model Training:**  
   - Used **Random Forest Classifier** to train on sepal & petal features.  
   - The model learned to classify flowers based on given measurements.  

3. **Model Evaluation:**  
   - Tested the model on unseen data.  
   - Achieved high accuracy and generated a **classification report**.  

4. **Prediction on New Samples:**  
   - Provided new flower measurements to predict species.  
   - Ensured predictions were converted back to species names.  

#### **Final Outcome:**  
- The model successfully classifies Iris flowers based on **size attributes**.  
- Achieved high **accuracy** with a simple **supervised learning** approach.  
- Can be **enhanced** by adding **deep learning** or **image-based classification**.

Would you like to deploy this model as a **web app** using **Streamlit or Flask**? 🚀
