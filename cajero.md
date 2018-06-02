# Cajero
## Problematica
Con el objetivo de tomar prestado de un cajero una cantidad que sea positiva, el cual solo puede dar billetes de 100, cierta cantidad, obtener el numero de billetes de 100 que puede prestar, y la cantidad que queda a deber.

## Pseudocodigo
    Inicio
        leer y guardar cantidad
        mientras (cantidad <= 0)
            Imprime "Cantidad invalida"
            leer y guardar cantidad

        Imprimir "Numero de billetes a prestar" , (cantidad / 100)
        Imprimir "Dinero a deber:", (cantdidad % 100)
     Fin

## Pruebas de escritorio
---
### Prueba 1
Entradas:

    cantidad = 0

Proceso:

    cantidad = -100
    cantidad = 100


Salidas:

    Cantidad invalida
    Cantidad invalida  
    "Numero de billetes a prestar 1"
    "Dinero a deber: 0"

---
### Prueba 2
Entradas:

    cantidad = 123

Proceso:

    "Numero de billetes a prestar 1"
    "Dinero a deber: 23"
     
Salidas:

    13
    2

