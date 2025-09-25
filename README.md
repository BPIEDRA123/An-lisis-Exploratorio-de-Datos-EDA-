# Proyecto Integrador – Clasificación de Nódulos Tiroideos 

Este repositorio contiene un **notebook en Python** que realiza un **Análisis Exploratorio de Datos (EDA)** y procesamiento de **imágenes de tiroides**, con el objetivo de explorar características útiles para la clasificación de nódulos **benignos** y **malignos**.

---

##  Contenido del Notebook
El archivo principal es:

- `Integrador_17.ipynb` → Notebook con el flujo de trabajo completo.

Dentro se incluyen los siguientes pasos principales:

1. **Montaje de Google Drive**  
   Para acceder a los datasets almacenados en Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

2. **Análisis Exploratorio de Datos (EDA)**  
   - Limpieza y carga de datos.  
   - Cálculo de estadísticos (media, varianza, asimetría, curtosis).  
   - Visualización con `matplotlib` y `seaborn`.  
   - Reducción de dimensionalidad con **PCA**.  
   - Detección de outliers con **Isolation Forest**.

3. **Análisis de Imágenes**  
   - Lectura de imágenes con `PIL`.  
   - Estadísticas básicas de imágenes.  
   - Preparación para clasificación.  

---

##  Librerías Utilizadas
El proyecto requiere las siguientes librerías de Python:

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scipy`
- `scikit-learn`
- `PIL` (Pillow)

---

##  Ejecución
Para correr el proyecto:

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/Integrador-Tiroides.git
   cd Integrador-Tiroides
   ```

2. Abrir el notebook en Google Colab o Jupyter:
   ```bash
   jupyter notebook Integrador_17.ipynb
   ```

---

##  Objetivo
Explorar y analizar imágenes de **nódulos tiroideos**, extrayendo métricas estadísticas y visuales que puedan ayudar en tareas de clasificación **benigno vs maligno**.

---

##  Autor
Ing. Christian Garcia
Ing. Byron Piedra
