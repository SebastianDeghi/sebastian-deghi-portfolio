# 👨‍💻 Sebastián Deghi — Data Science Project Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sebastian-deghi/)
[![GitHub followers](https://img.shields.io/github/followers/SebastianDeghi?label=Follow&style=social)](https://github.com/SebastianDeghi)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=3Nq5hTIAAAAJ&hl=en)

Welcome to my Data Science and Machine Learning Engineering portfolio.

This repository showcases projects that combine:

- **Data analysis and model development**
- **Production-oriented implementations of selected models**

Projects are organized by focus area.

---

## 📊 Data Science (Analysis & Modeling)

These projects focus on **data understanding, feature engineering, and model evaluation**.

| Project | Description | Technologies | Link |
|--------|-------------|-------------|------|
| 🔍 **Bitcoin Fraud Detection** | Classification of fraudulent transactions in the Bitcoin network using the Elliptic dataset. Includes temporal analysis, dimensionality reduction (PCA/UMAP), and comparison of 8 models such as XGBoost, GCN, and GAT. | `XGBoost` `GCN` `GAT` `PyTorch Geometric` `scikit-learn` `Bitcoin` `AML` | [Repository](https://github.com/SebastianDeghi/elliptic-bitcoin-fraud-detection) |
| 🎬 **IMDB Sentiment Analysis** | Binary sentiment classification (positive/negative) on 50,000 movie reviews. Comparison between TF-IDF and Word2Vec embeddings using models such as Logistic Regression, SVM, Random Forest, and MLP. | `NLP` `TF-IDF` `Word2Vec` `scikit-learn` `NLTK` `Gensim` `IMDB` | [Repository](https://github.com/SebastianDeghi/imdb-nlp-sentiment-analysis) |
| 🤖 **LLMs for Sentiment Analysis** | Evaluation of four architectures for sentiment classification: BiLSTM with attention, TinyLlama 1.1B (zero-shot), GPT-Neo 1.3B (zero-shot), and fine-tuned DistilBERT. Focus on performance vs computational cost and interpretability trade-offs. | `BiLSTM` `Attention` `TinyLlama` `GPT-Neo` `BERT` `Transformers` `PyTorch` `Hugging Face` | [Repository](https://github.com/SebastianDeghi/imdb-llm-sentiment-analysis) |
| 🌍 **Seoul Air Pollution Time Series Analysis** | Exploratory analysis and data cleaning of air quality data in Seoul (2017–2020), covering 25 monitoring stations and 6 pollutants. Includes temporal, seasonal, and spatial pattern analysis, as well as anomaly detection. | `Time Series` `EDA` `Geopandas` `Contextily` `Statsmodels` `Scipy` `Matplotlib` | [Repository](https://github.com/SebastianDeghi/seoul-air-pollution-time-series-analysis) |
| 📈 **Madrid Air Pollution Forecasting** | Time series analysis and forecasting of NO₂ and CO levels (2001–2018). Includes stationarity testing (ADF/KPSS), seasonal decomposition, Box-Cox transformation, differencing, and ARIMA / exponential smoothing models. | `Time Series` `Forecasting` `ARIMA` `Holt-Winters` `Statsmodels` `Pmdarima` | [Repository](https://github.com/SebastianDeghi/madrid-air-pollution-forecasting) |

---

## ⚙️ Machine Learning Engineering (Pipelines & Systems)

These projects emphasize **implementation, reproducibility, and engineering best practices**.

| Project | Engineering Focus | Highlights | Link |
|--------|------------------|------------|------|
| 🔍 **Bitcoin Fraud Detection Pipeline** | End-to-end pipeline | Data preprocessing, cross-validation pipeline, reproducible experiments | [Repository](https://github.com/SebastianDeghi/elliptic-bitcoin-fraud-detection) |
| 🎬 **NLP Training Pipelines** | Training workflows | Hyperparameter tuning, evaluation pipelines | [Repository](https://github.com/SebastianDeghi/imdb-nlp-sentiment-analysis) |
| 🤖 **LLM & Deep Learning Systems** | Multi-model experimentation | Zero-shot vs fine-tuning pipelines | [Repository](https://github.com/SebastianDeghi/imdb-llm-sentiment-analysis) |
| 📈 **Time Series Forecasting System** | Prediction pipeline | ARIMA, Holt-Winters, model evaluation (RMSE, MAE) | [Repository](https://github.com/SebastianDeghi/madrid-air-pollution-forecasting) |

---

## 📈 Key Results

| Project | Best Model / Insight | Metric | Value |
|--------|----------------------|--------|-------|
| Bitcoin Fraud Detection | XGBoost | F1-score | **0.94** |
| IMDB Sentiment Analysis | Logistic Regression + TF-IDF | F1-score | **0.8955** |
| LLM Comparison | Fine-tuned DistilBERT | F1-score | **~0.93** |
| Seoul Air Analysis | NO₂ daily traffic pattern | Peak hours | **8–9 AM / 6–7 PM** |
| Madrid Forecasting | Holt-Winters | RMSE | **~2.5 (NO₂)** |

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Languages** | Python, SQL |
| **Machine Learning** | scikit-learn, XGBoost, PyTorch, PyTorch Geometric |
| **NLP** | NLTK, Gensim, TF-IDF, Transformers (Hugging Face) |
| **LLMs & Models** | TinyLlama, GPT-Neo, BERT, DistilBERT, BiLSTM, Attention |
| **Graph ML** | GCN, GAT, NetworkX |
| **Time Series** | Statsmodels, Pmdarima, Scipy |
| **Forecasting** | ARIMA, Holt-Winters, SES |
| **Geospatial** | Geopandas, Contextily, Shapely |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Data Processing** | Pandas, NumPy, PCA, UMAP |
| **Engineering** | Git, Docker, Linux, Jupyter |

---

## 📫 Contact

- **GitHub:** [@SebastianDeghi](https://github.com/SebastianDeghi)  
- **LinkedIn:** [@sebastian-deghi](https://www.linkedin.com/in/sebastian-deghi/)  
- **Google Scholar:** [Sebastián E. Deghi](https://scholar.google.com/citations?user=3Nq5hTIAAAAJ&hl=en)

---

## 📄 License

This portfolio is licensed under the **MIT License**.