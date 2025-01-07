# Optimización Numérica y Combinatoria

# Parte 1: optimización numérica

Funciones de Prueba
Se utilizaron las siguientes funciones como referencia para la optimización:

Función de Rosenbrock
Función de Rastrigin

### Actividades Realizadas
Optimización mediante Descenso por Gradiente:

- Resolución de las funciones en dos y tres dimensiones con condiciones iniciales aleatorias.
- Representación gráfica del proceso de optimización en un GIF o video.
- Optimización mediante Métodos Heurísticos:

Implementación de los siguientes enfoques:
- Algoritmos Evolutivos.
- Optimización de Partículas.
- Evolución Diferencial.
- Representación gráfica del proceso de optimización en un GIF o video.

 ### Todo lo mencionado previamente se encuentra en la carpeta [Algoritmos bioinspirados](https://github.com/aleuse/rna_trabajo1_optimizacion_heuristica/tree/main/Algoritmos%20Bioinspirados) en el archivo optimizacion_ae_op_ed.ipynb allí podrá visualizar como fue implementado el algoritmo, sus gráficas y respectivos gifs

# Parte 2: Optimización Combinatoria

En esta sección, abordaremos el **Problema del Viajero (TSP, Traveling Salesman Problem)** aplicado a un caso práctico: un vendedor debe visitar las capitales de los 32 estados de los Estados Unidos Mexicanos, recorriendo cada una de ellas una única vez y minimizando el costo total del viaje. Este problema es un ejemplo clásico de **optimización combinatoria**, ampliamente estudiado en áreas como logística, transporte y planificación de rutas.

El costo total del recorrido incluye tres componentes principales:

1. **El costo del tiempo del vendedor**, calculado a partir del valor por hora de su trabajo.
2. **Los costos de peajes**, correspondientes a los trayectos específicos entre las capitales.
3. **El costo del combustible**, determinado por el vehículo utilizado y las distancias recorridas.

Para resolver este problema de manera eficiente, utilizaremos dos enfoques inspirados en la naturaleza y la evolución:

1. **Colonias de Hormigas (ACO, Ant Colony Optimization)**: un algoritmo inspirado en el comportamiento colectivo de las hormigas en la búsqueda de rutas óptimas hacia fuentes de alimento.
3. **Algoritmos Genéticos (GA, Genetic Algorithms)**: un enfoque basado en la evolución natural, utilizando conceptos como selección, cruce y mutación para explorar el espacio de soluciones.

### **Enfoque**

- **Colonias de Hormigas (ACO):** Se modelará el recorrido del vendedor como un grafo, donde las ciudades representan los nodos y los trayectos entre ellas las aristas, ponderadas por el costo total. A través de iteraciones, las hormigas buscarán construir rutas óptimas, utilizando feromonas para guiar la exploración.
  ### Se encuentra en la carpeta [Colonia de hormigas](https://github.com/aleuse/rna_trabajo1_optimizacion_heuristica/tree/main/Colonia%20de%20hormigas) en el archivo implementacion_ACO.ipynb allí podrá visualizar como fue implementado el algoritmo, sus gráficas y respectivos gifs
- **Algoritmos Genéticos (GA):** La solución inicial será representada por una población de rutas aleatorias. Utilizando operadores genéticos como cruce y mutación, se generarán nuevas soluciones, mejorando iterativamente hasta aproximarse a la ruta óptima.
  ### Se encuentra en la carpeta [Algoritmo génetico](https://github.com/aleuse/rna_trabajo1_optimizacion_heuristica/tree/main/Colonia%20de%20hormigas) en el archivo TSP_Algoritmo_genetico.ipynb allí podrá visualizar como fue implementado el algoritmo, sus gráficas y respectivos gifs

