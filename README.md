# Producto-Unidad-2
# 1.-Planteamieno del Problema 
La electrónica digital ha marcado un gran avance en la tecnología durante los últimos 80 años. Es una rama de la electrónica que nos permite realizar circuitos lógicos a partir de las necesidades que se presenten en cualquier situación. Permitiéndonos aplicar dicho concepto para resolver o sustentar necesidades más avanzadas como el resolver operaciones aritméticas, multiplexar diferentes salidas o decodificar una serie de valores binarios, que incluso pueden ser de alta relevancia en la fundamentación acerca del funcionamiento de microprocesadores.

En nuestro caso, al ser un entorno virtual en el cual vamos a trabajar, utilizaremos los componentes digitales que incorpora Tinkercad, para elaborar una calculadora básica que nos permita sumar y restar dos números de 8 bits (ingresados por el usuario), implementada en la plataforma Tinkercad utilizando principalmente el integrado 74283 (sumador de 4 bits), multiplexores 2 a 1 que nos permitan escoger la operación suma o resta, decodificadores y displays de 7 segmentos que nos permitan visualizar el resultado final en su salida. El propósito de este producto de unidad es analizar el funcionamiento de los circuitos lógicos aritméticos y combinacionales, haciendo énfasis en las aplicaciones que pueden tener en el ámbito de la electrónica y aplicándolo a un circuito, en nuestro caso,
a la operatividad de un sistema selector de operaciones matemáticas, donde las entradas, corresponden a la variable de control y a los números A y B. 
# 2.-Objetivos
## 2.1-Objetivo general
Diseñar e implementar en la plataforma virtual Tinkercad un circuito sumador-restador de números binarios de 8 bits, cuya operación se escoja mediante una variable de control a partir de un multiplexor, analizando el proceso que se lleve a cabo en base a la información de cada circuito integrado a utilizar y su respectiva funcionalidad, con el fin orientado a que se visualice el resultado a través de displays de 7 segmentos, previamente decodificados con el integrado 4511.
## 2.2.-Objetivos específicos
-	Investigar la funcionalidad y la composición de cada circuito lógico aritmético y combinacional que se ha de utilizar, haciendo énfasis principalmente en el sistema de multiplexación 2 a 1 necesario para escoger las salidas correspondientes a la suma o resta.
-	Buscar artículos relacionados a la problemática de resolver diferentes alternativas, mediante la multiplexación y comparar cuál es su relación con el proyecto a realizar en este producto de unidad, analizando los componentes que serán utilizados para la implementación del circuito a construir.
-	Desarrollar el proceso en el que se realice la suma o resta de dos números binarios de 8 bits, mediante un circuito aritmético sumador, cuya fundamentación esté relacionada al análisis del complemento a 1 y/o complemento a 2 de manera particular sobre el segundo número ingresado. Y el resultado ilustrado en displays de 7 segmentos.

# 3.-Estado del Arte
# Conflux: un multiplexor asíncrono de dos a uno para multiplexación por división de tiempo y lectura sin reloj y sin token
En este artículo se describe un multiplexor de dos a uno asíncrono independiente y auto arbitraje llamado Conflux. Conflux se puede utilizar para implementar multiplexación por división de tiempo sin reloj y sin token entre dos fuentes. Esta capacidad se puede usar para crear un bus de datos agregados sin reloj y sin token que se puede usar como una arquitectura de lectura asincrónica completa para un chip, una parte de un chip o un sistema multichip completo. Conflux utiliza un clásico apretón de manos asíncrono de cuatro fases en sus dos puertos de entrada, así como en su puerto de salida. La solicitud asincrónica se incluye con datos para garantizar un retraso de propagación constante. La solicitud también se implementa como una señal diferencial para tener en cuenta las diferencias de retardo de propagación entre los lógicos y los ceros. El arbitraje entre las dos corrientes de entrada de Conflux se logra mediante tres pestillos de restablecimiento y ajuste. Finalmente, las células Conflux se usaron con éxito para implementar la arquitectura de lectura del chip prototipo FCP130. Las pruebas indican retrasos únicos en la etapa de Conflux de 1.8 ns y un ancho de banda de aproximadamente 11 Gb / s en CMOS de 130 nm. 
En este artículo podemos ver otra aplicación o uso de un multiplexor y como este nos facilita algunos trabajos y nos ayuda hacer el uso de menos herramientas como en este que no hace uso de un reloj ni token 
# Análisis de fluctuación por flujo en multiplexores ATM CBR
En este artículo se nos informa primero sobre cómo es la espera que el tráfico de velocidad de bits constante (CBR) sea una fuente importante de tráfico en redes de alta velocidad. Dichas fuentes pueden tener requisitos estrictos de demora y pérdida y, en muchos casos, deben entregarse exactamente como se generaron. Un esquema de prioridad de retardo simple limitará el retardo de la celda y la fluctuación de fase para las secuencias CBR, de modo que en los conmutadores de red el tráfico CBR solo competirá con otro tráfico CBR en las redes. En este documento consideramos un multiplexor en dicho entorno. Proporcionamos un análisis exacto del proceso de fluctuación de fase en el caso homogéneo. En este caso obtenemos la caracterización completa del proceso de fluctuación que muestra las imprecisiones de los resultados existentes. Estos  resultados indican que la variación de la fluctuación de fase está limitada y nunca excede la ranura constante de 2/3. También se muestra que los tiempos sucesivos de interdeparación de células por flujo se correlacionan negativamente con la correlación de retraso 1 de -1/2. Los coeficientes de correlación de orden superior se muestran como cero. También se proporcionan resultados asintóticos simples sobre el comportamiento por flujo cuando el número de flujos CBR se considera grande. En el caso heterogéneo, limitamos la distribución y los momentos de fluctuación. Se proporcionan resultados simples para el cálculo del límite en la variación de la fluctuación de fase para cualquier combinación de flujos CBR en este caso. 
# Multiplexor de longitud de onda de rejilla Chirped Echelle perfecto: diseño y optimización
Se presenta un nuevo método para diseñar una rejilla de difracción para multiplexación por división de longitud de onda (WDM), que se sintoniza en un único punto estigmático. La nueva rejilla se define por el modo y la longitud de onda de la operación en una guía de onda de losa, la posición de las guías de onda, el orden de difracción y una ruta arbitraria, que se llama la línea de rejilla, sobre la cual se posicionan, se proyectan las facetas individuales. curvado a través del algoritmo esbozado. Se presenta un proceso de diseño sistemático para las rejillas de echelle (EG), que cubre todos los aspectos clave de este dispositivo. Se describe una serie de reglas para mejorar el rendimiento de cualquier dispositivo EG WDM. Se realizó una comparación simulada entre este dispositivo, una rejilla estándar de Rowland y una rejilla de dos puntos estigmáticos, con el nuevo diseño funcionando mejor y comparable en cada caso, respectivamente.

# 4.-Marco Teorico
#										Multiplexor
El multiplexor, también conocido de manera acortada como MUX, es un circuito lógico combinacional diseñado para conmutar una o varias líneas de entrada en una sola línea de salida común mediante la aplicación de una lógica de control.
Los multiplexores funcionan como conmutadores de acción muy rápida que gestionan varias líneas de entrada llamadas canales y conectan una de estas entradas a la línea de salida en función de la señal de control.
Los MUXs pueden ser:
Circuitos digitales hechos con puertas lógicas de alta velocidad para cambiar datos digitales o binarios.
Circuitos analógicos usando transistores, MOSFETs o relés para conmutar una de las entradas de voltaje o corriente en una sola salida.

# Su Funcionamiento

El principio de funcionamiento de un multiplexor se puede entender de manera muy sencilla a través de un ejemplo.
Vamos a emplear una serie de tuberías controladas por una llave de paso como en la siguiente imagen:
 
Como podemos ver en el primer ejemplo tenemos:
•	Dos tuberías de entrada con dos tipos de agua según su uso.
•	Una llave de paso con la que se elegirá el tipo de agua en cada momento.
•	Una tubería de salida que es común a todas las de entrada y por la que circulará el agua que esté «seleccionada» por la llave de paso.
 
Este último ejemplo es igual que el primero, a excepción de que existen cuatro tuberías de entrada en vez de dos.

# Multiplexores digitales

En electrónica digital, los multiplexores que hay disponibles en el mercado son tan pequeños que los podemos encontrar en un simple encapsulado. Esto contrasta con los selectores mecánicos que necesitan de varios interruptores y relés convencionales en función de la cantidad de datos a procesar.
La selección de cada línea de entrada es controlada por un conjunto adicional de entradas llamadas líneas de control (en el ejemplo como la llave de paso). En función del valor de las entradas de control,  HIGH  (1) o  LOW (0), una de las entradas de datos es conectada directamente a la salida.
Normalmente, un multiplexor tiene un número par de líneas de entrada. El número de entradas de datos será 2n, siendo n = 1, 2, 3, 4,… El número de entradas de control dependerá de las entradas de datos y será de valor n.
A continuación vamos a analizar los tipos de multiplexores más básicos que hay disponibles para entender mejor su funcionamiento. En estos ejemplos, todas las líneas transportarán un bit de información, es decir, o 1 o 0, aunque en la realidad existen multiplexores que son capaces de transportar varios bits por cada canal.

# Tipos de multiplexor
# Multiplexor 2 a 1
Este tipo de multiplexor dispone de dos señales de entrada y una salida. Como consta de sólo dos entradas, existirá una única línea de control de datos, ya que con un bit podrá seleccionar la entrada 0 (si recibe un ‘0’ de la señal de control) o la entrada 1 (si recibe un ‘1’ de la señal de control).
Un ejemplo es el circuito integrado TTL 74157.


![Multiplexor de 2 a 1](https://user-images.githubusercontent.com/66962449/89147938-defb4b00-d51d-11ea-97d3-fd933ae3139f.png)

# Multiplexor 4 a 1
En este caso, hay cuatro señales de entrada y una salida. Consta de cuatro entradas, así que habrán dos líneas de control, ya que son necesarios al menos dos bits de datos para poder seleccionar la totalidad de entradas. Recordemos que 4 entradas es 22, por tanto hacen falta 2 canales de control.
Un ejemplo es el circuito integrado TTL 74153.


![Multiplexor de 4 a 1](https://user-images.githubusercontent.com/66962449/89147939-defb4b00-d51d-11ea-9a13-4a6c72c3f5fc.png)

# Multiplexor 8 a 1
Este será el último caso que veremos en el post. Tenemos ahora ocho entradas y una salida. Aplicando la fórmula para ver el número de líneas de control nos encontramos con: 8 entradas es 23, por tanto son necesarios 3 canales de control.
Un ejemplo es el circuito integrado TTL 74151.


![Multiplexor de 8 a 1](https://user-images.githubusercontent.com/66962449/89147940-defb4b00-d51d-11ea-8b7f-8450c093b6af.png)

## Sumadores
EL sumador es un circuito digital que realiza la adición de números. En muchas computadoras y otros tipos de procesadores se utilizan sumadores en las unidades aritméticas lógicas. También se utilizan en otras partes del procesador, donde se utilizan para calcular direcciones, índices de tablas, operadores de incremento y decremento y operaciones similares.

Aunque los sumadores se pueden construir para muchas representaciones numéricas, tales como decimal codificado en binario o exceso-3, los sumadores más comunes funcionan en números binarios. En los casos en que se utiliza el complemento a dos o el complemento a uno para representar números negativos, es trivial modificar un sumador para convertirlo en un sumador-restador. 
Semisumador


 ![Semisumador](https://user-images.githubusercontent.com/66962449/89147941-df93e180-d51d-11ea-9ada-7e9e224531dc.png)
 
 
Esquema de un semisumador
El semisumador suma dos dígitos binarios simples A y B, denominados sumandos, y sus salidas son Suma (S) y Acarreo (C). La señal de acarreo representa un desbordamiento en el siguiente dígito en una adición de varios dígitos. El diseño más simple de semisumador, representado a la derecha, incorpora una puerta XOR para S y una puerta AND para C. Dos semisumadores pueden ser combinados para hacer un sumador completo, añadiendo una puerta OR para combinar sus salidas de acarreo.

Un sumador completo suma números binarios junto con las cantidades de acarreo. Un sumador completo de un bit añade tres bits, a menudo escritos como A, B y Cin; siendo A y B los sumandos y Cin el acarreo que proviene de la anterior etapa menos significativa. 1 El sumador completo suele ser un componente de una cascada de sumadores, que suman 8, 16, 32, etc. números binarios de bits. El circuito produce una salida de dos bits, al igual que el semisumador, denominadas acarreo de salida (Cout) y suma S.
Un sumador completo se puede implementar de muchas maneras diferentes, tales como con un circuito a transistores o compuesto de otras puertas. Un ejemplo de implementación es expresado con las siguientes ecuaciones:
Diagrama lógico de un sumador completo


![Sumador completo](https://user-images.githubusercontent.com/66962449/89147942-df93e180-d51d-11ea-8086-caf576841fc9.png)
 
 
En esta implementación, la puerta OR final antes del acarreo de salida puede ser reemplazada por una puerta XOR sin alterar la lógica resultante. El uso de sólo dos tipos de compuertas es conveniente si el circuito se está implementando usando circuitos integrados que contienen sólo un tipo de puerta.
Se puede construir un sumador completo a partir de dos semisumadores conectando las entradas A y B a la entrada de un primer semisumador, conectando su salida de suma a una de las entradas del segundo semisumador, conectando el acarreo de entrada Cin a la otra entrada y conectando los acarreos de salida de los semisumadores a una puerta OR. La ruta crítica de un sumador completo recorre ambas puertas XOR y hasta llegar a la salida S. Suponiendo que una puerta XOR tenga un retardo D, el retardo total por el camino crítico de un sumador completo es igual a:

# Decodificador 4511

El CD4511 es un decodificador bcd para display de 7 segmentos.
El display de 7 segmentos es un componente bastante empleado en el mundo de la electrónica, ya que permite que sea muy simple la exhibición de valores numéricos. Pudiendo representar cifras de 0 a 9 
Los display de 7 segmentos son empleados la mayoría de las veces a partir de circuitos digitales como circuitos integrados, microcontroladores y otros procesos que trabajan en sistema binario, cuyo sistema y representación es apenas realizado por dos niveles lógicos 0 y 1 denominados bits

# Funcionamiento CD4511

El CD4511 es un decodificador bcd de 4 bits para display cátodo común, que utiliza tecnología cmos. Recibe en los Pines de entrada a ABCD los datos en código binario y los decodifica a código decimal, siendo posible su exhibición en los display de 7 segmentos.
El Funcionamiento del cd4511 puede ser visualizado a través de su tabla de verdad. Solo se muestra la decodificación BCD:
Tabla de la verdad CD4511


![tabla 4511](https://user-images.githubusercontent.com/66962449/89147944-df93e180-d51d-11ea-8400-313894d568f1.png)


# Las características más importantes que podemos considerar se encuentran:

Tensión de operación: 3V a 18V de corriente continua.
Corriente de salida: 10mA.
Temperatura de operación: -55ºC a 125ºC.
Configuración de pines.
Cada pin de salida corresponde a un segmento del display, basta con hacer las conexiones y enviar las informaciones binarias a las entradas, luego CD4511 decodifica el código bcd y escribe la información en cifras decimales en el display.
 
![Display](https://user-images.githubusercontent.com/66962449/89147937-de62b480-d51d-11ea-9c0f-ea9a66757a5e.jpg)
 
 
Este Circuito integrado es específico para trabajar con diplay de 7 segmentos de cátodo común, en el caso de querer usar el CD 4511 con ánodo común se debe recurrir a un circuito inversor o usar otro circuito integrador decodificador.
Tenemos a disposición 3 Pines del CD4511 que pueden tener gran aplicación en diversos proyectos, brindando funciones como:
Economizar Batería.
Registrar el último dígito exhibido en el display.
Testear los segmentos del display, para validar su funcionamiento y el cableado.
Estos pines y su funcionamiento son:
Lamp Test LT(Pin 3): Este pin nos sirve para probar todos los segmentos. Debido a que es una entrada inversora, para tener un funcionamiento normalizado esta entrada debe estar en 1. Cuando la entrada toma un valor lógico 0 prende todos los segmentos del display para testear el funcionamiento.
Blank Input BI(Pin 4): Apaga todos los segmentos, tenér en cuenta que esto es una entrada inversora, por lo tanto para tener un funcionamiento normal del CI esta entrada precisa estar en 1.
Lath Enable LE(Pin 5): congela el último dígito exhibido en el display 7 segmentos después de recibir un 1 lógico. Para obtener un funcionamiento normal del CD4511 esta entrada precisa estar en 0.

## 5.- DIAGRAMAS
### 5.1. DIAGRAMA DE BLOQUES
![Diagrama 1 1](https://user-images.githubusercontent.com/68835261/89188009-ada56e00-d563-11ea-986e-711e420b10e3.JPG)
### 5.2. DIAGRAMA UML (CASO DE USO – CLASE)
![Diagrama 1 2](https://user-images.githubusercontent.com/68835261/89188012-b007c800-d563-11ea-88c4-e7f977330a8a.JPG)
### 5.3. DIAGRAMA ELÉCTRICO

## 6.- LIST  DE COMPONENTES
![Tabla 1 11](https://user-images.githubusercontent.com/68835261/89187069-5652ce00-d562-11ea-8194-fabb8efa6386.JPG)
![Tabla 1 12](https://user-images.githubusercontent.com/68835261/89187081-5a7eeb80-d562-11ea-8b14-4d60f3c7b30d.JPG)

## 7.- MAPARA DE VARIABLES
### •	Variables utilizadas para el funcionamiento del circuito (Operaciones aritméticas seleccionadas mediante multiplexor)
- Entradas
![Figura 1 1](https://user-images.githubusercontent.com/68835261/89186923-1be93100-d562-11ea-8058-57d9ae58577f.JPG)

- Salidas
![Figura 1 2](https://user-images.githubusercontent.com/68835261/89186955-2acfe380-d562-11ea-8b72-63ba1f7c03c1.JPG)

La figura 1.1 y 1.2 nos ilustra de manera detallada todas las variables que han sido utilizadas para la implementación y el correcto funcionamiento del circuito (Operaciones aritméticas. Suma o resta) seleccionadas mediante un multiplexor. 

En la figura 1.1 podemos observar las variables de entrada, las cuales corresponden al switch (1 | 0) y los dos dipswitch (Números A y B). Necesarios para realizar el control o selección de la operación aritmética a realizar y el ingreso de los valores en binario de A y B respectivamente.

La figura 1.2 ilustra las variables de salida (Y0, Y1, Y2, Y3, Y4, Y5, Y6, Y7) que se han utilizado para indicar el número binario resultante de la operación aritmética que se haya escogido realizar representadas por LEDs y también la variable (AC | SIGNO) que representa al bit de acarreo (suma) o el signo negativo (resta).

### •	Interfaz de usuario
![Figura 1 3](https://user-images.githubusercontent.com/68835261/89186967-2f949780-d562-11ea-82b0-307a9a8ab5a2.JPG)
![Figura 1 4](https://user-images.githubusercontent.com/68835261/89186974-33c0b500-d562-11ea-9f1a-7c0c63e0a19b.JPG)

### •	Tabla de variables visibles o no visibles
![Tabla 1 2](https://user-images.githubusercontent.com/68835261/89187050-4f2bc000-d562-11ea-9181-ce3f56fc2c87.JPG)

Donde:
- A7 Y B7 son los bits más significativos y A0 Y B0 los bits menos significativos
- Y7 es el bit más significativo y Y0 el menos significativo. 
A continuación, se presenta una tabla resumen de cada variable que se ha utilizado, el tipo y la función que realiza cada una en el circuito. Esto se ilustra en la tabla 1.3.
![Tabla 1 3](https://user-images.githubusercontent.com/68835261/89187125-72ef0600-d562-11ea-8e20-54ab7c41e647.JPG)

## 8.- EXPLICACIÓN DEL CIRCUITO

### OPERACIONES ARITMÉTICAS SELECCIONADAS MEDIANTE UN MULTIPLEXOR
El diseño del presente circuito, se basa en seleccionar, mediante un multiplexor con 1 variable de control, las operaciones correspondientes a la suma o resta de dos números binarios de 8 bits, cuyos resultados se presentarán en formato decimal en displays de 7 segmentos. Es decir:

![Tabla 1 4](https://user-images.githubusercontent.com/68835261/89187153-7d110480-d562-11ea-9473-09723bfd6deb.JPG)

### •	CIRCUITO SUMADOR RESTADOR
El circuito sumador restador, consta principalmente de cuatro circuitos integrados (sumadores) 74HC283, los cuales son necesarios para realizar la operación suma o resta de dos números binarios de 8 bits.

Como primer punto tenemos la variable de control, la cuales determinarán la operación que se llevará a cabo. En este caso en particular, tenemos que para realizar la suma debe ejecutarse la acción (0) y para el caso de la resta (1). (Figura 1.5)

![Figura 1 5](https://user-images.githubusercontent.com/68835261/89186987-38856900-d562-11ea-97c6-c416253b1ac7.JPG)

Ahora bien, debido a que el circuito integrado 74HC283 (Sumador) necesita de un 1 ó 0 lógico en el pin correspondiente al carry de entrada (Co) para realizar la suma (0) o la resta (1) de los números binarios. Entonces procedemos a ingresar los valores ingresados de la variable de control (Figura 1.5) a dicho pin del sumador. De esta manera se realizará la suma únicamente cuando el interruptor esté en estado lógico BAJO y realizará la resta cuando se encuentre en estado lógico ALTO. El multiplexor escogerá el resultado de la operación que hayamos escogido (Figura 1.6). Esto último se explicará más adelante con más detalle.

![Figura 1 6](https://user-images.githubusercontent.com/68835261/89187191-931ec500-d562-11ea-9709-f4480d8f25ea.JPG)

Por otro lado, tenemos las entradas de nuestro circuito, las cuales corresponden a los dos números de 8 bits A y B. Esto se ilustra en la figura 1.7.

![Figura 1 7](https://user-images.githubusercontent.com/68835261/89187224-9c0f9680-d562-11ea-8060-b947e932672b.JPG)

Donde A7 y B7 son las cifras más significativas (MSB) de ambos números, mientras que A0 y B0 son las cifras menos significativas (LSB).

Ahora bien, para realizar la suma o la resta de los números A y B, necesitamos realizar un cierto condicionamiento, para que funcione o la suma o la resta, dependiendo de lo que hayamos escogido, mediante el switch de la figura 1.5. Entonces para ello necesitamos de la utilización de las compuertas lógicas XOR, cuyo comportamiento lógico es necesario para, en el caso de la resta, realizar el complemento a 1 del número B. Mientras que en la suma se realizaría su operación aritmética de manera normal. Para entender de mejor manera el funcionamiento de este apartado, ilustramos la tabla de verdad de la compuerta lógica mencionada.

![Tabla 1 5](https://user-images.githubusercontent.com/68835261/89187241-a3cf3b00-d562-11ea-987c-899bfcda8df6.JPG)

Como podemos observar en la tabla 1.5, tenemos las salidas de 1 lógico cuando una de las dos entradas es diferente y 0 lógico cuando las dos entradas son iguales. Entonces, en base a este condicionamiento, podemos negar las cifras del número B (Complemento a 1), siempre y cuando se realice la operación aritmética resta. Para entender de mejor manera, postulamos un ejemplo.

Suponiendo que tenemos el switch de suma (0) o resta (1), y un número B, tal que:

Número B (en binario) = 10110001

Tendríamos las siguientes tablas de verdad, para cada caso:

![Tabla 1 6](https://user-images.githubusercontent.com/68835261/89187266-ab8edf80-d562-11ea-8f00-b3336bf3794d.JPG)

La tabla de la izquierda ilustra lo que sucedería con el número B si realizamos la operación resta. Entonces Complemento a 1 de B = 01001110.
Por otro lado, la tabla de la izquierda ilustra lo que sucedería con el número B si se realiza la operación suma. Es decir, el número sigue siendo el mismo.

Entonces, ya implementando esta fundamentación en el circuito, tenemos:

![Figura 1 8](https://user-images.githubusercontent.com/68835261/89187297-b3e71a80-d562-11ea-86da-0790bbd2c195.JPG)

Cabe recalcar que la salida (1 | 0) ilustrada en la figura 1.5 será conectada hacia el pin de entrada C0 del Circuito integrado 74HC283. Y la salida C4 (bit de acarreo) será conectada en el carry de entrada del siguiente sumador, es decir, se realiza una conexión en cascada, debido a que cada número tiene 8 bits.

### - Para la resta (bit que indica el signo)

![Figura 1 9](https://user-images.githubusercontent.com/68835261/89187312-ba759200-d562-11ea-9887-bdab8cd6a75e.JPG)

Todo lo que se ha realizado hasta el momento nos indican las operaciones, suma o resta cuyos resultados son las cifras S0(+), S1(+), S2(+), S3(+), S4(+), S5(+), S6(+), S7(+) y el bit de acarreo resultante de la suma que es C4_2. Sin embargo, nos hace falta el bit que indica el signo (para la resta). Para ello necesitamos, conectar la salida C4_2 (figura 1.9). Tal como se ilustra a continuación.

![Figura 2 1](https://user-images.githubusercontent.com/68835261/89187333-c2cdcd00-d562-11ea-9920-2a762aacc0dc.JPG)

Básicamente, se realizó un condicionamiento, en el cual se ha conectado la salida C4 del circuito sumador a una compuerta lógica NOT y esta salida, conectada al primer pin de la compuerta AND. Mientras que en la segunda entrada se conectó la salida del switch de la figura 1.5. Para entender mejor su funcionamiento, ilustramos el siguiente ejemplo:

Sabemos que C4_2 puede tomar el valor de 1 o 0, dependiendo de la suma o resta que se realice entre los números A y B ingresados, entonces la tabla de verdad para la salida (+ | -) nos queda de la siguiente manera:

![Tabla 1 7-8](https://user-images.githubusercontent.com/68835261/89187413-e133c880-d562-11ea-96e5-052d1636e5de.JPG)

Como podemos observar en la operación suma (Tabla 1.8), siempre vamos a obtener en la salida un 0, lo que representa al signo positivo. Mientras que en la operación resta (Tabla 1.7) tendremos un 1 (signo negativo) solamente cuando el bit de acarreo C4 sea 0, es decir, cuando el número A sea menor que el número B.

Hasta el momento sabemos que los dos primeros circuito integrado analizados se encargan de realizar la suma o resta entre los números A y B, siendo este último negado, es decir, con complemento a 1, por lo que tenemos un primer resultado. Sin embrago necesitamos de otros dos circuitos integrados (sumadores) conectados en cascada para realizar el complemento a 2 del resultado 1. Esto particularmente, para que el resultado final que obtengamos al realizar la operación resta, sea correcto. 

Ahora bien, las conexiones, que necesitamos realizar en el tercer y cuarto circuito integrado, son similares a las del anterior, con algunas diferencias, que podemos notar a continuación.

![Figura 2 2](https://user-images.githubusercontent.com/68835261/89187435-e7c24000-d562-11ea-833c-759548f9fd13.JPG)

Supongamos que se realizó la operación resta. Y el resultado obtenido en S7(+), S6(+), S5(+), S4(+), S3(+), S2(+), S1(+), S0(+) es 11010000 respectivamente. Entonces la tabla de verdad que se obtiene a partir de la figura 2.2. es la siguiente:

![Tabla 1 9 - 2 1](https://user-images.githubusercontent.com/68835261/89187450-eee94e00-d562-11ea-8268-d3dd3d399934.JPG)

Como podemos observar en las Tablas 1.9 y 2.1, notamos que se realiza el complemento a 1 del resultado 1 (R1) solamente si el signo es negativo (1 lógico). Caso contrario no se realiza la negación de R1. En otras palabras, si A>B no existe complemento a 1 de R1; Por otro lado, si A<B si existe complemento a 1 de R1 (Todo esto para el caso en el que se realice la operación resta). 

Entonces implementando esta fundamentación en el tercer y cuarto circuito integrado (sumadores), tenemos lo ilustrado en la figura 2.3. Cabe recalcar que el bit del signo es conectado al pin de entrada C0, mientras que las entradas B0, B1, B2, B3, B4, B5, B6, B7 son conectadas a tierra (0 lógico), ya que estos pines no serán utilizados. 

![Figura 2 3](https://user-images.githubusercontent.com/68835261/89187481-f90b4c80-d562-11ea-9058-7d4c79cc4e29.JPG)

A continuación, ilustramos un ejemplo para entender de mejor manera lo que realiza cada circuito integrado:

![Ejemplo 1](https://user-images.githubusercontent.com/68835261/89187505-00caf100-d563-11ea-9812-07d467ba9ed5.JPG)

![Ejemplo 2](https://user-images.githubusercontent.com/68835261/89187518-058fa500-d563-11ea-81ae-950b72eabf6c.JPG)

Ahora bien, para realizar la selección de cada operación dependiendo del estado lógico de la variable de control (interruptor de la figura 1.5) se ha requerido de la utilización de tres circuitos integrados 74157 (Multiplexores). Tal como se muestra en la figura 2.4. 

![Figura 2 4](https://user-images.githubusercontent.com/68835261/89187536-0d4f4980-d563-11ea-8fcb-0b91e2d04d69.JPG)

Cada circuito integrado contiene 4 multiplexores de 2 a 1, es decir 2 entradas a 1 salida, y 1 variable de selección, por lo que, se escogerá una sola operación a realizar dependiendo del estado lógico del interruptor de la figura 1.1. Ahora bien, como podemos observar, en la figura 2.3. Cada entrada corresponde a la salida de las operaciones realizadas detalladas anteriormente. 
Específicamente, la entrada menos significativa (XA) de cada multiplexor corresponde a las salidas de la operación SUMA. En la entrada siguiente (XB) se colocan las salidas la operación RESTA binaria, debido a que la combinación ingresada del interruptor de control estaría en (1) y de esta manera el circuito sumador restador explicada con anterioridad realizaría la sustracción de los dos números ingresados (A y B) mediante el complemento a 2 de B.
Cabe recalcar que se utilizó un multiplexor extra para obtener el bit de acarreo (en el caso de la suma) y el bit correspondiente al signo del resultado que se obtendría si se resta un número B mayor que A. Siendo así, un total de 9 multiplexores utilizados para obtener el resultado de cada operación. De esta manera obtenemos 8 bits de salida (donde Y0 es el bit menos significativo y Y7 el más significativo) y un bit extra (signo o acarreo) que se conectan a LEDs que indican el resultado de cada operación en binario, tal como se muestra a continuación:

![Figura 2 5](https://user-images.githubusercontent.com/68835261/89187556-14765780-d563-11ea-8096-f8dd72135069.JPG)

Finalmente, para ilustrar el funcionamiento del circuito, en los diferentes displays de 7 segmentos (cátodo común) necesitamos utilizar decodificadores BCD (4511), para los datos de salida, entonces el circuito visualizado de manera general se vería de la siguiente manera:

## 9.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN
En lo que corresponde a la utilización de programas secundarios para que el circuito funcione correctamente, podemos decir que no se ha necesitado de ninguna que influya directamente, ya que Tinkercad y Proteus ofrecen entornos de simulación muy intuitivos para realizar los respectivos diseños e implementaciones. 

Ahora bien, necesitamos saber cuales son los pasos para poder implementar un circuito en Tinkercad. Para lo cual, debemos:

1. Seleccionar en la sección de componentes, todos los elementos que se utilizarán en el circuito, (Circuitos integrados, resistencias, leds) que incorpora Tinkercad

# Data Sheet de los elementos Utilizados  



# 74283

 ![74283](https://user-images.githubusercontent.com/66962449/89147935-de62b480-d51d-11ea-94b8-1bfcaccdc4c6.jpg)
 
# 7485

![7485](https://user-images.githubusercontent.com/66962449/89147932-ddca1e00-d51d-11ea-87d5-c332cae5f6fa.png)
 
# 4511

 ![4511](https://user-images.githubusercontent.com/66962449/89147931-dd318780-d51d-11ea-973b-3a95b9add0eb.png)
 
# 74175

 ![74175](https://user-images.githubusercontent.com/66962449/89147934-ddca1e00-d51d-11ea-9c23-bba464279e3d.png)
 
# Display 7 segmentos
 
 ![Dislplay 7 seg](https://user-images.githubusercontent.com/66962449/89147936-de62b480-d51d-11ea-8e28-6806c73c0e2b.png)

# Cronograma 



# Bibliografia:
## [1] Privalov y K. Sohraby «Sci-Hub IEEEXplore» abril de 1998	
Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/664263
## [2]JR Hoff, «Sci-Hub IEEEXplore» 24 de octubre de 2019
Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/8882342
## [3]R. J. Lycett, «Sci-Hub IEEEXplore» 13 de marzo de 
Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/6479218   
## Anónimo (26 de agosto del 2017) electronica.com  Obtenido de:
https://blog.ars-electronica.com.ar/2017/08/cd4511-decodificador-para-display-7.html   
## Víctor González(15 de enero del 2020) piensa3d.com Obtenido de:
https://piensa3d.com/que-es-un-multiplexor-como-funciona/
