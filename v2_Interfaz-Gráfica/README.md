
# Career Search Tool

## Descripción
**Career Search Tool** es una herramienta gráfica que permite consultar las notas de corte de distintas carreras universitarias en un archivo Excel o CSV. Está diseñada para ser intuitiva y fácil de usar, brindando una interfaz moderna y eficiente.

## Características principales
- **Carga de archivo**: Admite archivos en formato `.xlsx` o `.csv`.
- **Búsqueda dinámica**: Permite buscar carreras por nombre, mostrando opciones relacionadas a medida que escribes.
- **Visualización clara**: Los resultados se presentan en forma de tabla con las columnas de universidad, carrera y notas de corte.
- **Mensajes informativos**: Proporciona retroalimentación sobre errores o acciones exitosas.

## Requisitos
- Python 3.11 o superior.
- Las siguientes bibliotecas:
  - `pandas`
  - `tkinter`

## Instrucciones de uso
1. Ejecuta el programa `career_search.py`.
2. Carga un archivo con los datos de las carreras utilizando el botón **"Cargar Archivo"**.
   - Asegúrate de que el archivo contenga las columnas: `Universidad`, `Grado`, `Corte Grupo 1`, `Corte Grupo 2`.
3. Escribe el nombre o parte del nombre de la carrera en el campo de texto.
4. Selecciona una opción del menú desplegable que aparecerá automáticamente.
5. Haz clic en **"Buscar Carrera"** para visualizar los resultados.
6. Los resultados se mostrarán en una tabla al final de la ventana.

## Ejemplo
Al buscar "Historia", el programa muestra todas las carreras que contienen dicho término, como:
- Historia
- Historia del Arte
- Historia y Ciencias de la Música

## Notas
- Si las columnas necesarias no están presentes en el archivo cargado, el programa mostrará un mensaje de error.
- Los datos del archivo deben estar bien formateados para un funcionamiento correcto.

## Autor
Desarrollado para facilitar la consulta de notas de corte de carreras universitarias.

## Licencia
Uso personal o educativo.
