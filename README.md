# Python
Breast Cancer Classification
Classify breast tumors as benign or malignant using classic machine-learning models.
This repo includes data preprocessing, exploratory data analysis (EDA), model training (Logistic Regression & Random Forest), evaluation, and a simple prediction function for new samples.

✨ Highlights

. Clean pipeline: load → preprocess → balance → split → scale → train → evaluate
. Models: Logistic Regression and Random Forest (RF typically performs better)
. EDA: class balance, distributions, and correlation heatmap
. Prediction function to classify new patient data
. Reproducible with a single notebook and minimal setup

1. Load Data
# Display first few rows
df.head()

<img width="1640" height="361" alt="image" src="https://github.com/user-attachments/assets/48ecc11d-d7b7-4d6d-a62e-c7957e844f3c" />
<img width="1640" height="386" alt="image" src="https://github.com/user-attachments/assets/49bd5f57-c4d9-4b74-8dc4-7a6ab358efee" />

# "Analysis of Cancer Dataset“
df.info()

Overview of the dataset (569 records, 32 columns).
Purpose of the dataset (e.g., predicting cancer diagnosis). 

<img width="787" height="940" alt="image" src="https://github.com/user-attachments/assets/b3a07e20-cfa3-4f1f-930a-f0bd05581ba5" />

# Descriptive Statistics 
df.describe()
<img width="1572" height="533" alt="image" src="https://github.com/user-attachments/assets/56702477-0e23-4a8c-ae99-a8d1c25dde52" />

# 2. Exploratory Data Analysis (EDA)

<img width="1132" height="738" alt="image" src="https://github.com/user-attachments/assets/a7c058b0-46b4-421e-9c33-a78db2165438" />

Diagnosis Categories Bar Plot

. 0 (Benign): Representing non-cancerous cases.

. 1(Malignant): Representing cancerous cases.

Insights from the Chart:

. Majority of the cases are Benign (0) with over 350 records.

. Malignant cases (1) are fewer, with less than 200 records.

. The dataset is imbalanced, requiring attention during model training to prevent bias.

# Analysis of Features by Diagnosis

<img width="1124" height="569" alt="image" src="https://github.com/user-attachments/assets/4773afd7-31f1-4643-91a8-df369ff53529" />

. Displaying the mean values of features

# HISTOGRAMS

Visualize the distribution of key features.
<img width="1710" height="425" alt="image" src="https://github.com/user-attachments/assets/4f663901-dd66-4b65-b51a-8e64efe9edd2" />

Radius Mean: Displays the frequency distribution of radius measurements.
Shows a skewed distribution with a peak around 15.

Texture Mean: Illustrates the texture measurements.
Exhibits a more uniform distribution with a slight peak around 20.

# Correlation Matrix

Analyze relationships between features
<img width="1566" height="919" alt="image" src="https://github.com/user-attachments/assets/78b4b183-1c9e-464f-bb68-4f67e21b498d" />

# 3. Data Preprocessing

<img width="1399" height="904" alt="image" src="https://github.com/user-attachments/assets/bba5ecf0-1b0f-480c-9b21-e0385495e742" />

# 4. Modeling (Logistic Regression & Random Forest

<img width="1251" height="533" alt="image" src="https://github.com/user-attachments/assets/7e2b76b4-5742-43b9-922e-03a22b60ebf4" />

# 5. Testing (Evaluating the models)

<img width="914" height="679" alt="image" src="https://github.com/user-attachments/assets/d54199ba-42d1-4c6a-9651-dedea975bfa9" />
<img width="845" height="680" alt="image" src="https://github.com/user-attachments/assets/b6c2cbd1-977d-4be7-a364-2cb94e50c48d" />

# Model Performance Comparison

<img width="1300" height="634" alt="image" src="https://github.com/user-attachments/assets/def79640-b1f1-4f9d-80dd-aaa5c3db7360" />

# 6. Inference

<img width="1412" height="690" alt="image" src="https://github.com/user-attachments/assets/eb01bf0b-8c92-4ed7-a8fd-8c4b98759d88" />















