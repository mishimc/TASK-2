# 🚀 Dashboard de Predicción de Churn con Streamlit

**Predice el abandono de clientes usando ML y visualiza insights clave.**

## 📌 Descripción
Dashboard interactivo que compara modelos de Machine Learning modelos (Random Forest, Regresión Logística y stacking classifier) para predecir *churn*, mostrando:
- 🔍 **Métricas de rendimiento** (Accuracy, F1, AUC).
- 📊 **Visualizaciones de variables** (top features).
- 🤖 **Inferencias en tiempo real** sobre clientes en riesgo.

## 🛠️ Ejecución
1. Asegurarse de que se tiene instalado lo descrito en ``requirements.txt``
2. Revisar que los archivos tengan el fornmato correcto, por ejemplo:
   - `app.py` *(aplicación principal en Streamlit)*  
   - `stack.pkl`, `random.pkl`, `regresion.pkl`, `stack2.pkl`, `random2.pkl`, `regresion2.pkl` *(modelos entrenados)*  
   - `pipeline.pkl` *(preprocesamiento de datos nuevos)*  
   - `selected_features.pkl` *(características seleccionadas para modelos reducidos)*  
   - `df_dis.pkl`, `df_limpio.pkl` *(datasets en formato procesado)*  
4. En el terminal, donde se use app.py ejecutar ``streamlit run app.py``
