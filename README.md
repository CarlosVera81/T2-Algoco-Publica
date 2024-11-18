# T2-Algoco-Publica

Consideraciones:
-  Para los dos programas, se necesitan que las matrices de costos esten en la misma carpeta de la ejecucion del programa,
las matrices tienen que tener los nombres: cost_insert.txt,cost_delete.txt,cost_replace.txt,cost_transpose.txt.
-  Para los dos programas, se necesita que el dataset se encuentre en la misma carpeta de la ejecucion del programa,
el dataset tiene que tener el nombre: dataset.txt

Para compilar y ejecutar el codigo bf.cpp:

- g++ -o bf bf.cpp -Wall
- ./bf

Para compilar y ejecutar el codigo dp.cpp:

- g++ -o dp dp.cpp -Wall
- ./dp

Si se quiere medir el uso de memoria con valgrind y la herramienta massif, se tiene que ejecutar el siguiente comando:

- valgrind --tool=massif ./bf
- valgrind --tool=massif ./dp

Para los programas de fuerza bruta y programacion dinamica, respectivamente.

Esta utilidad ejectutara los programas, por lo tanto tiene que tener todos los archivos necesarios mencionados anteriormente.

Después de la ejecución se creara un archivo massif.out.\<pid>

Para vizualizar este archivo, se tiene que ejecutar el siguiente comando:
-  ms_print massif.out.\<pid>
