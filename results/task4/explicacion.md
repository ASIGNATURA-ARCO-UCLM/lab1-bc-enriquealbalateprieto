# Comparación entre el análisis realizado por la intefaz gráfica de Intel Advisor(1) y el del entorno devcloud(2):

* Tras revisar ambos snapshot, nos damos cuenta de que el tiempo de CPU empleado en ambos casos es de 0.09 segundos; además de que en los dos resultados se citan los mismos "top time-consuming loops".

* Sin embargo, en el primero de ellos se arroja algo más de información. Por ejemplo, se describe la posibilidad de usar un  set de instrucciones mejor para el programa estudiado; y se muestran datos de rendimiento y memoria como los GFLOPS (0.575), los GINTOPS(2.864) y la métrica "CPU <-> Memory [L1+NTS GB/s]" (32.082).

(1) Con un **Intel(R) Core(TM) i7-10510U CPU @ 1.80GHz** que utiliza como sistema operativo Linux
(2) Con un **Intel(R) Xeon(R) Gold 6128 CPU @ 3.40GHz** que utiliza como sistema operativo Linux