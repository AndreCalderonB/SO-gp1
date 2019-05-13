# Practica 2

## Objectivo

Modificar al programa init para imprimir un mensaje de bienvenida.
Modificar al programa sh para ejecutar al programa anterior.

## Herramientas

make 

gcc

git

## Conceptos

1) Proceso

+ Instancia de un programa.
+ Esta compuesto de 3 partes
++ stack: variables y funciones esta limitado. Crece de arriba hacia abajo. Stack Overflow.
++ heap: area de memoria dinámica = RAM + SWAP.
++ código: segmentado, ie es una parte.

+ Tiene estados
+ Se crean mediate dos llamadas a sistema:
++ fork: clone
++ exec: cambia código

+ Hay un proceso padre
++ init

## Que aprendi

Que un proceso necesita tener sus secciones bien definidas como es el stack, heap y codigo. Asi como la importancia de entender y modificar archivo para crear nuestro codigo que en este caso recibe un string y ejecuta una aplicacion. 

## Url del commit

https://github.com/AndreCalderonB/SO-gp1/commit/7c77796c5f9b33a7ff1c0ada2d4b67ffd394303c
