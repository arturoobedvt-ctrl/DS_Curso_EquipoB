# Aportación de Arturo Obed Velázquez Téllez: videos 04 y 05

Ejercicios del curso de NumPy de Yacklyon. Esta carpeta es una aportación individual para integrarse al repositorio del equipo; no sustituye la entrega de los demás integrantes.

## Contenido
- `notebooks/04_listas_vs_arrays.ipynb`
- `notebooks/05_listas_con_arrays.ipynb`

## Ejecución
En una computadora con Python, desde esta carpeta:
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
# source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyterlab
```
No requiere datasets externos.

## Integración al equipo
Crear la rama `feat/ejercicios-videos-04-05`, copiar los notebooks a `notebooks/` del repositorio compartido, hacer commits descriptivos y abrir un Pull Request. Otro integrante debe revisarlo y comentarlo antes de integrarlo a `main`. No subir esta carpeta completa a `main`.

## Validación
Todas las celdas se ejecutaron en orden con Python 3.13 y NumPy 2.3. Las salidas están guardadas en los notebooks. Falta la prueba de clonado e integración del repositorio completo del equipo.

## Fuente
Videos “CURSO DE NUMPY BASICO · LISTAS O ARRAYS (diferencias)” y “usar listas con arrays”, canal Yacklyon. Se conservan los conceptos de los videos y se reemplazan los datos de los ejemplos por datos propios (tienda de abarrotes y temperaturas de ciudades), con comentarios que explican el porqué de cada paso.
