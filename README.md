# 📊 Power BI Dashboard: 6-Month Stock Market Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi) ![Python](https://img.shields.io/badge/Python-Data%20Extraction-blue?logo=python) ![License](https://img.shields.io/badge/Status-Completed-brightgreen)

Welcome to my Power BI dashboard project! 🚀  
This project analyzes **6 months of stock market data** for selected companies using **Python’s `yfinance` library** and visualizes trends using **Power BI**.

---

## 🧠 Objective

To extract real stock data using Python and analyze:

- 📈 Stock price trends over 6 months  
- ⚖️ Volatility (which stock fluctuates the most?)  
- 🕒 Highest trading days  
- 📊 Volume vs. price correlation  
- 🔍 Comparative closing prices

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Data extraction using `yfinance` |
| 📁 Pandas | Data cleaning & transformation |
| 📊 Power BI | Dashboard & data visualization |
| 📌 GitHub | Version control & portfolio hosting |

---

## 📁 Project Structure

PowerBI-Stock-Analysis-Dashboard/
│
├── project2.pbix # Power BI Dashboard file
├── README.md # Project overview and details
├── data/ # (Optional) Sample or processed stock data
└── images/ # Dashboard screenshots


---

## 📸 Dashboard Preview

> *(Upload a screenshot of your dashboard in the `images/` folder and insert it below)*

![Dashboard Screenshot](images/dashboard-preview.png)

---

## 📈 Key Insights

✅ Which stock is most volatile?  
✅ Which company had the highest trading volume day?  
✅ Any consistent growth trends?  
✅ Do volume spikes cause price jumps?

---
## 💡 Insights from the Dashboard

- 📉 **Most Volatile Stock:**  
  **Tesla** showed the highest volatility among the five,  
  with significant price fluctuations. This aligns with its  
  known market behavior and investor sentiment swings.

- 📈 **Consistent Growth Trend:**  
  **Microsoft** and **Apple** both exhibited relatively stable  
  and consistent upward trends over the 6-month period,  
  reflecting strong investor confidence and steady growth.

- 🔥 **Highest Trading Volume Day:**  
  **Amazon** had the highest single-day trading volume  
  during the analysis window — possibly triggered by  
  an earnings report or market event.

- ⚖️ **Volume vs Price Correlation:**  
  For most companies, especially **Google (Alphabet)** and **Tesla**,  
  sudden spikes in volume were often associated with price jumps  
  or dips, indicating potential market reactions to news or events.

- 🧠 **Closing Price Comparison:**  
  **Apple** and **Microsoft** maintained higher average closing prices  
  compared to **Amazon** and **Google**, while **Tesla** showed  
  wider swings around a moderate price range.

## 📌 How It Works

1. Used `yfinance` in Python to pull 6 months of stock data 📉  
2. Cleaned and prepared the dataset using Pandas  
3. Exported to CSV and loaded it into Power BI  
4. Created visual insights: bar charts, line graphs, slicers, and KPIs

---
## 🐍 Python Code for Data Extraction

The stock data for Apple, Amazon, Tesla, Google, and Microsoft was extracted using Python and the `yfinance` library:

## python
import yfinance as yf

companies = ["AAPL", "AMZN", "TSLA", "GOOGL", "MSFT"]
data = {}

for ticker in companies:
    stock = yf.download(ticker, period="6mo", interval="1d")
    data[ticker] = stock

## 🎥 Demo Video

Watch the demo video here: [Power BI Stock Analysis Demo](https://drive.google.com/file/d/19zq65-s1_5a-HFmdgs90ExD7diz4Z-nz/view?usp=drive_link)

## 🔍 Future Enhancements

- 🟢 Add sector-wise stock comparison  
- 🔄 Automate updates using Power BI Scheduled Refresh  
- 📡 Integrate with a real-time stock API  
- 📱 Make it mobile/tablet responsive

---

## 🤝 Connect With Me

👩‍💻 **Divya Mahajan**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Divya%20Mahajan-blue?logo=linkedin)](https://www.linkedin.com/in/divya-mahajan47)

---

## 📜 License

This project is open for learning and portfolio purposes. Attribution appreciated 😊

---
