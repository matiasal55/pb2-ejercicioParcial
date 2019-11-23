# pb2-ejercicioParcial
[PB2] Ejercicio Parcial 2

Una disquería vende cds y vinilos. Toda la mercadería se encuentra en una lista y tiene atributos en común. Sólo que para los vinilos se agregan además la cantidad de discos y el color del mismo, y en el caso de los cds se ingresa la cantidad de cds en un mismo título.
A su vez tiene una lista de ventas la cual tiene el disco vendido, la cantidad y el precio total en base a la cantidad. Se requiere:

- Hacer los vínculos de herencia y composición correspondientes.
- Implemente una interfaz o una clase abstracta si corresponde.
- Hacer una lista de discos ordenados por artista y año de publicación y una lista de ventas ordenada por su id de venta.
- Hacer un método que agregue discos, sin verificar si los agregó o no.
- Hacer un método que elimine un disco por su código.
- Hacer un método que agregue una venta.
- Hacer un método que elimine una venta por su id de venta.
- Hacer un método que elabore una lista nueva donde se encuentren los cds ordenados por título.
- Hacer un método que devuelva la cantidad de vinilos vendidos de color negro.
- Hacer un método que devuelva la venta total de cds simples (una unidad). NO se refiere a la cantidad de venta, sino a la cantidad de cds.
- Hacer un método que modifique el precio de un cd ingresando su código.
- Hacer las excepciones donde crea que corresponda.
- Utilice List y Set cuando corresponda.

Test:
- testQueVerifiqueQueSeAgregaronDosDiscos
- testQueEliminaUnDiscoCorrectamente
- testQueAgregaUnaVenta
- testQueEliminaUnaVenta
- testQueEliminaUnaVentaInexistente
- testQueEliminaUnDiscoInexistente
- testQueModificaMalUnPrecio
- testQueModificaPrecio
