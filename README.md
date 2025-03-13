# 🏦 Bank Customer Churn Prediction  

## 📌 Índice  
1. [📂 Descripción del Dataset](#-descripción-del-dataset)  
2. [🎯 Objetivo del Proyecto](#-objetivo-del-proyecto)  
3. [📊 Análisis Exploratorio](#-análisis-exploratorio)  
4. [📈 Modelado y Entrenamiento](#-modelado-y-entrenamiento)  

---

## 📂 Descripción del Dataset  
Este dataset contiene **10,000 registros y 14 columnas** con información sobre clientes de una entidad financiera.  
El objetivo es predecir la variable **Exited** (`1`: Cliente se dio de baja, `0`: Cliente sigue activo).  

### 🔹 Variables Principales:
- **CreditScore** 📊: Puntaje de crédito del cliente.  
- **Geography** 🌍: País donde reside el cliente.  
- **Gender** 👥: Género del cliente (`Male`, `Female`).  
- **Age** 🎂: Edad del cliente.  
- **Tenure** ⏳: Tiempo en años con el banco.  
- **Balance** 💰: Saldo en la cuenta bancaria.  
- **NumOfProducts** 🛍️: Número de productos contratados.  
- **HasCrCard** 💳: Tiene tarjeta de crédito (`1=Sí`, `0=No`).  
- **IsActiveMember** 🔄: Es un cliente activo (`1=Sí`, `0=No`).  
- **EstimatedSalary** 💵: Salario estimado.  
- **Exited** 🎯: Variable objetivo (`1=Cliente se va`, `0=Cliente permanece`).  

---

## 🎯 Objetivo del Proyecto  
El problema a resolver es **predecir qué clientes tienen más probabilidades de abandonar el banco**.  
Esto permitirá a la entidad financiera tomar **decisiones preventivas** y mejorar la retención de clientes.  

✔️ **Entender los factores que más influyen en la retención de clientes.**  
✔️ **Construir un modelo de Machine Learning para predecir el abandono.**  
✔️ **Evaluar el rendimiento del modelo con métricas de clasificación.**  

---

## 📊 Análisis Exploratorio  
Se realizaron los siguientes análisis:  

🔹 **Distribución de edades, ingresos y saldo bancario.**  
🔹 **Correlación entre variables para detectar patrones.**  
🔹 **Comparación de clientes que abandonaron vs. los que permanecen.**  
🔹 **Gráficos de dispersión y boxplots para detectar outliers.**  

---

## 📈 Modelado y Entrenamiento  
Se probaron diferentes algoritmos de **Machine Learning** para predecir el abandono de clientes:

🔹 **Regresión Logística**  
🔹 **Decision Tree** 🌲  
🔹 **Random Forest** 🚀  

Antes de entrenar el modelo, realizamos **preprocesamiento** de los datos:

1️⃣ **Manejo de valores nulos**  
2️⃣ **Codificación de variables categóricas**  
3️⃣ **Escalado de variables numéricas**  


