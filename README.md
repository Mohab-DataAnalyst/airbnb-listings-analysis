
![Logo](https://shorttermrentalz.com/wp-content/uploads/2023/02/Airbnb-800x445.jpg)


# 🏡✈️ Airbnb Listings Analysis (Python)

This project analyzes **Airbnb listings in Paris**, focusing on **data preparation, quality assurance, and visualization**. The goal is to explore trends in listing prices, accommodations, and the impact of regulations over time using **Pandas, Matplotlib, and Seaborn**.
## 🚀 How It Works

1️⃣ **Data Preparation & Quality Assurance**
- Load the dataset using **Pandas**
- Convert *host_since* column to **datetime**
- Filter only **Paris** listings
- Perform **Data Cleaning & QA checks**: handle missing values, compute min/max/average for numeric fields
- Remove **listings with 0 accommodations & price**


2️⃣ **Data Transformation for Analysis**
- **Neighborhood Analysis**: Calculate the **average price** for each neighborhood
- **Accommodation Pricing**: Analyze pricing trends **in Paris' most expensive neighborhood**
- **Historical Trends**: Group listings by **year**, track **new hosts** and **price trends** over time

3️⃣ **Data Visualization**
- **Bar charts** for **price by neighborhood & accommodations**
- **Line charts** to track **new hosts and price trends**
- **Dual-axis line chart** to visualize **impact of 2015 regulations**

## 🔍 Key Findings
1️⃣ **Most Expensive Neighborhood**: The **Elysee** neighborhood had the highest **average listing price**

2️⃣ **New Hosts Trend**: The number of **new Airbnb hosts declined significantly after 2015**, likely due to regulations

3️⃣ **Price Increase Over Time**: While new hosts dropped, **prices continued to rise**, indicating a **supply-demand shift**

🔹 This analysis helps **understand market trends** and can be valuable for **Airbnb hosts, investors, and policymakers**.
## 🛠️ Technologies Used
- **Python** – Core programming language
- **Pandas** – For data cleaning & transformation
- **Matplotlib & Seaborn** – For visualization

## 🚀 How to Run the Project
1️⃣ **Clone this repository**:

    git clone https://github.com/Mohab-DataAnalyst/airbnb-listings-analysis.git
    cd airbnb-listings-analysis

2️⃣ **Install dependencies**:

    pip install pandas seaborn matplotlib

3️⃣ **Run the script**:

    python "Airbnb Listings Analysis.py"

## 📎 Acknowledgements
- This project was inspired by [@Maven Analytics.](https://youtu.be/fwOU0lfreu8?si=KrBl0J8w2is1Dzmt)
- Dataset [here.](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=airbnb)

## ✍️ Author
- 👤 [@Mohab-DataAnalyst](https://github.com/Mohab-DataAnalyst)
