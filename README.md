# Stadistic_Analisis

Este repositorio contiene el análisis de una encuesta realizada a **178 estudiantes universitarios cubanos**, principalmente de la Universidad de La Habana, sobre sus **hábitos de consumo cultural**, como parte del proyecto final de la asignatura de estadística. El proyecto utiliza diversas herramientas de análisis estadístico y visualización para explorar las preferencias culturales, identificar patrones y realizar pruebas estadísticas relevantes.

---

## Índice  
- [Stadistic\_Analisis](#stadistic_analisis)
  - [Índice](#índice)
  - [Introducción](#introducción)
  - [Metodología](#metodología)
  - [Estructura del Proyecto](#estructura-del-proyecto)
  - [Tecnologías Utilizadas](#tecnologías-utilizadas)
  - [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
  - [Resultados Destacados](#resultados-destacados)

---

## Introducción  
El propósito de este proyecto es analizar el consumo cultural de los estudiantes universitarios y explorar la relación entre diversas variables como **edad, facultad, géneros culturales preferidos y plataformas de consumo de música**. Se aplican diferentes técnicas de análisis estadístico:  
- **Estadística descriptiva**  
- **Pruebas de hipótesis**  
- **ANOVA**  
- **Regresión Lineal**  
- **Análisis de Correspondencias Múltiples (MCA)**  
- **Análisis de Componentes Principales (PCA)**  

El análisis busca proporcionar una visión clara de las preferencias culturales y cómo estas varían según características sociodemográficas.

---

## Metodología  
1. **Carga y limpieza de datos:** Preparación del dataset, normalización de respuestas múltiples y tratamiento de valores faltantes.  
2. **Estadística descriptiva:** Resumen inicial de las principales variables del dataset.  
3. **Pruebas de hipótesis:** Evaluación de relaciones significativas entre variables categóricas y numéricas.  
4. **ANOVA:** Comparación de medias entre múltiples categorías.  
5. **Regresión Lineal:** Modelado de la relación entre la edad y diversas variables culturales.  
6. **MCA y PCA:** Reducción de dimensiones para identificar patrones en las preferencias culturales.  

---

## Estructura del Proyecto  
El análisis se encuentra organizado en un notebook de Jupyter (`Análisis_Cultural_Universitario_2024.ipynb`) con las siguientes secciones:  

1. **Introducción y Preparación de Datos**  
2. **Exploración de Datos**  
3. **Estadística Descriptiva**  
4. **Pruebas de Hipótesis**  
5. **ANOVA**  
6. **Regresión Lineal**  
7. **Análisis de Correspondencias Múltiples (MCA)**  
8. **Análisis de Componentes Principales (PCA)**  

Cada sección incluye explicaciones detalladas en celdas de Markdown para facilitar la comprensión del análisis y la interpretación de resultados.  

---

## Tecnologías Utilizadas  
- **Python 3.12**  
- **Jupyter Notebook** y **Visual Studio Code**
- **Librerías de Python:**  
  - `pandas`, `numpy`: Manipulación y análisis de datos  
  - `matplotlib`, `seaborn`: Visualización de datos  
  - `scipy`, `statsmodels`: Pruebas estadísticas y modelos lineales  
  - `prince`: Análisis de Correspondencias Múltiples (MCA)  
  - `sklearn`: Análisis de Componentes Principales (PCA)  

---

## Cómo Ejecutar el Proyecto  
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
    
2. Instala las dependencias necesarias:
    ```bash
    pip install -r requirements.txt

3. Abre el notebook en Jupyter:
   ```bash
   jupyter notebook Análisis_Cultural_Universitario_2024.ipynb

4. Ejecuta cada celda de código siguiendo la secuencia para reproducir el análisis completo.

--- 

## Resultados Destacados

- **Estadística Descriptiva**: La media de edad de los encuestados es de 21 años, con una distribución ligeramente sesgada hacia edades menores.
- **Pruebas de Hipótesis**: Se identificaron relaciones significativas entre la facultad y la vertiente cultural consumida.
- **ANOVA**: Se observaron diferencias significativas en la edad según la plataforma de consumo de música.
- **MCA y PCA**: Las primeras dos componentes principales explican el 70% de la varianza total, permitiendo visualizar patrones claros en las preferencias culturales.
