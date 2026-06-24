Customer Churn Prediction using Machine Learning

📊 Description


This project predicts customer churn using classification models. It analyzes customer data to find key factors affecting churn.

Steps

Data cleaning

Workflow

The project follows a structured machine learning workflow to predict customer churn effectively:

1. Data Collection 📂

The dataset is loaded, which contains customer demographic and financial information such as age, balance, geography, credit score, and activity status.

2. Data Cleaning 🧹

Unnecessary columns like RowNumber, CustomerId, and Surname are removed to improve model efficiency and focus on relevant features.

<img width="929" height="498" alt="01" src="https://github.com/user-attachments/assets/0e7e6682-294b-4e7f-8f1d-425bcaa6f3a9" />

<img width="707" height="287" alt="02" src="https://github.com/user-attachments/assets/765749ee-f081-407f-bbec-6c3bbd99f55d" />

3 . Data Preprocessing 🔄

Categorical variables such as Gender and Geography are converted into numerical format using encoding techniques:

Label Encoding for Gender

One-Hot Encoding for Geography

<img width="483" height="117" alt="03" src="https://github.com/user-attachments/assets/75836e24-44b5-4ff0-823b-a3598b7844f3" />

4. Feature Selection 🎯

Input features (X) and target variable (Exited) are defined for model training.

<img width="454" height="117" alt="04" src="https://github.com/user-attachments/assets/fdde5ae6-d38f-4786-ab28-3f9099a991f2" />

5. Train-Test Split ✂️

Dataset is split into training and testing sets to evaluate model performance properly.



<img width="556" height="296" alt="07" src="https://github.com/user-attachments/assets/ca067055-5ef2-48dd-8da8-85da0c273c04" />


7. Model Evaluation 📈

Model performance is evaluated using accuracy score and classification report.


<img width="488" height="210" alt="08" src="https://github.com/user-attachments/assets/0391c9f9-8310-401d-b4a7-1b6a58b91b04" />


8. Feature Importance Analysis ⭐

The model identifies which features (like age, balance, credit score) have the most impact on customer churn.


<img width="611" height="332" alt="09" src="https://github.com/user-attachments/assets/c512eed1-b7af-4101-8eb1-34bb1a8bceaf" />


<img width="860" height="478" alt="10" src="https://github.com/user-attachments/assets/e9b0e864-22b4-484e-9922-35d3569a8862" />


<img width="642" height="541" alt="11" src="https://github.com/user-attachments/assets/9991e3e7-535d-481d-9326-a64db2df1be1" />


<img width="529" height="377" alt="12" src="https://github.com/user-attachments/assets/ab94fa72-78bd-4230-a580-886fee633c9f" />


<img width="516" height="178" alt="13" src="https://github.com/user-attachments/assets/846470b9-5140-4c44-bb88-78f4b17ca7d1" />



<img width="616" height="465" alt="14" src="https://github.com/user-attachments/assets/4b35a91f-3b52-4bbc-919a-fcf793e81c6a" />


<img width="582" height="197" alt="15" src="https://github.com/user-attachments/assets/491eb37a-cac6-46ba-8a13-5871f836906e" />


<img width="570" height="382" alt="16" src="https://github.com/user-attachments/assets/24849499-dbee-493a-800d-d3e10d71e3f9" />


<img width="585" height="555" alt="17" src="https://github.com/user-attachments/assets/9a6940ed-a9d6-410e-bb06-e02011bee81d" />


<img width="617" height="475" alt="18" src="https://github.com/user-attachments/assets/03c938f0-4236-416e-8b5c-a6e94c2b09d3" />


<img width="618" height="514" alt="19" src="https://github.com/user-attachments/assets/d011db1e-755c-4710-89d2-f59838fe1f94" />


<img width="680" height="521" alt="20" src="https://github.com/user-attachments/assets/95f4eea8-2a1e-4b6f-b146-1e82eb024c4c" />


<img width="688" height="502" alt="21" src="https://github.com/user-attachments/assets/e42339fd-7902-427d-8df6-1ca12fdc4088" />



<img width="475" height="173" alt="22" src="https://github.com/user-attachments/assets/b020e0cb-9f77-47f4-bc0c-509f91ac1191" />



<img width="828" height="541" alt="23" src="https://github.com/user-attachments/assets/fbdaa042-b425-432a-a74f-96f6a232e040" />


## 📈 Key Insight

Age, Balance, and Credit Score are important factors in customer churn.

## 🚀 Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 👩‍💻 Author

Hira Imran





















































