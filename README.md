<p align="center">
  <img src="cover.png" alt="Telecom X">
</p>

# 🌐 Telecom X - Challenge 3: Predicción de Evasión (Machine Learning)

El desafío de la **Semana 3** de Alura Latam para el bootcamp en Data Science. Su objetivo es ampliar la limpieza de datos (*ETL*) desde el desafío anterior y construir modelos de **Machine Learning** capaces de predecir la cancelación del servicio por parte de los clientes (Churn).

## 🗂️ Herramientas y Librerías Utilizadas
El código ha sido implementado utilizando las herramientas clásicas de Data Science de Python 3:
- **Pandas**: Manipulación, tratamiento de nulos y estandarización (Dummies).
- **NumPy**: Tratamiento y matemáticas estadísticas.
- **Seaborn** y **Matplotlib**: Visualización (Gráfica de correlación de calor, Histograma y Diagrama de Cajas).
- **Scikit-Learn**: Para modelos predictivos de regresión logística y árboles aleatorios (*Random Forest Classifier*). 

## 🤖 Etapas de Desarrollo
1. **Extracción y Transformación (ETL)**: Extracción directa de los servidores de GitHub y limpieza de las dependencias redundantes (unificación de servicio telefónico).
2. **Ingeniería de Características**: Uso de *One-Hot Encoding* a través de `get_dummies` excluyendo a las columnas principales como IDs para eludir problemas de multicolinealidad.
3. **Despliegue del Modelo**: Testeo de una clásica Regresión y contrastada contra un Random Forest; resultando ambos modelos competentes (~80% de nivel asertivo sin balanceo paramétrico) e identificando las características más críticas.

> **¡Ver conclusiones completas en el cuaderno de Machine Learning!**
