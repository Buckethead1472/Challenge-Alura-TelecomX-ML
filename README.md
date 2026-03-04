# 📡 Predicción de Cancelación de Clientes (Churn) - Telecom X


## 🚀 Resumen del Proyecto
Telecom X busca reducir su tasa de cancelación. Mediante el uso de algoritmos de clasificación, logramos identificar patrones críticos en el comportamiento de los clientes, permitiendo una intervención proactiva.

## 🛠️ Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 3.x
* **Manipulación de Datos:** Pandas, Numpy
* **Visualización:** Seaborn, Matplotlib
* **Machine Learning:** Scikit-Learn
* **Balanceo de Clases:** Imbalanced-learn (SMOTE)

## 📊 Flujo de Trabajo (Pipeline)
1. **Limpieza y Preprocesamiento:** Eliminación de IDs y codificación de variables categóricas (One-Hot Encoding).
2. **Balanceo de Clases:** Aplicación de SMOTE para corregir el desbalance del dataset (originalmente 26% de Churn).
3. **Escalamiento:** Normalización de variables numéricas para modelos basados en distancias.
4. **Modelado:** Entrenamiento y comparativa entre **Regresión Logística** y **Random Forest**.
5. **Evaluación:** Análisis mediante Matriz de Confusión, Accuracy, Precisión y Recall.

## 📈 Resultados Clave
* **Modelo Ganador:** Random Forest.
* **Exactitud (Accuracy):** 85.57%
* **Precisión (Clase Churn):** 87%
* **Hallazgo Principal:** Los contratos "Mes a mes" y el servicio de Fibra Óptica son los mayores detonantes de fuga de clientes.

## 💡 Estrategias Recomendadas
* Incentivar la migración a contratos anuales.
* Implementar servicios de valor añadido (Soporte Técnico) en clientes de fibra óptica.
* Monitoreo intensivo durante los primeros 12 meses de antigüedad.

---
**Desarrollado por:** Yamil Solis Diaz  
*Data Science - Alura Latam*
