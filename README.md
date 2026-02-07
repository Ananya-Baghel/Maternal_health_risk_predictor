Maternal Health Risk Classification
===================================

Project Overview
----------------

Maternal health is a critical area in healthcare, where early prediction of pregnancy-related risks can help reduce complications and improve patient outcomes.

This project focuses on building a **Machine Learning-based classification system** to predict the **maternal health risk level** using clinical and physiological features.

The goal is to classify patients into different risk categories such as:

*   Low Risk
    
*   Medium Risk
    
*   High Risk
    

Features of the Project
-----------------------

*   Exploratory analysis of maternal health dataset
    
*   Data preprocessing and feature scaling
    
*   Training multiple classification algorithms
    
*   Performance evaluation using confusion matrix and accuracy metrics
    
*   Comparison of models for best risk prediction
    

Tech Stack
----------

*   **Python**
    
*   **Jupyter Notebook**
    
*   **Scikit-learn**
    
*   **Pandas**
    
*   **NumPy**
    
*   **Matplotlib / Seaborn**
    

Project Workflow
----------------

### 1️⃣ Dataset Distribution Check

Understanding how maternal risk levels are distributed across the dataset.

### 2️⃣ Feature & Target Separation

Splitting the dataset into:

*   Independent variables (features)
    
*   Dependent variable (risk classification label)
    

### 3️⃣ Data Scaling

Applying feature scaling to normalize values for better model performance.

### 4️⃣ Train-Test Split

Dividing the dataset into training and testing sets to validate model generalization.

### 5️⃣ Model Building & Prediction

Multiple ML models are trained for maternal risk prediction.

Machine Learning Models Implemented
-----------------------------------

### ✅ Logistic Regression

*   Baseline classification model
    
*   Evaluated using confusion matrix, accuracy, and precision score
    

### ✅ Decision Tree Classifier

*   Captures nonlinear patterns in maternal health data
    

### ✅ Random Forest Classifier

*   Ensemble-based approach for improved accuracy and stability
    

### ✅ Support Vector Machine (SVM)

*   Effective for high-dimensional classification problems
    

Model Evaluation Metrics
------------------------

Each model is evaluated using:

*   Confusion Matrix
    
*   Accuracy Score
    
*   Precision Score
    

These metrics help determine the most reliable classifier for maternal risk prediction.

Results
-------

The notebook compares multiple models to identify the best-performing algorithm for maternal health risk classification.

(Random Forest and SVM generally provide strong performance for healthcare classification tasks.)

Repository Structure
--------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   Maternal-Health-Risk-Classification   ┣ 📜 Maternal_Health_Risk_Classification.ipynb   ┣ 📜 README.md   ┗ 📊 Dataset (if included)   `

▶️ How to Run the Project
-------------------------

1.  Clone the repository:
    
git clone https://github.com/Ananya-Baghel/maternal-health-risk-classification.git   

2.  Navigate into the project folder:
    
cd maternal-health-risk-classification   

3.  Install required dependencies:
    
pip install -r requirements.txt   

4.  Open the notebook:
    
jupyter notebook Maternal_Health_Risk_Classification.ipynb   

Future Improvements
-------------------

*   Hyperparameter tuning for better accuracy
    
*   Deployment using Flask/FastAPI
    
*   Building an interactive web-based risk prediction tool
    
*   Adding explainability with SHAP/LIME
    

Author
------

**Ananya Baghel**Final-year Computer Science Engineering student passionate about AI/ML and Healthcare Applications.
