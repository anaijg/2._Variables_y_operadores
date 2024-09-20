<h1>Clase Random</h1>
Clase que permite generar valores pseudoaleatorios algo más cómodos que los generados con Math.random() (números enteros, números enteros entre un rango dado, valores booleanos, . . . )

````java
\\ Generr un número aleatorio entre 0 y 9
Random generator = new Random();
int integerNumber = generator.nextInt(10);

\\ Simular el lanzamiento de una moneda
Random generador = new Random();
boolean lanzamientoMoneda = generador.nextBoolean();

