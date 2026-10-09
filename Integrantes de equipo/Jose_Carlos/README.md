# Aportación de José Carlos: videos 10 y 11

Ejercicios de funciones estadísticas y álgebra lineal del curso de NumPy de Yacklyon. Esta carpeta es una aportación individual para integrarse al repositorio del equipo; no sustituye la entrega de los demás integrantes.

## Contenido
- `notebooks/Video_10_Funciones_Estadisticas.ipynb`
- `notebooks/Video_11_Algebra_Lineal.ipynb`


## Ejecución
En Google Colab: Archivo > Subir notebook; abrir cada `.ipynb` y ejecutar todas las celdas en orden. No requiere datasets externos.

En una computadora con Python, desde la carpeta descargada:
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
# source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyterlab
```

## Integración al equipo
El README principal del equipo debe añadir el enlace real del playlist, los autores completos, el reparto y las instrucciones con la URL real para clonar el repositorio. El enlace no se incluye aquí porque aún no se proporcionó.

Crear la rama `feat/videos-10-11`; copiar los notebooks a `notebooks/` del repositorio compartido. Hacer commits descriptivos y abrir un Pull Request. Otro integrante debe comentar y aprobar; después se integra a main. No subir este bloque directamente a main.

## Validación
Todas las celdas se ejecutaron en orden con Python y NumPy 2.3.5. Se comprobaron las dos soluciones con `allclose`. Las salidas están guardadas en los notebooks. Falta la prueba de clonado e integración del repositorio completo del equipo.

## Fuente y adaptación
Videos adjuntos: “CURSO DE NUMPY BASICO 🐍 funciones estadísticas” y “CURSO DE NUMPY BASICO 🐍 ALGEBRA LINEAL CON PYTHON”, Yacklyon. Se conservan los datos de los ejemplos, se reúnen las variantes general/por ejes y se añaden títulos, comentarios e interpretaciones. La comprobación del segundo sistema es adicional. No se reproducen errores transitorios mientras el instructor escribe.
