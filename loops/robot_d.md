# Robot

## Problemática

SE requiere que un robot_chat inicie la conversación con el usuario. 
a partir del saludo el robot tendrá que preguntar "algo" al usuario y dependiendo si el 
usuario le responde con palabras "clave" el robot tendrá  que decidir si continua con un 
monologo o se despedirse


nuestro SDK nos explica que podemos usar las siguientes Funcionalidades : 

saludar()  
Preguntar_tema_random () 
monologo() 
despedirse () 



## robot_chat

Inico
    Respuesta = 0;
    
    saludar()
    leer y guardar respuesta 

    mientras ( respuesta != adios )

        si ( respuesta == pregunta )
            Preguntar_tema_random()

        si ( respuesta == monologo )
            monologo() 

        saludar()
        leer y guardar respuesta 
    Inicio

    Fin
    
    despedirse()
    
Fin 




