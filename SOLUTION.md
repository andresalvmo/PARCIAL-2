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

*PARTE DISEÑO

![parte2](https://user-images.githubusercontent.com/80064766/115095092-8cb05d80-9ee5-11eb-8890-aeebbf5a3aba.JPG)


![PARTE55](https://user-images.githubusercontent.com/80064766/115095122-ace01c80-9ee5-11eb-9014-5e944bc9fa4f.JPG)

*PARTE EXTENDIENDO

De los diseños de "extendiendo" se debe cambiar la dependencia que Isynthetyzer debido a que tambien depende de la clase Student para saber el nombre, duracion

Se puede impedir poniendo la palabra "final" en la clase base
