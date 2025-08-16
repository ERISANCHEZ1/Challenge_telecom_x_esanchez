# Challenge_telecom_x_esanchez
Challenge Telecom X: análisis de evasión de clientes

# 📊 Proyecto: Análisis de Churn – Telecom X

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.5+-brightgreen.svg)
![License](https://img.shields.io/badge/License-Educational-yellow.svg)

---

## 🚀 Descripción
Este proyecto analiza la **evasión de clientes (Churn)** en Telecom X.  
Se examina un dataset de clientes con información demográfica, tipo de contrato, servicios y facturación, identificando patrones asociados a la cancelación del servicio.

El notebook incluye: limpieza de datos, transformación, análisis exploratorio, visualizaciones y correlaciones, generando insights para estrategias de retención.

---

## 📁 Dataset
- Formato: JSON  
- Fuente: [TelecomX_Data.json](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json)  
- Filas: 7,267 clientes  
- Variables principales:
  - Demográficas: `Gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - Servicios: `PhoneService`, `InternetService`, `StreamingTV`, etc.
  - Facturación: `MonthlyCharges`, `TotalCharges`, `DailyCharges`
  - Objetivo: `Churn` (Sí/No)

---

## 🛠 Requisitos
- Python 3.8+  
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`  

Instalación recomendada:
```bash
pip install pandas numpy matplotlib seaborn requests
