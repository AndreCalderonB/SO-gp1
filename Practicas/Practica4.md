# Practica 4
## Objetivo
Hacer un spike sobre IPC: señales, fork/exec, memoria compartida y archivos mapeados a memoria. 
# Herramientas
+ git
+ gcc


 # Conceptos:

 + IPC
   + Comunicación entre procesos.

 + Señales:
   + Es un ipc, consta de un procesos emisor y un receptor. 
   El emisor manda una señal y el receptor deja de hacer lo que esta haciendo y ejecuta el código de la señal.
   + Existen varias señales, para listarlas puedo usar el comando kill -l.

 + Memoria compartida.
    + Se crea un bloque de memoria, el bloque de memoria tiene un key.
    + Cualquier proceso con el key se puede conectar al bloque.
    + El bloque de memoria persiste hasta que se borre mediante un comando o se reinicie la computadora.

 + Archivos mapeados a memoria.
    + Es un bloque de memoria compartida que esta asociado a un archivo.
    + Los cambios en el bloque se guardan automaticamente.

 # ¿Que aprendí?
 
Que los IPC son mecanismos que permiten a los procesos sincronizarse y comunicar sus acciones entre ellos sin necedidad de estar en la misma dirección de memoria. Ademas de que es fundamental para la utilizacion del CPU en computadoras con sistema con multiples threads.

 # Url del commit

 https://github.com/AndreCalderonB/SO-gp1/commit/6bf0a7debada94e778a17c75151fcaf278b2b95c
