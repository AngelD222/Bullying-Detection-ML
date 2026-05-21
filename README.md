# Bullying-Detection-ML

# Machine Learning para el Análisis y Predicción del Bullying

Este repositorio contiene un proyecto completo de Machine Learning orientado a analizar patrones y predecir comportamientos relacionados con el *bullying*. El objetivo principal es aplicar técnicas rigurosas de ciencia de datos para extraer conocimiento estructurado de un conjunto de datos complejo, demostrando el ciclo de vida completo de un modelo predictivo.

## 📊 Sobre los Datos
El conjunto de datos utilizado incluye variables demográficas, psicológicas y conductuales. El análisis se enfoca en identificar los factores de riesgo más determinantes y en construir modelos capaces de clasificar o predecir la incidencia de estas conductas.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Manipulación y Análisis de Datos:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Visualización:** Matplotlib, Seaborn

## ⚙️ Metodología y Fases del Proyecto

El *notebook* documenta el proceso estructurado de la toma de decisiones algorítmicas:

### 1. Análisis Exploratorio de Datos (EDA)
* Análisis de distribuciones multivariantes para identificar correlaciones ocultas entre variables.
* Identificación y tratamiento de valores atípicos (*outliers*) y datos faltantes.
* Visualización avanzada para la extracción de *insights* iniciales.

### 2. Ingeniería de Características (Feature Engineering)
* Transformación de variables categóricas (codificación *One-Hot*, *Label Encoding*).
* Normalización y escalado de variables numéricas para optimizar la convergencia de los algoritmos.
* Selección de características (*Feature Selection*) para reducir la dimensionalidad y evitar el sobreajuste (*overfitting*).

### 3. Modelado Predictivo
Se entrenaron y evaluaron varios modelos de aprendizaje automático para encontrar el ajuste óptimo al problema. Los algoritmos implementados incluyen:
* [Añadir modelo 1, ej: Regresión Logística]
* [Añadir modelo 2, ej: Random Forest / Árboles de Decisión]
* [Añadir modelo 3, ej: Support Vector Machines (SVM) o KNN]

### 4. Evaluación y Métricas
Los modelos no solo se evaluaron en base a su precisión global (*Accuracy*), sino que, dada la naturaleza del problema (posible desbalanceo de clases), se priorizaron métricas más robustas:
* Matriz de Confusión.
* *Recall*, *Precision* y *F1-Score*.
* Curva ROC y cálculo del AUC (Área Bajo la Curva).

