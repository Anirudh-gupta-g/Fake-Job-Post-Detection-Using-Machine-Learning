### **Project Title:** Fake Job Post Detection Using Machine Learning

### **Project Overview:**
The rise of online job portals has led to an increase in fraudulent job postings, which can deceive job seekers and lead to various negative outcomes. This project aims to develop a machine learning model that can automatically detect and classify fake job postings, thereby helping job seekers avoid scams and improving the overall quality of online job platforms.

### **Objectives:**
- To identify and classify job postings as genuine or fraudulent based on the text content and other relevant features.
- To explore various machine learning algorithms and natural language processing (NLP) techniques for this classification task.
- To evaluate the performance of the models and select the best one for accurate and reliable fake job detection.

### **Data:**
The dataset used in this project consists of job postings from an online job portal. Each job posting includes various features such as:
- **Title**
- **Location**
- **Department**
- **Company Profile**
- **Description**
- **Requirements**
- **Benefits**
- **Employment Type**
- **Required Experience**
- **Required Education**
- **Industry**
- **Function**

The target variable is a binary label indicating whether a job posting is fraudulent or not.

### **Methodology:**
1. **Data Preprocessing:**
   - **Text Cleaning:** Removal of HTML tags, special characters, and unnecessary spaces from the text data.
   - **Feature Extraction:** Key features such as job title, description, requirements, etc., are extracted for analysis.
   - **Label Encoding:** The target variable is encoded into binary labels (0 for genuine, 1 for fraudulent).

2. **Exploratory Data Analysis (EDA):**
   - **Data Visualization:** Insights into the distribution of job postings, common words in fake vs. genuine postings, etc.
   - **Correlation Analysis:** Checking the correlation between different features and the target variable.

3. **Model Building:**
   - Several machine learning models are implemented and compared, including:
     - **Logistic Regression**
     - **Decision Tree Classifier**
     - **Random Forest Classifier**
     - **Support Vector Machine (SVM)**
     - **Naive Bayes**
   - NLP techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) are used to convert textual data into numerical features.

4. **Model Evaluation:**
   - The models are evaluated using metrics such as accuracy, precision, recall, and F1-score.
   - Cross-validation is performed to ensure the robustness of the models.

5. **Hyperparameter Tuning:**
   - Optimization of model parameters to improve performance and avoid overfitting.

### **Challenges:**
- **Imbalanced Dataset:** Fraudulent job postings may be significantly fewer in number compared to genuine postings, leading to class imbalance issues.
- **Textual Data Complexity:** Job descriptions and requirements are often lengthy and complex, making feature extraction and model training more challenging.

### **Conclusion:**
The project successfully demonstrates the application of machine learning and NLP in detecting fake job postings. By accurately identifying fraudulent postings, the model can significantly enhance the safety and trustworthiness of online job portals, ultimately protecting job seekers from scams.

### **Potential Applications:**
- **Job Portals:** Implementation of the model on job search platforms to automatically flag or remove suspicious job postings.
- **Recruitment Firms:** Assistance in filtering out fraudulent job listings during the job aggregation process.
- **Research and Development:** Further refinement of models and techniques to address new forms of job posting fraud as they emerge.
