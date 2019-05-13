# Objetivo
Investigar y practicar hilos

# Herramientas
gcc
git

# Conceptos
- Hilos
  - Proceso ligero
  - Solo tiene un stack y el codigo y el heap lo comparte con el proceso principal
  - Si el proceso principal muere, los hilos igual moriran.
 
- Lock
  - Mecanismo de sincronización 
  - Variable global que soporta dos operaciones
    - Lock, el primer hilo que hace lock se adueña del lock, el resto queda en espera.
    - Unlock, libera el lock de un hilo
  - Ayuda para resolver el problema de la sección crítica.
  
- Semáforo
  - Mecanismo de sincronización
  - Variable global que tiene un valor inicial mayor o igual a 0. Soporta dos operaciones. 
    - Wait/Decrease. Si es mayor a cero decrementa y continua, si es mayor, se suspende.
    - Post/Increase. Incrementa el valor del semáforo en uno.
  - Para asignar recursos.
  
- Problemas de sincronización
  - Condición de carrera. Ocurre cuando el resultado depende del orden en que se ejecutan los hilos.
  - Deadlock. Ocurre cuando dos o más hilos están esperando un recurso que no se libera nunca.
  - Productor/Consumidor. Ocurre cuando los datos se pueden sobreescribir.
 
 # URL de commit
 
 https://github.com/eduardoalonso/SO-gp2/commit/d7bd6beb36cecb6b5360f205b82634050ca5785b
  
 # Que aprendí?
Aprendí cual es el funcionamiento de los hilos, cual es el detalle de los locks y sus funciones. Tambien tuve oportunidad de aprender sobre los mecanismos de sincronización y cunado llegan a fallar.
