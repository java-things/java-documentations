# Metodos


## Métodos de instancia.

Un método de instancia es el que se invoca siempre sobre una instancia (objeto) de una clase. Por ejemplo p1.getNombre(); siendo p1 un objeto de tipo Persona es un método de instancia: para invocarlo necesitamos una instancia de persona.

## Métodos de clase.

 Un método de clase es aquel que puede ser invocado sin existir una instancia.

 Un método de clase se define agregando la palabra clave static antes del tipo en la signatura del método. 
 
 	public static String getNombre () { … }
 	
 Los métodos de clase pueden ser invocados con la notación de punto de estas dos maneras:
 
 	NombreDeLaClase.nombreDelMétodo (parámetros si los hay);
	NombreDelObjeto.nombreDelMétodo (parámetros si los hay);
 
 


[template]: https://github.com/rstacruz/flatdoc/raw/gh-pages/templates/template.html
