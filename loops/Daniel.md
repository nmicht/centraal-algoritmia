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


## corridas de prueba 1
cantidad_dinero  

0  
0  
-1  
100  


pantalla  
Cuanto dinero quieres"  
" Dame una cantidad real para prestarte ....¬¬ "     
" Dame una cantidad real para prestarte ....¬¬ "    
billetes de 100 que me puede prestar " 1     
dinero que no prestara " 0    




## corridas de prueba 1


cantidad_dinero
0    
1234    

pantalla   
Cuanto dinero quieres"      
billetes de 100 que me puede   prestar " 12   
dinero que no prestara " 34    











