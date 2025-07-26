# AI Job Risk Prediction

This project predicts whether a given job role is at **Low**, **Moderate**, or **High** risk of automation using machine learning.  
It is my first ML project as a fresher to showcase my skills in data preprocessing, model building, and deployment preparation.



##  Features
- Takes job-related numerical features as input.
- Uses a trained **Random Forest Classifier**.
- Outputs a **Risk Level**: `Low`, `Moderate`, or `High`.
- Demonstrates **data preprocessing, scaling, and encoding**.

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, imbalanced-learn, matplotlib
- **Model:** Random Forest Classifier
- **Development:** Jupyter Notebook


##  Dataset Source
The dataset is derived from:
- **O*NET (Occupational Information Network):** [https://www.onetcenter.org/database.html](https://www.onetcenter.org/database.html)  
- Includes job titles, required skills, and task ratings.  
- Processed to include a calculated **AI automation probability** and labeled into Low/Moderate/High risk.

