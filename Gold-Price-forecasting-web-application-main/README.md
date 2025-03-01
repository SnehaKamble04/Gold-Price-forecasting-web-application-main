# 🏆 Gold Price Forecasting Web Application  

<div align="justify">  
The **Gold Price Prediction Web App** is a **Django-based application** that leverages **machine learning techniques** to predict gold prices. This project integrates **historical data analysis**, **real-time gold price fetching**, and **predictive analytics** to provide users with valuable insights into gold price trends.  
</div>  

[**🎥 Presentation**](https://www.canva.com/design/DAF4tbnq1iY/nN6byRnGjQQlbrBdkqAH0A/edit?utm_content=DAF4tbnq1iY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)  

![Overview](https://github.com/shivatejapecheti/Gold-Price-forecasting-web-application/assets/126412107/62567332-eaba-4c7d-afc1-1f31bcc10773)  

---

## 🚀 Technologies Used  

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="Django"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="40" alt="Pandas"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python"  />
</div>  

---

## 📂 Folder Structure  

```
Gold-Price-Prediction/
│── static/             # CSS, JS, Images  
│── templates/          # HTML Templates  
│── gold_prediction/    # ML Model & Data Processing  
│   │── model.py        # Prediction Logic  
│   │── data_loader.py  # Fetch & Preprocess Data  
│   │── visualization.py # Plotly-based Graphs  
│── app.py              # Main Execution Script  
│── requirements.txt    # Dependencies  
│── README.md           # Project Documentation  
```

---

## ✨ Features  

✅ **Gold Price Prediction** 📈 - Forecasts future gold prices based on historical trends  
✅ **Real-Time Data Integration** ⏳ - Fetches live gold prices using an external API  
✅ **Interactive Visualizations** 📊 - Graphical representation of trends and predictions  
✅ **Machine Learning Model** 🤖 - Implements **Linear Regression** for forecasting  
✅ **Cumulative Returns Analysis** 💰 - Simulated trading strategy for investment insights  

---

## ⚙️ Tech Stack  

1️⃣ **Django (Web Framework):** Robust and scalable web application structure.  
2️⃣ **Pandas & NumPy:** Data manipulation and analysis.  
3️⃣ **Scikit-Learn:** Machine learning model (Linear Regression).  
4️⃣ **YFinance API:** Fetches historical gold price data.  
5️⃣ **Plotly:** Creates interactive data visualizations.  
6️⃣ **Pytz:** Handles time zones.  
7️⃣ **Requests:** Integrates external API for real-time gold prices.  
8️⃣ **HTML, CSS, JavaScript:** Frontend development.  
9️⃣ **Gold API:** Fetches live gold price data.  

---

## 🎯 Project Goals  

The aim of this project is to develop a robust **predictive analytics model** for **forecasting gold ETF prices** while implementing a **simulated trading strategy** based on predictions.  

### 🔥 Achievements  

✅ **Historical Data Utilization:**  
✔️ Successfully collected and processed historical gold ETF price data (GLD) from Yahoo Finance.  

✅ **Feature Engineering:**  
✔️ Created short-term (3-day) and medium-term (9-day) moving averages for enhanced predictive accuracy.  

✅ **Predictive Modeling:**  
✔️ Developed a **Linear Regression model** with a formula:  
   ```
   Gold ETF Price (y) = a * 3-Day Moving Avg (x1) + b * 9-Day Moving Avg (x2) + c
   ```  

✅ **Model Evaluation:**  
✔️ Achieved an **R² score of %.2f**, proving model reliability.  

✅ **Visualization & Analysis:**  
✔️ Plotted historical vs. predicted prices using **Plotly**.  

✅ **Trading Strategy Simulation:**  
✔️ Implemented a predictive **buy/sell strategy** based on price trends.  

✅ **Performance Metrics:**  
✔️ **Sharpe Ratio: %.2f** - Indicates risk-adjusted returns.  

---

## 🖥️ Web Application Pages  

📌 **Home Page:** Overview of price trends, predictions, and cumulative returns.  
📌 **Plots Page:** Displays historical, predicted, and cumulative return plots.  
📌 **Gold Price Page:** Fetches and displays real-time gold prices.  
📌 **Information Page:** Shows **Linear Regression model details** and R² score.  

Additional Pages:  
📌 **Cookie Page:** Demonstrates **cookie handling**.  
📌 **Timezone Page:** Allows users to **set time zones**.  
📌 **Historical Data Page:** Shows **gold price trends over 15 days**.  

---

## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/gold-price-forecasting.git  
cd gold-price-forecasting  
```

### 2️⃣ Create Virtual Environment & Install Dependencies  
```sh
python -m venv venv  
source venv/bin/activate  # Windows: `venv\Scripts\activate`
pip install -r requirements.txt  
```

### 3️⃣ Run Migrations  
```sh
python manage.py migrate  
```

### 4️⃣ Start the Server  
```sh
python manage.py runserver  
```
Now, open **http://localhost:8000/** in your browser 🚀  

---

## 🔮 Future Enhancements  

🚀 **Advanced ML Models** - Upgrade with **LSTM, Random Forest, XGBoost**  
🚀 **User Authentication** - Secure login & profile-based tracking  
🚀 **Investment Recommendations** - AI-powered **buy/sell insights**  
🚀 **Mobile-Friendly UI** - Responsive design for easy mobile access  

---

## 📜 Conclusion  

<div align="justify">  
The **Gold Price Prediction Web App** combines **machine learning, web development, and real-time data analysis** to offer valuable insights into gold price trends. With **interactive visualizations**, **predictive analytics**, and **real-time updates**, this application serves as an essential tool for financial analysis.  
</div>  

---

## 🤝 Contributing  

🙌 Contributions are welcome!  

1️⃣ **Fork** the repo  
2️⃣ **Create a feature branch** (`feature/new-feature`)  
3️⃣ **Commit changes** (`git commit -m "Added new feature"`)  
4️⃣ **Push & Submit a PR** 🚀  

---

## 👨‍💻 Developed by  

**Sneha K. Kamble**  
📧 Email: ksnehakirti123@gmail.com  
🐙 GitHub: [SnehaKamble04](https://github.com/SnehaKamble04)  
🔗 LinkedIn: [Sneha K. Kamble](https://www.linkedin.com/in/sneha-k-kamble-48b733267/)  

🚀 **Gold Price Forecasting - Unlocking Market Insights with AI!**  
