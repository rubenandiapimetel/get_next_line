# get_next_line

Para leer un archivo de texto:

hacer make

Usar la funcion int get_next_line(int filedescr, char **buffer) por cada linea leida

parametros

int filedescriptor: es el descriptor de archivo a leer devuelto por la funcion fopen().

char**buffer: un doble puntero que sirve como buffer para almacenar el texto leido en cada linea de la matriz.

cada llamada a la funcion devuelve en el buffer una linea leida.

retorna 0 cuando se han leido todas las lineas.
