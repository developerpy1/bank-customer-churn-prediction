# Bank Customer Churn Prediction

## Descripción General

Este proyecto se enfoca en la predicción de abandono de clientes (customer churn) en el sector bancario utilizando técnicas de machine learning. El flujo de trabajo incluye limpieza de datos, análisis exploratorio de datos (EDA), pipelines de preprocesamiento, feature engineering, evaluación de modelos y análisis de explicabilidad.

El objetivo principal es identificar clientes con alta probabilidad de abandonar el banco y detectar patrones de comportamiento relacionados con el churn.

---

## Información del Dataset

El dataset contiene información demográfica, transaccional y financiera de clientes bancarios.

### Variables Principales

- Customer_Age
- Income_Category
- Card_Category
- Credit_Limit
- Total_Trans_Amt
- Avg_Utilization_Ratio
- Months_Inactive_12_mon
- Contacts_Count_12_mon

### Variable Objetivo

- Attrition_Flag

---

## Tecnologías Utilizadas

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- XGBoost

---

## Flujo del Proyecto

1. Limpieza de datos
2. Análisis exploratorio de datos (EDA)
3. Feature engineering
4. Preprocesamiento de datos
5. Creación de pipelines
6. Entrenamiento de modelos
7. Evaluación de modelos
8. Predicción y explicabilidad

---

## Modelos de Machine Learning

- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Classifier (SVC)
- XGBoost

---

## Métricas de Evaluación

Los modelos fueron evaluados utilizando:

- F1 Score
- Cross-Validation

---

## Insights Principales

- Los clientes con menores ingresos presentan mayor probabilidad de churn.
- Una baja actividad transaccional está relacionada con el abandono de clientes.
- Los clientes con bajo ratio de utilización suelen abandonar el servicio con mayor frecuencia.
- El comportamiento del saldo revolvente muestra una fuerte relación con el churn.


---

## Autor

Proyecto de machine learning y análisis de datos desarrollado con fines de portafolio y prácticas profesionales.
