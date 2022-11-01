# Informe final

| Procesador | Núcleos | Hilos | Frecuencia | Caché L1 | Caché L2 | Caché L3 |
| -- | -- | -- | -- | -- | -- | -- | 
| Intel(R) Xeon(R) Gold 6128 | 6 | 12 | 3.40GHz| 394KB | 12,5MB | 40,4MB |
| Intel(R) Core(TM) i7-10750H | 6 | 12 | 2,60GHz| 196,6KB | 1,57MB | 12,6MB |

La **primera fila** representa los datos del sistema usado en el **devcloud** y la **segunda** el usado en el **advisor**

La diferencia entre ambos tiempos de ejecución se debe a la diferencia entre las frecuencias de ambos procesadores y el tamaño de ambos cachés. Como es el Intel Xeon Gold el procesador con mejores atributos la ejecución del programa (recuperación de instrucciones y cálculos necesarios) se realiza de forma más rápida.
