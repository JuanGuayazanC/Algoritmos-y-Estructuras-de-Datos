# Algoritmos y Estructuras de Datos (AYED)

Material de apoyo del curso organizado por tema: arenas, controles de lectura, informes, laboratorios, parciales, preparciales, prácticas en clase, recursos y el proyecto.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para saber cómo aprovechar este repositorio, ver [Cómo usar este repositorio](#cómo-usar-este-repositorio).

## Autor

[JUAN SEBASTIÁN GUAYAZÁN CLAVIJO](https://github.com/JuanGuayazanC)  
Escuela Colombiana de Ingeniería Julio Garavito

## Estructura del proyecto

```
Algoritmos-y-Estructuras-de-Datos/
├── 00_Fundamentos_y_Analisis/
│   ├── Analisis-de-Complejidad-AYED/
│   ├── Area-de-Efecto-en-Matriz-AYED/
│   ├── Caracter-Frecuente-y-Palindromo-AYED/
│   ├── Caracter-Mas-Frecuente-en-Cadena-AYED/
│   ├── Clase-Estudiante-AYED/
│   ├── Decoding-the-Message-AYED/
│   ├── Insertion-Sort-AYED/
│   ├── Insertion-Sort-Descendente-AYED/
│   └── Numeros-Primos-AYED/
├── 01_Recursion/
│   ├── Recursion-sobre-Arreglos-AYED/
│   ├── Taller-Recursion-AYED/
│   └── The-Power-Sum-AYED/
├── 02_Dividir_y_Conquistar/
│   ├── Dividir-y-Conquistar-AYED/
│   └── Parcial-Divide-y-Venceras-AYED/
├── 03_Programacion_Dinamica/
│   ├── Fibonacci-AYED/
│   └── Power-Sum-Recursivo-y-Memorizado-AYED/
├── 04_Estructuras_Lineales/
│   ├── Control-Estructuras-Lineales-AYED/
│   ├── Lista-Enlazada-Basica-AYED/
│   ├── Lista-Enlazada-con-Reversa-y-Union-AYED/
│   ├── Listas-Pilas-y-Colas-Enlazadas-AYED/
│   ├── Parcial-Estructuras-Enlazadas-AYED/
│   ├── Parentesis-Balanceados-AYED/
│   └── Throwing-Cards-Away-AYED/
├── 05_Arboles/
│   ├── Arbol-Binario-AYED/
│   └── Arboles-con-Rotacion-AYED/
├── 06_Grafos/
│   ├── Bicoloring-AYED/
│   ├── Grafos-Adyacencia-y-Recorridos-AYED/
│   └── Grafos-BFS-DFS-y-Bellman-Ford-AYED/
├── 07_Montones_y_Colas_de_Prioridad/
│   ├── Heap-AYED/
│   └── Montones-Binarios-AYED/
├── 08_Tablas_Hash_y_Conjuntos_Disyuntos/
│   ├── Conexiones-AYED/
│   ├── Disjoint-Sets-AYED/
│   ├── Hash-Tables-AYED/
│   ├── HashTable-y-Disjuntos-AYED/
│   └── Snipping-Tool-Print-Job-AYED/
├── 09_Proyecto/
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

Este repositorio no contiene código directamente: es una colección de repositorios independientes, uno por actividad, organizados por tema (`00_Fundamentos_y_Analisis/`, `01_Recursion/`, … `09_Proyecto/`). Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para estudiar un tema**: entra a su carpeta; el README de cada tema lista las actividades y su tipo.
- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Algoritmos-y-Estructuras-de-Datos.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
