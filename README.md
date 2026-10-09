# 🍔 Food Delivery Data Analysis

<p align="center">
  <strong>Exploratory Data Analysis using Python, Pandas, NumPy & Matplotlib</strong>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-objectives">Objectives</a> •
  <a href="#-dataset">Dataset</a> •
  <a href="#-analysis">Analysis</a> •
  <a href="#-visualizations">Visualizations</a> •
  <a href="#-installation">Installation</a>
</p>

---

## 📌 Overview

The **Food Delivery Data Analysis** project explores food delivery orders to identify revenue trends, popular cuisines, restaurant performance, customer ratings, payment preferences, and delivery efficiency.

Using Python and its data analysis libraries, this project transforms sample order data into meaningful insights through **Exploratory Data Analysis (EDA), statistical calculations, and data visualizations**.

## 🎯 Objectives

- Analyze total, delivered, and canceled orders.
- Calculate total revenue and average order value.
- Identify the highest-revenue restaurants.
- Discover popular cuisines.
- Analyze monthly revenue trends.
- Compare payment methods and city-wise orders.
- Evaluate restaurant ratings.
- Study delivery time distributions.
- Explore the relationship between delivery time and customer ratings.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Jupyter Notebook / VS Code | Development environment |
| Exploratory Data Analysis | Discovering trends and patterns |

## 📂 Dataset

Dataset file: `data/food_delivery.csv`

The dataset contains sample food delivery order records.

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date of the order |
| `Restaurant` | Restaurant name |
| `Cuisine` | Cuisine category |
| `Customer_ID` | Customer identifier |
| `City` | Order city |
| `Order_Value` | Order amount |
| `Delivery_Time_Min` | Delivery time in minutes |
| `Payment_Method` | Payment method used |
| `Rating` | Customer rating |
| `Order_Status` | Delivered or canceled status |

**Note:** This project uses a sample dataset created for learning and portfolio development. It does not represent actual food delivery company data.

## 🔍 Analysis Performed

### 1. Order Analysis
- Total number of orders
- Delivered and canceled orders
- Cancellation rate

### 2. Revenue Analysis
- Total revenue from delivered orders
- Average order value
- Revenue by restaurant
- Revenue by cuisine
- Monthly revenue trends

### 3. Restaurant and Cuisine Analysis
- Restaurant revenue comparison
- Most popular cuisines
- Average restaurant ratings
- Average delivery time by cuisine

### 4. Customer and Payment Analysis
- Orders by city
- Payment method distribution
- Customer rating patterns

### 5. Delivery Performance
- Average delivery time
- Delivery time distribution
- Relationship between delivery time and customer ratings

## 📊 Visualizations

The project generates the following charts:

- Order Status Distribution
- Revenue by Restaurant
- Orders by Cuisine
- Revenue by Cuisine
- Orders by Payment Method
- Orders by City
- Average Rating by Restaurant
- Delivery Time Distribution
- Monthly Revenue Trend
- Average Delivery Time by Cuisine
- Delivery Time vs Customer Rating

## 📈 Key Performance Indicators (KPIs)

- Total Orders
- Delivered Orders
- Canceled Orders
- Cancellation Rate
- Total Revenue
- Average Order Value
- Average Delivery Time
- Average Customer Rating
- Top Restaurant by Revenue
- Most Popular Cuisine
- Most Used Payment Method

Revenue is calculated using **delivered orders only**, excluding canceled orders from completed sales.

## 📁 Project Structure

```text
Food-Delivery-Data-Analysis/
│
├── data/
│   └── food_delivery.csv
│
├── food_delivery_analysis.py
│
└── README.md
```

## ⚙️ Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/shejal24-rgb/Food-Delivery-Data-Analysis.git
```

### Step 2: Open the Project Folder

```bash
cd Food-Delivery-Data-Analysis
```

### Step 3: Install Dependencies

```bash
pip install pandas numpy matplotlib
```

## ▶️ Run the Project

Run the Python analysis script from the project folder:

```bash
python food_delivery_analysis.py
```

Ensure the CSV file is located at `data/food_delivery.csv` and that the file path in the Python script matches your folder structure.

## 💡 Business Questions Answered

- Which restaurant generates the highest revenue?
- Which cuisine receives the most orders?
- What percentage of orders are canceled?
- Which city has the most orders?
- Which payment method is most popular?
- Which restaurant has the highest average rating?
- What is the average food delivery time?
- How does delivery time relate to customer ratings?
- Which month generates the highest revenue?

## 📚 Learning Outcomes

By completing this project, you will practice:

- Loading and inspecting CSV datasets
- Data validation and duplicate detection
- Date and time conversion
- Filtering data using Pandas
- GroupBy aggregation and sorting
- Revenue and KPI calculations
- Descriptive statistics
- Data visualization using Matplotlib
- Business-oriented data interpretation
- Organizing a GitHub portfolio project

## 🚀 Future Enhancements

- Build an interactive Power BI dashboard.
- Add advanced customer segmentation.
- Analyze peak ordering hours.
- Explore restaurant and cuisine profitability.
- Create interactive charts using Plotly.
- Develop a delivery-time prediction model.
- Expand the dataset with more records and realistic variables.

## 👨‍💻 Author

**Shejal Dhakate**

- GitHub: https://github.com/shejal24-rgb
- LinkedIn: https://linkedin.com/in/shejaldhakate

## ⭐ Support

If you find this project useful, consider giving the repository a star ⭐.

