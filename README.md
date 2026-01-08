# Representación femenina en el cine  
### Análisis y visualización a partir del Test de Bechdel

Este repositorio contiene los notebooks y materiales de análisis utilizados para el proyecto de visualización de datos sobre la representación femenina en el cine, desarrollado en el marco de la asignatura **Visualización de Datos** del Máster en Ciencia de Datos (UOC).

El proyecto utiliza el **Test de Bechdel** como herramienta analítica para estudiar la evolución de la representación femenina, el papel del equipo creativo, la recepción crítica y pública, y la relación con variables económicas y simbólicas.

---

## 📊 Visualización final

La visualización interactiva final ha sido desarrollada en **Flourish**, utilizando los datasets preparados en estos notebooks. En enlace es el siguiente: https://www.canva.com/design/DAG8yiUnMeY/qvM3mqsUe_jlXOtlcTA08w/view?utm_content=DAG8yiUnMeY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h4743f1ffa4

---

## 🗂️ Estructura del repositorio
├── source/  
│ └── Análisis.ipynb  
│ └── Limpieza_e_integración.ipynb  
├── data/  
│ └── movies_with_age_gap.xlsx  
│ └── age_gaps.csv  
└── README.md  

## 📁 Data

- **`age_gaps.csv`**  
  Archivo que contiene los datos de Hollywood Age Gap.
- **`movies_with_age_gap.xlsx`**  
  Dataset resultante de la limpieza e integración y a partir del cual se realiza en análisis y los datos finales para Flourish.
- **Bechdel test** se obtiene directamente de Github.

## 🧹 Notebook 1: Limpieza e integración

**`Limpieza e integración.ipynb`**

- Limpieza y normalización de los datasets originales.
- Integración de fuentes.
- Inferencia del género del equipo creativo (dirección y guion) a partir de nombres, utilizando aproximaciones conservadoras.
- Creación de variables analíticas clave:
  - Presencia femenina en dirección y guion.
  - Diferencia de edad y género del personaje mayor en relaciones.

## 📈 Notebook 2: Análisis y preparación para visualización

**`Análisis.ipynb`**

Este notebook prepara los datos finales que alimentan la visualización en Flourish:

- Agregaciones por año y por categorías del Test de Bechdel.
- Cálculo de proporciones y distribuciones necesarias para gráficos comparativos.
- Preparación de datasets específicos para cada bloque narrativo.

⚠️ **Nota**:  
Algunos gráficos de la visualización final **no tienen un equivalente directo en código dentro de este notebook**, ya que se han construido directamente en Flourish a partir del dataset resultante de la limpieza inicial.





**Idoia Dávila Uzcudun**  
Visualización de datos
Máster en Ciencia de Datos – UOC  
Enero 2026
