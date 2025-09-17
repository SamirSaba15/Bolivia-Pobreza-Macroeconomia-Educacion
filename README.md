# Bolivia-Pobreza-Macroeconomia-Educacion
Análisis de Pobreza, Macroeconomía y Educación en Bolivia con ciencia de datos | 20+ indicadores del BM e INE | Identificación de drivers clave y recomendaciones de política basada en evidencia | Python, Pandas, APIs, Visualización


# 📊 Análisis de Pobreza, Macroeconomía y Educación en Bolivia

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Data Science](https://img.shields.io/badge/Data_Science-Advanced-orange)
![License](https://img.shields.io/badge/License-MIT-green)

Análisis integral de la pobreza en Bolivia mediante ciencia de datos, integrando múltiples fuentes (Banco Mundial, INE Bolivia, Banco Central) para identificar drivers clave y recomendar políticas basadas en evidencia.

## 🌟 Highlights del Proyecto

- **🔍 Análisis multivariado** de 20+ indicadores económicos y sociales
- **📈 Integración de datos** de 4 fuentes diferentes con ETL personalizado
- **📊 Análisis comparativo con LATAM** Mapas interactivos para evaluación regional
- **🎯 Modelado de sensibilidad** con correlaciones y heatmaps interactivos
- **📊 Visualizaciones profesionales** para storytelling de datos
- **💡 Recomendaciones de política** basadas en análisis cuantitativo

## 📊 Hallazgos Clave

### Correlaciones Significativas
| Variable | Correlación con Pobreza | Significancia |
|----------|-------------------------|---------------|
| Gasto en Salud | -0.71 | p < 0.001 |
| PIB per cápita | -0.65 | p = 0.001 |
| Gasto en Educación | -0.55 | p = 0.017 |
| Tasa de Desempleo | -0.44 | p = 0.038 |

### Hallazgo Contraintuitivo
**La inflación muestra correlación débil (-0.21) con pobreza**, explicable por:
- Economía informal extensa (60%+ fuerza laboral)
- Mecanismos de amortiguación social
- Políticas de compensación históricas

## 🛠️ Tecnologías Utilizadas


# Stack técnico completo
Python 3.8+
Pandas + NumPy (Data Wrangling)
Matplotlib + Seaborn (Visualization)
Scikit-learn (Análisis estadístico)
Jupyter Notebooks (Análisis interactivo)
Requests + APIs (Extracción de datos)


## 📁 Estructura del Proyecto
Como acostubro, seguí la metodología de Google
(Ask -> Prepare -> Process -> Analyze -> Act & Share)

bolivia-poverty-analysis/
│
├── 📊 Data Acquisition & Cleaning
│   ├── API Banco Mundial (Data360 + WB API)
│   ├── Datos INE Bolivia (Censos 2001, 2012, 2024)
│   └── Datos Banco Central (Inflación 2025)
│
├── 📈 Analysis
│   ├── Análisis de series temporales (1990-2021)
│   ├── Análisis de sensibilidad multivariado
│   ├── Comparativa regional Latinoamérica
│   └── Análisis urbano/rural diferenciado
│
├── 📊 Visualization
│   ├── Heatmaps de correlación
│   ├── Trend analysis interactivo
│   └── Dashboard preparation
│
└── 📋 Reporting
    ├── Análisis ejecutivo
    ├── Recomendaciones de política
    └── Limitaciones metodológicas

##🚀 Cómo Ejecutar el Proyecto
prerrequisitos
pip install -r requirements.txt

Ejecución:
# 1. Extracción de datos, Análisis principal y Análisis de sensibilidad

jupyter notebook notebooks/Pobreza_BM_Bo_Fin3.ipynb

##💡 Aprendizajes Clave
Integración de datos heterogéneos: APIs, archivos Excel, datos manuales

Análisis de sensibilidad: Identificación de drivers clave mediante correlaciones

Storytelling con datos: Comunicación efectiva de hallazgos complejos

Limitaciones metodológicas: Transparencia sobre alcances y restricciones

##🎯 Aplicaciones Prácticas
Política pública: Recomendaciones basadas en evidencia cuantitativa

Academia: Base metodológica para investigación en economía del desarrollo

Cooperación internacional: Guía para inversión social efectiva

Sociedad civil: Herramientas para vigilancia social

##⚠️ Limitaciones y Consideraciones
Datos de pobreza disponibles solo hasta 2021 (pre-crisis actual)

Ruptura estructural en 2022-2025 limita capacidad predictiva

Análisis se centra en relaciones históricas, no predicciones

##🤝 Contribuciones
Este proyecto es de código abierto. Las contribuciones son bienvenidas en:
Mejoras en visualizaciones
Análisis adicionales
Actualización de datos
Traducciones

📄 Licencia
Distribuido bajo licencia MIT. Ver LICENSE para más información.

📞 Contacto
[Samir Saba] - [samirsaba15@gmail.com]

Project Link:
