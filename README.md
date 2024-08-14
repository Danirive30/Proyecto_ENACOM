# Proyecto de Análisis de Datos de Telecomunicaciones (ENACOM)

<p align="center">
  <img src="image.png" alt="alt text" width="500"/>
</p>

## Descripción del Proyecto

Este proyecto se centra en el análisis de datos relacionados con el acceso a servicios de internet en Argentina, utilizando datasets proporcionados por el Ente Nacional de Comunicaciones (ENACOM). A través de un análisis exploratorio de datos (EDA) y la creación de indicadores clave de rendimiento (KPIs), se busca evaluar el crecimiento y la calidad del acceso a internet en diversas provincias, identificando tendencias y oportunidades de mejora.

## Tecnologías y Herramientas Utilizadas

- **Python**: Lenguaje de programación principal para el análisis de datos.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **Matplotlib y Seaborn**: Bibliotecas para la visualización de datos.
- **Jupyter Notebook**: Entorno de desarrollo para la elaboración de informes interactivos.
- **Power BI**: Herramienta de visualización para presentar resultados finales.

## Metodología Aplicada

1. **Recolección de Datos**: Se recopilaron datos de diferentes fuentes, organizados en múltiples hojas dentro de archivos Excel, que abarcan desde 2014 hasta 2024 (primer trimestre).
2. **Preprocesamiento de Datos**: Se realizaron operaciones para limpiar los datos, incluyendo la verificación de duplicados y la imputación de valores nulos.
3. **Análisis Exploratorio de Datos (EDA)**: Se llevaron a cabo visualizaciones y análisis estadísticos para identificar patrones, tendencias y correlaciones significativas en los datos.
4. **Definición de KPIs**: Se definieron y calcularon KPIs relevantes para medir el acceso y la calidad del servicio de internet, con un enfoque en el crecimiento y la penetración del servicio entre los hogares, la velocidad Mbps y los ingresos.
5. **Visualización de Resultados**: Los resultados se presentaron de manera visual mediante gráficos y un dashboard, facilitando la interpretación de los hallazgos.

## Estructura del Repositorio

- **Dashboard**: Contiene el archivo .pbix de Power BI en el que se hizo la visualización y los KPIs.
- **Datasets**: Contiene el archivo de `Internet.xlsx`, los datos procesados (`data_general.xlsx` y `data_provincias.xlsx`), así como el diccionario de datos.
- **Notebook**: Contiene el notebook de jupyter en el que se elaboró el análisis exploratorio de datos (EDA).
- **README.md**: Este archivo, que describe el proyecto y sus resultados.

## Uso y Ejecución

Para ejecutar el proyecto, siga estos pasos:

1. Descargue el archivo .pbix del directorio `Dashboard`.
2. Abra el archivo en Power BI Desktop.
3. Conéctese a los datos con los archivos en el directorio `Datasets`.
4. Ejecute el notebook de jupyter en el directorio `Notebook` para realizar el análisis exploratorio de datos.
5. Revise el archivo README.md para obtener más información sobre el proyecto y sus resultados.

## Análisis Detallado

### Conclusiones del EDA

- Se observó un crecimiento sostenido en el acceso y la velocidad de conexión a internet en las provincias analizadas.
- No se encontraron datos duplicados ni outliers significativos; sin embargo, se identificaron y corrigieron algunas entradas nulas.
- La correlación positiva entre el acceso a cablemodem, fibra óptica y la velocidad de descarga promedio indica una modernización de las tecnologías de conexión.

### KPIs Generados

1. **KPI de accesos a internet p/c 100 hogares**: Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia.
2. **KPI de velocidad de conexión Mbps**: Aumentar en un 10% la velocidad de conexión a internet en las provincias analizadas, en el próximo trimestre.
3. **KPI de crecimiento de ingresos**: Aumentar en un 15% los ingresos en el próximo trimestre.

- Esta información trata sobre el estado de las telecomunicaciones en Argentina, centrado en el acceso a Internet, la velocidad de conexión y los ingresos. Los datos abarcan un período desde 2014 hasta 2024 (primer trimestre), organizados por año, trimestre, provincia. Se evidencia un notable aumento en el acceso a internet y la velocidad de conexión a lo largo del tiempo, lo que sugiere una mejora en la infraestructura tecnológica del país y por lo tanto, un significativo aumento en los ingresos. La construcción de KPIs fue relevante para medir y evaluar el crecimiento y la calidad del acceso a internet en diversas provincias.

## Fuente de Datos

- **Obligatorio: Internet**: <https://indicadores.enacom.gob.ar/datos-abiertos>
- **Diccionario de datos**: <https://docs.google.com/document/d/1BYW0vT_DNIjjKM9v4hNg5KmqjRNOc7OBB1jCXc80gnI/edit#heading=h.hjukififf3ol>

## Conclusiones Finales

Este proyecto proporciona un panorama claro del estado del acceso a internet en Argentina, ofreciendo información valiosa para la toma de decisiones. Los KPIs generados son fundamentales para monitorear el progreso y proponer mejoras en la infraestructura y servicios de telecomunicaciones.

## Autor

Este proyecto fue elaborado por: José Daniel Rivera Hernández. (<Daniel.rivera.30@outlook.com>)

---

¡Saludos! 🚀

# Proyecto_ENACOM
