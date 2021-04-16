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
