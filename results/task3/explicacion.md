A la hora de hacer el análisis hemos usado el comando **advisor --collect=survey -- ~/ejecutable.exe**, pero al ejecutarlo nos aparecía el siguiente error: **Process exceeded login node resource limit**

Para resolverlo hemos solicitado un nodo de cómputo de manera interactiva con el comando **qsub -I**

Y para el snapshot hemos usado el comando **advisor --snapshot --project-dir=./lab1tarea3 --no-pack --cache-sources --cache-binaries -- snapshot_lab1Tarea3**
