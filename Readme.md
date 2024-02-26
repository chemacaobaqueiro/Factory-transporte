# ESTABLECEMOS LAS CLASES QUE REPRESENTARÁN LOS MEDIOS DE TRANSPORTE

1. Inicialmente, interpretamos el enunciado que nos solicita que los objetos sean de tipo camión y bicicleta.
2. Procedemos a establecer las clases camión y bicicleta.
3. Generamos la interfaz IComunTransporte donde especificamos los métodos que las clases camión y bicicleta deben implementar.

***Interfaz IComunTransporte Aquí establecemos los métodos que serán compartidos por las clases que las implementen.***

1. El primer método calculará el costo en función del código postal.
2. El segundo determinará el tipo de embalaje en función del peso.
3. 
***Clase Camión***

1. Establecemos los atributos estáticos que serán el tipo de embalaje.
2. Recordamos que las clases deben implementar la interfaz IComunTransporte y luego implementar los métodos de la interfaz.
3. Implementamos los métodos y los ajustamos según nuestras necesidades.

***Clase Bicicleta***

1. Establecemos los atributos estáticos que serán el tipo de embalaje.
2. Recordamos que las clases deben implementar la interfaz IComunTransporte y luego implementar los métodos de la interfaz.
3. Implementamos los métodos y los ajustamos según nuestras necesidades.

***Clase FactoryTransport***

1. Establecemos los atributos estáticos finales que, según lo seleccionado en el método que describiremos a continuación, será un objeto de tipo camión o uno de tipo bicicleta.
2. Generamos el método getProducto que tiene un parámetro en el que definiremos si queremos que nos cree un objeto de tipo camión o de tipo bicicleta.
3. Si no seleccionamos nada, nos devolverá un nulo.

***Clase Main***

1. Aquí se ejecuta nuestro programa.

1. Primero creamos una variable que será de tipo interfaz, que será la interfaz IComunTransporte.
2. Esa variable será igual a la fábrica y sus métodos.
3. Introducimos el tipo que queremos por parámetro para que fabrique un camión o una bicicleta.
4. Llamamos a los métodos y los mostramos en pantalla para verificar que funciona.

***Generamos un Javadoc***

1. Realizamos un Javadoc en el que explicamos paso a paso todo el procedimiento.

***Objetivo del factory***

1. El objetivo es, ni más ni menos, una fábrica de objetos.