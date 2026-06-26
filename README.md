💊 PharmaPulse Commercial Analytics

An end-to-end commercial analytics case study focused on pharmaceutical product demand analysis using Python, SQL, Pandas, NumPy, Matplotlib, and Tableau.

This project demonstrates a complete analytics workflow, starting from raw pharmaceutical sales data, performing data cleaning and exploratory data analysis (EDA), extracting business insights using SQL, and building an interactive Tableau dashboard for decision-making.

⸻

📌 Project Overview

The objective of this project is to analyze pharmaceutical sales performance and answer key business questions such as:

* Which drug category contributes the highest sales?
* How do sales vary across months and years?
* Which weekdays generate the highest revenue?
* What sales patterns and trends can be identified?
* Which products should receive greater commercial focus?

docs/
├── dashboard.png
├── output1.png
├── output2.png
├── output3.png
├── output4.png
├── output5.png
└── output6.png


<img width="1710" height="1112" alt="Screenshot 2026-06-26 at 1 52 35 PM" src="https://github.com/user-attachments/assets/fc99e129-440d-4604-b9ea-1d1702b9e250" />


<img width="868" height="505" alt="output1" src="https://github.com/user-attachments/assets/498a9071-b52b-4f38-a5b8-65054737186e" />




<img width="868" height="505" alt="output1" src="https://github.com/user-attachments/assets/6bf9623b-e4cc-4e61-bdc6-892cec0125fc" />



<img width="1014" height="547" alt="output3" src="https://github.com/user-attachments/assets/7d861d5e-e2af-44b3-b950-944ded7d5559" />


<img width="1023" height="614" alt="output4" src="https://github.com/user-attachments/assets/616f06b6-577f-4c58-b3eb-0fbc5342b351" />


<img width="764" height="682" alt="output5" src="https://github.com/user-attachments/assets/a752c109-a28d-4868-a248-f8c455c9c46a" />


<img width="1160" height="528" alt="output6" src="https://github.com/user-attachments/assets/ffb9fcc2-ab22-41a0-a879-6250ebf49b3d" />



⸻

🛠️ Tech Stack

* Python
* Pandas
* NumPy
* SQL (SQLite)
* Matplotlib
* Jupyter Notebook
* Tableau Public
* Git & GitHub

⸻

📂 Project Structure

PharmaPulse-Commercial-Analytics/
│
├── data/
│   ├── salesdaily.csv
│   ├── salesweekly.csv
│   ├── salesmonthly.csv
│   ├── saleshourly.csv
│   └── pharma_cleaned.csv
│
├── python/
│   └── notebooks/
│       ├── 01_Data_Understanding.ipynb
│       ├── 02_SQL_Analysis.ipynb
│       └── pharma_sales.db
│
├── tableau/
│   └── PharmaPulse_Dashboard.twb
│
├── docs/
│   └── dashboard.png
│
├── requirements.txt
└── README.md

⸻

📊 Exploratory Data Analysis

Total Sales by Drug Category

Insights

* N02BE is the highest-selling drug category (~63K sales).
* N05B ranks second with approximately 18.6K sales.
* N05C records the lowest sales.

⸻

Monthly Sales Trend

Insights

* Sales peak during January and October.
* Mid-year demand declines before recovering in the last quarter.
* N02BE consistently dominates every month.

⸻

Yearly Sales Trend

Insights

* Highest annual sales were observed in 2016.
* Sales declined after 2018.
* N02BE remained the leading contributor every year.

⸻

Sales by Weekday

Insights

* Saturday generated the highest sales.
* Thursday recorded the lowest overall sales.
* Weekend demand is stronger than weekdays.

⸻

Drug Sales Distribution

Insights

* N02BE shows the highest variability and several outliers.
* Most remaining drug categories have relatively stable sales distributions.

⸻

Correlation Heatmap

Insights

* Drug categories exhibit generally weak positive correlations.
* No strong multicollinearity is observed between products.

⸻

📈 Interactive Tableau Dashboard

The Tableau dashboard provides interactive visualizations including:

* Total Sales by Drug Category
* Monthly Sales Trend
* Yearly Sales Trend
* Sales by Weekday
* Drug Sales Distribution

Tableau Public Dashboard

https://public.tableau.com/views/Book1_17824501614620/Dashboard2

⸻

📌 Key Business Insights

* N02BE contributes nearly half of the overall sales revenue.
* Sales are strongest during weekends, particularly Saturday.
* Demand decreases during the middle of the year before recovering in Q4.
* Annual sales peaked in 2016, followed by a gradual decline.
* Most drug categories operate independently with weak correlations.

⸻

🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* SQL Querying
* Business Analytics
* Data Visualization
* Dashboard Design
* Statistical Analysis
* Commercial Analytics
* Git Version Control

⸻

👩‍💻 Author

Shloka Shetty

GitHub: https://github.com/sagusoky

LinkedIn: https://www.linkedin.com/in/shloka-g-shetty/
