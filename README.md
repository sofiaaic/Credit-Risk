# 💳 Aplicación de Predicción de Riesgo Crediticio (Credit Risk)

Aplicación web desarrollada con **Streamlit** que predice si un solicitante representa un **Buen** o **Mal** riesgo crediticio utilizando un modelo de Machine Learning entrenado sobre el German Credit Dataset (https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk/data).

---

## 🚀 Descripción del Proyecto

Este proyecto implementa un flujo completo de Machine Learning, desde el análisis de datos hasta el despliegue de una aplicación web interactiva.

El objetivo es predecir el riesgo crediticio de un solicitante basado en información financiera y personal.

Variables utilizadas:

- Edad
- Sexo
- Nivel de trabajo
- Tipo de vivienda (Housing)
- Cuenta de ahorros
- Cuenta corriente
- Monto del crédito
- Duración del crédito

---

## 🧠 Análisis y Modelos Probados

Durante el desarrollo, se realizó un análisis exploratorio de datos y se entrenaron distintos modelos de Machine Learning para comparar su desempeño, incluyendo:

- Decision Tree
- Random Forest
- Extra Trees Classifier
- Logistic Regression

Se evaluaron utilizando métricas como:

- Accuracy


El modelo seleccionado para la aplicación final fue:

**ExtraTreesClassifier**

Debido a su mejor desempeño y capacidad de generalización.

---

## ⚙️ Procesamiento de Datos

Se aplicaron las siguientes transformaciones:

- Codificación de variables categóricas usando LabelEncoder
- Preparación de variables de entrada
- Entrenamiento y evaluación de modelos
- Serialización del modelo usando joblib

---

## 🌐 Aplicación Web

La aplicación permite al usuario ingresar datos del solicitante y obtener una predicción en tiempo real.

Desarrollada con:

**Streamlit**

---
## 📸 Demo de la aplicación

### Interfaz principal
![Demo App 1](https://github.com/user-attachments/assets/8a152539-f95a-4a45-85dc-732cf864098c)

### Resultado de la predicción
![Demo App 2](https://github.com/user-attachments/assets/189b4f82-426e-4a97-a027-5d4adde8571f)




