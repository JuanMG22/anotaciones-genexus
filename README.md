# Anotaciones GeneXus

## ¿Por qué colocó además de CountryId, el atributo CountryName en AmusementPark?

Respuesta: El atributo CountryName es importante que aparezca en la pantalla de la transacción,
para mostrarnos el nombre del país, que es el dato que recordamos mejor del país, en lugar de ver
solamente su identificador. También es necesario agregar al atributo en la estructura de la
transacción si luego lo queremos utilizar, por ejemplo, dentro de una regla.

## ¿Qué son la Tabla Base y la Tabla Extendida?

-Tabla Base: Cualquier tabla fisica de la DB en la cual estemos posicionados trabajando en determinado 
momento

-Tabla Extendida: dada cierta tabla base cualquiera, su tabla extendida es el conjunto de todos los 
atributos de la propia tabla base más todos los atributos de las tablas con la que se tenga una relacion
n a 1, directa o indirecta

## ¿Cuál es el orden de ejecución de las rules?

-Primero se ejecutan las reglas que no contienen condiciones (NoAccept, Default, etc) y luego las reglas que contengan condicionales

## Bussiness Component sirve para todo tipo de actualizacion que no sea interactiva, es la transaccion puesta en un tipo de dato

### Cosas que se tienen en cuenta al actualizar la DB:
Integridad referencial                  Bussiness Component controla
Unicidad de clave primaria              Bussiness Component y Procedure controla
Unicidad de clave candidata             Bussiness Component y Procedure controla
Reglas                                  Bussiness Component controla

## SDTCliente From Cliente // From hace que recorra toda la tabla en los SDT, basicmaente como un ForEach

## ForEach Product order (ProductExpirationDate) // Al colocar () se invierte el orden. En este caso se ordenaria de mayor a menor
Endfor 