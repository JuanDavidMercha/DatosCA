# Calidad del Aire Bogotá - Streamlit

Esta aplicación permite visualizar la calidad del aire en Bogotá por fecha y contaminante, generando un GIF animado con las estaciones y vectores de viento.

## Estructura

- `app.py` : aplicación principal de Streamlit.
- `gif_generator.py` : código para generar los GIFs.
- `requirements.txt` : librerías necesarias.
- `README.md` : instrucciones.

## Cómo desplegar en Streamlit Cloud

1. Subir toda la carpeta a un repositorio en GitHub.
2. Conectar el repositorio en [Streamlit Cloud](https://streamlit.io/cloud).
3. Configurar `app.py` como archivo principal.
4. Asegurarse de que los CSV de calidad del aire estén disponibles en la ruta especificada en `RUTA_BASE`.
5. Abrir la app y seleccionar la fecha y el contaminante para generar el GIF.
6. Descargar GIF y CSV usando los botones disponibles.

## Requisitos

- Python 3.8 o superior
- Librerías: ver `requerimientos3.txt`
