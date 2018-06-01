#Pedir_prestado_a_un_amigo

##Problemática
El usuario necesita que le presten dinero, solo tiene billetes de 100, no se tienen otras cantidades menores ni mayores y lo que se puede prestar es infinito. decir cuantos billetes le debe entregar y cuanto dinero no le puede prestar ejemplo 120$ se debe de dar 1 billete de 100 y no se pueden prestar 20$ ahora si se puede equivocar pidiendo 0 o menos.

##Pseudocódigo
Inicio  
    dinero_pedido  
    Imprime '¿Cuanto dinero desea?'
    Leer dinero_pedido  
    mientras (dinero_pedido <= 0)
    Inicio
        Imprime 'Esa cantidad no es valida por favor introduzca otra cantidad'
        leer dinero_pedido
    Fin
    BILLETES_A_PRESTAR = dinero_pedido / BILLETES  
    DINERO_QUE_NO_SE_PUEDE_ENTREGAR = dinero_pedido % BILLETES  
    Imprimir "Los billetes que se entregaran son:", BILLETES_A_PRESTAR  
    Imprimir "El dinero que no se puede prestar es:", DINERO_QUE_NO_SE_PUEDE  
Fin

##Corridas de escritorio

dinero_pedido
54863  
BILLETES_A_PRESTAR = 54863 / 100= 548  
DINERO_QUE_NO_SE_PUEDE = 54863 % 100 = 63  

dinero_pedido
-8056
0
101

pantalla
¿Cuanto dinero desea?
esa cantidad no es valida por favor introduzca otra cantidad
esa cantidad no es valida por favor introduzca otra cantidad
Los billetes que se entregaran son: 1
El dinero que no se puede prestar es: 1
