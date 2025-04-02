# Admission Prediction Using Machine Learning

## 📌 Project Overview
This project predicts the probability of student admissions based on various academic and research-related factors. Using a dataset containing GRE scores, TOEFL scores, CGPA, and other relevant features, multiple machine learning models were tested to find the best predictive model.

## 📊 Dataset
The dataset consists of 500 student records with the following features:
- **GRE Score** (0-340)
- **TOEFL Score** (0-120)
- **University Rating** (1-5)
- **SOP** (Statement of Purpose strength)
- **LOR** (Letter of Recommendation strength)
- **CGPA** (0-10 scale)
- **Research** (Binary: 0 - No, 1 - Yes)
- **Chance of Admit** (0-1 scale, target variable)

## 🛠 Steps Performed
1. **Exploratory Data Analysis (EDA)**
   - Checking missing values, data types, and distributions
   - Correlation analysis to find key factors affecting admission chances
   
2. **Data Visualization**
   - Scatter plots, histograms, and heatmaps for insights
   
3. **Data Cleaning**
   - Handling missing or inconsistent values
   - Normalizing/standardizing data where required

4. **Model Selection & Training**
   - Built multiple regression models (Linear Regression, Decision Tree, Random Forest, etc.)
   - Compared models using R-squared, RMSE, and MAE

5. **Evaluation & Insights**
   - Identified most influential factors for admission
   - Selected the best-performing model based on accuracy

## 🚀 Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

## 📌 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/admission-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run `Capston project.ipynb`.

## 📢 Results & Conclusion
- Successfully developed a predictive model for admission probability.
- Identified CGPA, GRE Score, and Research as the most influential factors.
- Built interactive visualizations for better understanding.

This project showcases essential skills in data science, machine learning, and predictive analytics.

