# Taller 01: Búsqueda A* — 8-puzzle

**Inteligencia Artificial - ELP 8012 - Universidad del Norte**
**Profesor:** Eduardo Zurek

## Descripción

Implementación del algoritmo de búsqueda A* para resolver el problema del 8-puzzle,
usando una heurística propia basada en grafos de adyacencia, diseñada e implementada por el equipo.

## Archivos

- `taller_01_busqueda_a_star_3.ipynb`
- `estadoinicial.txt` 
- `estadofinal.txt` 

## Cómo ejecutar

1. Colocar los archivos `estadoinicial.txt` y `estadofinal.txt` en la misma carpeta que el notebook
2. Abrir `taller_01_busqueda_a_star_3.ipynb`

## Heurística utilizada

Se usa una heurística basada en un grafo de adyacencias del tablero. Para cada
estado se construyen las relaciones entre fichas vecinas no vacías y luego se
comparan con las relaciones del estado objetivo. La heurística devuelve la
cantidad de diferencias entre ambos grafos.

Esta definición es simple, fácil de explicar y consistente con la implementada
en el notebook.

## Integrantes
MONTOYA GALINDO, BRYAN

QUINTERO LEON, ANDREA

SANTIAGO DONADO, WILMER
