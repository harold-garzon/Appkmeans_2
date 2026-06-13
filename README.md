# AppFlask

Este proyecto contiene una aplicación web desarrollada con Flask.

## Descripción

La aplicación está diseñada para ejecutar un servidor local y mostrar contenido dinámico mediante rutas de Flask. Incluye la configuración básica necesaria para iniciar un proyecto web ligero en Python.

## Requisitos

- Python 3.8 o superior
- Flask instalado

## Instalación

1. Clona o descarga el repositorio.
2. Abre una terminal en la carpeta del proyecto.
3. Crea un entorno virtual (opcional pero recomendado):

   ```bash
   python -m venv venv
   ```

4. Activa el entorno virtual:

   - En Windows:
     ```bash
     venv\Scripts\activate
     ```

   - En macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Instala Flask:

   ```bash
   pip install Flask
   ```

## Ejecución

1. Desde la carpeta del proyecto, ejecuta la aplicación Flask:

   ```bash
   python app.py
   ```

2. Abre un navegador y visita:

   ```
   http://127.0.0.1:5000
   ```

## Notas

- Si la aplicación utiliza otro archivo principal distinto de `app.py`, ajusta el comando de ejecución según corresponda.
- Para detener el servidor, presiona `Ctrl+C` en la terminal.
