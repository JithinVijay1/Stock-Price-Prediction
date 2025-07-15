# Stock-Price-Prediction
Stock price prediction using a hybrid MS-SSA-LSTM model integrating sentiment analysis
# MS-SSA-LSTM Stock Price Prediction

This project implements a hybrid deep learning model (MS-SSA-LSTM) for stock price prediction by combining:

- Long Short-Term Memory (LSTM) networks  
- Sentiment Analysis from financial forums  
- Singular Spectrum Analysis (SSA) for signal enhancement  

## 🚀 Key Features

- Web scraped financial forum data using `BeautifulSoup`
- Created sentiment index for modeling using NLP techniques
- Optimized LSTM hyperparameters using SSA, improving R² by **10.74%**
- Built using `TensorFlow`, `Keras`, `NumPy`, `Pandas`
- Visualized results with `Matplotlib` and `Seaborn`

## 📁 Project Structure

├── data/ # Raw & processed data
├── models/ # Saved model weights
├── src/ # Source code for preprocessing, training
├── notebooks/ # Jupyter notebooks (EDA, modeling)
├── requirements.txt # Python dependencies
└── README.md # Project overview

## 📊 Results

The model achieved significant improvements in prediction accuracy over baseline LSTM models, validated by a **10.74% higher R² score**.

## 📌 Technologies Used

- Python
- TensorFlow & Keras
- Pandas, NumPy
- Matplotlib, Seaborn
- BeautifulSoup (for web scraping)
- NLP libraries

## 🧠 Future Work

- Integrate real-time data pipelines
- Explore Transformer-based architectures (e.g., BERT + LSTM)

## 📜 License

MIT License

