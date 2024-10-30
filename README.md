
# Análisis del Valor del Metro Cuadrado en Buenos Aires

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el **valor del metro cuadrado** en diferentes comunas de la Ciudad de Buenos Aires, utilizando datos abiertos y herramientas de **análisis de datos**. Se aplicaron técnicas de **machine learning** y **visualizaciones** interactivas para identificar factores que afectan los precios de las propiedades, como el acceso al transporte público, ingresos familiares, y otros indicadores socioeconómicos.

El proyecto se llevo a cabo utilizando **Python** (con librerías como `pandas`, `numpy`, `scikit-learn`, etc.) y **Tableau** para las visualizaciones. Se desarrollaron **6 dashboards interactivos** en Tableau que ilustran diferentes aspectos del análisis.

## Contenidos del Repositorio

Este repositorio contiene los siguientes elementos:

-   **notebooks/**: Contiene los notebooks de Jupyter (`.ipynb`) que incluyen el análisis exploratorio, el preprocesamiento de datos, el modelado y las visualizaciones generadas en Python.
-   **data/**: Archivos de datos utilizados para el análisis. Incluye un dataset(.csv) originado por mi que contiene ademas de la informacion las fuentes de dicha informacion.
-   **scripts/**: Un Archivo Python.
-   **README.md**: Este archivo, que proporciona información general sobre el proyecto.
-   **images/**: Imágenes y capturas de pantalla de las visualizaciones creadas, utilizadas para documentación.
-   **requirements.txt**: Archivo con las dependencias necesarias para ejecutar el proyecto.

## Objetivos del Análisis

-   Conseguir trabajo como Data Scientist data analyst. :D
-   **Entender cómo diferentes factores socioeconómicos y de infraestructura afectan el valor del metro cuadrado** en distintas comunas de Buenos Aires.
-   **Identificar patrones y tendencias** que ayuden a explicar las diferencias de precios entre comunas.
-   **Construir un modelo predictivo** utilizando Random Forest para estimar el valor del metro cuadrado basado en las características de cada comuna.

## Tecnologías Utilizadas

-   **Python**: Análisis de datos y Machine Learning (`pandas`, `scikit-learn`, `numpy`, `matplotlib`, `seaborn`)
-   **Tableau**: Visualizaciones y dashboards interactivos
-   **Jupyter Notebook**: Documentación y ejecución del código.

## Metodología

1.  **Anílisis Exploratorio de Datos (EDA)**: Limpieza y análisis del dataset para entender las principales tendencias y relaciones.
2.  **Preprocesamiento de Datos**: Tratamiento de valores faltantes, estandarización de variables, y transformaciones categóricas con one hot encoding y dummies.
3.  **Modelado Predictivo**: Uso del algoritmo **Random Forest** para predecir el valor del metro cuadrado, seguido de optimización mediante **Grid Search**.
4.  **Visualización**: Creación de **dashboards interactivos** en Tableau para comunicar los principales insights.

## Principales Resultados

-   El modelo de Random Forest desarrollado tiene un R² Score de 0.92, lo cual indica que el modelo puede explicar el 92% de la variabilidad en el valor del metro cuadrado entre las diferentes comunas.

-   Las comodidades de la comuna como Hospitales generales, espacios verdes, institutos educativos no tienen impacto en el valor del metro cuadrado, si, aunque curioso, tiene una correlacion positiva la cantidad de clubes deportivos.

-   La **importancia de las características** según el modelo sugiere que el precio de los alquileres y los ingresos familiares son los principales factores que influyen en el precio del metro cuadrado.

## Cómo Ejecutar el Proyecto

1.  **Clonar el Repositorio**: git clone <https://github.com/GianCipollari/CABA_M2_Analysis.git>

2.  **Instalar Dependencias**: Navega al directorio del proyecto y ejecuta:

pip install -r requirements.txt

3.  **Ejecutar el Notebook**: Abre el notebook principal en Jupyter: jupyter notebook notebooks/analisis_m2_value.ipynb

## Enlaces Importantes

-   **Visualizaciones en Tableau**: [M2 Value Analysis in Buenos Aires - Tableau Public](https://public.tableau.com/app/profile/gianfranco.cipollari/viz/M2valueAnalysisinBuenosAiresCABAbyCommune/Presentation)

## Contribuciones

Las contribuciones son bienvenidas. Si?ntete libre de abrir un **issue** o un **pull request** si tienes ideas para mejorar el proyecto.

## Contacto

[gianfrancocipollari\@gmail.com](mailto:gianfrancocipollari@gmail.com){.email}.
