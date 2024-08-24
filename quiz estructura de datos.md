
1. diferencia entre un IDE y un editor de texto.
RTA1
Editores de Texto: Son más ligeros, rápidos y generales. Son adecuados para tareas básicas de edición y codificación.
Los editores de texto están diseñados para manejar texto en general, no solo código. Pueden usarse para escribir notas, documentos y otros tipos de texto además de código fuente.

IDEs: Ofrecen un entorno de desarrollo completo con herramientas integradas para facilitar el proceso de programación, depuración, y gestión de proyectos.
Un IDE esta diseñado específicamente para el desarrollo de software. Ofrece un entorno completo que facilita el proceso de desarrollo, incluyendo edición de código, depuración, y pruebas.
. diferencia entre un IDE y un editor de texto.
 
 2. Tipos de lenguajes de programacion ( tipados y no tipados)

RTA2

El termino "no tipado" o "sin tipo" se refiere a lenguajes que no tienen una estructura de tipos explicita, o donde el concepto de tipo es muy flexible o implicito.

Tipados : los lenguajes tipados requieren que se declare el tipo de dato de cada variable antes de su uso. ejemplos : Java ,c++.

No Tipados : los lenguajes no tipados no requieren la declaracion exlicita del tipo de dato de las variables. Ejemplo : Python, JavaScript ,ruby ,PHP.

Lenguajes Tipados: Definen explicitamente los tipos de datos y realizan comprobaciones de tipos en tiempo de compilacion (tipado estatico) o en tiempo de ejecucion (tipado dinamico).
Lenguajes No Tipados: Tienen sistemas de tipos menos estrictos o implicitos, lo que permite mas flexibilidad pero tambien puede introducir errores y problemas de rendimiento.

3. Tipos de datos en Java 
Numericos - Cadenas- Fechas.

RTA3
En Java, los tipos de datos se pueden clasificar en varias categorías, incluyendo datos numéricos, cadenas de texto y fechas. Aquí te detallo cada categoría:
*Tipos de Datos Numéricos
Java proporciona dos categorías principales de tipos numéricos: enteros y de punto flotante.
Enteros
Estos tipos almacenan valores enteros (sin decimales).

byte:

Tamaño: 8 bits (1 byte)
Rango: -128 a 127
short:

Tamaño: 16 bits (2 bytes)
Rango: -32,768 a 32,767
int:

Tamaño: 32 bits (4 bytes)
Rango: -2,147,483,648 a 2,147,483,647
long:

Tamaño: 64 bits (8 bytes)
Rango: -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807
Punto Flotante
Estos tipos almacenan valores numéricos con decimales.

float:

Tamaño: 32 bits (4 bytes)
Rango: Aproximadamente ±3.40282347E+38F (precisión de 7 dígitos decimales)
double:

Tamaño: 64 bits (8 bytes)
Rango: Aproximadamente ±1.79769313486231570E+308 (precisión de 15 dígitos decimales)

*Cadenas de Texto
En Java, las cadenas de texto se manejan mediante la clase String.

String:

Definición: Clase para representar cadenas de texto. Los objetos String son inmutables, lo que significa que una vez creado un String, no se puede modificar.
Uso: Se utiliza para manejar y manipular texto. La clase String ofrece métodos para concatenar, comparar, buscar, y modificar cadenas de texto.

*Fechas y Horas
Java proporciona varias clases para manejar fechas y horas, principalmente en el paquete java.time (disponible a partir de Java 8) y en el antiguo paquete java.util.

Paquete java.time (Java 8 y versiones posteriores)
LocalDate:

Definición: Representa una fecha sin hora (año, mes, día).
Uso: Se usa para representar una fecha, como una fecha de nacimiento o una fecha de evento.
