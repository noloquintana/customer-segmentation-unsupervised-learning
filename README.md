# 📊 Customer Segmentation using Unsupervised Learning

Este proyecto aplica técnicas de aprendizaje no supervisado para analizar y segmentar datos de clientes, utilizando métodos de reducción de dimensionalidad y algoritmos de clustering.

---

## 🎯 Objetivo

El objetivo principal es identificar patrones ocultos en los datos y explorar posibles segmentaciones que permitan comprender mejor el comportamiento de los clientes.

---

## 🧠 Técnicas utilizadas

### 🔹 Preprocesamiento
- Limpieza de datos
- Tratamiento de valores nulos
- Codificación de variables categóricas (Label Encoding)
- Escalado de variables (StandardScaler)

### 🔹 Reducción de dimensionalidad
- **PCA (Principal Component Analysis)**  
  Reducción lineal de dimensiones maximizando la varianza.

- **t-SNE (t-Distributed Stochastic Neighbor Embedding)**  
  Reducción no lineal que preserva relaciones locales.

### 🔹 Clusterización
- **K-Means**
- **DBSCAN**
- **Clustering Jerárquico (Dendrograma)**

---

## 📈 Resultados principales

- PCA permitió visualizar la estructura general de los datos.
- t-SNE mostró agrupaciones más definidas.
- K-Means identificó 4 clusters, aunque con cierta superposición.
- DBSCAN detectó principalmente un cluster grande y algunos outliers.
- El dendrograma evidenció una estructura jerárquica con subgrupos.

---

## 📊 Visualizaciones

Las principales visualizaciones generadas incluyen:

- PCA (2D)
- t-SNE (2D)
- Clusters con K-Means
- Clusters con DBSCAN
- Dendrograma

---

## 📁 Estructura del proyecto
