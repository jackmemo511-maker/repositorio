# Dashboard de Análisis de Datos de Vehículos en EE. UU.

Este proyecto consiste en una aplicación web interactiva desarrollada con **Streamlit** que permite explorar y analizar un conjunto de datos sobre anuncios de venta de vehículos en los Estados Unidos. El objetivo principal es identificar tendencias y patrones en los precios de los autos mediante gráficos visuales y dinámicos.

El repositorio está organizado de la siguiente manera:
* **`app.py`**: El script principal de Python que ejecuta la aplicación web de Streamlit.
* **`vehicles_us.csv`**: El conjunto de datos original que contiene la información de los vehículos (precio, odómetro, modelo, año, etc.).
* **`requirements.txt`**: Archivo de texto que detalla todas las librerías y dependencias necesarias para ejecutar el proyecto.
* **`notebooks/`**: Una carpeta que almacena todo para una descarga completa de todos los elementos. 
* **`EDA.ipynb`**: Un cuaderno de Jupyter donde se realizó el Análisis Exploratorio de Datos (EDA) preliminar, pruebas de gráficos y limpieza de datos.
* **`.streamlit/`** *(Opcional)*: Carpeta de configuración para el diseño o tema de la aplicación.

La aplicación web proporciona un panel interactivo (dashboard) donde el usuario puede interactuar directamente con los datos a través de los siguientes componentes:
1. **Visualización de Datos**: Una tabla interactiva para explorar el conjunto de datos cargado.
2. **Gráfico de Histograma**: Un botón que genera un histograma interactivo para analizar la distribución del kilometraje (odómetro) de los vehículos.
3. **Gráfico de Dispersión**: Un botón que construye un gráfico de dispersión para evaluar la relación entre el precio de los vehículos y su kilometraje.
4. **Filtros Dinámicos**: Herramientas que permiten al usuario manipular las gráficas en tiempo real para obtener insights específicos.

Para el desarrollo de este proyecto se utilizaron las siguientes herramientas del ecosistema de Python:
* **Streamlit**: Para la creación rápida de la interfaz web interactiva.
* **Pandas**: Para la manipulación, limpieza y análisis estructurado de los datos.
* **Plotly Express**: Para la generación de gráficos interactivos y dinámicos que se integran nativamente con Streamlit.

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1. **Clona este repositorio** en tu máquina local.
2. Asegúrate de tener Python instalado y crea un entorno virtual (recomendado).
3. **Instala las dependencias** requeridas ejecutando en tu terminal:
   ```bash
   pip install -r requirements.txt

   🌐 Despliegue en Producción
La aplicación se encuentra desplegada y disponible de forma pública. Puedes interactuar con ella en el siguiente enlace:
https://repositorio-5nem.onrender.com/
