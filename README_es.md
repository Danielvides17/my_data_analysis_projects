# Análisis del Mercado de Spotify (2000-2023): La Era del Streaming

## Resumen del Proyecto
Este proyecto analiza más de 1 millón de canciones de Spotify para descubrir los cambios estructurales en el consumo y producción de la música durante las dos primeras décadas del Siglo 21. El objetivo es traducir los resúmenes crudos de audio a resúmenes de negocio accionables enfatizando en la retención de la audiencia, popularidad de los géneros y las estrategias modernas de producción musical.

## Pila Tecnológica
- **Gestión y Consulta de Base de Datos:** SQL (SQLite)
- **Manipulación de Datos:** Python (Pandas)
- **Visualización de Datos:** Matplotlib & Seaborn (Con estética de modo oscuro)

## Perspectivas Claves del Negocio
- **El Efecto "Skip":** Se analizó un declivo sistemático en el promedio de duración de las canciones a través de los años recientes, destacando un cambio en la industria por optimizar la monetización bajo el modelo de pagos del streaming
- **La Guerra del Volumen:** Se filtraron y visualizaron las tendencias del volumen (dB) de los géneros más ruidosos, revelando qué tanta comprensión es usada para capturar la atención de la audiencia con algoritmos en las listas de reproducción.
- **Singeria de Características de Audio:** Se desarrolló un mapa de calor que muestra una fuerte correlación entre la Energía y Volumen (0.78) de las canciones, a su vez, se probó que el volumen no necesariamente garantiza la popularidad (0.10 en la correlación).
- **Evolución de las Tendecias en Géneros por Lustro:** Se muestra una transición global de los gustos musicales, observando el descenso del Rock Alternativo y la globalización de géneros como K-Pop y Sertanejo en mercados fuera de su idioma nativo.


## Cómo Correr el Proyecto
1. Clone el repositorio.
2. Asegúrese de tener el archivo `spotify_data.csv` en la raíz del directorio. En caso que no, descárguelo del siguiente link: https://www.kaggle.com/datasets/amitanshjoshi/spotify-1million-tracks/data  
3. Corra en Jupyter Notebook `analisis_mercado_spotify_es.ipynb` celda por celda.
