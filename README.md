Simplemente se trata de seguir la máxima del 'divide y vencerás'.

Separa los problemas en más pequeños. Solucionalos. Combínalos


Existen algoritmos de ordenamiento que siguen esta técnica

    - Quicksort
    - Merge Sort
    - Etc (por ver)



###Diferencias con Dynamic Programming (DP)

Ambos paradigmas resuelven subproblemas.

    - D&C debería de usarse cuando el subproblema no tenga que ser evaluado multitud de veces.
      Por ejemplo, Quicksort es un algoritmo de D&C. No vamos a evaluar el mismo problema 2 veces.



###Pros de D&C:

    - La dificultad del problema puede ser fácilmente resuelta
    - Divide el problema en subproblemas y puede ser resueltos paralélamente usando multiprocessing
    - Usa eficientemente memoria caché sin ocupar mucho espacio
    - Reduce el tiempo de complejidad del problema


### Cons de D&C:

    - Involucra recursión lo que a veces es lenta
    - La eficiencia depende de la implementación de la lógica
