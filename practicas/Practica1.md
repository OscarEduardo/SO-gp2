# Objetivo
Crear dos llamadas a sistema una para apagar y otra para realizar
Y crear sus respectivos programas

# Herramientas

git
make
gcc

## Conceptos
1)Llamadas a sistema
+ La forma que el kernel (SO) da acceso al HW.
+ Se implementa mediante interrupciones de software, ie,
la aplicación se interrumpe para que el kernel se ejecute.

2)Modo kernel
+ Es bit/registro que activa el CPU para acceder al HW.
+ Solo hay un programa que se ejecuta con este bit, es el kernel.

3) Interrupciones
+ Es la forma que el HW interactua con el CPU

# Que Aprendí
Que las llamadas a sistema pueden servir para agregar funciones a un hardware mediante el software. En esta practica lo que
hicimos fue agregar dos instrucciones para el sistema operativo que tomamos. Estas dos llamadas fueron apagar y otra para reiniciar
así el nuestro sistema operativo podria apagarse sin tener que reinciar nuestra ventana.

# Commit URL
https://github.com/eduardoalonso/SO-gp2/commit/03c382dc19f8ebb36f7436b798244d6a4667258e
