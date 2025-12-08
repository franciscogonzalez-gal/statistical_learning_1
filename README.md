# Statistical Learning 1

![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![pandas](https://img.shields.io/badge/pandas-latest-150458.svg?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-latest-013243.svg?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-latest-11557c.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-latest-3776AB.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-latest-F7931E.svg?logo=scikit-learn)
![License](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)

Repositorio de proyectos y tareas del curso de Aprendizaje Estadístico (Statistical Learning).

**Autor:** Francisco González

## 📋 Descripción

Este repositorio contiene una colección de notebooks de Jupyter que implementan diversos conceptos y técnicas de aprendizaje estadístico y machine learning. Los trabajos incluyen análisis exploratorio de datos, preprocesamiento, selección de características, clustering, y modelos de regresión.

## 📁 Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

```
statistical_learning_1/
├── tarea1.ipynb                    # Tarea 1: Codificación y selección de características
├── Tarea 2.ipynb                   # Tarea 2: Preprocesamiento y transformaciones
├── Tarea 3.ipynb                   # Tarea 3: Imputación de valores faltantes con K-Prototypes
├── proyecto_1_regresion.ipynb      # Proyecto 1: Análisis de regresión lineal
└── LICENSE.txt                     # Licencia CC0 1.0 Universal
```

## 📚 Contenido de los Notebooks

### Tarea 1: Codificación y Selección de Características
- Análisis de variables categóricas y numéricas
- Codificación de variables categóricas
- Selección de características por correlación
- Análisis de variables relacionadas con churn

### Tarea 2: Preprocesamiento y Transformaciones
- Técnicas de escalado de datos (MinMaxScaler, StandardScaler, RobustScaler)
- Transformaciones de potencia (PowerTransformer)
- Construcción de pipelines de preprocesamiento
- Análisis exploratorio de datos

### Tarea 3: Imputación de Valores Faltantes
- Imputación de valores faltantes utilizando K-Prototypes
- Análisis de componentes principales (PCA)
- Evaluación de clustering con silhouette score
- Selección de características por varianza y mutual information

### Proyecto 1: Regresión Lineal
- Preparación y exploración de datos
- Visualización con scatter plots
- Implementación de modelos de regresión (Linear Regression, Ridge, Lasso)
- Análisis de residuales
- Evaluación del desempeño del modelo
- Análisis de importancia de variables

## 🔧 Requisitos

### Software Necesario
- Python 3.x
- Jupyter Notebook o JupyterLab

### Bibliotecas Principales

```python
# Manipulación y análisis de datos
pandas
numpy

# Visualización
matplotlib
seaborn

# Machine Learning
scikit-learn
kmodes

# Utilidades
IPython
python-dateutil
```

## 🚀 Instalación y Uso

### 1. Clonar el Repositorio

```bash
git clone https://github.com/franciscogonzalez-gal/statistical_learning_1.git
cd statistical_learning_1
```

### 2. Instalar Dependencias

Se recomienda crear un entorno virtual antes de instalar las dependencias:

```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Linux/Mac:
source venv/bin/activate
# En Windows:
venv\Scripts\activate

# Instalar dependencias
pip install pandas numpy matplotlib seaborn scikit-learn kmodes jupyter python-dateutil
```

### 3. Ejecutar los Notebooks

```bash
# Iniciar Jupyter Notebook
jupyter notebook

# O usar JupyterLab
jupyter lab
```

Una vez iniciado Jupyter, navega a través de los notebooks (.ipynb) y ejecútalos célula por célula.

## 📊 Temas Cubiertos

Los notebooks cubren los siguientes temas de aprendizaje estadístico:

- **Preprocesamiento de Datos**
  - Escalado y normalización
  - Codificación de variables categóricas
  - Imputación de valores faltantes
  
- **Selección de Características**
  - Análisis de correlación
  - Varianza threshold
  - Mutual information
  
- **Análisis No Supervisado**
  - K-Prototypes clustering
  - Análisis de componentes principales (PCA)
  
- **Modelos de Regresión**
  - Regresión lineal simple
  - Ridge regression (regularización L2)
  - Lasso regression (regularización L1)
  - Análisis de residuales
  - Evaluación de modelos

## 📝 Notas

- Cada notebook está diseñado para ser ejecutado de manera independiente
- Los notebooks incluyen explicaciones y análisis de los resultados
- Se recomienda ejecutar las celdas en orden secuencial para evitar errores de dependencias

## 📄 Licencia

Este proyecto está bajo la licencia **CC0 1.0 Universal** (Creative Commons Zero v1.0 Universal).

Esto significa que puedes:
- Copiar, modificar y distribuir el trabajo
- Usarlo para fines comerciales
- Todo sin pedir permiso

Ver el archivo [LICENSE.txt](LICENSE.txt) para más detalles.

## 👤 Autor

**Francisco González**

## 🤝 Contribuciones

Este es un repositorio de tareas académicas. Si encuentras algún error o tienes sugerencias, no dudes en abrir un issue.

---

*Proyecto desarrollado como parte del curso de Statistical Learning*
