# Comparación entre el análisis realizado por la intefaz gráfica de Intel Advisor(1) y el del entorno devcloud(2):

* Tras revisar ambos snapshot nos damos cuenta que el tiempo de CPU en Intel Advisor es 0,01 segundos mayor con respecto al devcloud (0,10 en devcloud y 
 0,11 en advisor), además si miramos el tiempo consumido en los diferentes bucles observamos que se ejecutan mas rápido en devcloud

* Sin embargo, en el primero de ellos se arroja algo más de información. Por ejemplo, se describe la posibilidad de usar un set de instrucciones mejor para el programa estudiado

(1) Con un **Intel(R) Core(TM) i7-10510U CPU @ 1.80GHz** que utiliza como sistema operativo Linux
(2) Con un **Intel(R) Xeon(R) Gold 6128 CPU @ 3.40GHz** que utiliza como sistema operativo Linux
