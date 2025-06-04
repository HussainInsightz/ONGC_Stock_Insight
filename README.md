
# Title:- 📊 ONGC Stock Insight Analysis

# About this project:- 🔍This project dives deep into the historical stock performance of **ONGC (Oil and Natural Gas Corporation)** using Python. By leveraging time-series data analysis techniques, the project uncovers trends in prices, trading volumes, volatility, and key financial patterns.

# Aim - 🎯To extract valuable insights from ONGC's historical stock data using Python-based analysis methods such as:
-> Time-series visualization
-> Rolling average trend analysis
-> Volatility measurement
-> Volume spike detection

-------------------------------------------------------------------------------------------------------------------------------------------

## 📁 Dataset
- **Source**: [Kaggle – ONGC Stock Performance Dataset](https://www.kaggle.com/datasets/nitirajkulkarni/ongc-ns-stock-performance)  
- **Ticker**: `ONGC.NS`  
- **Fields Used**: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`

-------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools & Libraries Used
- **Language**: Python  
- **Libraries**:  
  - `Pandas` for data manipulation  
  - `Matplotlib` & `Seaborn` for visualization  
  - `NumPy` for numerical operations  
- **Platform**: Jupyter Notebook

-------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Objectives

- Clean and preprocess historical stock data
- Analyze OHLC prices and trading volume patterns
- Plot histograms and KDE curves for distribution analysis
- Visualize moving averages (MA20 and MA50)
- Measure volatility using rolling standard deviation
- Detect unusual volume spikes
- Plot a correlation heatmap of key financial features

-------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Sample Visualizations

All plots are auto-generated and saved under the `Plots/` directory:

- ![Correlation Matrix](Python_Project/Plots/Correlation_matrix.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_Open.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_High.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_Low.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_Close.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_adjclose.png)
- ![Histogram+KDE](Python_Project/Plots/Distribution_Volume.png)
- ![Line Chart](Python_Project/Plots/Moving_Average(20,50))
- ![Line Chart](Python_Project/Plots/Volatility(10))
- ![Lollipop+Line Chart](Python_Project/Plots/Volume_and_spikes)

-------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Key Features

- 📈 Moving Average Trendlines (MA20, MA50)  
- 📉 Rolling Volatility Tracking  
- 🔺 Volume Spike Detection using 20-day average  
- 🧼 Null value handling with forward and backward fill  
- 📊 Histograms + KDE for each numeric column  
- 🧠 Correlation Heatmap using custom colormaps

-------------------------------------------------------------------------------------------------------------------------------------------

## 🗂️ Project Structure

```bash
📁 Python_Project
│
├── ONGC_Stock_RawData.csv			# Raw CSV file (Downloaded)
├── ONGC_Stock_CleanedData.csv			# Cleaned CSV file (Exported)
├── ONGC_Stock_Insight.ipynb			# Python jupyter notebook 
├── Plots					# All graph  
└── README.md					# This file 

-------------------------------------------------------------------------------------------------------------------------------------------

## 🚀 How to Run

1. Clone or download this repository  
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn

-------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Future Scope

- Add stock price forecasting using Linear Regression or ARIMA
- Deploy as an interactive dashboard with Streamlit
- Integrate live stock data using the Yahoo Finance API
- Export insights as automated reports

-------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 Learnings

- Data cleaning and preprocessing techniques
- How to handle stock time-series data
- Importance of correlation analysis in finance
- Moving Average
- Volatility
- Volume and Spikes
- Visual analytics for financial datasets

-------------------------------------------------------------------------------------------------------------------------------------------

## 👤 Author
**Mohd Hussain Khan**  
MSc. Data Science | Data Enthusiast | Data Scientist, Data Analyst | ML, AI in progress
[LinkedIn](www.linkedin.com/in/HussainInsightz) | [GitHub](https://github.com/your-username)

## 📌 License
This project is open-source and available for learning, research, and academic demonstration purposes.