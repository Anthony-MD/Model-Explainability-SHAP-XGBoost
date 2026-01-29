# Model-Explainability-SHAP-XGBoost
Este proyecto resuelve el problema de la "Caja Negra" en modelos de Machine Learning. Utilizando el dataset del Titanic como base, implemento un modelo de clasificación de alto rendimiento (**XGBoost**) y aplico técnicas de interpretabilidad avanzada para entender los factores que impulsan cada predicción.

# Model Explainability & Interpretability with SHAP & XGBoost

## Descripción
Este proyecto resuelve el problema de la "Caja Negra" en modelos de Machine Learning. Utilizando el dataset del Titanic como base, implemento un modelo de clasificación de alto rendimiento (**XGBoost**) y aplico técnicas de interpretabilidad avanzada para entender los factores que impulsan cada predicción.

## Stack Tecnológico
* **Modelo:** XGBoost (Extreme Gradient Boosting).
* **Interpretabilidad:** SHAP (SHapley Additive exPlanations).
* **Data Science:** Scikit-learn, Pandas, NumPy.
* **Visualización:** Matplotlib y gráficos nativos de SHAP.

## Capacidades de Ingeniería
* **Transparencia de Modelos:** Uso de valores de Shapley para cuantificar la contribución individual de cada característica (sexo, edad, clase) al resultado final.
* **Análisis Crítico:** Identificación de sesgos y patrones (ej: el impacto positivo de ser mujer o viajar en primera clase en la supervivencia).
* **Optimización basada en Insights:** Capacidad para explicar a stakeholders técnicos y no técnicos la lógica detrás de un modelo complejo.

## Visualización de la Interpretabilidad
El gráfico "Beeswarm" permite ver de un vistazo qué variables empujan la predicción hacia la supervivencia y cuáles hacia la no supervivencia.
<img width="1291" height="431" alt="image" src="https://github.com/user-attachments/assets/34a2c9e9-943f-4837-ab4a-ff1335ad5c1c" />
<img width="1071" height="646" alt="image" src="https://github.com/user-attachments/assets/f6919479-3c42-41d8-ba6e-1a3ba04fcfb9" />
<img width="1835" height="477" alt="image" src="https://github.com/user-attachments/assets/9d87fd2e-7d1d-4c21-930c-ee6ea1073965" />
<img width="1121" height="665" alt="image" src="https://github.com/user-attachments/assets/d8037160-9b2e-48c4-8161-dfe3dc855389" />
<img width="944" height="738" alt="image" src="https://github.com/user-attachments/assets/a5cdbec9-da2a-4128-b5dd-bf125e045333" />





## Cómo empezar
1.  Instalar dependencias: `pip install xgboost shap pandas matplotlib`
2.  Clonar el repositorio.
3.  Ejecutar el notebook `CasoPractico_Unidad3_Interpretabilidad.ipynb`.
