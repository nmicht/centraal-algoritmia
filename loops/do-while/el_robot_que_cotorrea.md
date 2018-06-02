# El robot que cotorrea:

## Problema  
Se requiere que un roboto-chat inicie la conversación con el usuario. A partir del saludo el robot tendrá que preguntar "algo" al usuario y dependiendo si el usuario le responde con palabras "clave" el robot tendrá que decidir si continúa con un monologo o se despide.

Nuestro SDK(software development kit) nos explica que podemos usar las siguientes funcionalidades:

* saludar ()  
* preguntar_tema_random ()  
* monologo ()  
* despedirse ()  

## Pseudocódigo  
```
Inicio
  respuesta_saludo
  respuesta_tema_random
  respuesta_monologo
  saludar ()
  Leer respuesta_saludo
    if (respuesta_saludo != adios o respuesta_saludo != bye o respuesta_saludo != fuchi)
      hacer
        preguntar_tema_random ()
        Leer respuesta_tema_random
        monologo ()
        imprime '¿quieres otra pregunta?'
        Leer respuesta_monologo
      mientras (respuesta_monologo != adios o respuesta_monologo != bye o respuesta_monologo != no)
    if_Fin
    despedirse ()
inicio_Fin
```
## Nombres  
* Andrea
* Karla
* Cristian
