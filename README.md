# Telecom X - Customer Churn Analysis

Telecom X faces a significant challenge: a growing number of customers are canceling their services. To address this issue, the company launched the **Customer Churn Analysis Project**, aiming to uncover the main causes of customer loss and provide actionable insights.

In this project, we apply **data collection, preprocessing, and exploratory analysis** techniques using **Python** and its key data science libraries. Throughout this process, we identify patterns, correlations, and potential risk factors that influence customer decisions to leave the company.

The insights generated here will serve as a foundation for the Data Science team to:
- Build predictive machine learning models.
- Develop targeted retention strategies.
- Reduce the overall churn rate and improve long-term customer engagement.

---

## 📊 Data Dictionary

| Column Name       | Description |
|-------------------|-------------|
| `customerID`      | Unique identification number for each customer. |
| `Churn`           | Indicates whether the customer has left the company (Yes/No). |
| `gender`          | Customer's gender (Male/Female). |
| `SeniorCitizen`   | Indicates whether the customer is 65 years old or older (1 = Yes, 0 = No). |
| `Partner`         | Indicates whether the customer has a partner or spouse (Yes/No). |
| `Dependents`      | Indicates whether the customer has dependents (Yes/No). |
| `tenure`          | Number of months the customer has been under contract. |
| `PhoneService`    | Indicates if the customer subscribes to phone service (Yes/No). |
| `MultipleLines`   | Indicates if the customer has more than one phone line (Yes/No). |
| `InternetService` | Type of Internet service subscribed to by the customer (e.g., DSL, Fiber optic, None). |
| `OnlineSecurity`  | Additional subscription to online security service (Yes/No). |
| `OnlineBackup`    | Additional subscription to online backup service (Yes/No). |
| `DeviceProtection`| Additional subscription to device protection service (Yes/No). |
| `TechSupport`     | Additional subscription to technical support service with shorter wait times (Yes/No). |
| `StreamingTV`     | Subscription to TV streaming service (Yes/No). |
| `StreamingMovies` | Subscription to movie streaming service (Yes/No). |
| `Contract`        | Type of contract (e.g., Month-to-month, One year, Two year). |
| `PaperlessBilling`| Indicates if the customer prefers paperless billing (Yes/No). |
| `PaymentMethod`   | Customer's payment method (e.g., Electronic check, Mailed check, Bank transfer, Credit card). |
| `Charges.Monthly` | Total monthly charges for all the customer’s subscribed services. |
| `Charges.Total`   | Total amount spent by the customer over the subscription period. |

---

## 🛠 Requirements

- Python 3.8+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- jupyterlab or jupyter notebook  

Install via pip:

```
pip install -r requirements.txt  
```
---

## 🚀 How to Run

1. **Clone the repository**  

```
git clone https://github.com/kaio326/alura-telecom-x.git
cd telecomx-churn-analysis
```

2. **Install dependencies**  

```
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**  

```
jupyter lab # or jupyter notebook
```

4. **Open and execute** 

Open and execute `notebooks/Telecom_X_Analysis.ipynb` step by step to reproduce the analysis, visualizations, and final report.

---

## 📄 License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.  
---