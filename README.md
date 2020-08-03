# Producto-Unidad-2
#Planteamieno del Problema
Realiza en un circuito una calculadora básica que me permita sumar y restar dos números de 8 bits, este trabajo debe ser implementando en la plataforma de tinkercad demás de eso implementar el integrado 7483 que es un sumador de 4 bits, en la salida que se presente de esta y para que podamos decidir si queremos que nos de la operación de suma o la operación de resta se realizara a través de un multiplexor , esta salida se debe presentar a través de uno o varios display de 7 segmentos para el cual usaremos el integrado de 4511 y por ultimo las entradas se presentaran por medio de un dip switch.
#Objetivos
##Objetivo general:
-	Realizar un circuito sumador-restador de 8 bits en el que se implemente en la salida un multiplexor de integrado 4511 y por esta definir si el resultado es de operación de suma o de resta
##Objetivos específicos
-	A través de la página de tinkercad implementar el circuito para una mejor  visualización de los integrados y una simulación más realista a lo que haríamos dentro de un laboratorio
-	Usar uso del multiplexor al final del circuito para definir cuál es la salida y de ser el caso de la resta mostrar a través si es un número negativo mostrar el cambio
-	Mostrar el resultado a través del display de 7 segmentos BCD  en 3 display y este resultado debe ser hasta 510
Conflux: un multiplexor asíncrono de dos a uno para multiplexación por división de tiempo y lectura sin reloj y sin token
En este artículo se describe un multiplexor de dos a uno asíncrono independiente y auto arbitraje llamado Conflux. Conflux se puede utilizar para implementar multiplexación por división de tiempo sin reloj y sin token entre dos fuentes. Esta capacidad se puede usar para crear un bus de datos agregados sin reloj y sin token que se puede usar como una arquitectura de lectura asincrónica completa para un chip, una parte de un chip o un sistema multichip completo. Conflux utiliza un clásico apretón de manos asíncrono de cuatro fases en sus dos puertos de entrada, así como en su puerto de salida. La solicitud asincrónica se incluye con datos para garantizar un retraso de propagación constante. La solicitud también se implementa como una señal diferencial para tener en cuenta las diferencias de retardo de propagación entre los lógicos y los ceros. El arbitraje entre las dos corrientes de entrada de Conflux se logra mediante tres pestillos de restablecimiento y ajuste. Finalmente, las células Conflux se usaron con éxito para implementar la arquitectura de lectura del chip prototipo FCP130. Las pruebas indican retrasos únicos en la etapa de Conflux de 1.8 ns y un ancho de banda de aproximadamente 11 Gb / s en CMOS de 130 nm. 
En este artículo podemos ver otra aplicación o uso de un multiplexor y como este nos facilita algunos trabajos y nos ayuda hacer el uso de menos herramientas como en este que no hace uso de un reloj ni token 
Análisis de fluctuación por flujo en multiplexores ATM CBR
En este artículo se nos informa primero sobre cómo es la espera que el tráfico de velocidad de bits constante (CBR) sea una fuente importante de tráfico en redes de alta velocidad. Dichas fuentes pueden tener requisitos estrictos de demora y pérdida y, en muchos casos, deben entregarse exactamente como se generaron. Un esquema de prioridad de retardo simple limitará el retardo de la celda y la fluctuación de fase para las secuencias CBR, de modo que en los conmutadores de red el tráfico CBR solo competirá con otro tráfico CBR en las redes. En este documento consideramos un multiplexor en dicho entorno. Proporcionamos un análisis exacto del proceso de fluctuación de fase en el caso homogéneo. En este caso obtenemos la caracterización completa del proceso de fluctuación que muestra las imprecisiones de los resultados existentes. Estos  resultados indican que la variación de la fluctuación de fase está limitada y nunca excede la ranura constante de 2/3. También se muestra que los tiempos sucesivos de interdeparación de células por flujo se correlacionan negativamente con la correlación de retraso 1 de -1/2. Los coeficientes de correlación de orden superior se muestran como cero. También se proporcionan resultados asintóticos simples sobre el comportamiento por flujo cuando el número de flujos CBR se considera grande. En el caso heterogéneo, limitamos la distribución y los momentos de fluctuación. Se proporcionan resultados simples para el cálculo del límite en la variación de la fluctuación de fase para cualquier combinación de flujos CBR en este caso. 
Multiplexor de longitud de onda de rejilla Chirped Echelle perfecto: diseño y optimización
Se presenta un nuevo método para diseñar una rejilla de difracción para multiplexación por división de longitud de onda (WDM), que se sintoniza en un único punto estigmático. La nueva rejilla se define por el modo y la longitud de onda de la operación en una guía de onda de losa, la posición de las guías de onda, el orden de difracción y una ruta arbitraria, que se llama la línea de rejilla, sobre la cual se posicionan, se proyectan las facetas individuales. curvado a través del algoritmo esbozado. Se presenta un proceso de diseño sistemático para las rejillas de echelle (EG), que cubre todos los aspectos clave de este dispositivo. Se describe una serie de reglas para mejorar el rendimiento de cualquier dispositivo EG WDM. Se realizó una comparación simulada entre este dispositivo, una rejilla estándar de Rowland y una rejilla de dos puntos estigmáticos, con el nuevo diseño funcionando mejor y comparable en cada caso, respectivamente.

Marco Teorico
Multiplexor
El multiplexor, también conocido de manera acortada como MUX, es un circuito lógico combinacional diseñado para conmutar una o varias líneas de entrada en una sola línea de salida común mediante la aplicación de una lógica de control.
Los multiplexores funcionan como conmutadores de acción muy rápida que gestionan varias líneas de entrada llamadas canales y conectan una de estas entradas a la línea de salida en función de la señal de control.
Los MUXs pueden ser:
Circuitos digitales hechos con puertas lógicas de alta velocidad para cambiar datos digitales o binarios.
Circuitos analógicos usando transistores, MOSFETs o relés para conmutar una de las entradas de voltaje o corriente en una sola salida.

Su Funcionamiento

El principio de funcionamiento de un multiplexor se puede entender de manera muy sencilla a través de un ejemplo.
Vamos a emplear una serie de tuberías controladas por una llave de paso como en la siguiente imagen:
 
Como podemos ver en el primer ejemplo tenemos:
•	Dos tuberías de entrada con dos tipos de agua según su uso.
•	Una llave de paso con la que se elegirá el tipo de agua en cada momento.
•	Una tubería de salida que es común a todas las de entrada y por la que circulará el agua que esté «seleccionada» por la llave de paso.
 
Este último ejemplo es igual que el primero, a excepción de que existen cuatro tuberías de entrada en vez de dos.

Multiplexores digitales

En electrónica digital, los multiplexores que hay disponibles en el mercado son tan pequeños que los podemos encontrar en un simple encapsulado. Esto contrasta con los selectores mecánicos que necesitan de varios interruptores y relés convencionales en función de la cantidad de datos a procesar.
La selección de cada línea de entrada es controlada por un conjunto adicional de entradas llamadas líneas de control (en el ejemplo como la llave de paso). En función del valor de las entradas de control,  HIGH  (1) o  LOW (0), una de las entradas de datos es conectada directamente a la salida.
Normalmente, un multiplexor tiene un número par de líneas de entrada. El número de entradas de datos será 2n, siendo n = 1, 2, 3, 4,… El número de entradas de control dependerá de las entradas de datos y será de valor n.
A continuación vamos a analizar los tipos de multiplexores más básicos que hay disponibles para entender mejor su funcionamiento. En estos ejemplos, todas las líneas transportarán un bit de información, es decir, o 1 o 0, aunque en la realidad existen multiplexores que son capaces de transportar varios bits por cada canal.

 Tipos de multiplexor
Multiplexor 2 a 1
Este tipo de multiplexor dispone de dos señales de entrada y una salida. Como consta de sólo dos entradas, existirá una única línea de control de datos, ya que con un bit podrá seleccionar la entrada 0 (si recibe un ‘0’ de la señal de control) o la entrada 1 (si recibe un ‘1’ de la señal de control).
Un ejemplo es el circuito integrado TTL 74157.
Esquema MUX 2 a 1	Tabla de la verdad
  	S	O (Salida)
	0	I0
	1	I1
Multiplexor 4 a 1
En este caso, hay cuatro señales de entrada y una salida. Consta de cuatro entradas, así que habrán dos líneas de control, ya que son necesarios al menos dos bits de datos para poder seleccionar la totalidad de entradas. Recordemos que 4 entradas es 22, por tanto hacen falta 2 canales de control.
Un ejemplo es el circuito integrado TTL 74153.
Esquema MUX 4 a 1	Tabla de la verdad
  	S1	S0	O (Salida)
	0	0	I0
	0	1	I1
	1	0	I2
	1	1	I3
Multiplexor 8 a 1
Este será el último caso que veremos en el post. Tenemos ahora ocho entradas y una salida. Aplicando la fórmula para ver el número de líneas de control nos encontramos con: 8 entradas es 23, por tanto son necesarios 3 canales de control.
Un ejemplo es el circuito integrado TTL 74151.
Esquema MUX 8 a 1	Tabla de la verdad
  	S2	S1	S0	O (Salida)
	0	0	0	I0
	0	0	1	I1
	0	1	0	I2
	0	1	1	I3
	1	0	0	I4
	1	0	1	I5
	1	1	0	I6
	1	1	1	I7
Sumadores
EL sumador es un circuito digital que realiza la adición de números. En muchas computadoras y otros tipos de procesadores se utilizan sumadores en las unidades aritméticas lógicas. También se utilizan en otras partes del procesador, donde se utilizan para calcular direcciones, índices de tablas, operadores de incremento y decremento y operaciones similares.

Aunque los sumadores se pueden construir para muchas representaciones numéricas, tales como decimal codificado en binario o exceso-3, los sumadores más comunes funcionan en números binarios. En los casos en que se utiliza el complemento a dos o el complemento a uno para representar números negativos, es trivial modificar un sumador para convertirlo en un sumador-restador. 
Semisumador
 
Esquema de un semisumador
El semisumador suma dos dígitos binarios simples A y B, denominados sumandos, y sus salidas son Suma (S) y Acarreo (C). La señal de acarreo representa un desbordamiento en el siguiente dígito en una adición de varios dígitos. El diseño más simple de semisumador, representado a la derecha, incorpora una puerta XOR para S y una puerta AND para C. Dos semisumadores pueden ser combinados para hacer un sumador completo, añadiendo una puerta OR para combinar sus salidas de acarreo.1 La tabla de verdad para el semisumador se detalla seguidamente:
 
Funcionamiento de un semisumador
Entradas	Salidas
A	B	C	S
0	0	0	0
1	0	0	1
0	1	0	1
1	1	1	0
Sumador completo
 
Diagrama lógico de un sumador completo
 
Funcionamiento de un sumador completo

Un sumador completo suma números binarios junto con las cantidades de acarreo. Un sumador completo de un bit añade tres bits, a menudo escritos como A, B y Cin; siendo A y B los sumandos y Cin el acarreo que proviene de la anterior etapa menos significativa. 1 El sumador completo suele ser un componente de una cascada de sumadores, que suman 8, 16, 32, etc. números binarios de bits. El circuito produce una salida de dos bits, al igual que el semisumador, denominadas acarreo de salida (Cout) y suma S.
Un sumador completo se puede implementar de muchas maneras diferentes, tales como con un circuito a transistores o compuesto de otras puertas. Un ejemplo de implementación es expresado con las siguientes ecuaciones:
 
En esta implementación, la puerta OR final antes del acarreo de salida puede ser reemplazada por una puerta XOR sin alterar la lógica resultante. El uso de sólo dos tipos de compuertas es conveniente si el circuito se está implementando usando circuitos integrados que contienen sólo un tipo de puerta.
Se puede construir un sumador completo a partir de dos semisumadores conectando las entradas A y B a la entrada de un primer semisumador, conectando su salida de suma a una de las entradas del segundo semisumador, conectando el acarreo de entrada Cin a la otra entrada y conectando los acarreos de salida de los semisumadores a una puerta OR. La ruta crítica de un sumador completo recorre ambas puertas XOR y hasta llegar a la salida S. Suponiendo que una puerta XOR tenga un retardo D, el retardo total por el camino crítico de un sumador completo es igual a:
 
En cambio, la ruta crítica para la señal de acarreo recorre una puerta XOR, una AND y otra OR. Si cada una de estas puertas digitales presenta un retardo D, el retardo total es:
 
La tabla de verdad del sumador completo es la siguiente:
Entradas	Salidas
A	B	Cin	Cout	S
0	0	0	0	0
0	0	1	0	1
0	1	0	0	1
0	1	1	1	0
1	0	0	0	1
1	0	1	1	0
1	1	0	1	0
1	1	1	1	1

Decodificador 4511
El CD4511 es un decodificador bcd para display de 7 segmentos.
El display de 7 segmentos es un componente bastante empleado en el mundo de la electrónica, ya que permite que sea muy simple la exhibición de valores numéricos. Pudiendo representar cifras de 0 a 9 
Los display de 7 segmentos son empleados la mayoría de las veces a partir de circuitos digitales como circuitos integrados, microcontroladores y otros procesos que trabajan en sistema binario, cuyo sistema y representación es apenas realizado por dos niveles lógicos 0 y 1 denominados bits
Funcionamiento CD4511
El CD4511 es un decodificador bcd de 4 bits para display cátodo común, que utiliza tecnología cmos. Recibe en los Pines de entrada a ABCD los datos en código binario y los decodifica a código decimal, siendo posible su exhibición en los display de 7 segmentos.
El Funcionamiento del cd4511 puede ser visualizado a través de su tabla de verdad. Solo se muestra la decodificación BCD:
Tabla de la verdad CD4511
Pines BCD	Salida a Display	Digito
A B C D	a b c d e f g	 
0 0 0 0	1 1 1 1 1 1 0	0
0 0 0 1	0 1 1 0 0 0 0	1
0 0 1 0	1 1 0 1 1 0 1	2
0 0 1 1	1 1 1 1 0 0 1	3
0 1 0 0	0 1 1 1 0 1 1	4
0 1 0 1	1 0 1 1 0 1 1	5
0 1 1 0	0 0 1 1 1 1 1	6
0 1 1 1	1 1 1 0 0 0 0	7
1 0 0 0	1 1 1 1 1 1 1	8
1 0 0 1	1 1 1 0 0 1 1	9

Las características más importantes que podemos considerar se encuentran:
Tensión de operación: 3V a 18V de corriente continua.
Corriente de salida: 10mA.
Temperatura de operación: -55ºC a 125ºC.
Configuración de pines.
Cada pin de salida corresponde a un segmento del display, basta con hacer las conexiones y enviar las informaciones binarias a las entradas, luego CD4511 decodifica el código bcd y escribe la información en cifras decimales en el display.
 
Este Circuito integrado es específico para trabajar con diplay de 7 segmentos de cátodo común, en el caso de querer usar el CD 4511 con ánodo común se debe recurrir a un circuito inversor o usar otro circuito integrador decodificador.
Tenemos a disposición 3 Pines del CD4511 que pueden tener gran aplicación en diversos proyectos, brindando funciones como:
Economizar Batería.
Registrar el último dígito exhibido en el display.
Testear los segmentos del display, para validar su funcionamiento y el cableado.
Estos pines y su funcionamiento son:
Lamp Test LT(Pin 3): Este pin nos sirve para probar todos los segmentos. Debido a que es una entrada inversora, para tener un funcionamiento normalizado esta entrada debe estar en 1. Cuando la entrada toma un valor lógico 0 prende todos los segmentos del display para testear el funcionamiento.
Blank Input BI(Pin 4): Apaga todos los segmentos, tenér en cuenta que esto es una entrada inversora, por lo tanto para tener un funcionamiento normal del CI esta entrada precisa estar en 1.
Lath Enable LE(Pin 5): congela el último dígito exhibido en el display 7 segmentos después de recibir un 1 lógico. Para obtener un funcionamiento normal del CD4511 esta entrada precisa estar en 0.
Data Sheet de los elementos Utilizados 

74283
 
7485
 
4511
 
74175
 
Display 7 segmentos
 

Cronograma 



Bibliografia:
[1] Privalov y K. Sohraby «Sci-Hub IEEEXplore» abril de 1998	
Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/664263
[2]JR Hoff, «Sci-Hub IEEEXplore» 24 de octubre de 2019
Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/8882342
[3]R. J. Lycett, «Sci-Hub IEEEXplore» 13 de marzo de 
Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/6479218   
Anónimo (26 de agosto del 2017) electronica.com  Obtenido de:
https://blog.ars-electronica.com.ar/2017/08/cd4511-decodificador-para-display-7.html   
Víctor González(15 de enero del 2020) piensa3d.com Obtenido de:
https://piensa3d.com/que-es-un-multiplexor-como-funciona/
