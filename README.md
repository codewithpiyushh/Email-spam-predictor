Email spam classification involves automatically identifying and sorting emails into two categories: spam (unwanted messages) and ham (legitimate messages). Techniques like analyzing email content, user behavior, and machine learning models help achieve this. The goal is to keep spam out of your inbox and ensure you receive important emails .


## 🔍 Methodology

1. **Importing Libraries:**  
   - Libraries such as NumPy, Pandas, Sklearn, and others are imported for data manipulation, visualization, and Machine learning model building.

2. **Loading the Dataset:**
   - The dataset containing the multiple rows of spam or not spam message

3. **Data Preprocessing:**
   Prepare data for analysis: handle missing values, encode categorical data, scale features, perform feature engineering, split into train-test sets, and normalize data. Ensure data is in a suitable format for machine learning algorithms.

4. **Training the Models:**
   - Each model is compiled using the Support vector machines
   - The models are trained on the training dataset and evaluation is done.

5. **Model Performance Analysis:**
   - Training and validation loss and accuracy are plotted to visualize the models' performance.

6. **Model prediction:**
   - The model is then given a test dataset to check the accuracy and precision of the model with

7. **Deploy:**
   - By using the streamlit library the model is deployed


**Data and Model File Download:**
the Dataset used int the project is taken from kaggle spam Dataset
[https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset]
