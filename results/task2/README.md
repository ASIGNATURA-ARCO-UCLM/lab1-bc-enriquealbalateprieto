El warning que se muestra dice lo siguiente:
"Higher instruction set architecture (ISA) available. Your application was compiled using the SSE2 instruction set, which is lower 
than AVX2 - the highest ISA available on the target machine. To compile the application using the highest ISA available on the 
target machine: Use the -mavx2 option."

Por tanto, para solucionar este problema debería escribirse la opción "-mavx2" a la hora de realizar la compilación del programa 
"matmul.cpp". Así, se usaría un set de instrucciones óptimo, requiriéndose un comando como 
"g++ src/matmul.cpp -lgomp -mavx2 -o ejecutable2.exe"