* PARTE CONCEPTUAL

1. ¿Cuales son las acciones los tres momentos importantes de las excepciones? 

Son lanzamiento, propagación y captura

¿Cual es el objetivo de cada una?

- Lanzamiento: comunicar al usuario que existe una excepción
- Propagación: se quiere controlar
- Captura: se controla la excepción

¿Como se implementa en java cada acción?

- Lanzamiento: Se lanza con: throw new exception
- Propagación public void cualquiercosa() throws exception
- Captura: 

try{

//cualquiercosa

}catch(Exceptionerror){

}

2. ¿ Que es sobre-escritura de metodos? 

Es cuando un metodo tiene el mismo nombre y tipo de otro en diferente clase

¿Por que aplicarla? 

Nos permite redefinir un metodo que se heredo para que funcione de acuerdo a nuestras necesidades y no al metodo de la superclase ya definido

¿Como impedir que se sobre-escriba un metodo?

Se puede impedir poniendo la palabra "final" en la clase base
