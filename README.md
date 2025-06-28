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
   -app.py(aplicación)
   -stack.pkl random.pkl regresion.pkl stack2.pkl random2.pkl regresion2.pkl (modelos)
   -pipeline.pkl (para transformar datos ingresados)
   -selected_features.pkl (características más importantes)
   -df_dis.pkl df_limpio.pkl (dataset)
4. En el terminal, donde se use app.py ejecutar ``streamlit run app.py``
