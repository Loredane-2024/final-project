# Bank Customer Churn Analysis

## 📊 Project Overview
This project analyzes customer churn data from a bank, focusing on variables like age, balance, engagement, and other characteristics to understand the factors that influence whether customers stay or leave. We use statistical techniques, machine learning models, and visualizations to uncover insights and predict customer churn.

## 📁 Dataset
[Churn for Bank Customers dataset](https://www.openml.org/search?type=data&status=active&id=43390&sort=runs)

The dataset contains the following customer information:
- **CustomerId**: Unique ID for each customer.
- **Surname**: Customer’s last name.
- **CreditScore**: Credit score of the customer.
- **Geography**: Country of the customer (France, Spain, Germany).
- **Gender**: Male or Female.
- **Age**: Customer's age.
- **Tenure**: Number of years the customer has been with the bank.
- **Balance**: Bank balance of the customer.
- **NumOfProducts**: Number of products the customer has with the bank.
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary**: Customer’s estimated salary.
- **Exited**: Whether the customer has churned (1 = Yes, 0 = No).

## 🔑 Key Steps and Analyses
### 1. 🔍 Exploratory Data Analysis (EDA)
We conducted EDA to understand the dataset structure, identify missing values, and visualize key insights related to customer churn.
- **Visualizations**: Bar plots, box plots, and histograms were used to compare churn rates across features such as Age, Geography, and Active Membership.
- **Hypothesis Testing**:
    - **Active Membership and Churn**: A z-test assessed whether active members are significantly less likely to churn compared to inactive members.
    - **Balance and Churn**: A t-test checked if customers with higher balances were more likely to churn than those with lower balances.
    - **Age and Churn**: Another t-test explored whether older customers are more likely to churn than younger customers.

### 2. 🛠️ Data Preprocessing
- Dropped unnecessary columns.
- Encoded categorical variables such as Geography and Gender for analysis.

### 3. 📊 Visualization
- **Using Matplotlib, Seaborn, and Tableau**: We visualized relationships between variables like Balance, Age, and Active Membership, comparing churned vs. non-churned customers.
- **Custom Color Schemes**: Orange and gray were used to represent No Churn and Churn in the visuals.

### 4. 🤖 Churn Prediction
Various machine learning models (e.g., Logistic Regression, Gradient Boosting) were tuned using hyperparameters to predict churn. We also analyzed feature importance, focusing on variables like Age, Balance, and Engagement.

## 💡 Key Insights
- **Differences in Needs for Older Customers**: Older customers may have unmet financial needs, leading to dissatisfaction, especially with technology-driven services.
- **Customer Engagement and Retention**: Active engagement with the bank strongly correlates with customer retention. Banks could reduce churn by offering personalized services or loyalty programs to less active members.
- **High-Balance Customers and Higher Churn Rates**: Surprisingly, customers with higher balances tend to churn more, possibly seeking better offers elsewhere. Banks could counter this by providing personalized financial advice or exclusive products.

## 🛠️ Tools and Technologies
- **Python**: For data analysis, machine learning, and visualization.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For data visualizations (e.g., correlation matrices, box plots, histograms).
- **Scikit-learn**: For machine learning, hyperparameter tuning, and managing imbalanced data.
- **Jupyter Notebook**: For interactive analysis and reporting.
- **Tableau**: For creating interactive dashboards and additional visualizations.
- **Trello**: For project management and tracking tasks.
- **Miro**: For creating visual workflows during project development.

## 🏁 Conclusion
This project provides a comprehensive analysis of customer churn using statistical techniques, machine learning, and advanced visualizations. The insights gained from the analysis help in understanding customer behavior and can assist in developing targeted strategies to reduce churn. The use of ensemble methods, hyperparameter tuning, and handling imbalanced data ensures robust churn prediction.

Check out the interactive dashboard on [Tableau](https://public.tableau.com/app/profile/loredane.nery.da.silva/viz/ChurnforBankCustomers_17278781811900/ChurnAnalysis?publish=yes)

[Final Project Presentation](https://www.canva.com/design/DAGR3aV9D4E/w-NakodSH5ZC6CbESDgBog/view?utm_content=DAGR3aV9D4E&utm_campaign=designshare&utm_medium=link&utm_source=editor)
