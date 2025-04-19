Retail Sales Analysis using Apache Spark

Objective
This project aims to solve a real-world big data problem using **Apache Spark** by analyzing retail sales data. The goal is to extract actionable insights that help improve inventory management, optimize marketing strategies, and enhance customer satisfaction.

---

Dataset
The dataset used in this project includes the following columns:
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

Source: [Retail Sales Data Performance Analysis on GitHub / Kaggle](https://www.kaggle.com)

---

Technologies Used
- Apache Spark (PySpark)
- Python 3.x
- Jupyter Notebook / Python Script
- Matplotlib & Seaborn for visualization
- Pandas for post-processing

---

Features & Workflow

1.Data Ingestion & Cleaning
- Load dataset using PySpark
- Drop duplicates and handle missing values

2. Data Transformation
- Aggregation of total sales by:
  - Product Category
  - Customer ID
  - Monthly basis
- Convert date fields for temporal analysis

3. Data Analysis
- Identify:
  - Top-selling products
  - Most valuable customers
  - Average spend by gender
  - Monthly and seasonal sales trends

4. Data Visualization
- Visualizations generated using `matplotlib` and `seaborn`:
  - Monthly Sales Trends
  - Top Product Categories
  - Average Spend by Gender

5. Optimization Techniques
- Used `.cache()` on commonly reused datasets
- Dropped unused or invalid data early to improve performance
- Partition tuning (optional for cluster-based execution)

---

Folder Structure
Retail-Sales-Spark-Project/ │ ├── retail_sales_analysis.py / .ipynb # Main Spark script / notebook ├── Retail_Sales_Data.csv # Input data file ├── output/ # Folder to store output CSVs │ ├── sales_per_product/ │ ├── sales_per_customer/ │ └── monthly_sales/ ├── visualizations/ │ ├── monthly_sales_trend.png │ ├── top_products.png │ └── gender_spending.png └── README.md # Project documentation

 Steps to Run
1.Clone this repo:
git clone https://github.com/yourusername/Retail-Sales-Spark-Project.git
cd Retail-Sales-Spark-Project
2.Place your dataset as Retail_Sales_Data.csv in the root folder.

3.Run the analysis:
Option A: Run retail_sales_analysis.py as a script:
python retail_sales_analysis.py
Option B: Use Jupyter Notebook:
jupyter notebook
4.Check the output/ and visualizations/ folders for results.

 Key Insights
1.Top-selling categories can be focused on for marketing.

2.Customer segmentation helps in personalized campaigns.

3.Seasonal trends help improve stock and supply chain efficiency.

Author
AATMAN DESHMUKH



