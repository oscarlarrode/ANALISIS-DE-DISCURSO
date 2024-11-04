# ANALISIS-DE-DISCURSO
universo.nombre=”concesionario”
universo.discurso.comienzo

El universo es un concesionario de automóviles.

de los clientes se conoces los datos habituales,tambien los coches ,de los vendedores y de las ventas.

un coche puede ser recomprado a un cliente.

universo.discursivo.fin

-cliente
-automovil
-vendedor
-venta
-concesionario
- ~~dato~~
# ------------------------------------------------------------
v2
universo.discurso.comienzo

 concesionario de automóviles.
-cliente:se conoces los datos habituales
-coche:se conoces los datos habituales
-vendedor:se conoces los datos habituales
-venta:se conoces los datos habituales

un coche puede ser recomprado a un cliente.

universo.discursivo.fin
# ------------------------------------------------------------
v3
universo.discurso.comienzo

-concesionario de automoviles(de automoviles)
-clientes(,,)
-coche(,,)
-vendedor(,,)
-venta(,,)
-recompra(de coche)(por cliente)

universo.discursivo.fin
# ------------------------------------------------------------
v4 (con diseño)

-concesionario de automoviles(de automoviles)(cochecitospuntos.com)
-clientes(dni,nombre,apellido,tf,direccion)
-coche(numBastidor,matricula,año,marca,modelo,color)
-vendedor(numVendedor,dni,nombre,ape,tf)
-venta(,,)
-recompra(de coche)(por cliente)


