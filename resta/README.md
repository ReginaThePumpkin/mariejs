# Código que implementa una resta de dos números en MARIE

### Lectura de datos
Se lee un dato en cada línea y se almacena en su respectiva variable
``` mas
 store A
 input
 store B
```
### Ejecución de la resta
Se carga en el *Acumulador* el valor almacenado en la variable `A` y después se le resta al valor en el Acumulador lo que hay en la variable `B` 
``` mas
 load A
 subt B
``` 

### Salida
Se imprime en la pestaña output el valor del acumulador (la resta)
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
