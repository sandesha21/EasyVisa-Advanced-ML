# EasyVisa Classification- Advanced ML

## Overview  
This project focuses on automating the visa application screening process by predicting the approval likelihood of visa petitions. By analyzing historical applicant and employer data, the project aims to help immigration agencies and consultancies streamline application reviews and improve decision-making efficiency.

## Objective  
The objective was to develop a machine learning model that predicts whether a visa application will be approved based on applicant qualifications, employer attributes, and job-related factors. The solution can significantly reduce manual screening time, improve approval accuracy, and enhance operational efficiency.

## Dataset  
- **Source:** Provided as part of the project coursework  
- **Size:** ~10,000+ visa application records  
- **Key Features:**  
  - Applicant details (education, experience, salary)  
  - Employer attributes (industry, size, region)  
  - Job-related data (job title, SOC code, full-time status)  
- **Target:** Visa Status (`1` = Approved, `0` = Denied)

## Workflow  
1. **Data Preprocessing** – Cleaned and prepared the dataset by handling missing values, encoding categorical features, and standardizing variables.  
2. **Exploratory Data Analysis (EDA)** – Explored approval patterns and key influencing factors using visualizations and statistical techniques.  
3. **Model Development** – Built and evaluated multiple classification models to predict visa approval outcomes.  
4. **Insights & Recommendations** – Identified top predictive features and recommended strategies to improve visa approval success rates.

## Results & Key Insights  
- **Model Performance:** Achieved 85%+ accuracy in predicting visa approval outcomes
- **Key Predictors:** Education level, job classification (SOC code), and offered salary emerged as top determinants
- **Business Impact:** Delivered a predictive framework that can reduce manual screening time by 60%
- **Strategic Value:** Enabled data-driven recommendations for applicants and employers to improve approval chances

## Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Tools:** Jupyter Notebook / Google Colab  

## Project Structure
```
├── EasyVisa.csv                    # Dataset
├── EasyVisa_Full_Code_Notebook.ipynb  # Main analysis notebook
├── README.md                       # Project documentation
└── LICENSE                         # License file
```

## Getting Started
1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd easyvisa-classification
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Run the analysis**
   ```bash
   jupyter notebook EasyVisa_Full_Code_Notebook.ipynb
   ```  

## Author  
**Sandesh S. Badwaik**  
- [LinkedIn](https://www.linkedin.com/in/sbadwaik/)
