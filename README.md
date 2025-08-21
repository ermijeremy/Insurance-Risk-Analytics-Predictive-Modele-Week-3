<<<<<<< HEAD
=======
Data Version Control (DVC)

This task focuses on implementing **Data Version Control (DVC)** to ensure that datasets and other large files used in this project are reproducible, versioned, and easily shared across environments.

---

## 🎯 Objective

To set up DVC and use it to track the insurance claims dataset so that:
- Data changes can be versioned like code
- Collaborators can pull the exact version of the dataset
- Future modeling and experimentation steps can be traced and reproduced

---

## 🛠 Tools Used

- Python
- Git & GitHub
- [DVC](https://dvc.org/) (Data Version Control)
=======
>>>>>>> 3a4f73e18e7f7ce97b495248b0e49e494259949a
# 🚗 Insurance Risk Modeling – Week 3 Project  
---

## 🧭 Project Overview

This project supports **AlphaCare Insurance Solutions (ACIS)** in building smarter, **risk-based car insurance pricing** strategies using historical data from South Africa. We explore vehicle claims, premiums, and customer demographics to:
- Discover low-risk customer segments
- Identify high-risk patterns and pricing inefficiencies
- Build predictive models for claim risk and premiums
- Generate actionable business recommendations

<<<<<<< HEAD
---

## 📁 Project Structure
insurance-risk-week3/  
├── .git/workflows  
├── .dvc
=======


## 📁 Project Structure
insurance-risk-week3/  
>>>>>>> 3a4f73e18e7f7ce97b495248b0e49e494259949a
├── data/  
│   └── raw/  
|   |   └── MachineLearningRating_v3.txt  
|   └── clean/  
|   |   └── MachineLearningRating_v3_cleaned.csv    
<<<<<<< HEAD
├── notebooks/  
│   └── task1_eda.ipynb  
├── src
├── README.md  
├── .gitignore  
└── requirements.txt
=======
|   |   └── claims.csv.dvc   
├── scripts/  
│   └── task1_eda.ipynb 
├── .dvc/  
├── .dvcignore   
├── README.md  
├── .gitignore  
└── requirements.txt
>>>>>>> 3a4f73e18e7f7ce97b495248b0e49e494259949a
