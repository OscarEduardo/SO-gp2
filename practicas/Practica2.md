# Objetivo
modificar el programa sh.c para ejecutar al comando anterior

# Herramientas

git
make
gcc

## Conceptos
1)Como se crean nuevos procesos
+ Un proyecto padre(sh.c) ejecuta la llamada a sistema fork.
+ La llamada a sistema fork clona el proceso padre
+ El proceso hijo manda a llamar a execpara ejecutar otro codigo

## Que aprendí:
Aprendí que mediante los procesos te puedes dar cuenta de las instancias que estan siendo ejecutadas
Estos contiene el codigo y la actividad del proceso y dependiendo del sistema operativo es si los procesos 
se ejecutan frecuentemente. 


## URL del commit
https://github.com/eduardoalonso/SO-gp2/commit/ebe8127536a4f5e8c02f5183d579f5043c678dcc
