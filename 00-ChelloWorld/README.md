# 00-ChelloWorld

## Compilador seleccionado
Se utiliza **GCC** con soporte para C23.

### Versión
Comando usado: `gcc --version`  
Salida del compilador:  
gcc (Ubuntu 13.2.0-23ubuntu1) 13.2.0  
Copyright (C) 2023 Free Software Foundation  

---

## Programa de prueba

### Código fuente: hello.c  
#include <stdio.h>

int main(void) {
    printf("Hola Thiago Molina!\n");
    return 0;
}

### Compilación  
gcc -std=c23 hello.c -o hello  

### Ejecución  
./hello  

**Salida esperada:**  
Hola Thiago Molina!  

---

### Redirección de salida  
Comando:  
./hello > output.txt  

El archivo **output.txt** contendrá:  
Hola Thiago Molina!
