## Taller8

### Elaboración de ejercicios sobre Jerarquía de Herencia a través de Diagramas UML y Lenguaje de alto nivel

#### Problemática

Una universidad ha proporcionado la siguiente información sobre los docentes y los requerimientos para un posible sistema de registro:
* Docente:
  * Cada docente en la universidad tiene un conjunto de datos básicos que son esenciales para cualquier tipo de registro.
  * Se desea mantener un registro que permita identificar de manera única a cada docente, así como conocer su identidad completa básica.

* Docentes que tienen nombramiento:

  * Los docentes con nombramiento fijo tienen un salario base mensual que debe registrarse.
  * Además, estos docentes pueden trabajar horas extra, las cuales deben ser pagadas según un valor fijo por hora extra trabajada.
  * Es necesario calcular el total del sueldo mensual considerando el salario base y el pago por las horas extra.

* Docentes que trabajan por factura:

  * Los docentes que trabajan por factura emiten una factura por sus servicios.
  * De esta factura, se debe descontar un valor correspondiente al IVA (Impuesto al Valor Agregado).
  * El sistema debe ser capaz de registrar el valor total de la factura, el valor descontado por IVA y el valor final que debe ser cancelado al docente.



#### Pasos

1. Crear un diagrama UML que involucre las clases en la carpeta **Diagrama**.

2. Usar el proyecto de Netbeans llamado **Talle08**

  2.1. Generar la clase Docente

  2.2. Generar la clase DocenteNombramiento

  2.3. Generar la clase DocenteFactura

  2.4. Generar la clase Ejecutor. En el método **main**, se debe permitir ingresar objetos de tipo DocenteNombramiento y DocenteFactura. Uno a la vez. Si el usuario ingresa 1, se debe crear un DocenteNombramiento por teclado; si ingresa 2, se debe crear un DocenteFactura. Los datos de entrada serán ingresados por teclado. Si el usuario ingresa algo diferente de 1 o 2; el programa debe presentar un mensaje que diga: "Error, opción no válida.". Se debe presentar la información de cada objeto creado a través de to String.

  2.5. Generar la clase EjecutorDos. En el método **main**, se debe permitir ingresar muchos objetos de tipo DocenteNombramiento y DocenteFactura. Uno a la vez. Si el usuario ingresa 1, se debe crear un DocenteNombramiento por teclado; si ingresa 2, se debe crear un DocenteFactura. Los datos de entrada serán ingresados por teclado. Si el usuario ingresa algo diferente de 1 o 2; el programa debe presentar un mensaje que diga: "Error, opción no válida." Al finalizar el ciclo, cuando el usuario lo decida, se debe presentar la lista de docentes con nombramiento ingresados, y la lista de docentes con factura. Atención **NO se debe usar arreglos de ningún tipo**

Restricciones:

* En el código solo debe usar por una sola ocasión las siguientes sentencias:

  ```
  nombres = entrada.nextLine()
  cedula = entrada.nextLine()
  ```
