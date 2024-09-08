# Health Analysis Project

This project performs an in-depth analysis of a healthcare dataset, focusing on data preprocessing, exploratory data analysis (EDA), and predictive modeling. The goal is to extract valuable insights into patient demographics, medical conditions, hospital operations, and to build models for predicting key metrics such as patient length of stay and billing amounts. The project also includes data visualizations for better interpretation of trends and relationships within the dataset.

## Project Overview

### Dataset Description:
The dataset consists of information about patients admitted to a hospital, including demographic details, medical conditions, treatments, and billing information.

#### Key Columns:
- **Name**: Patient's name.
- **Age**: Patient's age at the time of admission.
- **Gender**: Patient's gender.
- **Blood Type**: Patient's blood type.
- **Medical Condition**: The diagnosis or medical condition for which the patient was admitted.
- **Date of Admission**: Admission date to the hospital.
- **Doctor**: The attending physician.
- **Hospital**: The hospital where the patient was admitted.
- **Insurance Provider**: Insurance company covering the medical expenses.
- **Billing Amount**: Total billed amount for services provided during the hospital stay.
- **Room Number**: The hospital room number assigned to the patient.
- **Admission Type**: Type of admission (e.g., emergency, elective).
- **Discharge Date**: The date the patient was discharged.
- **Medication**: Medications prescribed during the hospital stay.
- **Test Results**: Results of any medical tests conducted during hospitalization.

### Data Preprocessing:
- **Date Conversion**: Converts the admission and discharge dates into `datetime` format.
- **Length of Stay Calculation**: Computes the length of stay by subtracting the admission date from the discharge date.
- **Readmission Indicator**: Creates a feature to indicate whether a patient was readmitted.
- **Handling Missing Values**: Imputes missing values in the dataset.
- **Categorical Encoding**: Encodes categorical variables to prepare them for modeling.

### Exploratory Data Analysis (EDA):
- **Gender Distribution**: Visualizes the distribution of patients by gender.
- **Age Distribution**: Displays the age distribution across different medical conditions or hospital types.
- **Billing Analysis**: Investigates the billed amounts based on factors such as age, gender, and medical condition.

### Predictive Modeling:
#### 1. **Length of Stay Prediction** (Random Forest Model):
- A Random Forest model is built to predict the length of a patient’s stay based on the dataset's features.
- The model's performance is evaluated using **Mean Squared Error (MSE)** and **R-squared**.

#### 2. **Cost Prediction**:
- A model predicts the billing amount for a hospital stay.
- Visualization compares predicted vs. actual costs to assess the accuracy of the model.

## Conclusion:
This analysis offers key insights into patient demographics, medical conditions, and hospital operations. Predictive models, such as Random Forest, accurately forecast outcomes like length of stay and billing amounts, providing actionable insights for hospital resource management and cost optimization.

## How to Use

### Clone the Repository:
```bash
git clone https://github.com/your-repo-name/health_analysis.git
```

### Install Dependencies:
Make sure to install all the required Python libraries by running:
```bash
pip install -r requirements.txt
```

### Run the Notebook:
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Execute the notebook cells in sequence to preprocess the data, conduct analysis, and generate results.

## Conclusion
This health analysis project demonstrates how data-driven insights can enhance healthcare management. Through thorough data preprocessing, EDA, and predictive modeling, we can improve the understanding of patient needs, optimize hospital resources, and provide better healthcare outcomes.

---

### Future Enhancements:
- **Additional Models**: Experiment with other machine learning algorithms (e.g., Gradient Boosting, Neural Networks).
- **Feature Engineering**: Create new features from existing data to improve model performance.
- **Deeper EDA**: Further explore correlations and causations between different medical conditions and hospital operations.


### Contact:
For any inquiries or issues, feel free to reach out to [karansandhu96.com].

---
