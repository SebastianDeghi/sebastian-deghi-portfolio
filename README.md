# 👨‍💻 Sebastián Deghi — Portafolio de Proyectos

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sebastian-deghi/)
[![GitHub followers](https://img.shields.io/github/followers/SebastianDeghi?label=Follow&style=social)](https://github.com/SebastianDeghi)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=3Nq5hTIAAAAJ&hl=en)

Bienvenido a mi portafolio de proyectos en ciencia de datos y sus implementaciones. Estos involucran:

* Analisis e implementacion de diferentes modelos.
* Implementacion y reproducibilidad de los modelos óptimos.  

Aquí encontrarás mi trabajo organizado por áreas.

---

## 📊 Ciencia de Datos (Análisis y Modelado)

Estos proyectos se centran en la **comprensión de datos, ingeniería de características y evaluación de modelos**.

| Proyecto | Descripción | Tecnologías | Enlace |
|----------|-------------|-------------|--------|
| 🔍 **Detección de Fraude en Bitcoin** | Clasificación de transacciones fraudulentas en la red Bitcoin utilizando el dataset Elliptic. Análisis temporal, reducción de dimensionalidad (PCA/UMAP) y comparación de 8 modelos incluyendo XGBoost, GCN y GAT. | `XGBoost` `GCN` `GAT` `PyTorch Geometric` `scikit-learn` `Bitcoin` `AML` | [Repositorio](https://github.com/SebastianDeghi/elliptic-bitcoin-fraud-detection) |
| 🎬 **Análisis de Sentimiento en IMDB** | Clasificación binaria de sentimientos (positivo/negativo) en 50,000 reseñas de películas. Comparación de TF-IDF vs Word2Vec embeddings con modelos como Regresión Logística, SVM, Random Forest y MLP. | `NLP` `TF-IDF` `Word2Vec` `scikit-learn` `NLTK` `Gensim` `IMDB` | [Repositorio](https://github.com/SebastianDeghi/imdb-nlp-sentiment-analysis) |
| 🤖 **Comparativa de LLMs para Análisis de Sentimiento** | Evaluación de cuatro enfoques arquitectónicos para clasificación de sentimientos: BiLSTM con atención, TinyLlama 1.1B (zero-shot), GPT-Neo 1.3B (zero-shot) y BERT (DistilBERT fine-tuneado). Análisis de equilibrio entre precisión, interpretabilidad y costo computacional. | `BiLSTM` `Attention` `TinyLlama` `GPT-Neo` `BERT` `Transformers` `PyTorch` `Hugging Face` | [Repositorio](https://github.com/SebastianDeghi/imdb-llm-sentiment-analysis) |
| 🌍 **Análisis de Series Temporales de Contaminantes en Seúl** | Análisis exploratorio y limpieza de datos de calidad del aire en Seúl (2017-2020), abarcando 25 estaciones de monitoreo y 6 contaminantes (PM10, PM2.5, SO2, NO2, O3, CO). Identificación de patrones temporales, estacionales y diferencias geográficas, así como detección y corrección de errores instrumentales. | `Time Series` `EDA` `Geopandas` `Contextily` `Statsmodels` `Scipy` `Matplotlib` `Seaborn` | [Repositorio](https://github.com/SebastianDeghi/seoul-air-pollution-time-series-analysis) |
| 📈 **Forecasting de Contaminantes en Madrid** | Análisis y predicción de series temporales de NO₂ y CO en Madrid (2001-2018). Incluye tests de estacionariedad (ADF/KPSS), descomposición estacional, transformación Box-Cox, diferenciación, y modelos ARIMA y suavizado exponencial (SES, Holt, Holt-Winters). | `Time Series` `Forecasting` `ARIMA` `Holt-Winters` `Statsmodels` `Pmdarima` `Scipy` `Matplotlib` | [Repositorio](https://github.com/SebastianDeghi/madrid-air-pollution-forecasting) |

---

## ⚙️ Ingeniería de Machine Learning (Pipelines y Sistemas)

Estos proyectos enfatizan **implementación, reproducibilidad y prácticas de ingeniería**.

| Proyecto | Enfoque de Ingeniería | Aspectos Destacados | Enlace |
|----------|----------------------|---------------------|--------|
| 🔍 **Pipeline de Detección de Fraude en Bitcoin** | Pipeline end-to-end | Limpieza de datos, pipeline de validación cruzada, experimentos reproducibles | [Repositorio](https://github.com/SebastianDeghi/elliptic-bitcoin-fraud-detection) |
| 🎬 **Pipelines de Entrenamiento NLP** | Flujos de trabajo de entrenamiento | Optimización de hiperparámetros, pipelines de evaluación | [Repositorio](https://github.com/SebastianDeghi/imdb-nlp-sentiment-analysis) |
| 🤖 **Sistemas de LLM y Deep Learning** | Experimentación multi-modelo | Pipelines de zero-shot vs fine-tuning | [Repositorio](https://github.com/SebastianDeghi/imdb-llm-sentiment-analysis) |
| 📈 **Sistema de Forecasting de Series Temporales** | Pipeline de predicción | ARIMA, Holt-Winters, evaluación de modelos (RMSE, MAE) | [Repositorio](https://github.com/SebastianDeghi/madrid-air-pollution-forecasting) |

---

## 📈 Resultados Destacados

| Proyecto | Mejor Modelo / Hallazgo | Métrica | Valor |
|----------|------------------------|---------|-------|
| Detección de Fraude Bitcoin | XGBoost | F1-score | **0.94** |
| Análisis de Sentimiento IMDB (NLP básico) | Regresión Logística + TF-IDF | F1-score | **0.8955** |
| Comparativa de LLMs | BERT (DistilBERT fine-tuneado) | F1-score | **~0.93** |
| Análisis de Contaminantes en Seúl | NO₂ (patrón diario de tráfico) | Picos AM/PM | **8-9 AM y 6-7 PM** |
| Forecasting de Contaminantes en Madrid | Holt-Winters | RMSE | **~2.5 (NO₂)** |

---

## 🛠️ Tecnologías y Herramientas

| Categoría | Tecnologías |
|-----------|-------------|
| **Lenguajes** | Python, SQL |
| **Machine Learning** | scikit-learn, XGBoost, PyTorch, PyTorch Geometric |
| **NLP** | NLTK, Gensim (Word2Vec), TF-IDF, Transformers (Hugging Face) |
| **LLMs y Modelos** | TinyLlama, GPT-Neo, BERT, DistilBERT, BiLSTM, Attention |
| **Grafos** | GCN, GAT, NetworkX |
| **Series Temporales** | Statsmodels, Pmdarima, Scipy, Periodogram, Seasonal Decompose |
| **Forecasting** | ARIMA, SES, Holt, Holt-Winters |
| **Geospatial** | Geopandas, Contextily, Shapely |
| **Visualización** | Matplotlib, Seaborn, Plotly |
| **Datos** | Pandas, NumPy, UMAP, PCA |
| **Ingeniería** | Git, Docker, Linux, Jupyter |

---

## 📫 Contacto

- **GitHub:** [@SebastianDeghi](https://github.com/SebastianDeghi)
- **LinkedIn:** [@sebastian-deghi](https://www.linkedin.com/in/sebastian-deghi/)
- **Google Scholar:** [@Sebastian E. Deghi](https://scholar.google.com/citations?user=3Nq5hTIAAAAJ&hl=en)

---

## 📄 Licencia

Este portafolio está bajo la licencia **MIT**.

