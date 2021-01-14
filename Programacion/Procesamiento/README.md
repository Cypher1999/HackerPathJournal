# El procesamiento
## Qué es un Programa y cómo se ejecuta?

Todos hemos manejado un programa de computadora, hay una enorme variedad de ellos, para distintos fines, distintas areas de trabajo, distintos propósitos.
Pero muchos no saben como estos son creados, lo que es realmente el software y como le da vida a nuestra computadora, puede que si eres entusiasta a la
programación ya sepas unas cuantas cosas, quizá mas que el resto, pero siempre hay agujeros, siempre los habrá, inlcuso ahora cuando escribo soy solo 
otra persona con mas interrogantes que respuestas.

En aspectos generales un programa de computador son solo una serie de instrucciones binarias que el procesador puede intender y ejecutar en el orden en que le
son dadas, este conjunto de ordenes se conoce como algoritmo, el cual podemos definir como una serie de pasos o instrucciones que deben seguir para 
obtener un resultado, tal como los pasos para armar un mueble o una receta de cocina.

Los programadores son los encargados de elaborar y escribir dichos algoritmos, son quienes construyen los programas que el procesador debe ejecutar. Entonces sabemos
que el software es elaborado por los programadores y ejecutados por el procesador... Pero cómo sucede esto?

## Indice 
<a name=Indice></a>
* [El procesador](#El_Procesador)
* [Memorias](#Memorias) 
* [Algoritmos]() 
* [Lenguajes de Programación]()
* [Compilar e interpretar]()

## El Procesador
<a name=El_Procesador></a>

El procesador o CPU ( **C**entral **P**rocessing **U**nit) es la pieza central de un computador, es el cerebro que controla 
el hardware y software ( junto a otros controladores de apoyo ), es quien recibe los datos y los procesa de forma matemática y lógica.

![imagen no disponible](img/CPU2.jpg)

El procesador obtiene los datos (tareas, ordenes, instrucciones) en forma de código binario ( 1s y 0s ), y son transmitidos y leídos de manera
digital como pulsos electricos donde, por ejemplo:

Un pulso eléctrico representa un:
0, si -> voltaje bajo: 0.0V - 0.8V
1, si -> voltaje alto: 2V - 5V 

El procesador, a nivel de lógica booleana, está compuesto por circuitos de [compuertas lógicas](http://service.udes.edu.co/modulos/documentos/pedropatino/compuertas.pdf), las cuales según qué par de datos binarios se reciban, se obtiene una respueta. Este mismo concepto es el que se utiliza para los circuitos electrónicos del computador y el procesador, de forma que las compuertas son representadas por millores de transistores microscópicos y los numeros binarios por pulsos eléctricos.

![Imagen no disponible](img/CLogicas.png)  

El procesador está compuesto, de esta forma, por complejos circuitos de millones de transistores que, al obtener los datos de entrada, devuelven una salida binaria.

El código binario no es comprensible por el hombre, la forma en que este código es traducido a un lenguaje etendible es mediante la regla del código ASCII, donde cada símbolo, caracter o número tiene una representación binaria de 1 Byte (8 bits). 

![Imagen no disponible](img/ascii.JPG) 

### Distribución de la Unidad Central de Proceso 

El trabajo de la CPU está dividido en varias partes, como los departamentos de un edificio empresarial (equipo de marketing, equipo de contaduría), lo que le permite trabajar
con eficiencia distintas tareas y procesos que conllevan el buen funcionamiento de un computador. 

Pero en una vista general tenemos dos módulos esenciales, la Unidad de Control y la Unidad Aritmético-Lógica:

* Unidad de Control: 
Como lo indica su nombre, esta es la parte del procesador que se encarga de manejar y administrar todos los procesos en ejecución y operaciones del sistema, número de proceso, proceso siguiente, dirección en memoria de cada instrucción, control de tiempos de ejecución, cancelar un proceso, etc.

* Unidad Aritmético-Lógica:
En esta unidad se procesan todas las operaciones matemáticas, como sumas, restas, etc,  y lógicas, como comparaciones, requeridas en función al proceso que se esté ejecutando en el momento.

![Imagen no disponible](img/DiagramCPU.jpg) 

De esta forma tenemos una visión minimalista de qué es un procesador y como opera:

> 1 - Recibe instrucciones y datos que deben ser procesados.
> 2 - Analiza los procesos que deben ejecutarse para cumplir la tarea.
> 3 - Dichos procesos se ejecutan en orden y se realizan las operaciones necesarias.
> 4 - Una vez procesadas las entradas se obtiene una respuesta o salida. 
> 5 - Finaliza el proceso.

Sin Embargo, aun con la destreza del procesador por ejecutar ordenes y devolver resultados, dichas ordenes y resultados deben almacenarse en un sitio para que puedan ser accesibles, se necesita de una memoria.


## Memorias
<a name=Memorias ></a>
