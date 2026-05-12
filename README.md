# sales-dashboard-recommender
Sales analytics dashboard with hybrid recommendation system (Jupyter Notebook)
Overview
This project combines sales analytics and a hybrid recommendation engine into one interactive Jupyter Notebook dashboard.
It provides insights into sales trends, category distribution, customer segmentation, and personalized product recommendations with explainability.
Features
Sales Analytics
Line chart of sales trends over time
Category distribution pie chart

Customer Segmentation
Bar chart showing distribution of customer segments

Personalized Recommendations
Hybrid recommender (user‑based + item‑based + popularity fallback)
Explainability layer (shows why each product is recommended)

Cold Start Handling
Popular products recommended for new customers

Dashboard View
Multi‑panel layout combining analytics and recommendations

Tech Stack
Python (Pandas, NumPy)

Matplotlib / Seaborn (visualizations)

Scikit‑learn (similarity calculations)

Jupyter Notebook (interactive dashboard)
working-
Data Preparation  
Transaction data with transaction_date, product_id, product_name, customer_id, customer_segment, quantity.

Analytics  
Grouped by date, category, and segment for insights.

Recommendation Engine

User‑based collaborative filtering

Item‑based collaborative filtering

Popularity fallback for cold start

Hybrid approach blends all three.

Explainability  
Each recommendation includes a reason:

“Similar customers bought this”

“Popular fallback recommendation”

Dashboard View
Top‑left: Sales trend line chart

Top‑right: Category distribution pie chart

Bottom‑left: Customer segmentation bar chart

Bottom‑right: Personalized recommendations bar chart




