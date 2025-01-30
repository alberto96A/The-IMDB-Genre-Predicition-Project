# **Predicción de Géneros Cinematográficos Rentables**

Este proyecto tiene como objetivo predecir cuáles géneros cinematográficos seguirán siendo rentables en el futuro, basándose en datos históricos de IMDb y las métricas de recaudación de taquilla. Utilizando técnicas de **Machine Learning**, este análisis ayuda a identificar tendencias y posibles géneros que se verán más o menos frecuentemente en los próximos años.

## **Tecnologías utilizadas**
- **Python** (para la manipulación de datos, análisis y modelos predictivos)
- **Pandas** (para limpieza y manipulación de datos)
- **Scikit-learn** (para la implementación de modelos de Machine Learning)
- **Plotly** (para la creación de visualizaciones interactivas)
- **Power BI** (para la creación de un dashboard interactivo con resultados)
- **Jupyter Notebook** (para la realización del análisis y pruebas)

## **Descripción del Proyecto**
El análisis comenzó con una exploración de datos (EDA) sobre un dataset de IMDb, centrado principalmente en los géneros cinematográficos. El objetivo es predecir qué géneros serán más populares en términos de recaudación de taquilla en el futuro, basándose en el análisis de datos históricos.

### **Fases del Proyecto:**
1. **Exploración de Datos (EDA):** Limpieza y análisis inicial de los datos.
2. **Análisis de Géneros:** Estudio de los géneros más populares y sus ingresos de taquilla.
3. **Modelo Predictivo:** Implementación de un modelo de regresión multinomial para predecir la rentabilidad futura de los géneros.
4. **Evaluación de Modelos:** Análisis de precisión, recall y f1-score para evaluar el desempeño del modelo.
5. **Dashboard:** Creación de un dashboard interactivo en Power BI con los resultados del modelo y las tendencias de género.

## **Archivos Requeridos**
Los datasets necesarios para ejecutar el proyecto deben estar ubicados en una carpeta llamada `datasets` dentro del repositorio de GitHub. Asegúrate de descargar los siguientes archivos y colocarlos en esta carpeta:

- **`df_cleaned_with_gross.csv`** (contiene los datos de IMDb con los ingresos de taquilla).
- **`Top_1000_Highest_Grossing_Movies_Of_All_Time.csv`** (datos de las películas más taquilleras de todos los tiempos, utilizado para enriquecer el análisis).
- **`ImdbTitleBasics.csv`** (contiene información básica sobre las películas, como título, año, duración, etc.).
- **`ImdbTitleAkas.csv`** (contiene los títulos alternativos de las películas en diferentes países).
- **`ImdbTitleCrew.csv`** (información sobre los equipos de producción de las películas, como directores, productores, guionistas, etc.).
- **`ImdbTitlePrincipals.csv`** (datos sobre los actores principales de las películas).
- **`ImdbTitleRatings.csv`** (contiene las valoraciones de las películas).

## **Cómo usarlo**

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/alberto96A/The-IMDB-Genre-Predicition-Project.git


2. Instala las dependencias:

   pip install -r requirements.txt


3.  Asegúrate de que los archivos de datos estén en la carpeta datasets
4.  Abre el Jupyter Notebook análisis_géneros.ipynb para visualizar el análisis y los modelos


## **Contribuciones y Notas**

Este es el proyecto más ambicioso de análisis y entrenamiento de datos que he realizado hasta la fecha. Sin embargo, es posible que aún haya algunos errores o áreas de mejora, ya que mi aprendizaje se trata de un trabajo en constante evolución. Estoy abierto a sugerencias, consejos o cualquier tipo de mejora que puedan tener, y estaría encantado de recibir contribuciones de cualquier persona interesada en dar feedback, sin importar el tipo que sea.

Si tienes ideas para optimizar el proyecto, o si encuentras algún error, no dudes en **abrir un _issue_** o hacer un **_pull request_**. ¡Tu colaboración es muy apreciada!

¡Gracias por tu interés en el proyecto!

