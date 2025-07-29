# Predicción del precio de Bitcoin (BTC)

Este repositorio contiene un cuaderno de Jupyter para analizar series de tiempo de **Bitcoin (BTC)** 
y construir un modelo de predicción del precio (por ejemplo, precio de cierre).
Incluye exploración de datos, preparación de la serie, entrenamiento, evaluación y visualización de resultados. 
También se adjunta un informe con el resumen del proyecto.


## 🧠 Objetivos

- Cargar y preparar datos históricos de BTC (OHLCV o al menos cierre).
- Analizar la estacionalidad/tendencias y realizar pruebas de estacionariedad.
- Entrenar un modelo de predicción con ARIMA.
- Evaluar el desempeño (MSE/MAE/MAPE/RMSE) e interpretar resultados.
- Generar proyecciones a corto/mediano plazo y visualizarlas.

## 📦 Dependencias
- Python 3.9+  
- Jupyter Notebook / JupyterLab  
- pandas, numpy, matplotlib  
- scikit-learn (métricas y escalado)  
- statsmodels (ARIMA/SARIMA)  
- prophet (opcional, si usaste Prophet)  
- tensorflow / keras (opcional, si usaste LSTM/GRU)  
- yfinance / ccxt / requests (según fuente de datos)

Puedes instalar un conjunto típico así (ejemplo):

pip install jupyter pandas numpy matplotlib scikit-learn statsmodels yfinance
# Opcionales:
pip install prophet
pip install tensorflow

