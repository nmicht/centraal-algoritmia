 Calcular cuanto dinero me presta un amigo

## Problemática

Queremos pedir prestado a un amigo, pero solo nos puede prestar dinero con solo billetes de $100 infinitos. 

Diseñar un programa que debe indicarnos cuantos billetes de $100 me puede prestar y cuanto dinero no podra  

prestarnos por que no tiene monedas ni billetes para cubrir la cantidad.

## Pseudocodigo 

Inicio
    leer cantidad_prestamo

    imprimir "billetes de 100 que me puede prestar " cantidad_prestamo / 100 
    imprimir "dinero que no prestara " cantidad_prestamo % 100


fin

## Con ciclo

Inicio

    Cantidad_prestamo = 0 
    imprimir "Cuanto dinero quieres"
    leer y guardar cantidad_prestamo

    mientras( cantidad_prestamo <= 0 )
    inicio
        imprimir " Dame una cantidad real para prestarte ....¬¬ "
        leer y guardar cantidad_prestamo
    fin

    imprimir "billetes de 100 que me puede prestar " cantidad_prestamo / 100 
    imprimir "dinero que no prestara " cantidad_prestamo % 100

fin













