<h1>Algo de código para empezar</h1>

````java
/* Primer programa escrito en Java
  */
  public class HelloWorld {
     public static void main(String args[]) {
          System.out.println("Hello students!");
     }
  }
  ````
- Los comentarios se escriben entre los caracteres /* y */ y pueden ocupar varias líneas
- Si un comentario sólo ocupa una línea se puede escribir justo después de los caracteres //
- La instrucción System.out.println(“Hello Students”) escribe el texto indicado por pantalla
- Cada sentencia de código se termina siempre con un ;
- La definiciones de las clases y métodos no se consideran sentencias y no terminan con el caracter ; ya que definen nuevos bloques de código
- Cada bloque de código se inicia con el caracter { y termina con }

<h1>Palabras reservadas</h1>
<img src="img.png"/>
<a href="https://docs.oracle.com/javase/tutorial/java/nutsandbolts/_keywords.html">Fuente: Oracle Java Docuentation</a>

<h1>Proceso de desarrollo de una aplicación Java</h1>

<h2>Algunas consideraciones</h2>

- Normalmente una aplicación se corresponde con un Proyecto (en IntelliJ IDEA en nuestro caso)
- Estructura basada en paquetes (carpetas) y debemos especificar uno como mínimo
- La unidad mínima de un proyecto es la clase (normalmente pública) y normalmente cada una se escribe en un fichero de código
- La unidad mínima de ejecución es el método que normalmente estará compuesto de un conjunto de instrucciones relacionadas
- **Como mínimo tendrá que haber una clase pública con el método public static void main(String args[])**, que será el punto de arranque cuando se ejecute el proyecto
- El compilador nunca procesa los comentarios
- Nunca debemos editar/modificar los ficheros del proyecto que no sean código Java


<h1>Estructura de un proyecto Java</h1>
<img src="img_1.png"/>

<h2>Proceso de creación de una aplicación</h2>
- Al compilar, cada clase de código genera un fichero .class y sólo una de ellas será la que inicie la aplicación
- No es raro que un proyecto pueda contener más de 100 clases, a lo que habría que sumar otros recursos (texto, imágenes, . . .)

<h1>Los comentarios</h1>
Los comentarios permiten añadir texto al programa que no será procesado por el compilador, por lo que no forma parte del programa. Se utiliza para que el programador pueda añadir notas al código que le permitan dejar explicaciones de algoritmos complicados o de partes del código que deban ser interpretadas en el futuro por él mismo u otro programador.

También se pueden utilizar para lo que se conoce como comentar el código. En ocasiones, no estamos seguros de cómo funcionará una alternativa a un código que ya tenemos escrito. Podemos meter entre comentarios el fragmento que ya tenemos y probar la alternativa sin necesidad de eliminarlo. Hay que tener en cuenta que, posteriormente, podemos descubrir que el código tal y como lo teníamos era correcto o que el fallo era algo menor y sólo hacía falta hacer algún pequeño cambio, no reemplazar todo ese fragmento de código.

Podemos eliminar las marcas de comentario y volver a dejar el código inicial sin mucha complicación.

Los comentarios que ocupan una línea se preceden de los caracteres // y son válidos a partir de dichos caracteres, pudiéndose escribir a la derecha de una línea de código que sí deba ser procesada.

Si queremos escribir varias líneas como comentario, podemos iniciar el bloque con los caracteres /* y terminarlos con */ sin necesidad de añadir ningún caracter adicional para cada una de las líneas.
````java
int x = 10;
// Esto es un comentario y no se ejecuta
x = x + 10;

/* Este comentario
será de varias
líneas
*/
x = 100;

/* Esto es un comentario
* de varias lineas
* que tampoco se ejecuta
* y se ve mejor que el anterior
  */
  System.out.println(x);  // Esto también sirve como comentario
````  
 