# 🧩 Seguro de Vivienda – Clustering de Clientes

Este repositorio contiene un **Jupyter Notebook** enfocado en la **aplicación de técnicas de clustering (aprendizaje no supervisado)** sobre un **dataset de seguros de vivienda**, con el objetivo de **segmentar clientes** en grupos homogéneos según sus características demográficas, contractuales y de comportamiento.

Este notebook complementa las etapas previas de **análisis exploratorio y Machine Learning supervisado**, aportando una visión estratégica orientada a la **segmentación de clientes y toma de decisiones de negocio** en el sector asegurador.

---

## 📌 Contenido del Notebook

El archivo principal del repositorio es:

* `Clustering.ipynb`

En él se desarrollan las siguientes etapas:

---

## 1️⃣ Importación de librerías

Se utilizan librerías estándar para análisis y clustering en Python:

* `pandas` y `numpy` para manipulación de datos
* `scikit-learn` para algoritmos de clustering y escalado
* `matplotlib` y `seaborn` para visualización

---

## 2️⃣ Descripción del dataset

El dataset corresponde a **clientes de seguros de vivienda** y contiene variables que describen:

* Información demográfica de los clientes
* Características de la vivienda
* Variables económicas y de riesgo
* Historial y comportamiento relacionado con el seguro

Estas variables permiten identificar **patrones naturales** entre los clientes sin necesidad de una variable objetivo.

---

## 3️⃣ Preparación de los datos

Antes de aplicar los algoritmos de clustering se realizan tareas clave:

* Selección de variables relevantes para segmentación
* Eliminación de identificadores que no aportan al modelo
* Escalado de variables numéricas
* Revisión de valores atípicos

Esta etapa es fundamental para garantizar resultados de clustering consistentes.

---

## 4️⃣ Aplicación de algoritmos de clustering

Se aplican técnicas de aprendizaje no supervisado, tales como:

* **K-Means** para segmentación de clientes
* Determinación del número óptimo de clusters mediante métodos como:

  * Método del codo (Elbow Method)
  * Análisis de inercia

El objetivo es encontrar grupos de clientes con características similares.

---

## 5️⃣ Análisis de los clusters

Una vez definidos los clusters, se realiza un análisis detallado de cada grupo:

* Perfilado de clientes por cluster
* Comparación de variables clave entre segmentos
* Identificación de patrones de riesgo y comportamiento

Este análisis permite traducir los resultados técnicos en **insights de negocio**.

---

## 6️⃣ Visualización de resultados

El notebook incluye visualizaciones para facilitar la interpretación de los clusters:

* Gráficos de dispersión
* Visualizaciones comparativas por cluster
* Representación gráfica de la segmentación

---

## 🎯 Objetivo del proyecto

El objetivo principal de este notebook es **segmentar clientes de seguros de vivienda** para:

* Identificar perfiles de clientes diferenciados
* Apoyar estrategias de marketing y retención
* Mejorar la gestión del riesgo
* Complementar modelos supervisados de predicción

---

## 🛠️ Requisitos

Para ejecutar el notebook se requiere:

* Python 3.8 o superior
* Jupyter Notebook o Jupyter Lab
* Librerías:

  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:

   ```bash
   git clone <url-del-repositorio>
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd <nombre-del-repositorio>
   ```

3. Abre el notebook:

   ```bash
   jupyter notebook
   ```

4. Ejecuta las celdas en orden para reproducir el análisis de clustering.

---

## 📚 Dataset

El dataset utilizado corresponde a **datos de clientes de seguros de vivienda**, empleados con fines académicos para análisis y segmentación mediante técnicas de clustering.

---

## ✍️ Autor

**Johan Suarez**

---

## 📄 Licencia

Este proyecto se comparte con fines educativos y académicos. Puedes reutilizarlo y adaptarlo libremente citando la fuente.

---

⭐ Si este repositorio te resulta útil, considera darle una estrella en GitHub.
