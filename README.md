# DS_Curso_EquipoB · Curso de NumPy básico

Ejercicios del **Curso de NumPy con Python** (canal *yacklyon*), implementados en Jupyter Notebook por el Equipo B.

**Materia:** Ciencia de Datos · **Docente:** Fernando Mayorga Guittins · ITSAV

- Lista de reproducción: https://youtube.com/playlist?list=PLg9145ptuAij_8zYgMeqwOV8ABwRYLuR3

## Equipo y reparto

| Integrante | Videos | Notebooks |
|---|---|---|
| Arturo Obed Velázquez Téllez | 04 y 05 | `04_listas_vs_arrays`, `05_listas_con_arrays` |
| Ángel de Jesús González Molina | 06 y 07 | `06_funciones_basicas_matrices`, `07_operaciones_basicas_matrices` |
| Antonia Martínez Santos | 08 y 09 | `08_numeros_aleatorios`, `09_ejes_matrices` |
| José Carlos Hernández Ballado | 10 y 11 | `Video_10_Funciones_Estadisticas`, `Video_11_Algebra_Lineal` |

Los videos 01 a 03 son introducción e instalación y el 12 es un avance del curso de pandas; no tienen ejercicios de código.

## Mapeo del curso

La lista de reproducción tiene **12 videos** y **8 de ellos tienen ejercicios de código** (del 04 al 11):

| Video | Tema | Ejercicios |
|---|---|---|
| 01 | Presentación | No |
| 02 | Introducción | No |
| 03 | Cómo instalar NumPy | No |
| 04 | Listas o arrays (diferencias) | Sí |
| 05 | Usar listas con arrays | Sí |
| 06 | Usar funciones básicas en matrices | Sí |
| 07 | Usar operaciones básicas con matrices | Sí |
| 08 | Cómo usar los números aleatorios | Sí |
| 09 | Implementar ejes a las matrices | Sí |
| 10 | Funciones estadísticas | Sí |
| 11 | Álgebra lineal con Python | Sí |
| 12 | Avance del curso de pandas | No |

El avance de cada video se sigue en los [Issues](https://github.com/arturoobedvt-ctrl/DS_Curso_EquipoB/issues) del repositorio, con las etiquetas `To Do`, `In Progress`, `Review` y `Done`.

## Estructura

```
DS_Curso_EquipoB/
├── Integrantes de equipo/    # aportación de cada integrante: notebooks y README
│   ├── Arturo/
│   ├── Antonia/
│   ├── Angel/
│   └── Jose_Carlos/
├── notebooks/                # notebooks de todos juntos (se llena con los Pull Requests)
├── data/                     # datos de apoyo (el curso no usa archivos externos)
├── requirements.txt
└── README.md
```

## Cómo ejecutarlo

```bash
git clone https://github.com/arturoobedvt-ctrl/DS_Curso_EquipoB.git
cd DS_Curso_EquipoB
python -m venv .venv
# Windows: .venv\Scripts\activate   |   macOS/Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyterlab
```

Probado con Python 3.13 y NumPy 2.3.

## Flujo de trabajo

- `main` está protegida: los cambios entran por Pull Request con al menos 1 revisión.
- Cada integrante trabaja en su rama `feat/ejercicios-…` y otro compañero revisa su Pull Request.
- Los commits son descriptivos (`feat:`, `docs:`, `fix:`).
