A la hora de hacer el análisis hemos usado el comando **advisor --collect=survey --project-dir=./labTarea3 --exclude-files=./src/foo --exclude-files=./src/bar -- ./src/ejecutable.exe**, pero al ejecutarlo nos aparecía el siguiente error: **Process exceeded login node resource limit**

Para resolverlo hemos ejecutado el comando desde un nodo de cómputo de manera interactiva solicitado con el comando **qsub -I**

Y para el snapshot hemos usado el comando **advisor --snapshot --pack --cache-sources --cache-binaries --project-dir=./labTarea3 -- snapshotTarea3**
