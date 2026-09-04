# Algoritmos y Estructuras de Datos (AYED)

Agrupa las arenas, controles de lectura, informes, laboratorios, parciales, preparciales, prácticas en clase, recursos de apoyo y el proyecto del curso.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para saber cómo aprovechar este repositorio, ver [Cómo usar este repositorio](#cómo-usar-este-repositorio).

## Estructura del proyecto

```
Algoritmos-y-Estructuras-de-Datos/
├── Arenas/
│   ├── The-Power-Sum-AYED/
│   ├── Throwing-Cards-Away-AYED/
│   ├── Parentesis-Balanceados-AYED/
│   ├── Lista-Enlazada-Basica-AYED/
│   ├── Bicoloring-AYED/
│   ├── Heap-AYED/
│   ├── Conexiones-AYED/
│   └── Snipping-Tool-Print-Job-AYED/
├── ControlesDeLectura/
│   ├── Insertion-Sort-Descendente-AYED/
│   ├── Recursion-sobre-Arreglos-AYED/
│   └── Control-Estructuras-Lineales-AYED/
├── Informes/
│   └── Taller-Recursion-AYED/
├── Laboratorios/
│   ├── Dividir-y-Conquistar-AYED/
│   ├── Caracter-Frecuente-y-Palindromo-AYED/
│   ├── Decoding-the-Message-AYED/
│   ├── HashTable-y-Disjuntos-AYED/
│   ├── Montones-Binarios-AYED/
│   └── Grafos-Adyacencia-y-Recorridos-AYED/
├── Parciales/
│   ├── Parcial-Divide-y-Venceras-AYED/
│   └── Parcial-Estructuras-Enlazadas-AYED/
├── Preparciales/
│   └── Numeros-Primos-AYED/
├── PracticaEnClase/
│   ├── Analisis-de-Complejidad-AYED/
│   ├── Clase-Estudiante-AYED/
│   ├── Fibonacci-AYED/
│   ├── Insertion-Sort-AYED/
│   ├── Caracter-Mas-Frecuente-en-Cadena-AYED/
│   ├── Area-de-Efecto-en-Matriz-AYED/
│   ├── Power-Sum-Recursivo-y-Memorizado-AYED/
│   ├── Grafos-BFS-DFS-y-Bellman-Ford-AYED/
│   ├── Arbol-Binario-AYED/
│   ├── Listas-Pilas-y-Colas-Enlazadas-AYED/
│   ├── Lista-Enlazada-con-Reversa-y-Union-AYED/
│   └── Arboles-con-Rotacion-AYED/
├── Recursos/
│   ├── Disjoint-Sets-AYED/
│   └── Hash-Tables-AYED/
├── Proyectos/
│   └── Patinaje-AYED/
└── Monitoria/
    └── DDYA/
```

## Temas del curso

- Análisis de complejidad algorítmica (temporal y espacial).
- Recursión: casos base, recursión de cola, ramificación y poda.
- Dividir y conquistar (merge sort, conjetura de Collatz).
- Estructuras lineales: listas simplemente y doblemente enlazadas, pilas y colas.
- Estructuras jerárquicas: árboles binarios, árboles balanceados por rotación.
- Grafos: representación por matriz/lista de adyacencia, recorridos BFS y DFS, caminos más cortos (Bellman-Ford).
- Tablas hash y manejo de colisiones (encadenamiento, búsqueda binaria, redimensionamiento).
- Montículos binarios (heaps) y heapsort.
- Conjuntos disjuntos (Disjoint Sets / Union-Find).

## Cosas a tener en cuenta

- Cada repositorio corresponde a una actividad puntual (arena, control de lectura, informe, laboratorio, parcial, preparcial o práctica en clase); el tipo de actividad está indicado en la descripción de cada repositorio, no en su nombre.
- Cuando dos archivos eran versiones sucesivas de un mismo ejercicio (el segundo extendía al primero con nueva funcionalidad), se conservaron en un solo repositorio con dos commits secuenciales para mantener la trazabilidad de esa evolución, en vez de crear repositorios separados.
- El proyecto del curso (`Patinaje-AYED`) tiene una estructura de README distinta a la del resto de actividades académicas, ya que corresponde a un proyecto de software y no a una entrega puntual.
- La carpeta `Monitoria/DDYA/` es un submódulo (repositorio [Monitoria-DDYA](https://github.com/JuanGuayazanC/Monitoria-DDYA)), con el material elaborado como monitor del curso Diseño de Datos y Algoritmos (DDYA), homologado con AYED.

## Herramientas

- Python 3
- Lectura de entrada estándar (`stdin`) para la resolución de problemas de jueces en línea (arenas)

## Profesor

Sebastian Camilo Martinez Reyes.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes, uno por actividad, organizados por carpetas (`Arenas/`, `ControlesDeLectura/`, `Informes/`, `Laboratorios/`, `Parciales/`, `Preparciales/`, `PracticaEnClase/`, `Recursos/`, `Proyectos/`, `Monitoria/`). Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Algoritmos-y-Estructuras-de-Datos.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
