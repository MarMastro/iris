

# Iris Classification Pipeline 🚀

**Data Science • Python • Machine Learning • KNN • EDA • Model Evaluation**

---

## 🔍 Descripción

Mini proyecto práctico de Data Science aplicado al clásico dataset **Iris**.  
Demuestra un pipeline completo: exploración de datos, preprocesamiento, modelado (KNN), validación cruzada y evaluación con métricas y matriz de confusión. Análisis, reproducibilidad y machine learning básico.

---

## 🧪 Qué incluye este proyecto

- Carga y análisis exploratorio del dataset Iris  
- Escalado de features con `StandardScaler`  
- Clasificación con **K-Nearest Neighbors (KNN)**  
- Validación cruzada estratificada (5 folds) para evaluar estabilidad  
- Evaluación final sobre test set independiente  
- Reporte de métricas (accuracy, precision, recall, F1)  
- Matriz de confusión visualizada  
- Pipeline reproducible con `scikit-learn`

---

## ⚙️ Tecnologías

- Python 3  
- pandas  
- seaborn  
- matplotlib  
- scikit-learn  
- Git / GitHub

---

## 🚀 Cómo reproducir

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/iris-classification.git
   cd iris-classification
2. Instalar dependencias (recomendado en un entorno virtual):
   pip install pandas seaborn matplotlib scikit-learn
3. Ejecutar el notebook:
   Abrí proyecto_iris.ipynb en Jupyter o Google Colab.
   O corré el script equivalente en Python.

---

🧠 Resultado principal
Accuracy promedio en validación cruzada: muestra consistencia del modelo.
Accuracy en test set: evaluación realista con datos no vistos.
Reporte de clasificación: precision, recall y F1 por cada especie.
Matriz de confusión: visualiza qué clases se confunden.
Insight clave: setosa es fácilmente separable; versicolor y virginica requieren combinación de features para distinguirse bien.

📈 Insights / Aprendizajes
El escalado de features es crítico para modelos basados en distancia como KNN.
Las combinaciones de petal_length y petal_width son las más discriminantes.
Validación cruzada ayuda a evitar conclusiones erróneas por overfitting de un solo split.
Métricas desglosadas por clase revelan si el modelo favorece o perjudica alguna categoría.

📦 Estructura del repositorio
├── proyecto_iris.ipynb      # Notebook con pipeline completo
├── README.md               # Este archivo
├── requirements.txt        # Dependencias (opcional)
├── img/                    # Visualizaciones (matriz de confusión, pairplot)

📬 Contacto
Si te interesa colaborar, dar feedback o tienes oportunidades en Data Science, contáctame.
⭐ Dale "Star" si te sirvió este proyecto.
