# Título del proyecto

Análisis estadístico e interpretación de variables para el mantenimiento predictivo de máquinas industriales

## Objetivo
- **¿Qué problema resuelve?**  
  Este proyecto implementa un script capaz de representar de forma eficaz, visual e interpretativa —utilizando técnicas de Machine Learning y métricas estadísticas— qué máquinas son las que presentan fallas con mayor frecuencia, con el fin de detectar anomalías y encontrar correlaciones entre variables.
- **¿Metrica a optimizar?**  
  El principal objetivo es analizar la correlación entre las variables del dataset para interpretar patrones y, potencialmente, predecir con antelación qué máquinas podrían necesitar mantenimiento.

## Datos
- **Origen del dataset:**  
  Este proyecto utiliza un conjunto de datos obtenido de [Kaggle](https://www.kaggle.com/datasets/ziya07/smart-manufacturing-iot-cloud-monitoring-dataset), empleado con fines exploratorios y de análisis estadístico, aplicando modelos de Machine Learning para facilitar la interpretación y predicción de fallas.
- **Número de filas/columnas y variables clave:**  
  El dataset cuenta con **13 columnas** y **100,001 filas**. Las principales variables clave para este análisis son:
  - `machine_id`
  - `temperature`
  - `machine_status`
  - `anomaly_flag`

## Metodología
1. Análisis exploratorio de datos (EDA)
2. Preprocesamiento (limpieza, imputación, escalado)
3. Modelado (algoritmos de ML)
4. Evaluación (métricas y validación)
5. Interpretabilidad (importancia de variables)

## Resultados
- Métricas principales: accuracy, precision, recall, F1, AUC, etc.
- Principales hallazgos y conclusiones clave.

## Cómo ejecutar
```bash
# Recomendado: entorno virtual
pip install -r requirements.txt
# Abrir el notebook:
jupyter notebook DashBoard_EDA.ipynb

## 📦 Estructura sugerida
```
.
├── data/               # datasets (smart_manufacturing_data.csv)
├── notebooks/
│   └── DashBoard.ipynb
├── src/                # funciones reutilizables (opcional)
├── README.md
└── requirements.txt
```

## 🛠️ Requisitos
- Python 3.10+
- pandas, numpy, matplotlib, scikit-learn (si modelas)


