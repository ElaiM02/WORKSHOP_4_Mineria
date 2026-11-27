# Laboratorio 4 — EDA de Estadísticas Policiales del OIJ (2025)

Universidad Técnica Nacional · Minería de Datos ISW-911

## Contenido

| Archivo | Descripción |
|---|---|
| `data/estadisticas_oij_2025.csv` | Dataset original: delitos registrados por el OIJ del 01/01/2025 al 31/12/2025 (41 073 filas) |
| `lab4_IC2025.ipynb` | Notebook con el análisis exploratorio de datos (EDA) |

## Fuente de los datos

Organismo de Investigación Judicial (OIJ), Poder Judicial de Costa Rica — Estadísticas Policiales
<https://pjenlinea3.poder-judicial.go.cr/estadisticasoij/> · Licencia CC-BY.

**Nota:** el archivo se publica tal como lo exporta el portal. Su encabezado no coincide con las columnas de
los datos (falta `Hora` y sobra `Distrito`); el notebook corrige esto al leerlo.
