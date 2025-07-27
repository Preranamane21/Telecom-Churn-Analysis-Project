📊 **Telecom-Churn-Analysis-Project**
A complete Data Analytics and Machine Learning project aimed at identifying customer churn trends, analyzing customer behavior, and predicting future churners using SQL Server, Power BI, and Python (Random Forest model).

**🚀 Project Objective**

-Analyze customer churn using demographic, geographic, service, and account information.
-Visualize and monitor churn trends using Power BI dashboards.
-Build a machine learning model to predict potential future churners.

**🛠 Tools & Technologies**

**-SQL Server** – ETL process and data storage
**-Power BI** – Data transformation, DAX measures, and visualizations
**-Python (Jupyter Notebook)** – Random Forest model for churn prediction
-Pandas, Sklearn, Matplotlib, Seaborn, Joblib – ML libraries used

 **🔁 ETL Process (Step 1)**
 
Loaded customer data into SQL Server from source file.

Created necessary views:
-**vw_ChurnData**
**-vw_JoinData**

 **📈 Power BI Dashboard (Steps 2 to 4)**
 
**-Summary Page**

**KPIs:** Total Customers, New Joiners, Total Churn, Churn Rate %
**Demographic Analysis:** Gender, Age Group
**Account Info:** Payment Method, Contract, Tenure Group
**Geographic:** Top 5 States by Churn Rate
**Service Usage & Churn Reasons:** Internet Type, Services Used, Churn Category

**🔍 Churn Reasons (Tooltip Page)**

Churn Reason-wise distribution of total churners.

**📊 Churn Prediction (Steps 5 & 6)**

Model: Random Forest Classifier
Built in Python (Jupyter Notebook)
Trained on customer churn data from SQL Server
Exported predictions to Excel/CSV

**Power BI Integration**

Imported predicted churn data
Created measures and visuals to highlight predicted churners

📊 **Prediction Page Includes**

**Customer Grid:** ID, Monthly Charges, Total Revenue, Refunds, Referrals
**Demographic & Account Info:** Gender, Age Group, Marital Status, Payment, Contract, Tenure
**Geographic Info:** State-wise Churn Count

**📁 Project Structure**

**📦Telecom_Churn_Analysis**

│
├── data/
│   └── Customer_Data.xlsx
│
├── sql/
│   └── etl_scripts.sql
│
├── notebook/
│   └── churn_prediction_model.ipynb
│
├── powerbi/
│   └── Telecom_Churn_Dashboard.pbix
│
└── README.md

**✅Key Metrics Tracked**

Total Customers
Churn Count & Churn Rate , New Joiners
Churn Distribution by: Demographics (Age, Gender)
Services Used Geography (Top States)
Account Info (Tenure, Contract, Payment Method)

**📌 Results & Insights**

Identified churn-prone customer segments.
Recommended data-driven marketing interventions.
Enabled early churn detection with ML predictions.

