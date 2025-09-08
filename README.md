# 📊 Customer Purchasing Behavior Analysis  

## 📌 Project Overview  
This project analyzes the **UCI Online Retail dataset** to understand **customer purchasing behavior**.  
I used **Python (Pandas, Numpy, Matplotlib, Seaborn, SQLite3)** for data cleaning, SQL queries, and visualization.  

The goals of this project are:  
- Identify top customers and products  
- Analyze monthly revenue trends  
- Segment customers using **RFM (Recency, Frequency, Monetary)** analysis  
- Generate actionable insights for business growth  

---

## 🛠️ Tools & Technologies  
- **Python**: Pandas, Numpy, Matplotlib, Seaborn, SQLite3  
- **SQL**: SQLite for queries  
- **Jupyter Notebook**: For analysis and visualization  

---

## 📂 Project Structure
Customer_Purchasing_Behavior/
│
├── customer_purchasing_behaviour.ipynb # Jupyter Notebook with analysis
├── README.md # Project documentation
├── requirements.txt # Python libraries
├── Online Retail.xlsx # Dataset
└── images/
├── Top_10_by_revenue.png
├── Top_10_by_revenue(1).png
└── monthly_revenue_trend.png


---

## 📊 Key Insights  
- 📈 **Monthly Revenue Trend**: Shows seasonal peaks in sales.  
- 🛒 **Top Products**: A few products contribute the majority of revenue.  
- 👥 **Top Customers**: A small group of loyal customers drive high sales.  
- 🎯 **RFM Segmentation**: Customers classified as **loyal, frequent, or high-value**.  

---

## 📷 Visualizations  

### Monthly Revenue Trend  
![Monthly Revenue](images/monthly_revenue_trend.png)  

### Top 10 Products by Revenue  
![Top Products](images/Top_10_by_revenue.png)  
(images/Top_10_by_revenue(1).png)
---

## ▶️ How to Run This Project  

### 1. Clone the repository  
```bash
git clone https://github.com/<your-username>/customer-purchasing-behavior.git
cd customer-purchasing-behavior
```
### 2. Create a virtual environment (optional)
```
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux
```
### 3. Install required libraries
```
pip install -r requirements.txt
```
### 4. Dataset
```
Download the Online Retail Dataset from UCI Repository
Save it inside the data/ folder as:
data/Online Retail.xlsx
```
### 5. Open the Notebook
```
jupyter notebook customer_purchasing_behaviour.ipynb
```
