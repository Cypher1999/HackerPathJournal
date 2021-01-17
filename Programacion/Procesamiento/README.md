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

## Índice 
<a name=Indice></a>
* [El procesador](#El_Procesador)
* [Memorias](#Memorias) 
* [Algoritmos]() 
* [Lenguajes de Programación]()
* [Compilar e interpretar]()

<a name=El_Procesador></a>
## El Procesador

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

* 1 - Recibe instrucciones y datos que deben ser procesados.
* 2 - Analiza los procesos que deben ejecutarse para cumplir la tarea.
* 3 - Dichos procesos se ejecutan en orden y se realizan las operaciones necesarias.
* 4 - Una vez procesadas las entradas se obtiene una respuesta o salida. 
* 5 - Finaliza el proceso.

Sin Embargo, aun con la destreza del procesador por ejecutar ordenes y devolver resultados, dichas ordenes y resultados deben almacenarse en un sitio para que puedan ser accesibles, se necesita de una memoria.

[Índice](#Indice)

<a name=Memorias ></a>
## Memorias

Qué pasaría si por más que estudiaras no pudieses retener ningún tipo de información? no importa cuanto te esfuerces, a medida que lees todo lo que acabas de leer se desvanece y por más que 
empieces desde el inicio simplemente no lo recuerdas. Qué pasaría si no tuvieses memoria?

Así como nuestra mente es capaz de grandes cosas, de encontrar soluciones creativas, innovadoras y eficientes a problemas, la misma tiene la capacidad de retener grandes cantidades de
información, de igual forma el procesador tiene la capacidad computacional de resolver grandes problemas y realizar simples y complejos procesos, necesita una memoria donde poder leer y 
almacenar información.

Tener una memoria nos da la facilidad de: 

* Almacenar información
* Analizar información
* Recopilar datos
* Crear y guardar nuevos conocimientos

De esta misma forma, el procesador necesita una memoria donde poder almacenar y buscar los programas, analizar los procesos antes de ser ejecutados, guardar los resultados para poder 
consultarlos, modificarlos o reutilizarlos, crear nueva información.

Hay dos tipos de memorias en un computador, la memoria principal y memoria secundaria, las cueales sirven a distintos propósitos:

* Memoria Principal: 

Es aquella memoria volatil donde se cargan los programas y los procesos que se encuentran en ejecución y se caracterizan por ser de rápido acceso pero no 
almacenar la información permanentemente ( es eliminada al apagar la computadora ), y la más conocida de este grupo es la memoria [RAM](https://es.wikipedia.org/wiki/Memoria_de_acceso_aleatorio). En esta categoría se les puede simar los [registros del CPU]() y la [memoria cache]().

Esta es tu memoria de corto plazo, en ella está la información que necesitas para lo que sea que estes haciendo en ese preciso momento, pero mucha información de la que está ahí será olvidado
cuando te duermas, o incluso siquiera unas horas despues de haberla utilizado. 

* Memoria Secundaria: 

Es la memoria en la que puedes almacenar, leer y eliminar información, la información que se encuentra ahí es permanente, pero de acceso lento. Esta es la memoria que almacena toda la información y programas de la computadora y que los envía a la memoria principal cuando se requiere dicha información, este viene siendo principalmente tu [disco duro](https://es.wikipedia.org/wiki/Unidad_de_disco_duro) (HDD o SDD).

La memoria secundaria sería para ti tu memoria a largo plazo, esa parte de tu cerebro donde se almacena aquella información que nunca pierdes, que por más que cueste siempre puedes recordar 
lo que allí se encuentra, está guardada, no piensas en ella, solo rebuscas ahí cuando necesitas algo y utilizarlo.

![](img/PrinYSec.jpg)

**Por ejemplo:**
<br>Imagina que vas cocinar una de tus recetas favoritas, en todo el día no has pensado en ello, has estado ocupado en otras labores o viendo memes, pero no has pensado en la receta ni como
vas a cocinarla, no es hasta que llega el momento en que vas a la cocina que recuerdas todos los ingredientes que necesitas y los pasos necesarios para cocinar dicha receta.

De esta manera trabaja el procesador junto a las memorias, en el disco duro (memoria secundaria) se almacena toda la información y programas, pero no es hasta que se desea ejecutar una acción
cuando esta información es ubicada y leída por el procesador para posteriormente cargarla a la memoria principal para ejecutar dicha acción, de la misma forma en que tu cerebro busca la 
información y puedes recordarla conscientemente cuando es necesaria, (aunque claro la computadora no requiere horas de estudio y práctica para grabar información).  

En pocas palabras un ejemplo de una caracteristica crucial en una computadora, en el disco duro(secundaria) se instala y se almacena el sistema operativo, y al encender tu computadora el sistema escargado a la memoria ram(primaria).

Otras memorias mencionables son los [registros del CPU](https://www.profesionalreview.com/2019/11/18/registros-del-procesador/), la [memoria cache](https://hardzone.es/tutoriales/rendimiento/memoria-cache-procesador-como-funciona/) y la [ROM](https://es.wikipedia.org/wiki/Memoria_de_solo_lectura).

### Memoria Virtual: 

Aquí entra otro concepto muy importante, si los programas deben cargarse en memoria principal para ser ejecutados, cómo es que un programa que ocupa 30GB de espacio puede ser cargo en 4GB de 
RAM?. La memoria virtual es un sistema que ayuda a organizar y optimizar el uso de la memoria principal, es una simulación de memoria principal, en esta se cargan los programas que se desean
ejecutar, pero cómo sucede esto?.

Para obtener un espacio virtual (simulado) suficiente para cargar el programa se utiliza un espacio físico del disco duro, una vez cargado el programa en este espacio virtual el procesador se 
encarga de cargar a la memoria RAM solo aquella parte del programa que es necesaria, y el resto queda en la memoria virtual en caso de necesitarse o hasta que el proceso termine. Por ejemplo, si tu tienes un problema matemático y un libro de matemáticas no acudes a leer el libro completo para resolverlo, vas directo a la sección que te es útil para resolver el problema.
  
Normalmente para lograr esto con éxito, se realiza un proceso de traducción entre las direcciones de memoria virtual a direcciones reales de memoria física con el método de [paginación](https://es.wikipedia.org/wiki/Paginaci%C3%B3n_de_memoria), el cual consiste en la división del programa en pequeñas piezas (páginas) junto a una dirección falsa (marco de página), permitiendo que dichas páginas puedan cargarse en direcciones de memoria real (Memoria RAM) según se necesite.  

![](img/PaginacionMV.jpg)

[Índice](#Indice)

