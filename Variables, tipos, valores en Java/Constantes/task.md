<h1>Las constantes</h1>
Las constantes son estructuras que se definen con un valor fijo que no se puede modificar. Se utilizan para evitar tener que escribir números literales a lo largo del código, cuyos valores pueden cambiar en un futuro. De esa manera, colocaremos el nombre de la constante que defina dicho valor y en el momento en que ésta cambie, sólo tendremos que cambiar el valor en el lugar donde fue definida.

Hay que tener en cuenta que Java recomienda utilizar una notación diferente para los identificadores de las constantes. Se recomienda utilizar sólo mayúsculas y si el nombre contiene más de una palabra, se deben de separar con el caracter subrayado _
````java
// Constantes para uso local
final float IVA = 0.21;
final int NUMERO_PAGINAS = 10;

// Constantes para uso global
public static final float IVA = 0.21;
public static final int NUMERO_PAGINAS = 10;
````


