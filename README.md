# 🧠 Segmentación de Clientes — Clustering

**Autor:** Ignacio Robles  
**Institución:** Desafío Latam  

---

## 📌 Descripción

Este proyecto desarrolla una segmentación de clientes utilizando técnicas de aprendizaje no supervisado (clustering), con el objetivo de identificar grupos de consumidores con comportamientos de compra similares.

A partir de datos transaccionales a nivel de boleta, se construyen variables agregadas por cliente —incluyendo el modelo RFM (Recencia, Frecuencia y Monto)— para posteriormente aplicar distintos algoritmos de clustering y analizar los segmentos resultantes.

---

## 🎯 Objetivos

- Analizar y limpiar datos transaccionales
- Generar variables a nivel cliente
- Construir métricas RFM
- Aplicar algoritmos de clustering
- Evaluar la calidad de los modelos
- Interpretar los segmentos desde una perspectiva de negocio

---

## 🧪 Técnicas Utilizadas

- Análisis Exploratorio de Datos (EDA)
- Ingeniería de características
- Escalamiento de variables
- K-Means Clustering
- Clustering Jerárquico / Alternativos
- Métricas de evaluación (Silhouette, Davies-Bouldin)
- Interpretación de segmentos

---

## 📊 Resultados Esperados

La segmentación permite:

- Identificar clientes de alto valor
- Detectar clientes en riesgo de abandono
- Reconocer compradores ocasionales
- Diseñar estrategias de marketing personalizadas
- Optimizar recursos comerciales

---

## 🛠️ Tecnologías

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## ⚙️ Entorno de ejecución

El repositorio incluye el archivo:

```
environment.yml
```

Este archivo permite recrear el entorno de Conda utilizado en el proyecto.

### Crear el entorno

```bash
conda env create -f environment.yml
```

### Activar el entorno

```bash
conda activate <nombre_del_entorno>
```

---

## ▶️ Cómo usar este repositorio

1. Clonar el repositorio
2. Crear el entorno con `environment.yml`
3. Abrir el notebook principal en Jupyter
4. Ejecutar las celdas en orden
5. Revisar los análisis y resultados

---

## 📄 Licencia

Uso académico y educativo.
"""

