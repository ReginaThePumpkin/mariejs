# Código que implementa una suma de dos números en MARIE

### Lectura de datos
Se lee un dato en cada línea y se almacena en su respectiva variable
``` mas
 input
 store A
 input
 store B
```
### Ejecución de la suma
Se carga en el **Acumulador** el valor almacenado en la variable `A` y después se le suma al valor en el **Acumulador** lo que hay en la variable `B` 
``` mas
 load A
 add B
``` 

### Salida
Se imprime en la pestaña output el valor almacenado en el **Acumulador** (la suma)
``` mas
 output
```

### Fin del programa
Detiene la ejecución del programa
``` mas
halt
```
### Declaración de variables
Se declaran las variables al final. En este caso, `A` y `B` como decimales (`DEC`) 
``` mas
A, DEC 0
B, DEC 0 
```
