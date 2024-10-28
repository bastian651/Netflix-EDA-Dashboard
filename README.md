Análisis de Contenidos de Netflix
Descripción

Este repositorio contiene un análisis exploratorio de datos (EDA) del catálogo de contenido de Netflix y un dashboard interactivo en Power BI que visualiza los principales insights. El objetivo de este proyecto es entender los tipos de contenido disponibles en Netflix, identificar patrones basados en las calificaciones, año de lanzamiento y géneros populares, así como obtener información sobre la estrategia de contenido de Netflix en diferentes regiones.
Estructura del Proyecto

Dataset

El dataset utilizado en este proyecto proviene de Kaggle Netflix Movies and TV Shows Dataset. Contiene información sobre el catálogo de Netflix, incluyendo:

    type: Película o programa de TV.
    title: Nombre de la película o programa.
    director y cast: Director y elenco.
    country: País de producción.
    date_added: Fecha en la que se añadió a Netflix.
    release_year: Año de lanzamiento.
    rating y duration: Calificación por edades y duración.
    listed_in: Categorías y géneros.

Análisis Exploratorio de Datos (EDA)

El notebook Jupyter (netflix_analisis.ipynb) proporciona un análisis exploratorio en profundidad del contenido de Netflix. Las conclusiones clave incluyen:

    Desglose de Contenidos:
        Las películas constituyen 69,82% del catálogo de Netflix, mientras que los programas de TV representan 30,18%.

    Principales Calificaciones por Edad:
        Las calificaciones más comunes son:
            TV-MA (36,66%)
            TV-14 (24,44%)
            TV-PG (9,67%)

    Países con Mayor Producción:
        Estados Unidos (32,07%) e India (11,10%) países con más producciones.

    Principales Categorías:
        Las categorías más comunes son:
            Películas Internacionales (14,31%)
            Dramas (12,65%)
            Comedias (8,72%)

    Tendencias por Año de Lanzamiento:
        Visualización de las tendencias a lo largo de los años para identificar cambios en la estrategia de contenido de Netflix.

    netflix_analisis.ipynb: Este notebook contiene la limpieza de datos, transformación y análisis exploratorio utilizando Python y Pandas. Las visualizaciones se generan con Seaborn y Matplotlib.

Dashboard en Power BI

El dashboard de Power BI visualiza los hallazgos del EDA de forma interactiva. Incluye:

    Desglose del Tipo de Contenido: Distribución entre películas y programas de TV.
    Distribución de Calificaciones por Edad: Desglose del contenido de Netflix por calificaciones de edad.
    Principales Países de Producción: Visualización de los países con más contenido en Netflix.
    Principales Géneros/Categorías: Categorías y géneros más populares en Netflix.

Vista Previa del Dashboard

Incluye una captura de pantalla de tu dashboard de Power BI aquí para dar a los visitantes una vista previa de las visualizaciones.
Cómo Utilizar Este Repositorio

    Notebook Jupyter:
        Abre netflix_analisis.ipynb para explorar el análisis de datos y las visualizaciones usando Python.
    Dashboard en Power BI:
        Descarga dashboard netflix.pbix y ábrelo en Power BI Desktop para interactuar con las visualizaciones.

Insights y Conclusiones
Insights Clave:

    La estrategia de contenido de Netflix se ha centrado principalmente en películas, pero se observa un cambio hacia la producción de programas de TV en los últimos años.
    Estados Unidos e India lideran en términos de producción de contenido en el catálogo de Netflix.
    Los géneros más comunes son Películas Internacionales, Dramas y Comedias, lo que sugiere un enfoque global.

Recomendaciones:

    Estrategia de Contenido: Dada la creciente popularidad de los programas de TV, Netflix podría explorar la producción de más series exclusivas dirigidas a nichos de géneros específicos.
    Expansión Regional: Netflix podría beneficiarse de ampliar su biblioteca de contenido en países subrepresentados con alta demanda.

Trabajo Futuro

    Análisis de características basadas en texto para identificar contenido similar.
    Creación de un análisis de red de actores y directores para encontrar colaboraciones interesantes.
    Estudio del crecimiento de géneros o tipos específicos de contenido a lo largo del tiempo.

Agradecimientos

    El dataset utilizado para este análisis fue obtenido de Kaggle.

Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más información.
