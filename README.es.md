# 🌊 Análisis y Pronóstico del Nivel del Agua del Acuífero
Este repositorio contiene un notebook de análisis exploratorio de datos (EDA) enfocado en las tendencias temporales de los niveles de agua del conjunto de datos *Aquifer Auser*. El proyecto incluye preprocesamiento, visualización y pronóstico utilizando herramientas estadísticas y de aprendizaje automático.

---

## 📁 Estructura del Proyecto

```
📦 Aquifer-Water-Analysis/
├── explore (4).ipynb       # Notebook principal con el análisis completo
├── data/
│   └── raw/                # Archivos de datos originales, incluyendo Aquifer_Auser.csv
├── README.md               # Descripción general del proyecto e instrucciones
```

---

## 📊 Características

- 📉 Imputación de valores faltantes mediante interpolación lineal  
- 🔄 Descomposición estacional utilizando STL  
- 📈 Pronóstico con modelos Prophet y Holt-Winters  
- 📋 Estadísticas resumidas con TableOne  
- 📎 Diagnósticos visuales con Seaborn y Missingno  

---

## 🧰 Librerías Utilizadas

- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
- `missingno`, `colorama`  
- `statsmodels`  
- `prophet`  
- `tableone`  
- `sklearn`  

---

## 🚀 Primeros Pasos

Para ejecutar el notebook localmente:

### 🔹 Clonar el repositorio:

```bash
git clone https://github.com/your-username/aquifer-water-analysis.git
cd aquifer-water-analysis
```

### 🔹 Instalar dependencias:

```bash
pip install -r requirements.txt
```

### 🔹 Lanzar el notebook:

```bash
jupyter notebook "explore.ipynb"
```

---

## 📈 Resultados

El notebook demuestra que pronosticar niveles de agua utilizando modelos de series temporales puede ofrecer predicciones razonablemente precisas, siendo los componentes estacionales y de tendencia clave para comprender los patrones de los datos.

---

## 📬 Contacto

Para preguntas, no dudes en abrir un *issue* en GitHub o hacer un *fork* del repositorio y contribuir.
