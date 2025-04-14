Apple clang version 17.0.0 (clang-1700.0.13.3)

#include <stdio.h>

int main() {
    FILE *archivo_salida = fopen("output.txt", "w");
    printf("Hola Santiago Siclari!");
    fprintf(archivo_salida,"Hola Santiago Siclari!");
    fclose(archivo_salida);
    return 0;
}
