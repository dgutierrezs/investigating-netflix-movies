# Investigating Netflix Movies

## Descripción del problema
Análisis exploratorio del catálogo de Netflix para identificar tendencias
en duración de películas a lo largo del tiempo.

## Datos
- Fuente: DataCamp (netflix_data.csv)
- Variables principales: título, año de estreno, duración, género, país
- Tamaño: ~1500 filas, 7 columnas

## Enfoque
- Carga y exploración inicial del dataset con pandas
- Filtrado y limpieza de valores nulos
- Visualización de tendencias de duración por año con matplotlib
- Análisis por género y subconjuntos de datos

## Principales hallazgos
- La duración media de las películas ha disminuido en la última década
- Los documentales tienen una duración significativamente menor que el resto
- El género de acción concentra las películas más largas del catálogo

## Tecnologías
`Python` `pandas` `matplotlib`

## Cómo ejecutar
```bash
pip install pandas matplotlib
jupyter notebook notebook.ipynb
```
