# 🍎 Apple Stock Price Forecasting using LSTM

A deep learning project that forecasts **Apple Inc. (AAPL) stock prices** using **Long Short-Term Memory (LSTM)** neural networks. The project includes an end-to-end Jupyter Notebook for data exploration and modeling, along with an interactive **Streamlit web application** for real-time forecasting.

---

## 📌 Project Overview

This project uses historical Apple stock data (2002–2023) to:
- Perform **Exploratory Data Analysis (EDA)**
- Visualize stock trends using **Plotly** and **Matplotlib**
- Build and train an **LSTM model** using **TensorFlow/Keras**
- Deploy an interactive **Streamlit app** to forecast future stock prices

---

## 🗂️ Project Structure

```
Forecasting_Project/
│
├── Final_Apple.ipynb        # Main Jupyter Notebook (EDA + LSTM Model)
├── lstm.py                  # Streamlit web app for forecasting
├── Apple_dataset.csv        # Historical Apple stock data (2002–2023)
├── dataset.csv              # Supporting dataset
├── validation.csv           # Validation data
├── Apple_project.pptx       # Project presentation slides
├── requirements.txt         # Python dependencies
├── LICENSE                  # MIT License
└── README.md                # Project documentation
```

---

## 🧠 Model Architecture

- **Input**: Time-series stock prices (Close price)
- **Preprocessing**: MinMax Scaling, sliding window (time steps = 10)
- **Model**: 2-layer LSTM → Dense output
- **Optimizer**: Adam | **Loss**: Mean Squared Error (MSE)
- **Epochs**: 10 | **Batch Size**: 128

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/SyamSashank1512/Forecasting-of-Apple.git
cd Forecasting-of-Apple
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App
```bash
streamlit run lstm.py
```

### 4. Open the Notebook
Launch Jupyter and open `Final_Apple.ipynb` for full analysis.

---

## 📊 Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python 3 |
| Deep Learning | TensorFlow, Keras |
| Data Processing | Pandas, NumPy, Scikit-learn |
| Visualization | Matplotlib, Seaborn, Plotly |
| Web App | Streamlit |
| Notebook | Jupyter |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
