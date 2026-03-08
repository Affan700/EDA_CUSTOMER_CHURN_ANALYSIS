# EDA_CUSTOMER_CHURN_ANALYSIS
Executive Summary –
The visualizations use countplots to compare telecom service adoption with customer churn status, helping identify which services influence customer retention. The analysis reveals clear behavioral patterns in customer churn based on the availability of specific services.
1. PhoneService and MultipleLines
The majority of customers subscribe to PhoneService, accounting for roughly 90% of the dataset, while only about 10% do not use phone services. However, churn differences between these groups are relatively small.
 Similarly, customers with MultipleLines represent nearly 42–45% of the dataset, while around 48–50% have a single line. The churn distribution across these groups remains fairly balanced, indicating that basic telecommunication services do not strongly influence churn behavior.
2. InternetService
The InternetService feature shows a strong correlation with churn. Customers using Fiber Optic internet account for approximately 44–45% of the dataset but represent the highest churn proportion, with nearly 40–42% of them leaving the service.
 In comparison, DSL users represent about 34–36% of customers and show significantly lower churn rates (around 18–20%). Customers without internet service show the lowest churn percentage, suggesting that fiber optic customers may have higher expectations, pricing concerns, or service-related dissatisfaction.
3. OnlineSecurity, OnlineBackup, and DeviceProtection
These features display one of the clearest churn patterns in the visualizations.
Customers without OnlineSecurity represent nearly 50–55% of users, and almost 35–40% of them churn.


Customers with OnlineSecurity show much lower churn, around 15–18%.


A similar trend is observed in OnlineBackup and DeviceProtection:
Customers without these services churn at nearly twice the rate of customers who have them.


For example, churn among customers without DeviceProtection is roughly 30–35%, while it drops to around 18–20% for customers who subscribe to the service.


This suggests that value-added protection and backup services significantly improve customer retention.
4. TechSupport
Among all features, TechSupport appears to be one of the strongest indicators of churn behavior.
Customers without TechSupport make up nearly 55–60% of the dataset, and their churn rate is around 35–40%.


In contrast, customers with TechSupport have a churn rate closer to 15–18%.


This large difference highlights the importance of reliable customer support in maintaining long-term customer relationships.
5. StreamingTV and StreamingMovies
Entertainment services such as StreamingTV and StreamingMovies show relatively neutral effects on churn.
Approximately 38–40% of customers subscribe to streaming services.


Churn percentages remain similar between users and non-users, generally ranging between 25–30%.


This suggests that entertainment add-ons alone are not strong drivers of customer retention.

Overall Business Insight
The visual analysis indicates that customer support, security, and protection services have the greatest impact on reducing churn. Customers lacking these services consistently exhibit churn rates 10–20 percentage points higher than those who subscribe to them.
On the other hand, basic telecom services and entertainment features show minimal influence on churn behavior. Therefore, telecom companies aiming to improve retention should focus on:
Promoting OnlineSecurity, OnlineBackup, and DeviceProtection services.


Investigating potential service quality or pricing concerns related to Fiber Optic internet users
